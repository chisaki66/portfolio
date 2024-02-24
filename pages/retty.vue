<template>
  <div class="main">
    <h1 class="title">Retty</h1>
    <div class="body">
      <img class="body__site-img" src="./images/retty.png" alt="">
      <div class="body__subtitle">Skilled</div>
      <p>JavaScript / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test Utils / PHP / GraphQL</p>
      <div class="body__subtitle">主な業務内容</div>
      <p>
        Vue.jsを用いた機能追加・編集<br>
        TypeScriptを用いたNuxt.jsプロジェクトの経験や機能追加・編集<br>
        Jestとvue-test-utilsを使ったユニットテストの追加・編集<br>
        サービス向上のためのUI改善<br>
        サービスの改善や機能編集などの思索や提案(それに伴い自らIssueを作成し編集)<br>
        外部APIから取得したデータを用いた実装<br>
        PHPのコードをVue.jsに移行<br>
        ESLintやStylelintなどのLintツールの導入<br>
        ​​報告の上がったフロントエンドまわりのバグの修正<br>
        PHPの機能追加<br>
        リリース準備の検証<br>
        バックエンドで実装したGraphQLのデータをフロントエンドに反映
      </p>
      <div class="body__subtitle">技術的なアプローチや工夫した点</div>
      <p>ただ形としてタスクをこなすだけでなく自分の実装の後に他の開発者が見て理解できるかバグが起きにくいか関数名などで役割が理解され易いかなど良質なコードを書くことを常に意識しておりました。登録店舗の情報によってはデータの扱いが変わってくるものなどもあり、それらがバグの原因となったりUIが崩れてしまうことがあるためコードを良く理解し、自分の実装が与える影響などを常に考えることを習慣としておりました。</p>
      <div class="body__subtitle">チーム内の自身の役割</div>
      <p>
        主に私の役割としては開発チーム内のサポートに徹して技術的な負債を減らしたり、開発のし易さに貢献することになります。<br>
        他部署からのフロントエンドのバグの報告に対応したり、自らIssueを確認して優先度の高いものから編集を行うことをしておりました。
      </p>
      <div class="body__subtitle">取り組みの成果</div>
      <p>私が入社してから今に至るまでに貢献したことの一つとして先延ばしにされていたNuxt.jsへの移行タスクの多くを消化したことやライブラリのアップグレード、小さなバグや開発者しか行えないコーポレートサイトの編集業務を受け持つことで開発チームの稼働率を向上させることに貢献しました。</p>
      <div class="body__subtitle">Link</div>
        <a href="https://retty.me/" target="_blank">
          <p>https://retty.me/</p>
        </a>
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
  padding: 40px 0;

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

  a {
    text-decoration: none;
  }
}
</style>
