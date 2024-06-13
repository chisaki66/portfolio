<template>
  <div class="main">
    <h1 class="title">Career</h1>
    <div class="body">
      <div class="body__block">
        <div class="body__subtitle">株式会社レアジョブテクノロジーズ</div>
        <img class="body__site-img" src="./images/rarejob.png" alt="" />
        <div class="body__text">
          <p class="body__text-period">Apr 2024 to May 2024</p>
          <p class="body__text-skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Storybook /
            Swagger
          </p>
          <br />
          <p>
            株式会社レアジョブテクノロジーズのフロントエンドエンジニアとしてオンライン英会話サービスの開発に従事していました。<br />
            ※短期間である理由は早めにプロジェクトが完了したためです
          </p>
          <br />
          <a href="https://www.wantedly.com/id/chisaki0606" target="_blank"
            >詳細な情報はこちら (Wantedly)</a
          >
        </div>
      </div>
      <div class="body__block">
        <div class="body__subtitle">
          弁護士ドットコム株式会社 (CloudSign 開発事業部)
        </div>
        <img class="body__site-img" src="./images/cloudsign.png" alt="" />
        <div class="body__text">
          <p class="body__text-period">Dec 2022 to Feb 2024</p>
          <p class="body__text-skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue
            Test Utils / Storybook
          </p>
          <br />
          <p>
            弁護士ドットコム株式会社のフロントエンドエンジニアとして電子契約サービスの
            CloudSign の開発に従事していました。
          </p>
          <br />
          <a href="https://www.wantedly.com/id/chisaki0606" target="_blank"
            >詳細な情報はこちら (Wantedly)</a
          >
        </div>
      </div>
      <div class="body__block">
        <div class="body__subtitle">Retty 株式会社</div>
        <img class="body__site-img" src="./images/retty.png" alt="" />
        <div class="body__text">
          <p class="body__text-period">Apr 2021 to Dec 2022</p>
          <p class="body__text-skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue
            Test Utils / PHP / GraphQL
          </p>
          <br />
          <p>
            Retty 株式会社のフロントエンドエンジニアとして主に
            日本最大級の実名型グルメサービス Retty の開発に従事していました。
          </p>
          <br />
          <a href="https://www.wantedly.com/id/chisaki0606" target="_blank"
            >詳細な情報はこちら (Wantedly)</a
          >
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
  box-sizing: border-box;
}

.title {
  padding-left: 0.5em;
  border-left: solid 5px #88d1e7;
}

.body {
  padding-bottom: 60px;
  box-sizing: border-box;

  &__block {
    margin-top: 60px;
  }

  &__subtitle {
    padding-left: 0.5em;
    border-left: solid 4px #88d1e7;
    font-size: 24px;
  }

  &__site-img {
    width: 400px;
    margin-top: 20px;
  }

  &__text {
    margin-top: 20px;

    a {
      text-decoration: none;
      color: #333333;
      padding-top: 20px;
      padding-bottom: 20px;
      padding-left: 34px;
      background-size: 24px;
      background-position: left center;
      background-repeat: no-repeat;
      background-image: url(./images/link.png);
    }

    a:hover {
      opacity: 0.5;
      transition: 0.3s;
    }
  }

  &__text-period {
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 34px;
    background-position: left center;
    background-repeat: no-repeat;
    background-size: 24px;
    background-image: url(./images/calendar.png);
  }

  &__text-skilled {
    margin-top: 10px;
  }
}
</style>
