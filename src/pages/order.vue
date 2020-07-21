<!--
 * @Author: Tmier
 * @Date: 2020-07-21 21:44:55
 * @LastEditTime: 2020-07-21 21:46:05
 * @Description: 
--> 
<template>
  <div>
    <nav-header></nav-header>
    <router-view />
    <nav-footer></nav-footer>
  </div>
</template>

<script>
//import x from ''
import NavHeader from "../components/NavHeader";
import NavFooter from "../components/NavFooter";
export default {
  name: "order",
  components: {
    NavHeader,
    NavFooter
  },
  data() {
    return {};
  },
  computed: {},
  methods: {}
};
</script>

<style lang='less' scoped>
//@import url()
</style>