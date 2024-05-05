<template>
  <div class="main">
    <h1 class="title">Personal Project</h1>
    <div class="body">
      <div class="body__block">
        <NuxtLink class="body__img-link" to="/stockchart">
          <img class="body__site-img" src="./images/stock-chart.png" alt="" />
        </NuxtLink>
        <div class="body__block-right">
          <div class="body__subtitle">
            StockChart<span class="body__block-hashtag"># personal</span>
          </div>
          <div class="body__skilled">JavaScript / React.js</div>
          <p class="body__text">
            検索した銘柄の株価の情報を取得する株価チャートの個人アプリです。<br />
            指定した期間の株価情報をチャート形式で表示します。
          </p>
          <ul class="body__app-links">
            <li>
              <a
                class="body__app-links--github"
                href="https://github.com/chisaki66/stock-chart"
                target="_blank"
                >GitHub</a
              >
            </li>
            <li>
              <a class="body__app-links--link" target="_blank">
                <strike>SiteLink</strike>
                現在は非公開です
              </a>
            </li>
          </ul>
          <div class="body__link">
            <NuxtLink class="body__link-text" to="/stockchart"
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
