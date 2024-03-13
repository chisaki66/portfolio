<template>
  <div class="main">
    <h1 class="title">StockChart</h1>
    <div class="body">
      <a class="body__site-link" target="_blank">
        <img class="body__site-img" src="./images/stock-chart.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / React.js</p>
      <div class="body__subtitle">アプリの詳細</div>
      <p>
        StockChart
        は検索した銘柄の株価の情報を取得する株価チャートの個人アプリです。<br />
        Nasdaq, NYSE などを含む 70 の世界的な取引所から収集された 170,000
        以上の株価の情報を取得することが可能です。(東京証券取引所は含まれていません)<br />
        指定した期間の株価情報をチャート形式で表示することが可能で、それ以外にも「始値」「高値」「安値」「終値」「出来高」の情報を表示できる仕様にしています。
      </p>
      <img
        class="body__detail-img"
        src="./images/stock-chart-period.png"
        alt=""
      />
      <p>
        株価を表示する期間は「1日」「1週」「1ヶ月」「3ヶ月」「6ヶ月」「1年」「2年」「3年」で自由に変更することが可能です
      </p>
      <img
        class="body__detail-img"
        src="./images/stock-chart-error.png"
        alt=""
      />
      <p>
        もし存在しない銘柄や何も入力しない状態でリクエストをすると「株式データの取得に失敗しました」とエラーメッセージが表出する仕様になっています
      </p>
      <div class="body__subtitle">API</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--link"
            href="https://marketstack.com/"
            target="_blank"
          >
            marketstack
          </a>
        </li>
      </ul>
      <div class="body__subtitle">Package</div>
      <p>Chart.js / react-chartjs-2 / date-fns / ESlint / Prettier</p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--github"
            href="https://github.com/chisaki66/stock-chart"
            target="_blank"
          >
            Github
          </a>
        </li>
        <li>
          <a class="body__block-links--link" target="_blank">
            <strike>SiteLink</strike>
            現在は非公開です
          </a>
        </li>
      </ul>
      <div class="body__link">
        <NuxtLink class="body__link-text" to="/project">Go Back</NuxtLink>
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
