<template>
  <q-page class="flex column">
    <div class="flex">
      <div class="flex column">
        <q-card class="q-ma-sm">
          <q-card-section>
            <div class="text-h1">I Build Web Applications</div>
          </q-card-section>
        </q-card>
        <div class="flex">
          <q-card class="q-ma-sm bg-positive">
            <q-card-section class="flex flex-center column">
              <div class="text-h3">3+</div>
              <div class="text-subtitle1">Years Experience</div>
            </q-card-section>
          </q-card>
          <q-card class="q-ma-sm bg-warning">
            <q-card-section class="flex flex-center column">
              <div class="text-h3">20+</div>
              <div class="text-subtitle1">Handled Projects</div>
            </q-card-section>
          </q-card>
          <q-card class="q-ma-sm bg-negative">
            <q-card-section class="flex flex-center column">
              <div class="text-h3">8+</div>
              <div class="text-subtitle1">Clients</div>
            </q-card-section>
          </q-card>
        </div>
      </div>
      <div class="flex column">
        <q-card class="q-ma-sm">
          <q-card-section horizontal>
            <div class="text-h6">Clément Bonal</div>
            <q-card-action>
              <q-btn>My Resume</q-btn>
            </q-card-action>
          </q-card-section>
        </q-card>
        <div class="flex">
          <q-card class="q-ma-sm">
            <img />
          </q-card>
          <div class="flex column">
            <q-card class="q-ma-sm">
              <q-card-section horizontal>
                <div class="text-subtitle1">Name:</div>
                <div class="text-h6">Clément Bonal</div>
              </q-card-section>
            </q-card>
            <q-card class="q-ma-sm">
              <q-card-section horizontal>
                <div class="text-subtitle1">Based in:</div>
                <div class="text-h6">Paris, France</div>
              </q-card-section>
            </q-card>
            <q-card class="q-ma-sm">
              <q-card-section horizontal>
                <div class="text-subtitle1">Languages:</div>
                <div class="text-h6">French, English & Spanish</div>
              </q-card-section>
            </q-card>
            <q-card class="q-ma-sm">
              <q-card-action>
                <q-btn icon="mail" />
                <q-btn icon="mail" />
                <q-btn icon="mail" />
              </q-card-action>
            </q-card>
          </div>
        </div>
      </div>
    </div>

    <div class="flex no-wrap">
      <q-card class="q-ma-sm">
        <q-card-section>
          <div class="text-h6">Portfolio</div>
          <div class="flex">
            <img />
            <img />
          </div>
        </q-card-section>
      </q-card>
      <q-card class="q-ma-sm">
        <q-card-section>
          <div class="text-h6">About</div>
          <p>Lorem ipsum dolor sit amet, 
            consectetur adipiscing elit, 
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
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
