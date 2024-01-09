<template>
  <div id="sidebar">
    <div class="user">
      <img src="../assets/img/avatar.png" alt="">
    </div>
    <div class="menu">
      <a class="active" href="javascript:void(0)">
        <svg t="1704814043557" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7711" width="200" height="200"><path d="M896 0H128C57.6 0 0 57.6 0 128v768c0 70.4 57.6 128 128 128h768c70.4 0 128-57.6 128-128V128c0-70.4-57.6-128-128-128zM448 794.496l-237.248-237.248 90.496-90.496L448 613.504l306.752-306.752 90.496 90.496L448 794.496z" p-id="7712" fill="#ffffff"></path></svg>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
  props: {
  }
}
</script>

<style lang="less" scoped>
  #sidebar{
    background-color: rgba(71, 114, 250, 0.8);
    color: #fff;
    width: 50px;
    padding: 15px 5px;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    .user{
      img{
        width: 32px;
        height: auto;
        border-radius: 5px;
      }
    }
    .menu{
      margin-top: 20px;
      svg{
        width: 20px;
        height: auto;
      }
    }
  }
</style>
