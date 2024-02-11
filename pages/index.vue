<template>
  <div class="main">
    <h1 class="title">Profile</h1>
    <div class="body">
      <img src="../public/images/profile pic.jpg">
      <div>
        <div class="body__block">
          <div class="body__subtitle">Name</div>
          <p>Chisaki Ibe</p>
        </div>
        <div class="body__block">
          <div class="body__subtitle">Skill</div>
          <p></p>
        </div>        
        <div class="body__block">
          <div class="body__subtitle">Introduction</div>
          <p></p>
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
  
  img {
    width: 300px;
  }

  &__subtitle {
    padding-left: 0.5em;
    border-left: solid 3px #88d1e7;
  }
}
</style>
