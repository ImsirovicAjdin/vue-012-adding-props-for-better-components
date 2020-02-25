<template>
  <div class="hello">
    <h1>{{ content }}</h1>
    <h2>{{ additionalContent }}</h2>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    content: String,
    additionalContent: String
  }
};
</script>

