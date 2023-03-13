<template>
  <div class="summary">
    <div class="banner"></div>
    <div class="banner-description">
      <div class="desc-item">
        <section class="desc-title">
          行业TOP
        </section>
        <section class="desc-content">
          20多项行业奖项 <br/>上市集团实力品牌
        </section>
      </div>
      <div class="desc-item">
        <section class="desc-title">
          经验足
        </section>
        <section class="desc-content">
          16年专注月子服务 <br/>率先创立行业标准
        </section>
      </div>
      <div class="desc-item">
        <section class="desc-title">
          口碑好
        </section>
        <section class="desc-content">
          四万家庭信赖之选 <br/>广受明星名人好评
        </section>
      </div>
      <div class="desc-item">
        <section class="desc-title">
          专业强
        </section>
        <section class="desc-content">
          9大成熟服务体系 <br/>1300项精细化服务标准
        </section>
      </div>
      <div class="desc-item">
        <section class="desc-title">
          环境佳
        </section>
        <section class="desc-content">
          坐拥优越的地理位置 <br/>设计饱含专业关怀
        </section>
      </div>
    </div>
    <div class="introduce">
      <div class="introduce-title">
        深耕母婴健康行业 - 只做品质直营
      </div>
      <div class="introduce-content">
        <div class="introduce-content-left">
          <div class="introduce-content-left-title">
            <h3>走进月子中心</h3>
            <span>每一个细节,都有爱</span>
          </div>
          <div class="introduce-content-left-content">
          </div>
        </div>
        <div class="introduce-content-right">
          <div class="introduce-content-right-title">
            <span class="left-title">每一个细节，都有爱</span>
            <span class="right-title"> / QUICK NAVIGATION</span>
            <div class="introduce-content-right-content">
              <div class="topic">
                <section class="left">
                  <img src="../assets/summary/service.png" alt="服务专题">
                </section>
                <div class="right">
                  <h3>服务专题</h3>
                  <section class="content">
                    <span>
                      <span class="symbol"></span>
                      <span class="text">月子餐</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">中医调养</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">韩式通乳</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">产后塑形</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">消水肿护理</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">盆底肌修复</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">情绪管理</span>
                    </span>
                    <span><span class="symbol"></span>
                      <span class="text">查看更多</span>
                    </span>
                  </section>
                  <div class="split-line"></div>
                </div>
              </div>
              <div class="topic">
                <section class="left">
                  <img src="../assets/summary/case.png" alt="案例专题">
                </section>
                <div class="right">
                  <h3>案例专题</h3>
                  <section class="content">
                    <span>
                      <span class="symbol"></span>
                      <span class="text">明星妈妈案例</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">地区案例</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">查看更多</span>
                    </span>
                  </section>
                  <div class="split-line"></div>
                </div>
              </div>
              <div class="topic">
                <section class="left">
                  <img src="../assets/summary/search.png" alt="热搜关键词">
                </section>
                <div class="right">
                  <h3>热搜关键词</h3>
                  <section class="content">
                    <span>
                      <span class="symbol"></span>
                      <span class="text">月子中心排名</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">国际月子中心</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">月子中心价格</span>
                    </span>
                    <span>
                      <span class="symbol"></span>
                      <span class="text">查看更多</span>
                    </span>
                  </section>
                  <div class="split-line"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="comfortable">
      <span class="title">
        天然安全的
        <span class="bold">舒适环境</span>
      </span>
      <div class="img-preview">
        <div class="preview-img environment-one"></div>
        <div class="preview-img environment-two"></div>
        <div class="preview-img environment-three"></div>
      </div>
      <div></div>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
.banner {
  width: 100%;
  height: 736px;
  background: url("@/assets/banner.png") no-repeat center center;
  background-size: 100% 100%;
}
.banner-description {
  width: 100%;
  height: 251px;
  background: #FFFAF6;
  border-radius: 0;
  opacity: 1;
  display: flex;
  padding: 0 10%;
  justify-content: space-around;
  align-content: space-around;
  .desc-item {
    width: max-content;
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 2em;
    justify-content: center;
  }
  .desc-title {
    font-size: 30px;
    color: rgba(51, 51, 51, 1);
  }
  .desc-content {
    font-size: 18px;
    color: rgba(102, 102, 102, 1);
  }
}
.introduce {
  color: #333333;
  text-align: center;
  height: 950px;

  .introduce-title {
    font-size: 46px;
    margin: 63px 0;
  }

  .introduce-content {
    text-align: center;
    display: flex;
    justify-content: space-around;
    gap: 1em;
    align-items: center;
  }

  .introduce-content-left {
    width: 50%;
    display: flex;
    justify-content: center;
    text-align: center;

    .introduce-content-left-title {
      h3 {
        margin: 66px 128px 14px 128px;
        font-size: 44px;
        color: #FFFFFF;
        line-height: 52px;
      }

      span {
        font-size: 24px;
        color: #FFFFFF;
        line-height: 28px;
      }

      height: 600px;
      color: white;
      background-color: var(--el-color-primary);
    }

    .introduce-content-left-content {
      width: 520px;
      height: 500px;
      background: url("@/assets/summary/walk-into.png") no-repeat center center;
      background-size: 100% 100%;
      position: absolute;
      transform: translate(8%, 40%);
    }
  }

  .introduce-content-right {
    align-self: flex-start;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    width: 50%;
    .introduce-content-right-title {
      text-align: left;
      .left-title {
        height: 42px;
        font-size: 30px;
        color: #333333;
        line-height: 35px;
      }
      .right-title {
        height: 41px;
        font-size: 30px;
        font-family: Prata-Regular, Prata;
        font-weight: 400;
        color: #999999;
        line-height: 35px;
      }
    }
    .introduce-content-right-content {
      .topic {
        display: flex;
        justify-content: flex-start;
        img {
          margin-top: 8px;
          line-height: 30px;
          height: 30px;
        }

        .right {
          .split-line {
            width: inherit;
            margin: 2em 0;
            height: 0;
            opacity: 1;
            border: 1px solid #D2D2D2;
          }
          margin-left: 1em;
          h3 {
            height: 48px;
            font-size: 24px;
            vertical-align: center;
            font-weight: 500;
            color: #333333;
            line-height: 48px;
            margin-bottom: 0.6em;
          }
          .symbol {
            margin: 0 1em 0 0;
            display: inline-block;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            opacity: 1;
            border: 2px solid #D9D9D9;
          }

          .content {
            display: flex;
            justify-content: flex-start;
            flex-wrap: wrap;
            gap: 1em 3em;
            .text {
              height: 25px;
              font-size: 18px;
              font-weight: 500;
              color: #666666;
              line-height: 21px;
            }
          }
        }
      }
    }
  }
}
.comfortable {
  text-align: center;
  width: 100%;
  height: 1000px;
  background-color: #f2f2f2;
  .title {
    display: inline-block;
    margin: 0.6em 0 0.4em 0;
    font-size: 46px;
    .bold {
      font-weight: bold;
    }
  }
  .img-preview {
    display: flex;
    justify-content: space-around;
    .preview-img {
      width: 464px;
      height: 564px;
    }
    .environment-one {
      background: url("@/assets/summary/environment-one.png") no-repeat center center;
      background-size: 100% 100%;
    }
    .environment-two {
      background: url("@/assets/summary/environment-two.png") no-repeat center center;
      background-size: 100% 100%;
    }
    .environment-three {
      background: url("@/assets/summary/environment-three.png") no-repeat center center;
      background-size: 100% 100%;
    }
  }
}

</style>
