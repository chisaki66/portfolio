<template>
  <div class="main">
    <h1 class="title">CloudSign</h1>
    <div class="body">
      <a
        class="body__site-link"
        href="https://www.cloudsign.jp/"
        target="_blank"
      >
        <img class="body__site-img" src="./images/cloudsign.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>
        JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test
        Utils
      </p>
      <div class="body__subtitle">主な業務内容</div>
      <p>
        新規機能の実装<br />
        Vue 2.x => Vue 3.x にバージョンを上げるための技術負債を解消<br />
        Options API から Composition API に移行<br />
        その他機能改善やバグの修正など複数担当
      </p>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>
        ライブラリのバージョンを上げることや非推奨パッケージから推奨パッケージに移行するタスクを行う中で意識したことは、他の方が見てもわかりやすく見通しの良いコードを実装することを特に意識しました。<br />
        それと事前にライブラリの最新版で非推奨となるメソッドなどをキャッチアップして、それらのメソッドを用いない実装などを心がけていました。
      </p>
      <div class="body__subtitle">チーム内の自身の役割</div>
      <p>
        Issue
        をこなすことより、ライブラリのバージョンを上げるために必要なことを自発的に調査して、自ら
        Issue を立ててタスクを行うということを多くこなしていました。<br />
        それ以外にも、自らリポジトリ内の問題点などを洗い出して Issue
        を作成することも積極的に行なっていました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>
        サービスの課題であった非推奨パッケージの移行や古いバージョンから最新版に上げて、過去に実装された不適切なコードをドキュメントに即した実装にリファクタリングをすることで保守性の向上に貢献しました。
      </p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--link"
            href="https://www.cloudsign.jp/"
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
