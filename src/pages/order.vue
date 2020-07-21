<!--
 * @Author: Tmier
 * @Date: 2020-07-21 21:44:55
 * @LastEditTime: 2020-07-21 23:00:17
 * @Description: 
--> 
<template>
  <div>
    <order-header></order-header>
    <router-view />
    <nav-footer></nav-footer>
  </div>
</template>

<script>
//import x from ''
import OrderHeader from "../components/OrderHeader";
import NavFooter from "../components/NavFooter";
export default {
  name: "order",
  components: {
    OrderHeader,
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