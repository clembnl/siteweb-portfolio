<template>
  <q-page class="flex items-center column" style="max-width: 1200px; margin: auto;">
    <div class="flex no-wrap" style="width: 100%;">
      <div class="flex column" style="width: 50%;">
        <q-card class="q-ma-sm card">
          <q-card-section>
            <div class="text-h2 text-weight-bolder">Get your MVP in 2 Weeks</div>
            <div class="text-subtitle1">I build effective MVP fast using powerfull development tools and cloud technologies.</div>
          </q-card-section>
        </q-card>
        <q-btn class="q-ma-sm card " color="accent" label="Contact Me" />
        <div class="flex no-wrap" style="justify-content: space-between;">
          <q-card class="q-ma-sm bg-positive card small-card">
            <q-card-section class="flex flex-center column">
              <div class="text-h3 text-bold">3+</div>
              <div class="text-subtitle1">Years Experience</div>
            </q-card-section>
          </q-card>
          <q-card class="q-ma-sm bg-warning card small-card">
            <q-card-section class="flex flex-center column">
              <div class="text-h3 text-bold">15+</div>
              <div class="text-subtitle1">Handled Projects</div>
            </q-card-section>
          </q-card>
          <q-card class="q-ma-sm bg-negative card small-card">
            <q-card-section class="flex flex-center column">
              <div class="text-h3 text-bold">10+</div>
              <div class="text-subtitle1">Clients</div>
            </q-card-section>
          </q-card>
        </div>
      </div>
      <q-card class="q-ma-sm card" style="width: 50%;">
        <q-card-section>
          <div class="text-h5 text-grey q-ml-md">See my work</div>
          <div class="q-mt-sm image-container flex flex-center">
            <!--
            <div class="flex" style="justify-content: space-between;">
              <div class="text-h6">Portfolio</div>
              <div class="text-subtitle1">View All</div>
            </div>
            -->
            <img src="../assets/Screenshot_FinScreen.png" class="card" style="width: 100%;"/>
            <div class="content card">
              <p>See More</p>
            </div>
            <!--<img src="../assets/Screenshot_Ecom.png" width="350px" height="228px" class="card"/>-->
          </div>
        </q-card-section>
      </q-card>
    </div>

    <div class="flex no-wrap " style="width: 100%;">
      <q-card class="q-ma-sm card" style="width: 40%;">
        <q-card-section horizontal>
          <img src="../assets/site_portfolio.jpg" height="260px" width="185px" class="q-ma-sm card"/>

          <div class="flex column" style="justify-content: space-between;">
            <div>
              <div class="text-subtitle1 text-grey">Name:</div>
              <div class="text-h6">Clément Bonal</div>

              <div class="text-subtitle1 text-grey">Based in:</div>
              <div class="text-h6">Paris, France</div>

              <div class="text-subtitle1 text-grey">Languages:</div>
              <div class="text-h6">French, English & Spanish</div>
            </div>

            <q-card-action class="q-mb-sm flex flex-center" style="justify-content: space-around;">
              <q-btn round icon="fa-brands fa-x-twitter" />
              <q-btn round icon="fa-brands fa-github" />
              <q-btn round icon="fa-brands fa-reddit" />
              <q-btn round icon="fa-brands fa-linkedin-in" />
              <q-btn round icon="fa-regular fa-envelope" />
            </q-card-action>
          </div>
        </q-card-section>
      </q-card>
      <q-card class="q-ma-sm card" style="width: 60%;">
        <q-card-section>
          <div class="text-h6 text-grey">About</div>
          <p>Hi ! My name is Clément Bonal, I am a French software developer that is passionate about developing apps. 
            Through my journey, I have come to enjoy the process and challenge of being able to quickly develop MVP (minimum viable product) to launch new business ideas.</p>
            <q-separator />
          <p></p>
          <p>Indeed 35% of startups fail because they spend time, effort, and money on a product or service that no one needs or already exists <span class="text-italic">(CB Insights, 2022)</span>
              and 20% fail within the first year if there’s no market for it <span class="text-italic">(Fundera, 2021)</span>.
            <br/>
              Thus MVPs are the best way to test a market and validate your product or service.
            <br />
              Which is why I offer my service in order to help entrepreneurs (like you) succeed by helping them to quicly develop an efficient MVP at affordable cost 
              and immediatly get better results.
          </p>
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>

<style>
.card {
  border-radius: 20px !important;
  box-shadow: none;
}

.small-card {
  width: 30%;
  display: flex;
  justify-content: center;
  height: 150px;
}

.content {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0;
  cursor: pointer;
  font-size: 1.25rem;
  margin: 16px;
}

.image-container:hover img{
  filter: blur(2px);
}

.image-container:hover .content {
  opacity: 1;
}
</style>