<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <ion-button size="large">1</ion-button>
      <ion-button size="large">2</ion-button>
      <ion-button size="large">3</ion-button>
      <br>
      <ion-button size="large">4</ion-button>
      <ion-button size="large">5</ion-button>
      <ion-button size="large">6</ion-button>
      <br>
      <ion-button size="large">7</ion-button>
      <ion-button size="large">8</ion-button>
      <ion-button size="large">9</ion-button>
      <br>
      <ion-button size="large">0</ion-button>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent , IonButton} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Home',
  components: {
    IonContent,
    IonButton
  }
});
</script>

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