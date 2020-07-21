<!--
 * @Author: Tmier
 * @Date: 2020-07-21 21:46:48
 * @LastEditTime: 2020-07-21 23:01:27
 * @Description: 
--> 
<template>
  <div class="cart">
      <order-header></order-header>
    <h2>Cart页面</h2>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
//import x from ''
import OrderHeader from "../components/OrderHeader";
import NavFooter from "../components/NavFooter";
export default {
  name: "cart",
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