<template>
  <div id="app">
        <header id="header">
          <div id="header">
            <b-navbar-brand href="#"><svg id="tesla__logo" class="tds-icon tds-icon-logo-wordmark tds-site-logo-icon" viewBox="0 0 342 35" xmlns="http://www.w3.org/2000/svg"><path d="M0 .1a9.7 9.7 0 007 7h11l.5.1v27.6h6.8V7.3L26 7h11a9.8 9.8 0 007-7H0zm238.6 0h-6.8v34.8H263a9.7 9.7 0 006-6.8h-30.3V0zm-52.3 6.8c3.6-1 6.6-3.8 7.4-6.9l-38.1.1v20.6h31.1v7.2h-24.4a13.6 13.6 0 00-8.7 7h39.9v-21h-31.2v-7h24zm116.2 28h6.7v-14h24.6v14h6.7v-21h-38zM85.3 7h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 13.8h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 14.1h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zM308.5 7h26a9.6 9.6 0 007-7h-40a9.6 9.6 0 007 7z" fill="var(--tds-icon--fill, #171a20)"></path></svg></b-navbar-brand>
            <b-navbar toggleable="lg" type="light" variant="white" id="navbar" class="navbar-horizontal">
              <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
              <b-collapse id="nav-collapse" v-model="showCollapse" is-nav>
                <b-navbar-nav class="navbar-nav">
                    <router-link to="/" id="router__link">Home</router-link>
                    <router-link to="/Model-S" id="router__link">Model S</router-link>
                    <router-link to="/Model-3" id="router__link">Model 3</router-link>
                    <router-link to="/Model-X" id="router__link">Model X</router-link>
                    <router-link to="/Model-Y" id="router__link">Model Y</router-link>
                    <router-link to="/Solar-Roof" id="router__link">Solar Roof</router-link>
                    <router-link to="/Solar-Panels" id="router__link">Solar Panels</router-link>
                  <a href="https://www.facebook.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation" ><i class="fab fa-facebook-f" alt="Facebook Link"></i></a>
                  <a href="https://www.instagram.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation" ><i class="fab fa-instagram" alt="Instagram Link"></i></a>
                  <a href="https://www.youtube.com/user/pikespeakhillclimb" target="blank" rel="noreferrer" class="hover-underline-animation" ><i class="fab fa-youtube" alt="Youtube Link"></i></a>
                </b-navbar-nav>
              </b-collapse>
            </b-navbar>
          </div>
        </header>
    <!-- <header id="header">
      <div class="impact__report">
        <router-link to="/Impact"><p>Read Tesla's 2020 Impact</p></router-link>
      </div>
      <svg id="tesla__logo" class="tds-icon tds-icon-logo-wordmark tds-site-logo-icon" viewBox="0 0 342 35" xmlns="http://www.w3.org/2000/svg"><path d="M0 .1a9.7 9.7 0 007 7h11l.5.1v27.6h6.8V7.3L26 7h11a9.8 9.8 0 007-7H0zm238.6 0h-6.8v34.8H263a9.7 9.7 0 006-6.8h-30.3V0zm-52.3 6.8c3.6-1 6.6-3.8 7.4-6.9l-38.1.1v20.6h31.1v7.2h-24.4a13.6 13.6 0 00-8.7 7h39.9v-21h-31.2v-7h24zm116.2 28h6.7v-14h24.6v14h6.7v-21h-38zM85.3 7h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 13.8h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 14.1h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zM308.5 7h26a9.6 9.6 0 007-7h-40a9.6 9.6 0 007 7z" fill="var(--tds-icon--fill, #171a20)"></path></svg>
      <div id="header__nav">
        <router-link to="/" id="router__link">Home</router-link>
        <router-link to="/Model-S" id="router__link">Model S</router-link>
        <router-link to="/Model-3" id="router__link">Model 3</router-link>
        <router-link to="/Model-X" id="router__link">Model X</router-link>
        <router-link to="/Model-Y" id="router__link">Model Y</router-link>
        <router-link to="/Solar-Roof" id="router__link">Solar Roof</router-link>
        <router-link to="/Solar-Panels" id="router__link">Solar Panels</router-link>
        <div class="side__nav">
          <router-link to="/Shop" id="router__link">Shop</router-link>
          <router-link to="/Account" id="router__link">Account</router-link>
          <router-link to="/Menu" id="router__link">Menu</router-link>
        </div>
      </div>
    </header> -->
    <router-view/>
    <footer>

    </footer>
  </div>
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

header{
  position: relative;
  margin-top: -5vh;
}

.impact__report p{
  margin-bottom: 15px;
  text-decoration: none;
  color: #2c3e50;
}

#tesla__logo{
width:120px;
position:absolute;
top: 8vh;
left: 40px;
z-index: 1;
}

#header__nav{
  position: absolute;
  top: 40px;
  left: 30%;
  z-index:1;
}

#router__link{
  margin:10px;
}



</style>
