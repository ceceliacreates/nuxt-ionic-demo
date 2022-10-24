<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Resources</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Resources</ion-title>
        </ion-toolbar>
      </ion-header>
      <div id="container">
        <ion-list :inset="true">
          <ion-item>
            <ion-icon :icon="ioniconsBookOutline" slot="start"></ion-icon>
            <ion-label
              ><a
                target="_blank"
                rel="noopener noreferrer"
                href="https://ionic.nuxtjs.org/"
              >
                Nuxt Ionic Documentation</a
              ></ion-label
            >
          </ion-item>
          <ion-item>
            <ion-icon :icon="ioniconsRocketOutline" slot="start"></ion-icon>
            <ion-label>
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://stackblitz.com/github/nuxt-modules/ionic/tree/main/playground"
                >Nuxt Ionic Playground</a
              ></ion-label
            >
          </ion-item>
          <ion-item>
            <ion-icon :icon="ioniconsLogoGithub" slot="start"></ion-icon>
            <ion-label>
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://github.com/nuxt-modules/ionic"
                >Nuxt Ionic GitHub Repo</a
              ></ion-label
            >
          </ion-item>
          <ion-item>
            <ion-icon :icon="ioniconsVideocamOutline" slot="start"></ion-icon>
            <ion-label class="ion-text-wrap">
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://www.youtube.com/watch?v=f4sB7NhCgRw"
                >Video: Getting Started with Nuxt Ionic Module for Nuxt 3 by
                Aaron Saunders</a
              ></ion-label
            >
          </ion-item>
        </ion-list>
        <ion-button href="/">Back</ion-button>
      </div>
    </ion-content>
  </ion-page>
</template>

<style scoped>
#container {
  text-align: center;

  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}
#container strong {
  font-size: 20px;
  line-height: 26px;
}
#container p {
  font-size: 16px;
  line-height: 22px;

  color: #8c8c8c;

  margin: 0;
}
#container a {
  text-decoration: none;
}
</style>
