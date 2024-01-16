<template>
  <div class="container text-center pt-5 mb-5">
    <h3 class="text-uppercase text_color pt-5">LATEST BLOG POSTS</h3>
    <img src="/public/images/short.png" alt="" class="pb-3" />

    <div class="row pt-3 px-5">
      <div class="col-lg-3">
        <img class="img1" src="/public/images/person1.jpeg" alt="" />
        <div class="align pt-4">
          <h4 class="">Christian Peri</h4>
          <h6>Co-Founder</h6>
          <p class="pt-2">
            Backed by some of the biggest names in the industry, Firefox OS is
            an open platform that fosters greater
          </p>
        </div>
        <i class="bi bi-facebook px-1"></i>
        <i class="bi bi-twitter-x px-1"></i>
        <i class="bi bi-google px-1"></i>
        <i class="bi bi-linkedin px-1"></i>
      </div>
      <div class="col-lg-3">
        <img class="img1" src="/public/images/person1.jpeg" alt="" />
        <div class="align pt-4">
          <h4 class="">Jane Manz</h4>
          <h6>Project Manager</h6>
          <p class="pt-2">
            Backed by some of the biggest names in the industry, Firefox OS is
            an open platform that fosters greater
          </p>
        </div>
        <i class="bi bi-facebook px-1"></i>
        <i class="bi bi-twitter-x px-1"></i>
        <i class="bi bi-google px-1"></i>
        <i class="bi bi-linkedin px-1"></i>
      </div>
      <div class="col-lg-3">
        <img class="img1" src="/public/images/person1.jpeg" alt="" />
        <div class="align pt-4">
          <h4 class="">Paulinho Rubos</h4>
          <h6>Designer</h6>
          <p class="pt-2">
            Backed by some of the biggest names in the industry, Firefox OS is
            an open platform that fosters greater
          </p>
        </div>
        <i class="bi bi-facebook px-1"></i>
        <i class="bi bi-twitter-x px-1"></i>
        <i class="bi bi-google px-1"></i>
        <i class="bi bi-linkedin px-1"></i>
      </div>
      <div class="col-lg-3">
        <img class="img1" src="/public/images/person1.jpeg" alt="" />
        <div class="align pt-4">
          <h4 class="">Loreto Andas</h4>
          <h6>Developer</h6>
          <p class="pt-2">
            Backed by some of the biggest names in the industry, Firefox OS is
            an open platform that fosters greater
          </p>
        </div>
        <i class="bi bi-facebook px-1"></i>
        <i class="bi bi-twitter-x px-1"></i>
        <i class="bi bi-google px-1"></i>
        <i class="bi bi-linkedin px-1"></i>
      </div>
    </div>
  </div>
</template>

<style scoped>
.img1 {
  height: 60%;
  width: 100%;
  filter: grayscale(1);
  transition: 1s;
}
.img1:hover {
  filter: grayscale(0);
}
.align {
  text-align: left;
}
p {
  font-size: 12px;
  line-height: 1.5;
  /* padding: 20px 8% !important; */
}
h6 {
  font-family: inherit;
  color: rgba(0, 0, 0, 0.727)9);
}

i{
    /* color: #2234ae; */
    /* color: linear-gradient(315deg, #2235aec9 0%rgba(25, 23, 20, 0.842)14 74%); */
    font-size: 20px;
    transition: 2px;

}
i:hover{
    color: #2234ae;
    color: linear-gradient(315deg, #2235aec9 0%rgba(25, 23, 20, 0.842)14 74%);
}
</style>