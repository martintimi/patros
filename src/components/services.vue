
<template>
  <div>
    <div class="container-fluid nav-background text-center border_rd">
      <div class="container">
        <h3 class="text-uppercase text_color py-5">Services</h3>

        <div class="row px-5">
          <div class="col-md-3 wrapper">
            <div class="boeder_radius pb-3">
              <i class="bi bi-graph-up-arrow hover_icon"></i>
            </div>
            <div>
              <a href="#" class="pb-5"> Strategy</a>
              <p class="text-center">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
                viverra euismod odio, gravida pellentesque urna varius vitae.
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </p>
            </div>
          </div>
          <div class="col-md-3 wrapper">
            <div class="boeder_radius">
              <i class="bi bi-person-circle hover_icon"></i>
            </div>
            <div>
              <a href="#" class=""> User Friendly</a>
              <p class="text-center">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
                viverra euismod odio, gravida pellentesque urna varius vitae.
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </p>
            </div>
          </div>
          <div class="col-md-3 wrapper">
            <div class="boeder_radius">
              <i class="bi bi-code-slash hover_icon"></i>
            </div>
            <div>
              <a href="#" class=""> Clean Code</a>
              <p class="text-center">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
                viverra euismod odio, gravida pellentesque urna varius vitae.
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </p>
            </div>
          </div>
          <div class="col-md-3 wrapper">
            <div class="boeder_radius">
              <i class="bi bi-gear hover_icon"></i>
            </div>
            <div>
              <a href="#" class=""> Flexibility</a>
              <p class="text-center">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
                viverra euismod odio, gravida pellentesque urna varius vitae.
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.text_color {
  color: var(--color-text-two);
}
i {
  color: var(--color-text-two);
  /* border: 1px solid white; */
  font-size: 70px;
  font-weight: 800;
  padding: 0;
}

a {
  color: var(--color-text-two);
  text-decoration: none;
  /* padding-top: 50px; */
  font-size: 22px;
}
p {
  color: var(--color-text-two);
  font-size: 12px;
  line-height: 1.5;
  padding: 20px 8% !important;
}
.boeder_radius {
  border: 1px solid white;
  border-radius: 50%;
  margin-bottom: 30px;
  height: 150px;
  width: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover_icon {
  transition: 0.4s;
}
.hover_icon:hover{
  transform: scale(1.2);
}
.border_rd{
  /* border: 30% 70% 100% 0% / 30% 53% 47% 70%; */
  /* border-radius: 0% 100% 0% 100% / 73% 0% 100% 27%; */
}

</style>