<template>
  <div id="sidebar">
    <div class="user">
      <img src="../assets/img/avatar.png" alt="">
    </div>
    <div class="menu">
      <a class="active" href="javascript:void(0)">
        <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-check-item-filling"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-calendar-fill"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-focus-2-fill"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-locationfill"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-check-square-fill"></use>
        </svg>
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
      display: flex;
      flex-direction: column;
      align-items: center;
      a{
        margin-bottom: 15px;
        color: rgba(255,255,255,.4);
        &:hover{
          color: rgba(255,255,255,.6);
        }
        &.active{
          color: #ffffff;
        }
      }
      .icon{
        font-size: 24px;
      }
    }
  }
</style>
