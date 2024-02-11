<template>
  <div class="main">
    <h1 class="title">Career</h1>
    <div class="body">
      <div>
        <div class="body__block">
          <div class="body__subtitle">弁護士ドットコム株式会社</div>
          <img class="body__image" src="../public/images/cloudsign.png" alt="">
          <p>Dec 2022 to Current</p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Retty Inc.</div>
          <img class="body__image" src="../public/images/retty.png" alt="">
          <p>Apr 2021 to Dec 2022</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
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
  }

  &__subtitle {
    padding-left: 0.5em;
    border-left: solid 4px #88d1e7;
    font-size: 24px;
  }

  &__image {
    width: 400px;
    margin-top: 20px;
  }  
}
</style>
