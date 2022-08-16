<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
  methods: {
    testFunction() {
      // 我是单引号
      const str1 = "hello World";
      // 我是双引号
      const str2 = "hello World";
      // 我是无结束符
      const str3 = "hello World";
      // 我是有结束符
      const str4 = "hello World";
      console.log("sayHello", str1);
      console.log("sayHello", str2);
      console.log("sayHello", str3);
      console.log("sayHello", str4);
    },
  },
};
</script>
