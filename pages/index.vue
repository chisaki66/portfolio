<template>
  <div class="main">
    <h1 class="title">Profile</h1>
    <div class="body">
      <img class="body__profile-img" src="./images/profile-pic.jpg" />
      <div>
        <div class="body__block">
          <div class="body__subtitle">Name</div>
          <p>Chisaki Ibe</p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Skilled</div>
          <p>
            JavaScript / React.js / React Native / Vue.js / Nuxt.js / TypeScript
            / Node.js / Vite / Jest / Vue Test Utils / PHP / Ruby / Ruby on
            Rails / GraphQL / Storybook / Swagger / HTML5 / CSS3 and SASS / Expo
            / Electron
          </p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Environment</div>
          <p>
            GitHub / GitLab / Slack / Chatwork / JIRA / Confluence / esa /
            Discord / oVice
          </p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Introduction</div>
          <p>
            フロントエンドエンジニアとして Vue.js/Nuxt.js を中心とした
            3年の実務経験があります。<br />
            新規機能の開発からリファクタリングまで幅広く対応を行ってきた経験を活かして、現在は個人プロジェクトで
            React.js と React Native を使用したアプリを開発しています。<br />
            そのため Vue も React
            も汎用的に使いこなし、様々なタスクをこなすことが可能です。
          </p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Links</div>
          <ul class="body__block-links">
            <li>
              <a
                class="body__block-links--github"
                href="https://github.com/chisaki66"
                target="_blank"
                >GitHub</a
              >
            </li>
            <!-- <li>
              <a
                class="body__block-links--linkedin"
                href="https://www.linkedin.com/in/chisaki-ibe-91494b239/"
                target="_blank"
                >LinkedIn</a
              >
            </li> -->
            <li>
              <a
                class="body__block-links--wantedly"
                href="https://www.wantedly.com/id/chisaki0606"
                target="_blank"
                >Wantedly</a
              >
            </li>
          </ul>
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
  padding: 40px 0;
  box-sizing: border-box;

  &__block {
    margin-top: 40px;

    p {
      margin-top: 8px;
    }
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

    &--github {
      background-size: 30px;
      background-image: url(./images/github.png);
    }

    &--linkedin {
      background-size: 30px;
      background-image: url(./images/linkedin.png);
    }

    &--wantedly {
      background-size: 24px;
      background-image: url(./images/link.png);
    }
  }

  &__profile-img {
    width: 300px;
  }

  &__subtitle {
    padding-left: 0.5em;
    border-left: solid 4px #88d1e7;
    font-size: 20px;
  }

  &__icon {
    width: 30px;
  }
}
</style>
