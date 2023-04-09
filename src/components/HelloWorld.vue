<template>
  <h1>{{ msg }}b分支222222</h1>
  <button @click="count++">count is: {{ count }}改变按钮123</button>
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
