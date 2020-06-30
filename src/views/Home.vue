<template>
  <div class="home-page">
    <div class="user-section">
      <el-row :gutter="40">
        <el-col :lg="12">
          <div class="grid-content">
            <h3 class="sub-title">能力简介</h3>
            <ul class="user-power">
              <li>
                1、精通 HTML、CSS、JavaScript
                基础，高效还原设计稿，高质量实现业务逻辑交互，遵守代码规范。
              </li>
              <li>2、掌握使用前端框架，jQuery、 Vue、Element Ui。</li>
              <li>3、熟悉移动端开发，能兼容移动版H5、微信小程序移动版产品。</li>
              <li>4、熟悉前端工程化搭建、webpack、Glup、Git。</li>
              <li>
                5、熟悉后端 Node.js，能操作
                Express、Koa能快速启动项目、独立敏捷开发。
              </li>
            </ul>
          </div>
        </el-col>
        <el-col :lg="12">
          <div class="grid-content">
            <h3 class="sub-title">技能清单</h3>
            <ul class="user-power">
              <li>
                Web开发：
                <el-tag size="small">HTML</el-tag>
                <el-tag size="small">CSS</el-tag>
                <el-tag size="small" type="danger">JavaScript</el-tag>
              </li>
              <li>
                Web框架：
                <el-tag size="small" type="danger">Node.js</el-tag>
                <el-tag size="small">Express</el-tag>
                <el-tag size="small">Koa2</el-tag>
                <el-tag size="small">egg</el-tag>
              </li>
              <li>
                前端框架：
                <el-tag size="small">jQuery</el-tag>
                <el-tag size="small" type="danger">Vue.js</el-tag>
                <el-tag size="small">Element UI</el-tag>
                <el-tag size="small" type="danger">微信小程序</el-tag>
              </li>
              <li>
                前端工具：
                <el-tag size="small">Webpack</el-tag>
                <el-tag size="small">Gulp</el-tag>
                <el-tag size="small">Vue CLI3</el-tag>
              </li>
              <li>
                数据存储：
                <el-tag size="small">MySQL</el-tag>
              </li>
              <li>
                版本管理：
                <el-tag size="small">Git</el-tag>
                <el-tag size="small">Github</el-tag>
              </li>
            </ul>
          </div>
        </el-col>
      </el-row>
    </div>
    <div class="work-section">
      <h3 class="sub-title">项目经验</h3>
      <div class="block">
        <el-timeline>
          <el-timeline-item type="success" placement="top">
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      EDU
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span>EDU
                      是一个连接企业和学校的一个平台。从企业端获取项目资源，通过敏捷开发的模式，把项目按版本、
                      故事、任务、价值点拆解，并制订好测试、验收条件。每个任务都有对应的难度、技能要求，能匹配不同阶段水平的同学，让大家都参与进来，
                      在平台专业工程师的带领下打怪升级。已经完成的项目，将会把技术细节、步骤、文档描述清楚，提供给老师、学生进行教研结合的参考与训练。
                      整套体系的过程都是可跟踪和量化，学生的能力水平、技能广度都通过项目来验证，有效的和企业进行人才匹配。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      通过本项目，熟悉了企业级框架egg,对教育类项目有了进一步了解。
                    </p>
                  </el-card>
                </div>
              </el-col>
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">销售管理系统（ 扎克斯外包项目）</h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >企业吸引更多的消费者，和广告公司合作做出各类精良的营销落地页，并在各个社交、媒体平台中进行投放。
                      为了更好地获取广告信息，指导投放营销，需要一套承接这类营销落地页收集用户的购买行为信息，并进行跟踪、统计、反馈的管理系统。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>通过本项目，在 Node.js 环境中使用
                      Express 快速搭建服务框架，并熟悉简单的 MySQL
                      数据库操作，可以完成数据的增删改查以及连表查询数据。同时，我们还对后端中
                      MVC
                      有深入的了解和实际的运用，懂得了在一个项目中数据是如何从数据库渲染到页面，页面是如何与服务端进行交互从而影响数据的变化。
                    </p>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
          <el-timeline-item type="success" placement="top">
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      OKR-云开发（ 个人项目）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >能够将目标管理自上而下贯穿到基层。通过要设定一个“目标”（Objective），然后，设定若干可以量化的“关键结果”（Key
                      Results），用来帮助实现目标。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span
                      >对微信小程序开发中云函数、云存储、云数据库进一步的实践
                    </p>
                  </el-card>
                </div>
              </el-col>
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      极客 - H5 课程（ 扎克斯外包项目 ）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span> 极客移动项目 H5
                      主要承载课程的播放以及营销直播的相关业务属性。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span
                      >通过本项目，掌握移动端样式的原理和开发，对视频领web域端有了进一步了解。
                    </p>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
          <el-timeline-item type="success" placement="top">
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      目标与成就管理系统（ 扎克斯外包项目 ）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span>OKR
                      为探月学院内部研发的目标管理的系统，能够将目标管理自上而下贯穿到基层。
                      通过要设定一个“目标”（Objective），然后，设定若干可以量化的“关键结果”（Key
                      Results），用来帮助实现目标。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>通过本项目首先对 OKR
                      有一个初步的认识，之前没有丁点概念，也熟悉企业的管理机制。在项目中使用
                      Koa2 来构建简易的 API，对 Nodejs API
                      的生产有更熟悉的运用，同时对小程序开发有一定的了解，能够完成负责业务场景下的小程序研发工作。
                    </p>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
        </el-timeline>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  components: {}
};
</script>

<style type="text/css" lang="less" scoped>
.home-page {
  padding: 40px;

  .sub-title {
    font-size: 18px;
    margin-bottom: 16px;
  }

  .card-title {
    font-size: 16px;
    margin-bottom: 8px;
  }

  .card-text {
    font-size: 14px;
    color: #666;
    margin: 8px 0;
    span {
      font-size: 14px;
      color: #333;
      font-weight: 600;
      display: block;
    }
  }

  .user-power {
    list-style: none;
  }

  .grid-content {
    margin-bottom: 20px;
    font-size: 14px;
    line-height: 2;
  }

  .el-tag {
    margin-right: 8px;
  }
}
</style>
