<template>
  <div class="main">
    <h1 class="title">Retty (corporate website)</h1>
    <div class="body">
      <a class="body__site-link" href="https://corp.retty.me/" target="_blank">
        <img class="body__site-img" src="./images/retty-corp.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / microCMS</p>
      <div class="body__subtitle">主な業務内容</div>
      <ul class="body__list">
        <li class="body__list-title">採用情報の更新</li>
        <li class="body__list-title">静的ページの追加</li>
        <li class="body__list-title">ライブラリのアップグレード</li>
        <li class="body__list-title">
          今後Nuxt3へアップグレードするための施策とその洗い出し
        </li>
        <li class="body__list-title">microCMSの導入</li>
        <ul class="body__sublist">
          <li>外部API(microCMS)を叩いて実装</li>
          <li>ページング機能を既存の構成から置き換え</li>
          <li>カテゴリ選択と年別選択の一覧機能を追加</li>
          <li>記事詳細ページの追加</li>
          <li>Figmaを用いたコーディング</li>
          <li>Webデザイナーと協力して施策や発案</li>
        </ul>
      </ul>
      <p>
        microCMSを使用したニュースページの開発は一人で担当しました<br />
        <a href="https://corp.retty.me/news/">https://corp.retty.me/news/</a>
      </p>
      <br />
      <a class="body__site-link" href="https://corp.retty.me/news/">
        <img
          class="body__site-img-small"
          src="./images/retty-corp-news.png"
          alt=""
        />
      </a>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>
        Markdown形式のニュース一覧ページのコンテンツを追加するときにコーポレート担当部署が資料作成しそれを開発チームが追加しないといけないという手間のかかる工程であったためmicroCMSを導入することになりその開発担当を一人で請け負いました。<br />
        その中で工夫したこととして外部APIを取得するにあたり、よりデータが増えても負荷がかからないようにすることやmicroCMSの入稿者が自由にカテゴリなどを追加できるように値を固定値にせず、microCMS上の管理ページで追加した値を自動的にUIに表出するような工夫を施し、形として成果ができるだけでなく、その後の管理やユーザーの方の利用のし易さなどを意識した実装を心がけました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>
        私が入社する前まではマネージャーや開発チームのフロントエンドエンジニアが担当していましたが、入社後は私が開発者しか行えない編集業務をメインで担当しておりました。それ以外にMarkdown形式だったNewsページの投稿をコーポレート部門が追加・編集を行えるようmicroCMSの導入を行い効率化に取り組んでいました。
      </p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--link"
            href="https://corp.retty.me/"
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

  &__site-img-small {
    width: 600px;
  }

  &__subtitle {
    margin-top: 30px;
    padding-left: 0.5em;
    border-left: solid 4px #88d1e7;
    font-size: 20px;
  }

  &__list {
    margin-top: 10px;
  }

  &__list-title {
    margin-left: 15px;
  }

  &__sublist {
    margin-left: 30px;
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
