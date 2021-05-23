<template>
  <div class="element-section-wrap">
    <section class="element-section element-top-section">
      <div class="element-container">
        <!-- Container with logo and navbar -->
        <!-- Flex row 2 sectors -->
        <div class="element-column element-left-column">
          <!-- Column with Logo -->
          <!-- Flex -->
          <div class="element-widget-wrap">
            <div class="element-widget-container">
              <!-- Logo -->
              <a href="#"
                ><img
                  class="jetpack-lazy-image"
                  width="237"
                  height="140"
                  src="https://i2.wp.com/ting.global/wp-content/uploads/2021/04/logo18-1.png?fit=237%2C140&ssl=1"
                  alt
                  loading="eager"
              /></a>
            </div>
          </div>
        </div>
        <div class="element-column element-right-column">
          <!-- Flex column 2 sectors -->
          <!-- Container with image on top and navbar on button -->
          <div class="element-widget-wrap">
            <div class="element-image">
              <img
                src="https://i1.wp.com/ting.global/wp-content/uploads/2021/04/new-logo-with.png?fit=2098%2C850&ssl=1"
                alt=""
              />
            </div>
            <div class="element-nav-manu">
              <div class="element-manu toggle">
                <i class="icon-menu-bar" aria-hidden="true"></i>
              </div>
              <div class="element-widget-container">
                <nav class="element-nav-menu--main">
                  <ul class="elementor-nav-menu">
                    <li class="menu-item">
                      <a
                        href="https://ting.global/"
                        aria-current="page"
                        class="elementor-item elementor-item-active"
                        >Home</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/what-we-do-challenge/"
                        class="elementor-item"
                        >What we do</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/about-us-challenge/"
                        class="elementor-item"
                        >About us</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/articles-challenge/"
                        class="elementor-item"
                        >Articles</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/score-table/"
                        class="elementor-item"
                        >Score table</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/players-challenge/"
                        class="elementor-item"
                        >Players</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/contactus-challenge/"
                        class="elementor-item"
                        >Contact us</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/register-challenge/"
                        class="elementor-item"
                        >Register</a
                      >
                    </li>
                  </ul>
                </nav>
                <!-- <nav class="element-nav-menu-dropdown" aria-hidden="palse">
                  <ul class="element-nav-manu">
                    <li class="menu-item">
                      <a
                        href="https://ting.global/"
                        aria-current="page"
                        class="elementor-item elementor-item-active"
                        >Home</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/what-we-do-challenge/"
                        class="elementor-item"
                        >What we do</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/about-us-challenge/"
                        class="elementor-item"
                        >About us</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/articles-challenge/"
                        class="elementor-item"
                        >Articles</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/score-table/"
                        class="elementor-item"
                        >Score table</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/players-challenge/"
                        class="elementor-item"
                        >Players</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/contactus-challenge/"
                        class="elementor-item"
                        >Contact us</a
                      >
                    </li>
                    <li class="menu-item">
                      <a
                        href="https://ting.global/register-challenge/"
                        class="elementor-item"
                        >Register</a
                      >
                    </li>
                  </ul>
                </nav> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.element-section-wrap {
  background: rgb(0, 43, 90);
  /* height: 140px; */
}
.element-container {
  display: flex;
  justify-content: center;
  height: 140px;
}
.element-image {
  width: 149.594px;
  height: 60.625px;
  margin-bottom: 7px;
}
.jetpack-lazy-image {
  width: 204.984px;
  height: 121.094px;
}
.element-widget-wrap {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  /* width: 935px; */
}
.elementor-nav-menu {
  /* background: chartreuse; */
  list-style-type: none;
  list-style-position: outside;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: flex-end;
  width: 935px;
}
.elementor-item {
  display: flex;
  align-items: center;
  color: white;
  cursor: pointer;
  font-family: "Roboto", sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
  padding: 13px 20px;
}
</style>
