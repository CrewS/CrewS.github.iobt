<template>
    <router-view
      v-ref:list
        keep-alive>
    </router-view>
</template>

<script>

</script>

<style lang="stylus">
font-stack = Helvetica, sans-serif
primary-color = #999
body{
  font 100% font-stack
  color primary-color
}
  
.logo{
  width 40px
  height 40px
}
  
</style>