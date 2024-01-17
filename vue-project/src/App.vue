<template>
  <h2 class="item">Hello world!</h2>
  <Block/>
  <contentList/>
</template>

<script> 
  import Block from './components/Block.vue'
  import ContentList from './components/ContentList.vue'
  export default {
    components: {
      Block, ContentList
    }
  }
</script>

<style>
  .item{
      color:red;
  }
</style>