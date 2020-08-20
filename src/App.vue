<template>
  <div id="app">
    <header class="header">
      <div class="header-all">
        <div class="header-wrap">
          <router-link to="/" class="logo">
            <img src="https://mysugarshop.ca/wp-content/uploads/2016/08/Pink-Small.png">
          </router-link>
            <div class="header-nav">
                <a class="active" href="/">Главная</a>
                <a href="/service">Услуги</a>
                <a href="/contact">Контакты</a>
            </div>
          <div class="header-unit">
            <span>г.Винница</span>
            <ul class="phone-list">
              <li>
                <span>
                  +38(067)942 89 37
                </span>
              </li>
              <li>
                <span>
                  +38(063)883 67 33
                </span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
    <router-view />
    <footer class="footer">
      <div class="footer-wrap">
        <div class="footer-unit">
          <span>
            Бесплатная консультация:
            <ul class="phone-list">
              <li>
                <span>
                  +38(067)942 89 37
                </span>
              </li>
              <li>
                <span>
                  +38(063)883 67 33
                </span>
              </li>
            </ul>
          </span>
        </div>
      </div>
    </footer>
  </div>

</template>
<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  box-sizing: border-box;
  margin: 0 auto;
  width: 80%;
}
.header{
  overflow: hidden;
}
.header img{
  display: flex;
  max-width: 50px;
  max-height: 50px;
  padding: 5px;
}
.header a{
  float: left;
  color: black;
  text-align: center;
  padding: 15px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
}
.header-nav{
  padding: 20px 10px;
}
li{
  list-style: none;
}
.header-unit, .footer-unit{
  float: right;
}
footer{
  margin-top: 10px;
    border-top: 1px solid #000524;
  }
  .footer-unit{
    margin-top: 10px;
  }
</style>
