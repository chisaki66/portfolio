<template>
  <div class="main">
    <h1 class="title">Company Project</h1>
    <div class="body">
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/rarejob">
          <img class="body__site-img" src="./images/rarejob.png" alt="" />
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">
            レアジョブ英会話<span class="body__block-hashtag"># company</span>
          </div>
          <div class="body__skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Vite /
            Storybook / Swagger
          </div>
          <p class="body__text">
            株式会社レアジョブテクノロジーズのフロントエンドエンジニアとしてレアジョブ英会話の開発に従事していました。<br />
            レアジョブ英会話はインターネットを使ったオンライン英会話サービスで、ホスピタリティ溢れるフィリピン人講師の高品質なレッスンを提供できるサービスです。
          </p>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/rarejob"
              >Find Out More</NuxtLink
            >
          </div>
        </div>
      </div>
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/cloudsign">
          <img class="body__site-img" src="./images/cloudsign.png" alt="" />
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">
            CloudSign<span class="body__block-hashtag"># company</span>
          </div>
          <div class="body__skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Vite / Jest /
            Vue Test Utils / Storybook
          </div>
          <p class="body__text">
            弁護士ドットコム株式会社のフロントエンドエンジニアとして電子契約サービスの
            CloudSign の開発に従事していました。<br />
            CloudSign は Web
            完結型の契約締結クラウドアプリケーションで、契約締結の他に保管・管理に使用ができ、発注書・請書・納品書・検収書・
            請求書・領収書など、さまざまな対外的なやりとりに活用できるアプリです。
          </p>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/cloudsign"
              >Find Out More</NuxtLink
            >
          </div>
        </div>
      </div>
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/retty">
          <img class="body__site-img" src="./images/retty.png" alt="" />
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">
            Retty<span class="body__block-hashtag"># company</span>
          </div>
          <div class="body__skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue
            Test Utils / PHP / GraphQL
          </div>
          <p class="body__text">
            Retty 株式会社のフロントエンドエンジニアとして主に Web
            アプリケーションとコーポレートサイトの開発業務に従事していました。<br />
            Retty
            はユーザーの皆様の「オススメのお店」の情報が集まる実名型グルメサービスです。
          </p>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/retty"
              >Find Out More</NuxtLink
            >
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
  padding-bottom: 80px;

  &__block {
    margin-top: 80px;
    display: flex;
  }

  &__img-link:hover {
    opacity: 0.5;
    transition: 0.3s;
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
    color: #f9f9f9;
    text-shadow: 1px 1px 2px #00858d;
    background-color: #42c9f3;
    font-size: 14px;
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
    transition: all 0.6s ease;
  }

  &__link-text:hover {
    color: #f9f9f9;
    text-shadow: 1px 1px 2px #00858d;
    background-color: #42c9f3;
    border: solid 2px #42c9f3;
  }

  &__app-links {
    margin-top: 10px;

    li {
      list-style: none;
      margin-top: 10px;
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

    &--github {
      background-size: 30px;
      background-image: url(./images/github.png);
    }

    &--link {
      background-size: 24px;
      background-image: url(./images/link.png);
    }
  }
}
</style>
