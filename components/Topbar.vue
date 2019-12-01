<template>
  <div>
    <v-app-bar
      :color="primary"
      fixed
      prominent
      elevate-on-scroll
    >
      <v-toolbar-title class="image">
        <a class="a_icon" href="https://f-ventures.vc" target="_blank">
          <el-image :src="require('~/assets/img/F-Ventures_logo2.png')" />
          <!-- <span class="span_icon">とは？</span> -->
        </a>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <!-- <a class="a_form" href="https://twitter.com/Fventures_jp" target="_blank">
        <el-button type="primary" class="nav_button_twitter" large>
          <v-icon class="twitter_icon" :color="primary">mdi-twitter</v-icon>
          <span color="primary">Twitter</span>
        </el-button>
      </a> -->
      <a class="a_form" href="https://docs.google.com/forms/d/e/1FAIpQLSfUOTLJO3ItHCT-CcBCwqD0FnQ3arEQWxJHzbUlKbRPvHRk9w/viewform?usp=sf_link" target="_blank">
        <el-button type="primary" class="nav_button_send" large>
          <i class="el-icon-loading"></i>
          The prologueに申し込む
        </el-button>
      </a>
    </v-app-bar>
  </div>
</template>

<script>

import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
  },
  data() {
    return {
      activeIndex: '1',
      activeIndex2: '1',
      dialog: false,
    };
  },
  methods: {
    handleSelect(key, keyPath) {
      console.log(key, keyPath);
    },
    open() {
      this.$alert(
        <Logo/>
        ,'HTML String', {
        dangerouslyUseHTMLString: true,
        showConfirmButton: false
      });
    }
  }
}
</script>

<style>
  .container {
    width: 100%;
    height: 100%;
  }
  .image {
    width: 400px;
    margin: 15px;
    display: block;
  }
  .menu {
    margin: 15px;
    padding: 30px;
    text-align: right;
  }
  .twitter {
    margin: 40px 40px 0px 60px;
  }
  .twitter_icon {
    padding: 0 5px 0 0;
  }
  .button {
    color: "#fff"
  }
  .a_form {
    text-decoration: none;
    color: "#fff"
  }
  .a_icon {
    text-decoration: none;
    color: "#fff"
  }

  @media screen and (max-width: 767px) {
  .img{
    width: 100%;
    height: 100%;
    max-width: 375px;
    min-height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .nav_button_send {
    display: none;
  }
  .nav_button_twitter {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 10px 15px 10px 10px;
    margin: 55px 0px 20px 10px;
    font-size: 15px;
    font-weight: bold;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 15px
  }
  .h1_subtitle{
    margin: 10px;
    font-size: 40px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 3px;
    font-size: 10px;
    font-weight: bold ;
  }
  .a_icon {
    text-decoration: none;
    color: "#fff"
  }

  .span_icon {
    margin: 0px 10px 0px 290px;
    font-size: 20px;
    font-weight: bold ;
    text-decoration: none;
    color: "#fff"
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
  .nav_button_send {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 18px;
    margin: 30px;
    font-size: 17px;
    font-weight: bold ;
    display: center;
  }
  .nav_button_twitter {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px 50px 15px 30px;
    margin: 30px;
    font-size: 20px;
    font-weight: bold ;
    display: center;
  }
  .span {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 30px
  }
  .h1_subtitle{
    margin: 10px;
    font-size: 50px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 5px;
    font-size: 20px;
    font-weight: bold ;
  }
  .span_icon {
    margin: 10px;
    font-size: 40px;
    font-weight: bold ;
    text-decoration: none;
    color: "#fff"
  }
}
</style>