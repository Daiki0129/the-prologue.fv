<template>
  <v-app light>
    <nuxt />
    <v-footer class="footer_v" light>
        <a class="a_icon" href="https://www.facebook.com/fventures.vc" target="_blank">
        <v-icon class="footer_icon" :size="50" :style="{ color: '#808080' }">mdi-facebook</v-icon>
      </a>
      <a class="a_icon" href="https://twitter.com/Fventures_jp" target="_blank">
        <v-icon class="footer_icon" :size="50" :style="{ color: '#808080' }">mdi-twitter</v-icon>
      </a>
      <a class="a_icon" href="https://www.instagram.com/toryumontokyo/" target="_blank">
        <v-icon class="footer_icon" :size="50" :style="{ color: '#808080' }">mdi-instagram</v-icon>
      </a>
      <div class="footer_copy">&copy; {{ new Date().getFullYear() }} F Ventures All Rights Reserved.</div>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>

<style>
.container {
  width: 100%;
  height: 100%;
  max-width: 300vh;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-image: url("../assets/img/toryumon.jpg");
}
.container2 {
  width: 100%;
  height: 100%;
  max-width: 300vh;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-image: url("../assets/img/the_prologue2.jpg");
}
.container3 {
  width: 100%;
  height: 100%;
  max-width: 300vh;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-image: url("../assets/img/fventures_ryokadosan1.jpg");
}
.container4 {
  width: 100%;
  height: 100%;
  max-width: 300vh;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  background-image: url("../assets/img/the_prologue4.jpg");
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: flex;
  font-weight: 300;
  font-size: 500%;
  margin-bottom: 10px;
  color: #909090;
}
.subtitle {
  font-weight: 300;
  font-size: 200%;
  color: #f3efef;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
.button {
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 25px 60px;
  margin: 40px;
  display: center;
}
.span {
  justify-content: center;
  align-items: center;
  text-align: center;
  display: center;
  font-size: 25px
}
.a_form {
  text-decoration: none;
  color: "#fff"
}
.a_icon {
  text-decoration: none;
  color: "#fff"
}
.span_subtitle1 {
  color: rgb(0, 183, 255);
}

@media screen and (max-width: 767px) {
  .img{
    width: 100%;
    height: 100%;
    max-width: 360px;
    min-height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .button {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 30px;
    margin: 20px;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 15px
  }
  .h1_subtitle1{
    margin: 25px 0px 25px 0px;
    font-size: 43px;
    font-weight: bold ;
  }
  .h1_subtitle2 {
    margin: 50px 0 50px 0;
    font-size: 43px;
    color: #000;
    font-weight: bold ;
  }
  .h1_subtitle3 {
    margin: 20px;
    font-size: 43px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 3px;
    font-size: 10px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .p_subtitle3 {
    margin: 8px;
    font-size: 12px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .container_text {
    margin: 20px;
  }
  .container_text3 {
    margin: 45px 15px 10px 15px;
    text-align: center;
  }
  .container_text_end {
    margin: 20px 20px 80px 20px;
  }
  .footer_v {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 20px;
  }
  .footer_icon {
    text-decoration: none;
    margin: 30px 12px 30px 12px;
  }
  .footer_copy {
    margin: 0px 0px 60px 0px;
  }
  .iframe_form {
    margin: 10px 0px 0px 0px;
    width: 350px;
    height: 2000px;
  }
  .button_container1 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 50px;
    margin: 20px 0;
    display: center;
  }
  .button_container3 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 20px;
    margin: 60px 0px 40px 0px;
    display: center;
  }
  .button_tweet_container1 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 20px;
    margin: 40px;
    display: center;
  }
  .span_container1 {
    font-size: 20px;
    font-weight: bold ;
  }
  .span_container3 {
    font-size: 20px;
    font-weight: bold ;
  }
  .span_tweet_container1 {
    padding: 0px 20px 10px 0px;
    color: rgb(0, 183, 255);
    font-size: 25px;
    font-weight: bold ;
  }
  .twitter_icon {
    text-decoration: none;
    color: rgb(0, 183, 255);
    padding: 0px 5px 15px 0px;
    margin: 0px;
  }
}

@media screen and (min-width:768px) {
  .img{
    margin-top: 150px;
    width: 100%;
    height: 100%;
    max-width: 800px;
    min-height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .button {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 25px 60px;
    margin: 40px;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 30px
  }
  .h1_subtitle1 {
    margin: 100px 0px 50px 0px;
    font-size: 100px;
    font-weight: bold ;
  }
  .h1_subtitle2 {
    margin: 100px 0 100px 0;
    font-size: 70px;
    color: #000;
    font-weight: bold ;
  }
  .h1_subtitle3 {
    margin: 40px;
    font-size: 70px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 5px;
    font-size: 20px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .p_subtitle3{
    margin: 15px;
    font-size: 20px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .container_text {
    margin: 30px;
  }
  .container_text3 {
    margin: 130px 0px 10px 110px;
    text-align: left;
  }
  .container_text_end {
    margin: 30px 30px 150px 30px;
  }
  .footer_v {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    padding: 100px 500px 100px 500px;
    font-size: 20px;
  }
  .footer_icon {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    margin: 5px 30px 80px 30px;
  }
  .iframe_form {
    margin: 10px 0px 0px 0px;
    width: 1000px;
    height: 2500px;
  }
  .button_container1 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 30px 60px;
    margin: 20px 0;
    display: center;
  }
  .button_container3 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 30px 100px;
    margin: 70px 0px 40px 0px;
    display: center;
  }
  .button_tweet_container1 {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 10px 135px;
    margin: 0px;
    display: center;
  }
  .span_container1 {
    font-size: 30px;
    font-weight: bold ;
  }
  .span_container3 {
    font-size: 30px;
    font-weight: bold ;
  }
  .span_tweet_container1 {
    padding: 40px 0px 10px 0px;
    color: rgb(0, 183, 255);
    font-size: 40px;
    font-weight: bold ;
  }
  .twitter_icon {
    padding: 0px 10px 20px 0px;
    margin: 0px;
  }
}
</style>
