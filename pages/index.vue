<template>
  <div class="index-page">
    <div class="container">
      <!-- 导航 -->
      <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand" href="#">
          <img src="@/assets/logo.png" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavDropdown"
          aria-controls="navbarNavDropdown"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarNavDropdown"
        >
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">首页</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">关于我们</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">产品中心</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">新闻中心</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">服务支持</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">联系我们</a>
            </li>
            <li></li>
          </ul>
        </div>
      </nav>
    </div>
    <!-- banner -->
    <div id="homeBannerIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li
          data-target="#homeBannerIndicators"
          data-slide-to="0"
          class="active"
        ></li>
        <li data-target="#homeBannerIndicators" data-slide-to="1"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="@/assets/banner/banner01.png" class="d-block w-100" />
        </div>
        <div class="carousel-item">
          <img src="@/assets/banner/banner02.png" class="d-block w-100" />
        </div>
      </div>
    </div>
    <!-- 关于我们 -->
    <div id="about-us">
      <div class="container">
        <div class="flex flex-space-between">
          <div class="head">
            <span>关于我们</span>
            <span>about us</span>
          </div>
          <div class="content">
            <div class="title">
              <div class="font-weight-600">倍光明 beygomim</div>
              <div class="sub">天之光照明科技（中山）有限公司旗下品牌</div>
            </div>
            <div class="items flex flex-space-between">
              <div class="">
                <div class="text-green-01 font-weight-600">
                  <span class="font-size-28">1974</span><sub>年</sub>
                </div>
                <div>始于</div>
              </div>
              <div class="">
                <div class="text-green-01 font-weight-600">
                  <span class="font-size-28">20</span><sub>万家庭</sub>
                </div>
                <div>服务过</div>
              </div>
              <div class="">
                <div class="text-green-01 font-weight-600">
                  <span class="font-size-28">20000</span><sub>平方米</sub>
                </div>
                <div>制造基地</div>
              </div>
            </div>
            <div class="text">
              倍光明致力于光学研发，拥有2万平米制造基地，以前瞻技术还原太阳自然光，打造适应现代生活场景的健康照明环境。近年来，陆续推出了多款护眼照明产品，包括台灯、落地灯、吸顶灯、吊灯等系列，专注保护视力健康。已服务过20万家庭。倍光明以创新科技和全球化视野，为用户提供高品质的照明解决方案，助力打造更舒适、健康的生活空间。
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- 产品展示 -->
    <div id="product">
      <div class="container">
        <div class="flex flex-space-between">
          <div class="head">
            <span>产品展示</span>
            <span>product center</span>
          </div>
          <div class="tabs">
            <div class="item active">吸顶灯</div>
            <div class="item">无主灯</div>
            <div class="item">落地大路灯</div>
            <div class="item">风扇灯</div>
            <div class="item">学习台灯</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style>
@import url("~/styles/index.css");
</style>
