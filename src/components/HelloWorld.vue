<template>
  <div class="hello">
    eslint -- 简单配置
    <div>空4个或者2个空格</div>
  </div>
</template>

<script>
export default {
    name: "HelloWorld",
    data() {
        return {
            name: "a",
        };
    },
    props: {
        msg: String,
    },
    methods: {
        add() {},
    },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
