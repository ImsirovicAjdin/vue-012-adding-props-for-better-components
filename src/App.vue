<template>
  <div id="app">
    <HelloWorld
      content="This content was added with the help of a prop."
      additionalContent="This additional content was also added using a prop."
    />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

