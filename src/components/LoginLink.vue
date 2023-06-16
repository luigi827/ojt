<template>
    <q-card class="q-pa-md shadow-2 my_card" bordered>
          <q-card-section class="text-center">
            <div class="text-grey-9 text-h5 text-weight-bold">Login Form</div>
          </q-card-section>
          <q-card-section>
            <q-input dense outlined v-model="email" label="Email Address"></q-input>
            <q-input dense outlined class="q-mt-md" v-model="password" type="password" label="Password"></q-input>
          </q-card-section>
            <div class="text-grey-8 forgot">Forgot Password?</div>
          <q-card-section>
            <q-btn color="blue" rounded size="md" label="Sign in" no-caps class="full-width signin"></q-btn>
          </q-card-section>
          <q-card-section class="text-center q-pt-none">
            <div class="text-grey-8">Not a Member?
              <a href="#" class="text-dark text-weight-bold" style="text-decoration: none; color: linear-gradient(to right top, #051937, #004d7a, #008793, #00bf72, #a8eb12);">Signup now</a></div>
          </q-card-section>

        </q-card>
</template>

<style lang="scss" scoped>
.signin {
    border-radius: 8px;
}
.forgot {
    margin-left: 20px;
}
</style>
<!-- <style lang="sass" scoped>
.my-card
  width: 800%
  max-width: 180px

</style> -->


<script>
import {
    defineComponent
}
from "vue"
export default defineComponent ({
    name : 'LoginLink'
})
</script>