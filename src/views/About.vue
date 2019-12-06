<template>
  <div class="about">
    <h1>This is an about page</h1>
    {{ textWord }} //add this
  </div>
</template>

// add whole script
<script>
export default {
  data() {
    return {
      textWord: "my first vue app"
    };
  }
};
</script>
