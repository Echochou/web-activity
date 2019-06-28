<template>
  <div class="wrap">
    <div class="banner">
      <div class="banner-img">
        <div class="banner-detail">
          <div class="banner-title">
            新疆体彩官方APP
          </div>
          <div class="banner-text">
            公益体彩 乐善人生
          </div>
          <a class="banner-btn-wrap" name="#download" href="#download">
            <span class="banner-btn" >
              立即下载
            </span>
          </a>
        </div>
      </div>
      <div class="banner-phone"></div>
    </div>
    <ul class="content-list">
      <li class="content-item">
        <div class="list-img img-left list-img1"></div>
        <div class="list-detail">
          <div class="list-title titlt-1st">
            开奖信息
          </div>
          <div class="list-text">
            超级大乐透，排列三、排列五，七星彩，竞彩足篮，传统足彩各玩法实时准确的开奖数据
          </div>
        </div>
      </li>
      <li class="content-item">
        <div class="list-detail">
          <div class="list-title titlt-2nd">
            走势图表
          </div>
          <div class="list-text">
            大乐透、排列三、排列五、七星彩等彩种走势分析，为彩票选号提供有力数据支撑
          </div>
        </div>
        <div class="list-img img-right list-img2"></div>
      </li>
      <li class="content-item">
        <div class="list-img img-left list-img3"></div>
        <div class="list-detail">
          <div class="list-title titlt-3rd">
            权威资讯
          </div>
          <div class="list-text">
            最快最全的体彩官方各类资讯，公告和政策信息
          </div>
        </div>
      </li>
      <li class="content-item">
        <div class="list-detail">
          <div class="list-title title-4th">
            附近门店
          </div>
          <div class="list-text">
            动态展示您身边的体彩线下实体店位置
          </div>
        </div>
        <div class="list-img img-right list-img4"></div>
      </li>
    </ul>
    <div class="footer-wrap" id="download">
      <div class="footer-title">
        更多服务功能，敬请下载体验！
      </div>
      <div class="logo"></div>
      <div class="download-btn-wrap">
        <a class="android download-btn" href="javascript:;">
          Android下载
        </a>
        <a class="ios download-btn" href="javascript:;">
          iPhone下载
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'index',
    created() {
      document.documentElement.style.fontSize = document.documentElement.clientWidth / 375 * 16 + 'px';
    }
  };
</script>

<style lang="less" scoped>
  .wrap {
    .banner {
      padding-bottom: 6.16rem;

      .banner-img {
        position: relative;
        width: 23.4rem;
        height: 13.56rem;
        background-image: url("./img/banner@2x.png");
        background-size: contain;
        background-repeat: no-repeat;

        .banner-detail {
          position: absolute;
          left: 1.7rem;
          bottom: 3rem;

          .banner-title {
            font-size: 1.36rem;
            font-family: SourceHanSansCN-Bold;
            font-weight: bold;
            color: rgba(255, 255, 255, 1);
            text-shadow: 0rem 0rem 1rem rgba(160, 0, 26, 0.36);
          }

          .banner-text {
            margin: 1.34rem 0 1.6rem;
            font-size: 1.04rem;
            font-family: SourceHanSansCN-Regular;
            font-weight: 400;
            color: rgba(255, 255, 255, 1);
            line-height: 0.9rem;
          }

          .banner-btn-wrap {
            display: inline-block;
            width: 5.78rem;
            padding: 0.41rem;
            background: rgba(24, 149, 255, 1);
            border-radius: 1rem;
            text-align: center;

            .banner-btn {
              font-size: 0.92rem;
              font-family: SourceHanSansCN-Regular;
              font-weight: 400;
              color: rgba(255, 255, 255, 1);
              line-height: 0.83rem;
            }
          }
        }
      }

      .banner-phone {
        position: absolute;
        top: 1.84rem;
        right: 0.65rem;
        width: 9.91rem;
        height: 17.88rem;
        background-image: url("img/phone@2x.png");
        background-size: contain;
        background-repeat: no-repeat;
      }
    }

    .content-list {
      padding: 0 0.81rem 0 1.06rem;

      .content-item {
        margin-top: 2.16rem;

        &:first-child {
          margin-top: 0;
        }

        .list-img {
          display: inline-block;
          vertical-align: top;
          width: 11.16rem;
          height: 12.15rem;
        }
        .list-img1 {
          background-image: url("img/ph-content1@2x.png");
          background-size: contain;
          background-repeat: no-repeat;
        }
        .list-img2 {
          background-image: url("img/ph-content2@2x.png");
          background-size: contain;
          background-repeat: no-repeat;
        }
        .list-img3 {
          background-image: url("img/ph-content3@2x.png");
          background-size: contain;
          background-repeat: no-repeat;
        }
        .list-img4 {
          background-image: url("img/ph-content4@2x.png");
          background-size: contain;
          background-repeat: no-repeat;
        }
        .img-left {
          margin-right: 0.7rem;
        }

        .img-right {
          margin-left: 0.7rem;
        }

        .list-detail {
          display: inline-block;
          vertical-align: top;

          .list-title {
            margin-top: 1.4rem;
            font-size: 1.13rem;
            font-family: SourceHanSansCN-Medium;
            font-weight: 500;
            color: rgba(151, 31, 46, 1);
          }

          .titlt-1st {
            width: 6.47rem;
            height: 3.16rem;
            line-height: 3.16rem;
            background-image: url("img/01@2x.png");
            background-size: contain;
            background-repeat: no-repeat;
          }

          .titlt-2nd {
            width: 6.38rem;
            height: 3.13rem;
            line-height: 3.13rem;
            background-image: url("img/02@2x.png");
            background-size: contain;
            background-repeat: no-repeat;
          }

          .titlt-3rd {
            width: 6.38rem;
            height: 3.13rem;
            line-height: 3.13rem;
            background-image: url("img/03@2x.png");
            background-size: contain;
            background-repeat: no-repeat;
          }

          .title-4th {
            width: 6.38rem;
            height: 3.13rem;
            line-height: 3.13rem;
            background-image: url("img/04@2x.png");
            background-size: contain;
            background-repeat: no-repeat;
          }

          .list-text {
            margin-top: 1.34rem;
            width: 9.13rem;
            line-height: 1rem;
            font-size: 0.75rem;
            font-family: SourceHanSansCN-Regular;
            font-weight: 400;
            color: rgba(130, 89, 94, 1);
          }
        }
      }
    }

    .footer-wrap {
      margin-top: 1rem;
      width: 23.46rem;
      height: 26.56rem;
      background-image: url("img/bg-footer@2x.png");
      background-size: contain;
      background-repeat: no-repeat;

      .footer-title {
        padding-top: 5.13rem;
        text-align: center;
        font-size: 1.13rem;
        font-family: SourceHanSansCN-Medium;
        font-weight: 500;
        color: #FFFFFF;
      }

      .logo {
        margin: 1.53rem auto;
        width: 5.47rem;
        height: 5.47rem;
        background-image: url("img/192@2x.png");
        background-size: contain;
        background-repeat: no-repeat;
      }

      .download-btn-wrap {
        width: 10rem;
        margin: 0 auto;
        .download-btn {
          display: inline-block;
          padding: 0.72rem 0;
          margin:  0 auto;
          width: 9.38rem;
          text-align: center;
          background: #fff;
          color: #EF1286;
          font-size: 1.13rem;
          font-family: SourceHanSansCN-Medium;
          font-weight: 500;
          box-shadow: 0rem 0rem 0rem 0rem rgba(100, 0, 26, 0.27);
          border-radius: 2rem;
        }

        .android {

        }

        .ios {
          margin-top: 1.69rem;
        }
      }
    }
  }
</style>
