<template>
  <div class="hello">
    <p>{{ $t("hello") }}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<i18n>
{
  "en": {
    "hello": "Hello i18n in SFC!"
  },
   "tw": {
    "hello": "你好"
  }
}
</i18n>
