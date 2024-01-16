<template>
  <div class="hero">
    <div class="hero-overlay">
         <h5 class="overlay">Lorem Ipsum is simply dummy text of typesetting industry.</h5>
        </div>
  </div>
</template>

<style scoped>
.hero {
  background-image: url("/images/pexels-bri-schneiter-346529.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  height: 80vh;
  animation-name: heroChange;
  animation-direction: alternate-reverse;
  animation-timing-function: ease-out;
  animation-fill-mode: forwards;
  animation-duration: 20s;
  animation-iteration-count: infinite;
  animation-play-state: running;
  transition: 5s;
}

@keyframes heroChange {
  background-image: url("../../public/images/pexels-bri-schneiter-346529.jpg");
  0% {
  }
  25% {
    background-image: url("../../public/images/pexels-krishnakant-mahamuni-1201179.jpg");
  }
  50% {
    background-image: url("../../public/images/pexels-photo-10012673.jpeg");
  }
  75% {
    background-image: url("../../public/images/pexels-saeid-anvar-827209.jpg");
  }
  100% {
    background-image: url("../../public/images/r-m-_wtP2TIJLuA-unsplash.jpg");
  }
}
.overlay{
    padding-top: 13%;
    color: var(--color-text-two);
}

.hero-overlay {
  background: rgba(0, 0, 0, 0.3);
  width: 100%;
  height: 80vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero-overlay::after {
  position: absolute;
  color: var(--color-text-two);
  content: "Premium Creative Content";
  font-size: 60px;
  font-weight: 500;

  animation-name: textChange;
  animation-direction: alternate-reverse;
  animation-timing-function: ease-in-out;
  animation-fill-mode: forwards;
  animation-duration: 20s;
  animation-iteration-count: infinite;
  animation-play-state: running;
  transition: content 5s ease-in-out;
}

@-webkit-keyframes textChange {
    0% {
        content: "Premium Creative Content!";
    }
    25% {
        content: "Unique Design!";
    }
    50% {
        content: "Digital Marketing Solution!";
    }
    75% {
        content: "Search Engine Optimization!";
    }
    100% {
        content: "Smart Business Solution!";
    }
}
</style>