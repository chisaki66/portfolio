<template>
  <div class="main">
    <h1 class="title">Allies</h1>
    <div class="body">
      <a class="body__site-link" target="_blank">
        <img class="body__site-img" src="./images/allies_1.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>Ruby / Ruby on Rails</p>
      <div class="body__subtitle">アプリの詳細</div>
      <p>
        立案から設計、実装そして公開（現在は非公開）までを工程を行いました。性的マイノリティ向けのオリジナルのマッチングサイトになります。
      </p>
      <img class="body__detail-img" src="./images/allies_2.png" alt="" />
      <p>ユーザー詳細ページ</p>
      <img class="body__detail-img" src="./images/allies_3.png" alt="" />
      <p>DM一覧ページ</p>
      <img class="body__detail-img" src="./images/allies_4.png" alt="" />
      <p>サイトコンセプトページ</p>
      <img class="body__detail-img" src="./images/allies_5.png" alt="" />
      <p>サイトマップ</p>
      <img class="body__detail-img" src="./images/allies_6.png" alt="" />
      <p>コンテンツの概要</p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--github"
            href="https://github.com/chisaki66/allies"
            target="_blank"
          >
            Github
          </a>
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
    width: 600px;
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
    width: 500px;
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
