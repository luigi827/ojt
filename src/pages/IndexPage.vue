<template>
  <q-page class="flex flex-center">
    <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <q-page class="flex flex-center" style="background: linear-gradient(to right top, #051937, #004d7a, #008793, #00bf72, #a8eb12);">
        <login-link />
        <!-- <banner-link /> -->
      </q-page>
    </q-page-container>
  </q-layout>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import LoginLink from 'src/components/LoginLink.vue';
// import BannerLink from  'src/components/BannerLink.vue';

export default defineComponent({
  name: 'IndexPage',
  components : {
    LoginLink
  }
})
</script>
