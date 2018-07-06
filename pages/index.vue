<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <section class="portfolio">
        <div class="my-info">
          <h2>Mohaimin Islam</h2>
          <div class="my-contact">
            <a href="https://www.linkedin.com/in/mohaimin-islam/" target="_blank" rel="noopener"><i class="ion-social-linkedin"></i></a>
            <a href="https://www.facebook.com/Mohaiminislam17" target="_blank" rel="noopener"><i class="ion-social-facebook"></i></a>
            <a href="https://plus.google.com/102535643689453338746" target="_blank" rel="noopener"><i class="ion-social-googleplus"></i></a>
            <a href="https://github.com/SL0TR" target="_blank" rel="noopener"><i class="ion-social-github"></i></a>
          </div>
        </div>
      </section>
    </v-flex>
  </v-layout>
</template>

<script>

export default {
}
</script>


<style>

.portfolio {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(270deg, #723d5d, #003d5d);
  background-size: 400% 400%;
  animation: AnimationName 30s ease infinite;
}

@keyframes AnimationName { 
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}

.my-info {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  z-index: 5;
}

.my-info h2 {
  position: relative;
  top: 10%;
  z-index: 5;
  font-size: 8rem;
  color: #eee;
  margin: 2rem 0;
  
}

.my-contact {
  height: 80%;
  width: 80%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  z-index: 5;  
}

i {
  font-size: 4rem;
  cursor: pointer;
  transition: all .2s;
  z-index: 5;
  color: #000;
}

.ion-social-linkedin:hover {
  color: #007bb5;
}

.ion-social-facebook:hover {
  color: #3b5998;
}

.ion-social-googleplus:hover {
  color: #dd4b39;
}

.ion-social-github:hover {
  color: #333;
}

@media (max-width: 700px) {
  .my-info h2 {
    font-size: 2.5rem;
  }

  i {
    font-size: 2rem;
  }
}

</style>
