<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#portfolio">Portfolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Welcome To Tangguh's Portfolio</div>
        </div>
      </div>
    </header>

    
    <!-- Portfolio Grid -->
    <Portfolio></Portfolio>

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">About Me</h2>
            <h3 class="section-subheading text-muted">My Profile.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4 class="subheading">Profiles</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Tangguh Rizqi Nurwendys. Born in Banyumas, Central Java, Indonesia.</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2019</h4>
                    <h4 class="subheading">Graduated from High School</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Majoring Computer and Network Engineering SMKN 1 Purwokerto</p>
                  </div>
                </div>
              </li>
              
              
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Contact Me</h2>
            <h3 class="section-content">Email : nurwendys@gmail.com</h3>
            <h2 class="section-heading text-uppercase">My Linkedin Page</h2>
            <h3 class="section-content">https://www.linkedin.com/in/tangguh-rizqi-nurwendys-241b09228/</h3>
          </div>
        </div>
        
      </div>
    </section>

    <footer>
      <div class="container">
        <div class="row">
          
            <span class="copyright">Copyright &copy; 2022</span>
          
        </div>
      </div>
    </footer>

  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: rgb(58, 55, 55);
}
</style>
