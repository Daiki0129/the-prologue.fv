<template>
  <div>
    <Topbar />
    <div class="container">
      <div class="block">
        <img class="img" :src="require('~/assets/img/talk2.jpg')"/>
        <div class="block">
          <h1 class="h1_subtitle1">The prologue</h1>
          <p class="p_subtitle" :position="center">シード投資家はあなたの物語のファン1号。</p>
          <p class="p_subtitle" :position="center">起業家との個別相談会</p>
          <p class="p_subtitle" :position="center">シード投資家「F Ventures（エフベンチャーズ）」とのMTGを、誰でも登録出来ます。</p>
          <p class="p_subtitle" :position="center">初めての方でも、お気軽に下記からご連絡下さい。</p>
        </div>
        <a class="a_form" href="https://docs.google.com/forms/d/e/1FAIpQLSfUOTLJO3ItHCT-CcBCwqD0FnQ3arEQWxJHzbUlKbRPvHRk9w/viewform?usp=sf_link" target="_blank">
          <el-button type="success" class="button" :position="center" x-large>
            <span class="span">
              The prologueに申し込む
            </span>
          </el-button>
        </a>
      </div>
    </div>
    <div class="container2">
      <div class="block">
        <h1 class="h1_subtitle2">
          CONCEPT
        </h1>
        <div class="container_text">
          <p class="p_subtitle" :position="center">起業家は物語を紡ぐ小説家である。</p>
          <p class="p_subtitle" :position="center">僕たちは、その物語のファン１号になりたい。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたが物語を紡ぐための筆と紙を持っていないのなら、筆と紙を送ろう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">真夏の暑さで筆が止まってしまうのなら、風を送ろう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">真冬の寒さで手がかじかんでしまうのなら、暖炉を組み立てよう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたがどうしても書けないと言うのなら、僕たちが代わりに物語を紡ごう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">そうして、六畳一間のアパートの一室からあなたの物語を始めよう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">僕たちは、あなたの紡ぐ物語を少し覗かせてもらえれば、十分なんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたの物語にはそれだけの価値があるんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">僕たちはあなたの才能と可能性とあなたの物語にすっかり惚れ込んでしまっているのだから。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">力強く書かれた言葉。</p>
          <p class="p_subtitle" :position="center">眠い目をこすりながら書かれた言葉。</p>
          <p class="p_subtitle" :position="center">涙を流しながら書き殴られた言葉。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">その全てを僕たちは読んでいたいんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">そして、いつかあなたはあなたの物語を書き上げるだろう。</p>
          <p class="p_subtitle" :position="center">その時、僕たちはあなたのそばにはいない。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">僕たちは、あなたの書き上げた物語を書店で手に取り、こっそり読むんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたの物語にはそれだけの価値があるんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたは物語が完成したら、きっとまた新しい物語を描くんだろう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">僕たちもまた、新たな物語を紡ごうとする起業家とともに、新たな物語を紡いでいるだろう。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたの物語にはそれだけの価値があるんだ。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">だが、それでいい。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">僕たちは、見たことのない景色を見たくてたまらない生き物なのだから。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">だけど、忘れないでほしい。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">あなたが新たな物語を描こうとする時、あなたにはすでに僕たちというファンがいることを。</p>
        </div>
        <div class="container_text">
          <p class="p_subtitle" :position="center">何かなくても、力になりたいと思っている人がいることを。</p>
        </div>
        <div class="container_text_end">
          <p class="p_subtitle" :position="center">あなたが新たな物語を描こうとする時、あなたにはすでに僕たちというファンがいることを。</p>
        </div>
      </div>
    </div>
    <div class="container2">
      <div class="block">
        <h1 class="h1_subtitle3">
          OVERVIEW
        </h1>
        <div class="container_text">
          <p class="p_subtitle" >所要時間：20分ほどいただければと思います！</p>
          <p class="p_subtitle" >場所：渋谷</p>
          <p class="p_subtitle" >※日程の調整は、フォーム記入後の画面に候補日程を記載したURLを表示します。</p>
          <p class="p_subtitle" >続けてURLから申請をお願いします。</p>
        </div>
      </div>
    </div>
    <div class="container2">
      <div class="block">
       <h1 class="h1_subtitle3">
          Form
        </h1>
        <form >
          <iframe class="iframe_form" src="https://docs.google.com/forms/d/e/1FAIpQLSfUOTLJO3ItHCT-CcBCwqD0FnQ3arEQWxJHzbUlKbRPvHRk9w/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0">読み込んでいます…</iframe>
        </form>
      </div>
    </div>
    <div class="container3">
      <div class="block">
        <h1 class="h1_subtitle3">
          The prologue
        </h1>
        <div class="container_text">
          <p class="p_subtitle" :position="center">まだ見ぬ起業家とその物語と出会うことが僕たちの何よりの楽しみです。</p>
          <p class="p_subtitle" :position="center">資金調達・事業の壁打ち・将来の相談、なんでも構いません。</p>
          <p class="p_subtitle" :position="center">お話していただける方は、下の申し込みフォームから、気軽にご連絡ください。</p>
          <a class="a_form" href="https://docs.google.com/forms/d/e/1FAIpQLSfUOTLJO3ItHCT-CcBCwqD0FnQ3arEQWxJHzbUlKbRPvHRk9w/viewform?usp=sf_link" target="_blank">
            <el-button type="success" class="button" :position="center" x-large>
              <span class="span">
                The prologueに申し込む
              </span>
            </el-button>
          </a>
        </div>
      </div>
    </div>
    <el-footer class="footer_el" light>
      <a class="a_icon" href="https://www.facebook.com/fventures.vc" target="_blank">
        <v-icon class="facebook_icon footer_icon" color="primary" :size="50">mdi-facebook</v-icon>
      </a>
      <a class="a_icon" href="https://twitter.com/Fventures_jp" target="_blank">
        <v-icon class="twitter_icon footer_icon" color="primary" :size="50">mdi-twitter</v-icon>
      </a>
      <a class="a_icon" href="https://www.instagram.com/toryumontokyo/" target="_blank">
        <v-icon class="instagram_icon footer_icon" color="primary" :size="50">mdi-instagram</v-icon>
      </a>
      <v-spacer></v-spacer>
      <div class="footer_copy">&copy; {{ new Date().getFullYear() }} F Ventures Capital All Right Reserved.</div>
    </el-footer>
  </div>
</template>

<script>
import ElementUI from 'element-ui'
import Vuetify from 'vuetify'
import Logo from '~/components/Logo.vue'
import Topbar from '~/components/Topbar.vue'

export default {
  components: {
    Logo,
    Topbar
  },
  data() {
    return {
      src: 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg'
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

@media screen and (max-width: 767px) {
  .img{
    width: 100%;
    height: 100%;
    max-width: 370px;
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
    margin: 10px;
    font-size: 40px;
    font-weight: bold ;
  }
  .h1_subtitle2 {
    margin: 40px 0 20px 0;
    font-size: 30px;
    color: #000;
    font-weight: bold ;
  }
  .h1_subtitle3 {
    margin: 20px;
    font-size: 40px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 3px;
    font-size: 10px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .container_text {
    margin: 20px;
  }
  .container_text_end {
    margin: 20px 20px 80px 20px;
  }
  .footer_el {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 15px;
    height: 200px;
  }
  .footer_icon {
    margin: 30px 12px 30px 12px;
  }
  .footer_copy {
    margin: 0px 0px 30px 0px;
  }
  .iframe_form {
    margin: 10px 0px 0px 0px;
    width: 350px;
    height: 2000px;
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
    margin: 10px;
    font-size: 50px;
    font-weight: bold ;
  }
  .h1_subtitle2 {
    margin: 60px 0 40px 0;
    font-size: 60px;
    color: #000;
    font-weight: bold ;
  }
  .h1_subtitle3 {
    margin: 40px;
    font-size: 60px;
    font-weight: bold ;
  }
  .p_subtitle{
    margin: 5px;
    font-size: 20px;
    color: #4d4c4c;
    font-weight: bold ;
  }
  .container_text {
    margin: 30px;
  }
  .container_text_end {
    margin: 30px 30px 150px 30px;
  }
  .footer_el {
    justify-content: center;
    align-items: center;
    text-align: center;
    display: center;
    font-size: 20px;
    margin: 150px 30px 150px 30px;
  }
  .footer_icon {
    margin: 5px 30px 80px 30px;
  }
  .iframe_form {
    margin: 10px 0px 0px 0px;
    width: 1000px;
    height: 2500px;
  }
}
</style>
