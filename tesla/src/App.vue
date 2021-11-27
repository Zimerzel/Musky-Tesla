<template>
  <div id="app">
      <header id="header">
        <div class="impact__report">
        <router-link to="/Impact"><p>Read Tesla's 2020 Impact</p></router-link>
        </div>
          <div id="nav">
            <b-navbar toggleable="lg">
              <b-navbar-brand href="#"> <svg id="tesla__logo" class="tds-icon tds-icon-logo-wordmark tds-site-logo-icon" viewBox="0 0 342 35" xmlns="http://www.w3.org/2000/svg"><path d="M0 .1a9.7 9.7 0 007 7h11l.5.1v27.6h6.8V7.3L26 7h11a9.8 9.8 0 007-7H0zm238.6 0h-6.8v34.8H263a9.7 9.7 0 006-6.8h-30.3V0zm-52.3 6.8c3.6-1 6.6-3.8 7.4-6.9l-38.1.1v20.6h31.1v7.2h-24.4a13.6 13.6 0 00-8.7 7h39.9v-21h-31.2v-7h24zm116.2 28h6.7v-14h24.6v14h6.7v-21h-38zM85.3 7h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 13.8h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zm0 14.1h26a9.6 9.6 0 007.1-7H78.3a9.6 9.6 0 007 7zM308.5 7h26a9.6 9.6 0 007-7h-40a9.6 9.6 0 007 7z" fill="var(--tds-icon--fill, #171a20)"></path></svg></b-navbar-brand>

              <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

              <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                  <router-link to="/" id="router__link">Home</router-link>
                  <router-link to="/Model-S" id="router__link">Model S</router-link>
                  <router-link to="/Model-3" id="router__link">Model 3</router-link>
                  <router-link to="/Model-X" id="router__link">Model X</router-link>
                  <router-link to="/Model-Y" id="router__link">Model Y</router-link>
                  <router-link to="/Solar-Roof" id="router__link">Solar Roof</router-link>
                  <router-link to="/Solar-Panels" id="router__link">Solar Panels</router-link>
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                  <b-nav-item-dropdown text="Shop" right>
                    <b-dropdown-item href="#">EN</b-dropdown-item>
                    <b-dropdown-item href="#">ES</b-dropdown-item>
                    <b-dropdown-item href="#">RU</b-dropdown-item>
                    <b-dropdown-item href="#">FA</b-dropdown-item>
                  </b-nav-item-dropdown>
                  <b-nav-item-dropdown text="Account" right>
                    <b-dropdown-item href="#">EN</b-dropdown-item>
                    <b-dropdown-item href="#">ES</b-dropdown-item>
                    <b-dropdown-item href="#">RU</b-dropdown-item>
                    <b-dropdown-item href="#">FA</b-dropdown-item>
                  </b-nav-item-dropdown>
                  <b-nav-item-dropdown right>
                    <!-- Using 'button-content' slot -->
                    <template #button-content>
                      <em>Menu</em>
                    </template>
                    <b-dropdown-item href="#">Profile</b-dropdown-item>
                    <b-dropdown-item href="#">Sign Out</b-dropdown-item>
                  </b-nav-item-dropdown>
                </b-navbar-nav>
              </b-collapse>
            </b-navbar>
        </div>
      </header>
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
}

#nav{
  margin-top: 80px !important;
}

nav{
  z-index: 1;
}

#nav-collapse{
  margin-left: 25%;
}

.bg-info{
  background-color: black transparent !important;
}

.impact__report p{
  margin-top: -45px;
  margin-bottom: -65px !important;
  text-decoration: underline;
  color: #2c3e50;
}

#tesla__logo{
width:120px;
position:absolute;
top: 22px;
left: 50px;
z-index: 1;
}

#header__nav{
  position: absolute;
  top: 40px;
  left: 30%;
  z-index:1;
}

#router__link{
  font-size: 1rem;
  margin:10px;
  color: black;
  text-decoration: none;
}


</style>
