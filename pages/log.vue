<template>
  <section class="hero is-black is-large">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item">
              <img src="https://bulma.io/images/bulma-type-white.png" alt="Logo" />
            </a>
            <span class="navbar-burger burger" data-target="navbarMenuHeroB">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </div>
          <div id="navbarMenuHeroB" class="navbar-menu">
            <div class="navbar-end">
              <!-- <a class="navbar-item is-active">Sign Up</a> -->
              <nuxt-link to="/signup" class="navbar-item is-active">Sign Up</nuxt-link>
              <span class="navbar-item">
                <a class="button is-primary is-inverted is-medium">
                  <nuxt-link to="/login">Home</nuxt-link>
                </a>
              </span>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <span
      style="margin:0 auto;margin-top:7%; font: 700 100px Comic Sans MS;color: white;text-shadow: 0 0 20px #fdec84,10px -10px 30px #ffae35,20px -20px 40px #ec760c,-20px -60px 50px #cd4607,0px -80px 60px #973717,10px -40px 70px #451b0e;"
    >Loging Now</span>
    <div class="hero-body" style="width:40%; margin:0 auto; margin-top:-10%;">
      <div class="container">
        <div class="field">
          <p class="control has-icons-left has-icons-right">
            <input class="input" type="email" placeholder="Email" />
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"></i>
            </span>
            <span class="icon is-small is-right">
              <i class="fas fa-check"></i>
            </span>
          </p>
        </div>
        <div class="field">
          <p class="control has-icons-left">
            <input class="input" type="password" placeholder="Password" />
            <span class="icon is-small is-left">
              <i class="fas fa-lock"></i>
            </span>
          </p>
        </div>
        <div class="field">
          <p class="control">
            <button class="button is-success" style="margin-left:43%;">Login</button>
          </p>
        </div>
        <span
          style="margin:0 auto;margin-top:7%; font: 700 20px Comic Sans MS;color: white;text-shadow: 0 0 20px #fdec84,10px -10px 30px #ffae35,20px -20px 40px #ec760c,-20px -60px 50px #cd4607,0px -80px 60px #973717,10px -40px 70px #451b0e;"
        >
          Don't have a account? Click here to
          <nuxt-link to="/signup">Sign Up!</nuxt-link>
        </span>
      </div>
    </div>
    <div class="hero-foot"></div>
  </section>
</template>