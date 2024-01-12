<template>
  <div id="sidebar">
    <div class="user">
      <img src="../assets/img/avatar.png" alt="">
    </div>
    <div class="menu">
      <a class="active" href="javascript:void(0)">
        <svg class="icon icon-task" aria-hidden="true">
            <use xlink:href="#icon-bxs-checkbox-checked"></use>
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
        <svg class="icon icon-search" aria-hidden="true">
            <use xlink:href="#icon-search"></use>
        </svg>
      </a>
    </div>
    <div class="menu menu-bottom">
      <a href="javascript:void(0)">
        <svg class="icon icon-sync" aria-hidden="true">
            <use xlink:href="#icon-sync"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon icon-notice" aria-hidden="true">
            <use xlink:href="#icon-notice"></use>
        </svg>
      </a>
      <a href="javascript:void(0)">
        <svg class="icon icon-help" aria-hidden="true">
            <use xlink:href="#icon-help-fill"></use>
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
      margin-top: 12px;
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
        font-size: 26px;
        &.icon-task{
          font-size: 32px;
        }
        &.icon-search{
          font-size: 22px;
        }
      }
    }
    .menu-bottom{
      margin-top: auto;
      .icon{
        &.icon-sync{
          font-size: 24px;
        }
        &.icon-notice{
          font-size: 20px;
        }
        &.icon-help{
          font-size: 20px;
        }
      }
    }
  }
</style>
