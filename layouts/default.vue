<template>
  <div class="container">
    <div class="sidebar">
      <nav class="sidebar__link">
        <ul>
          <li class="sidebar__link-list">
            <a href="https://github.com/chisaki66" target="_blank">
              <svg class="sidebar__link--github" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="36" height="36"><path d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z"></path></svg>
            </a>
          </li>
          <li class="sidebar__link-list">
            <a href="https://www.linkedin.com/in/chisaki-ibe-91494b239/" target="_blank">
              <svg class="sidebar__link--linkedin" xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" viewBox="0 0 16 16">
                <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
              </svg>
            </a>
          </li>          
        </ul>
      </nav>
      <nav class="sidebar__menu">
        <div class="sidebar__logo">
          <NuxtLink class="sidebar__logo-text" to="/">
            Chisaki's<br>portfolio
          </NuxtLink>          
        </div>
        <ul>
          <li>
            <NuxtLink class="sidebar__text-link" to="/">profile</NuxtLink>
          </li>
          <li>
            <NuxtLink class="sidebar__text-link" to="/career">career</NuxtLink>
          </li>
          <li>
            <NuxtLink class="sidebar__text-link sidebar__text-link--small" to="/CompanyProject">company pj</NuxtLink>
          </li>
          <li>
            <NuxtLink class="sidebar__text-link sidebar__text-link--small" to="/PersonalProject">personal pj</NuxtLink>
          </li>                      
        </ul>
      </nav>
    </div>
    <slot />
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
}

.container {
  height: 100vh;
  display: flex;
}

.sidebar {
  width: 260px;
  height: 100vh;
  display: flex;
  position: fixed;

  &__link {
    width: 60px;
    padding: 40px 8px;
    box-sizing: border-box;
    background-color: #56b7d4;

    &--github {
      padding: 4px;
      border-radius: 8px;
      background-color: white;      
    }

    &--linkedin {
      padding: 7px;
      border-radius: 8px;
      background-color: white;      
    }
  }

  &__link-list {
    margin-bottom: 10px;

    a {
      color: inherit;
    }
  }

  &__menu {
    width: 200px;
    box-sizing: border-box;
    background-color: #88d1e7;

    ul {
      list-style: none;
      padding-top: 60px;

      li {
        margin-bottom: 6px;
      }

      li:hover {
        background-color: #93ddf4;
      }
    }
  }

  &__logo {
    padding: 40px 40px 0;
  }

  &__logo-text {
    text-decoration: none;
    color: #F9F9F9;
    font-size: 24px;
    line-height: 1.2em;
    text-shadow: 1px 1px 2px #00858d;
  }

  &__logo-text:hover {
    text-shadow: 2px 2px 4px #00858d;
  }

  &__text-link {
    text-decoration: none;
    color: #F9F9F9;
    font-size: 20px;
    padding: 0 40px;
    text-shadow: 1px 1px 2px #00858d;
    display: block;

    &--small {
      font-size: 18px;
    }
  }
}
</style>
