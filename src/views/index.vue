<template>
  <div class="app-container home">
    <el-row :gutter="20">
      <el-col :sm="24" :lg="24">
        <h1>通用运输（GTM）管理平台</h1>
        <p>
          GTM是为了满足当今各大单位对运输工具管理问题而研发的一款运输设备管理软件<br>
          通过对围绕在运输设备周边的相关对象的精细化管理，
          提升了单位对运输设备实时状态的了解，
          提高了运输设备使用效率，
          降低了运输设备的支出成本
        </p>
        <hr />
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :sm="24" :lg="24">
        <h1>主要的功能有：</h1>
        <ol>
          <li>
            系统管理，对系统本身进行权限、基础数据、使用者进行管理
          </li>
          <li>
            系统监控，对系统运行状态进行实时展示
          </li>
          <li>
            系统工具，提供了表单设计及其它相关工具，辅助使用系统
          </li>
          <li>
            车务管理，对运输设备及保养信息、保险信息、年检信息、维修信息进行管理
          </li>
          <li>
            司乘管理，对运输设备的操作者进行管理
          </li>
          <li>
            任务管理，对运输任务申请、审批、派单、结单进行操作
          </li>
          <li>
            财务管理，对运输设备维修、日常、保养、规费等费用进行记录和统计
          </li>
          <li>
            数据感知，对运输设备当前的运行状态进行展示
          </li>
        </ol>
        <hr />
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "index",
  data() {
    return {
      
    };
  },
  methods: {
    goTarget(href) {
      window.open(href, "_blank");
    },
  },
};
</script>

<style scoped lang="scss">
.home {
  blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee;
  }
  hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee;
  }
  .col-item {
    margin-bottom: 20px;
  }

  ul {
    padding: 0;
    margin: 0;
  }

  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    list-style-type: none;
  }

  h4 {
    margin-top: 0px;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  p {
    margin-top: 10px;

    b {
      font-weight: 700;
    }
  }

  .update-log {
    ol {
      display: block;
      list-style-type: decimal;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0;
      margin-inline-end: 0;
      padding-inline-start: 40px;
    }
  }
}
</style>

