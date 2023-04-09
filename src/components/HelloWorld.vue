<template>
  <h1>{{ msg }}a分支改变</h1>
  <button @click="count++">count is: {{ count }}改变按钮</button>
  <p>
    Edit <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    };
  },
};
</script>
