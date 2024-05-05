<template>
  <div class="main">
    <h1 class="title">しばっこ タスク管理アプリ (スマホ)</h1>
    <div class="body">
      <a class="body__site-link" target="_blank">
        <img
          class="body__site-img"
          src="./images/shiba-mobile-app_1.jpg"
          alt=""
        />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / React Native / Expo</p>
      <div class="body__subtitle">アプリの詳細</div>
      <p>
        リリースをすることを目的に、スマホアプリとデスクトップアプリで同期できる「しばっこ」というタスク管理アプリを現在開発しています。<br />
        開発途中のため、まだまだ機能を追加していく予定です。<br />
        ※当ページはスマホ版です<br />
        <br />
        アプリの概要としてはリスト一覧から特定のリストを選択するとさらにリストを追加できるようになる二階層式のタスク管理アプリです。<br />
        今後は TypeScript やユニットテストを追加して firebase
        でスマホとデスクトップの両方で管理できるようにする計画となっています。
      </p>
      <img
        class="body__detail-img"
        src="./images/shiba-mobile-app_2.jpg"
        alt=""
      />
      <p>トップのリストです</p>
      <img
        class="body__detail-img"
        src="./images/shiba-mobile-app_3.jpg"
        alt=""
      />
      <p>三点リーダーをタップするとオプションを選択できます</p>
      <img
        class="body__detail-img"
        src="./images/shiba-mobile-app_4.jpg"
        alt=""
      />
      <p>完了したタスクを打ち消し線でチェックすることが可能です</p>
      <img
        class="body__detail-img"
        src="./images/shiba-mobile-app_5.jpg"
        alt=""
      />
      <p>リストが存在しないときは「まだリストはありません！」と表示されます</p>
      <img
        class="body__detail-img"
        src="./images/shiba-mobile-app_6.jpg"
        alt=""
      />
      <p>
        トップのリストの「やること」を選択したことで「やること」のリストが表示されます
      </p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--github"
            href="https://github.com/chisaki66/shiba-mobile-app"
            target="_blank"
          >
            Github
          </a>
        </li>
        <li>
          <a class="body__block-links--link" target="_blank"> ※進行中 </a>
        </li>
      </ul>
      <div class="body__link">
        <NuxtLink class="body__link-text" to="/PersonalProject"
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
    width: 500px;
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

  &__detail-img {
    width: 300px;
    margin-top: 40px;
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
