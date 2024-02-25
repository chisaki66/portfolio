<template>
  <div class="main">
    <h1 class="title">Profile</h1>
    <div class="body">
      <img class="body__profile-img" src="./images/profile-pic.jpg">
      <div>
        <div class="body__block">
          <div class="body__subtitle">Name</div>
          <p>Chisaki Ibe</p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Skilled</div>
          <p>JavaScript / React.js / Vue.js / Nuxt.js / TypeScript / Node.js / Jest / Vue Test Utils / PHP / GraphQL / HTML5 / CSS3 and SASS</p>
        </div>        
        <div class="body__block">
          <div class="body__subtitle">Introduction</div>
          <p>
            フロントエンドエンジニアとして 3年の実務経験があり、主に Vue.js/Nuxt.js を得意としています。<br>
            現在はプライベートで React でアプリを作成するなどしているため、Vue と React どちらでも対応可能です。
          </p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Links</div>
          <ul class="body__block--links">
            <li>
              <a href="https://github.com/chisaki66" target="_blank">GitHub</a>
            </li>
            <li>
              <a href="https://www.linkedin.com/in/chisaki-ibe-91494b239/" target="_blank">LinkedIn</a>
            </li>
            <li>
              <a href="https://www.wantedly.com/id/chisaki0606" target="_blank">Wantedly</a>
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
    margin-top: 30px;

    p {
      margin-top: 8px;
    }

    &--links {
      li {
        margin-top: 6px;
        list-style: none; 
      }

      a {
        text-decoration: none;       
      }      
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
}
</style>
