<template>
  <div class="main">
    <h1 class="title">Retty (LP制作)</h1>
    <div class="body">
      <a
        class="body__site-link"
        href="https://drive.google.com/file/d/1yw7oKruFQfvEabF89RVjnVgqGGmNS_il/view"
        target="_blank"
      >
        <img class="body__site-img" src="./images/retty-lp.png" alt="" />
      </a>
      <div class="body__subtitle">Skilled</div>
      <p>HTML5 / CSS3 and SASS / Figma</p>
      <div class="body__subtitle">主な業務内容</div>
      <ul class="body__list">
        <li class="body__list-title">
          BEMとSCSSを用いたコーディング&コンパイル
        </li>
        <li class="body__list-title">
          Figmaを用いたデザインカンプからのコーディング
        </li>
        <li class="body__list-title">
          レスポンシブ対応&ワイドモニターに対応したUI設計
        </li>
        <li class="body__list-title">動きをつけたUX向上</li>
      </ul>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>
        HTMLとCSSで構成した単一ファイルでデザイナーに渡す予定でしたがBEMとSCSSを用いてそれをコンパイルするというやり方で効率化や作業スピードを意識した実装に努めました。それ以外にもPCとデバイス端末以外のもワイドモニターで見たときに崩れないようにすることを心がけました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>
        Googleのオンライン広告として活用することでオーナー様の利用拡大に貢献しました。<br />
        それとデザイナーではコーディングできない内容で、その上サービスの実装で忙しい開発チームの作業ペースを落とさずに制作できたため開発チームのサポートに徹することができました。
      </p>
      <div class="body__subtitle">Link</div>
      <ul class="body__block-links">
        <li>
          <a
            class="body__block-links--link"
            href="https://drive.google.com/file/d/1yw7oKruFQfvEabF89RVjnVgqGGmNS_il/view"
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

  &__list {
    margin-top: 10px;
  }

  &__list-title {
    margin-left: 15px;
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
