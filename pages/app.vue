<template>
  <div class="main">
    <h1 class="title">App</h1>
    <div class="body">
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/cloudsign">
          <img class="body__site-img" src="./images/cloudsign.png" alt="">
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">CloudSign<span class="body__block-hashtag"># company</span></div>
          <div class="body__skilled">JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test Utils</div>
          <p class="body__text">
            Vue 2.6 => Vue 2.7 => Vue 3.x にバージョンを上げるためのリファクタリング<br>
            ESlint, Stylelint, Prettier のバージョンを上げるためのリファクタリング<br>
            Moment.js  から data-fns に移行 (主に一人で担当)<br>
            (その他の詳細は下記のリンクをクリックしてご覧ください)
          </p>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/cloudsign">Find Out More</NuxtLink>
          </div>
        </div>
      </div>
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/retty">
          <img class="body__site-img" src="./images/retty.png" alt="">
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">Retty<span class="body__block-hashtag"># company</span></div>
          <div class="body__skilled">JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test Utils / PHP / GraphQL</div>
          <p class="body__text">
            Vue.jsを用いた機能追加・編集<br>
            TypeScriptを用いたNuxt.jsプロジェクトの経験や機能追加・編集<br>
            Jestとvue-test-utilsを使ったユニットテストの追加・編集<br>
            (その他の詳細は下記のリンクをクリックしてご覧ください)
          </p>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/retty">Find Out More</NuxtLink>
          </div>
        </div>
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
  padding-bottom: 40px;

  &__block {
    margin-top: 80px;
    display: flex;
  }

  &__img-link:hover {
    opacity:0.5;
	  transition:0.3s;
  }

  &__site-img {
    width: 400px;
  }

  &__block-right {
    margin-left: 40px;
  }

  &__subtitle {
    font-size: 24px;
  }
  
  &__block-hashtag {
    font-size: 14px;
    color: #F9F9F9;
    text-shadow: 1px 1px 2px #00858d;
    background-color: #42c9f3;
    margin-left: 20px;
    padding: 6px;
    border-radius: 8px;
  }

  &__skilled {
    margin-top: 10px;
  }

  &__text {
    margin-top: 10px;
    font-size: 14px;
  }

  &__link {
    margin-top: 30px;
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
