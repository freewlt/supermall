<template>
  <div class="tabbar">
      <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'tabbar'
}
</script>

<style>
.tabbar{
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 49px;
  background: #f6f6f6;
  box-shadow: 0 -1px 1px rgba(100,100,100,.2)
}
</style>
