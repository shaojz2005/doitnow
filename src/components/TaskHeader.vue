<template>
  <header>
    <div class="title"><svg t="1704815053854" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="13163" width="200" height="200"><path d="M896 192H128v128h768V192z m0 256H384v128h512v-128z m0 256H128v128h768v-128zM320 384l-192 128 192 128v-256z" p-id="13164" fill="#8a8a8a"></path></svg> <span>所有</span></div>
  </header>
</template>

<script>
export default {
  name: 'TaskHeader',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
  header{
    color: #333;
    svg{
      width: 18px;
      height: auto;
    }
    
    .title{
      font-size: 20px;
      font-weight: bold;
      span{
        margin-left: 3px;
      }
    }
  }
</style>
