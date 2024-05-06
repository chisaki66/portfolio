<template>
  <div class="main">
    <h1 class="title">レアジョブ英会話</h1>
    <div class="body">
      <a
        class="body__site-link"
        href="https://www.rarejob.com/"
        target="_blank"
      >
        <img class="body__site-img" src="./images/rarejob.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js</p>
      <div class="body__subtitle">主な業務内容</div>
      <p>
        新規機能の実装<br />
        Vue 2.x => Vue 3.x にバージョンを上げるための技術負債を解消<br />
        Chat Bot をスクラッチで開発するための設計と実装
      </p>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>
        新規に機能を追加する際に保守性やわかりやすさなどを特に意識しながら開発を行っています。<br />
        具体的に行ったこととしてメンテナンスされていないパッケージの使用を避けることや不要なコードを増やさないように注意を払いながら設計を考慮して実装しています。
      </p>
      <div class="body__subtitle">チーム内の自身の役割</div>
      <p>
        技術負債を洗い出してそれに応じたリファクタや新規に機能を追加することやリポジトリ内のサポートが終了となったパッケージなどを見つけて変更することを提案するなどを行ってきました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>
        Vue3.x
        でサービスを稼働させることと保守性を高めることに成功しています。<br />
        加えてチーム内で気づけなかった技術負債を見つけてそれらを解消することにも貢献しています。
      </p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--link"
            href="https://www.rarejob.com/"
            target="_blank"
          >
            SiteLink
          </a>
        </li>
      </ul>
      <div class="body__link">
        <NuxtLink class="body__link-text" to="/CompanyProject"
          >Go Back</NuxtLink
        >
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
    opacity: 0.5;
    transition: 0.3s;
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

  &__block-links {
    margin-top: 16px;

    li {
      list-style: none;
      margin-top: 14px;
    }

    a {
      text-decoration: none;
      color: #333333;
      padding-top: 20px;
      padding-bottom: 20px;
      padding-left: 34px;
      background-position: left center;
      background-repeat: no-repeat;
    }

    a:hover {
      opacity: 0.5;
      transition: 0.3s;
    }

    &--link {
      background-size: 24px;
      background-image: url(./images/link.png);
    }
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
    transition: all 0.6s ease;
  }

  &__link-text:hover {
    color: #f9f9f9;
    text-shadow: 1px 1px 2px #00858d;
    background-color: #42c9f3;
    border: solid 2px #42c9f3;
  }
}
</style>
