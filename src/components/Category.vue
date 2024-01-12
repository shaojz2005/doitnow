<template>
  <div id="category">
    <ul class="list">
      <li>
        <a class="active" href="javascript:void(0)">
          <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-cards"></use>
          </svg>
          <span class="title">所有</span>
          <span class="sum">9</span>
        </a>
      </li>
      <li>
        <a class="" href="javascript:void(0)">
          <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-calendartoday"></use>
          </svg>
          <span class="title">今天</span>
          <span class="sum">9</span>
        </a>
      </li>
      <li>
        <a class="" href="javascript:void(0)">
          <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-sunrise"></use>
          </svg>
          <span class="title">明天</span>
          <span class="sum">9</span>
        </a>
      </li>
      <li>
        <a class="" href="javascript:void(0)">
          <svg class="icon" aria-hidden="true">
              <use xlink:href="#icon-week"></use>
          </svg>
          <span class="title">最近7天</span>
          <span class="sum">19</span>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Category',
  props: {
  }
}
</script>

<style lang="less" scoped>
  #category{
    background-color: rgb(242, 245, 254);
    border-right: 1px solid rgba(25, 25, 25, 0.05);
    width: 212px;
    flex-shrink: 0;
    padding: 15px 10px;
    .list{
      li a{
        display: flex;
        align-items: center;
        padding: 10px 15px;
        border-radius: 5px;
        &.active{
          background-color: rgba(71, 114, 250, 0.1);
        }
        &:hover{
          background-color: rgba(25, 25, 25, 0.03);
        }
        .icon{
          font-size: 18px;
          margin-right: 5px;
        }
        .title{
          margin-left: 5px;
          color: #333;
          flex-grow: 1;
        }
        .sum{
          width: 30px;
          text-align: right;
          margin-left: auto;
          color: #999;
        }
      }
    }
  }
</style>
