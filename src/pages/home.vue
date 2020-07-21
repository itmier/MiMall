<!--
 * @Author: Tmier
 * @Date: 2020-07-21 21:27:57
 * @LastEditTime: 2020-07-21 21:45:55
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
  name: "home",
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