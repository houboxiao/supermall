<template>
  <div id="tabbar">
    <slot></slot>
  </div>
</template>

<script>

  import TabBarItem from "./TabBarItem";
    export default {
        name: "TabBar"
    }
</script>

<style scoped>
  #tabbar {
    /*flex: 弹性定位*/
    display: flex;
    background-color: #f6f6f6;
    position: fixed;
    bottom: 0;
    right: 0;
    left: 0;
    box-shadow: 0px -3px 1px rgba(100,100,100,.1);

  }

</style>
