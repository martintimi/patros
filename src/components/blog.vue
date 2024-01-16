<template>
  <div >  
    <div class="container text-center">
      <h3 class="text-uppercase text_color pt-5">LATEST BLOG POSTS</h3>
      <img src="../../public/images/short.png" alt="" class="pb-3" />

      <div class="row px-5">
        <div class="col-lg-4">
          <!-- <img src="/public/images/blog1.jpeg" alt="" class="gradient-img"> -->

          <div class="hero ">
            <div class="inner_container"></div>

            <div class="hero-overlay">
              <h5 class="overlay"><h4>BLOG POST LONGT TITLE</h4></h5>
            </div>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra
            euismod odio, gravida pellentesque urna varius vitae. Lorem ipsum
            dolor sit amet.
          </p>
          <button class="button"><span>Read More </span></button>
        </div>
        <div class="col-lg-4">
          <!-- <img src="/public/images/blog1.jpeg" alt="" class="gradient-img"> -->

          <div class="hero2">
            <div class="inner_container"></div>

            <div class="hero2-overlay">
              <h5 class="overlay"><h4>BLOG POST LONGT TITLE</h4></h5>
            </div>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra
            euismod odio, gravida pellentesque urna varius vitae. Lorem ipsum
            dolor sit amet.
          </p>
          <button class="button"><span>Read More </span></button>
        </div>
        <div class="col-lg-4">
          <!-- <img src="/public/images/blog1.jpeg" alt="" class="gradient-img"> -->

          <div class="hero3">
            <div class="inner_container"></div>

            <div class="hero3-overlay">
              <h5 class="overlay"><h4>BLOG POST LONGT TITLE</h4></h5>
            </div>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam viverra
            euismod odio, gravida pellentesque urna varius vitae. Lorem ipsum
            dolor sit amet.
          </p>

          <button class="button"><span>Read More </span></button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero {
  width: 95%;
  height: 28vh;
  background-image: url(/public/images/blog1.jpeg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  position: relative;
}
.hero .inner_container {
  position: absolute;
  width: 6px;
  height: 6px;
  border: 2px solid #000;
  background: transparent;
  /* top: 0; */
  /* bottom: 0; */
  /* left: 0; */
  /* right: 0; */
  inset: 0;
  margin: auto;

}
@keyframes grow {
  0% {
    width: 0;
    height: 0;
  }
  100% {
    height: 100%;
    width: 100%

  }
}
.hero:hover .inner_container {

}
p {
  /* color: var(--color-text-two); */
  font-size: 12px;
  line-height: 1.5;
  padding: 20px 5% !important;
  padding-right: 40px !important;
}
.overlay {
  padding-top: 13%;
  color: var(--color-text-two);
}
.hero-overlay {
  background: rgba(0, 0, 0, 0.599);
  width: 100%;
  height: 28vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 0.7s ease;
}
.hero h4 {
  color: var(--color-text-two);
  font-size: 18px;
  /* transform: translateX(-50%); */
}
/* .inner_container {
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  position: absolute;
  top: 0;
  left: 0;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  transition: 2s;
} */
.hero-overlay:hover {
  /* background-position: 400% 400%; */
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  opacity: 0.4;
  transition: 0.7s ease;
}
.hero2 {
  width: 95%;
  height: 28vh;
  background-image: url(/public/images/blog2.jpeg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  position: relative;
}
.overlay {
  padding-top: 13%;
  color: var(--color-text-two);
}
.hero2-overlay {
  background: rgba(0, 0, 0, 0.599);
  width: 100%;
  height: 28vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 0.7s ease;
}
.hero2 h4 {
  color: var(--color-text-two);
  font-size: 18px;
  /* transform: translateX(-50%); */
}
/* .inner_container {
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  position: absolute;
  top: 0;
  left: 0;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  transition: 2s;
} */
.hero2-overlay:hover {
  /* background-position: 400% 400%; */
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  opacity: 0.4;
  transition: 0.7s ease;
}
.hero3 {
  width: 95%;
  height: 28vh;
  background-image: url(/public/images/blog3.jpeg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  position: relative;
}
.overlay {
  padding-top: 13%;
  color: var(--color-text-two);
}
.hero3-overlay {
  background: rgba(0, 0, 0, 0.599);
  width: 100%;
  height: 28vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 0.7s ease;
}
.hero3 h4 {
  color: var(--color-text-two);
  font-size: 18px;
  /* transform: translateX(-50%); */
}
/* .inner_container {
  width: 100%;
  height: 100%;
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  position: absolute;
  top: 0;
  left: 0;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  transition: 2s;
} */
.hero3-overlay:hover {
  /* background-position: 400% 400%; */
  background: linear-gradient(45deg, #22682a 0%, #9b4a1b 40%, #3a342a 100%);
  opacity: 0.4;
  transition: 0.7s ease;
}

.button {
  border-radius: 4px;
  background-color: #2234ae;
  background-image: linear-gradient(315deg, #2234ae 0%, #191714 74%);
  border: none;
  color: #ffffff;
  text-align: center;
  font-size: 15px;
  padding: 10px;
  width: 150px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: "\00bb";
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
</style>