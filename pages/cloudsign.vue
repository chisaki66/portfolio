<template>
  <div class="main">
    <h1 class="title">CloudSign</h1>
    <div class="body">
      <a class="body__site-link" href="https://www.cloudsign.jp/" target="_blank">
        <img class="body__site-img" src="./images/cloudsign.png" alt="">
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test Utils</p>      
      <div class="body__subtitle">主な業務内容</div>
      <p>
        Vue 2.6 => Vue 2.7 => Vue 3.x にバージョンを上げるためのリファクタリング<br>
        ESlint, Stylelint, Prettier のバージョンを上げるためのリファクタリング<br>
        Moment.js  から data-fns に移行 (主に一人で担当)<br>
        Options API から Composition API に移行<br>
        その他機能改善やバグの修正など複数担当
      </p>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>
        ライブラリのバージョンを上げることや非推奨パッケージから推奨パッケージに移行するタスクを行う中で意識したことは、他の方が見てもわかりやすく見通しの良いコードを実装することを特に意識しました。<br>
        それと事前にライブラリの最新版で非推奨となるメソッドなどをキャッチアップして、それらのメソッドを用いない実装などを心がけていました。
      </p>
      <div class="body__subtitle">チーム内の自身の役割</div>
      <p>
        Issue をこなすことより、ライブラリのバージョンを上げるために必要なことを自発的に調査して、自ら Issue を立ててタスクを行うということを多くこなしていました。<br>
        それ以外にも、自らリポジトリ内の問題点などを洗い出して Issue を作成することも積極的に行なっていました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>
        サービスの課題であった非推奨パッケージの移行や古いバージョンから最新版に上げることなどを幅広く行いました。<br>
        そのため CloudSign の開発に携わる他のエンジニアの方が集中して新規機能などの実装を行えるよう、安定して運用を支えることに貢献しました。    
      </p>
      <div class="body__subtitle">Link</div>
      <a href="https://www.cloudsign.jp/" target="_blank">
        <p>https://www.cloudsign.jp/</p>
      </a>
      <div class="body__link">
        <NuxtLink class="body__link-text" to="/project">Go Back</NuxtLink>
      </div>      
    </div>
  </div>
</template>

<style lang="scss" scoped>
.main {
  width: 100%;
  height: 100vh;
  padding: 60px 60px 60px 320px;
}

.title {
  padding-left: 0.5em;
  border-left: solid 5px #88d1e7;  
}

.body {
  padding: 40px 0 80px;

  &__site-link:hover {
    opacity:0.5;
	  transition:0.3s;
  }  

  &__site-img {
    width: 700px;
  }

  &__subtitle {
    margin-top: 30px;
    padding-left: 0.5em;
    border-left: solid 4px #88d1e7;
    font-size: 20px;   
  }

  p {
    margin-top: 12px;
  }

  a {
    text-decoration: none;
  }

  &__link {
    margin-top: 80px;
  }

  &__link-text {
    text-decoration: none;
    padding: 16px;
    border: solid 2px #56b7d4;
    color: #56b7d4;
    border-radius: 8px;
    -webkit-transition: all 0.6s ease;
    -moz-transition: all 0.6s ease;
    -o-transition: all 0.6s ease;
    transition: all  0.6s ease;    
  }

  &__link-text:hover {
    color: #F9F9F9;
    text-shadow: 1px 1px 2px #00858d;
    background-color: #42c9f3;
    border: solid 2px #42c9f3;
  }
}
</style>
