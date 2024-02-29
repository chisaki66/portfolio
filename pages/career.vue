<template>
  <div class="main">
    <h1 class="title">Career</h1>
    <div class="body">
      <div class="body__block">
        <div class="body__subtitle">
          弁護士ドットコム株式会社 (CloudSign 開発事業部)
        </div>
        <img class="body__site-img" src="./images/cloudsign.png" alt="" />
        <div class="body__text">
          <p>Dec 2022 to Feb 2024</p>
          <p class="body__text-skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue
            Test Utils
          </p>
          <br />
          <p>
            弁護士ドットコム株式会社のフロントエンドエンジニアとして電子契約サービスの
            CloudSign の開発に従事していました。<br />
            主な担当業務は Vue
            のバージョンアップを行うチームに所属し、リファクタリング系のタスクなどを中心にサービスの保守・運用を行なっていました。
          </p>
          <br />
          <a href="https://www.wantedly.com/id/chisaki0606" target="_blank"
            >詳細な情報はこちら (Wantedly のページリンク)</a
          >
        </div>
      </div>
      <div class="body__block">
        <div class="body__subtitle">Retty Inc.</div>
        <img class="body__site-img" src="./images/retty.png" alt="" />
        <div class="body__text">
          <p>Apr 2021 to Dec 2022</p>
          <p class="body__text-skilled">
            JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue
            Test Utils / PHP / GraphQL
          </p>
          <br />
          <p>
            Retty 株式会社のフロントエンドエンジニアとして主に Web
            アプリケーションとコーポレートサイトの開発業務を任せて頂いていました。<br />
            それ以外にも LP ページのコーディングや Python
            を用いた登録店舗のデータ収集を行うなど精力的に業務に従事していました。
          </p>
          <br />
          <a href="https://www.wantedly.com/id/chisaki0606" target="_blank"
            >詳細な情報はこちら (Wantedly のページリンク)</a
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
  padding: 40px 0 60px;
  box-sizing: border-box;

  &__block {
    margin-top: 30px;
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
    }
  }

  &__text-skilled {
    margin-top: 10px;
  }
}
</style>
