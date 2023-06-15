<!-- <template>
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
</template> -->
<template>
    <q-page class="linear-gradient(to right top, #051937, #004d7a, #008793, #00bf72, #a8eb12)" style="width: 90%; padding: auto;">
        <div class="row">
            <div class="col" style="text-align: center;">
                <div class="text-h4 text-bold text-white q-mt-xl q-pt-xl">Unlock Your Potential with Our</div>
                <div class="text-h4 text-bold text-white q-pt-sm">Online Learning Flatform</div>
                <div class="text-h6 text-bold">Explore a World of Knowldge and Advance</div>
                <div class="text-h6 text-bold q-pb-lg">Your Career from Anywhere, Anytime.</div>
                <div class="row">
                    <div class="col">
                        <q-card class="my-card">
                            <img src="https://cdn.quasar.dev/img/mountains.jpg">

                            <q-card-section>
                                <div class="text-h6">Our Changing Planet</div>
                                <div class="text-subtitle2">by John Doe</div>
                            </q-card-section>

                            <q-card-section class="q-pt-none">
                                {{ lorem }}
                            </q-card-section>
                        </q-card>
                    </div>
                    <div class="col">
                        <q-card class="my-card">
                            <img src="https://cdn.quasar.dev/img/mountains.jpg">

                            <q-card-section>
                                <div class="text-h6">Our Changing Planet</div>
                                <div class="text-subtitle2">by John Doe</div>
                            </q-card-section>

                            <q-card-section class="q-pt-none">
                                {{ lorem }}
                            </q-card-section>
                        </q-card>
                    </div>
                    <div class="col">
                        <q-card class="my-card">
                            <img src="https://cdn.quasar.dev/img/mountains.jpg">

                            <q-card-section>
                                <div class="text-h6">Our Changing Planet</div>
                                <div class="text-subtitle2">by John Doe</div>
                            </q-card-section>

                            <q-card-section class="q-pt-none">
                                {{ lorem }}
                            </q-card-section>
                        </q-card>
                    </div>
                </div>
            </div>  
            <div class="col">
                <div class="q-pa-md" style="margin: auto; padding: 50px;">
                    <q-video :ratio="16/9" src="https://www.youtube.com/embed/k3_tw44QsZQ?rel=0"/>
                </div>
            </div>
        </div>
    </q-page>
</template>
<!-- <style lang="scss" scoped>
.signin {
    border-radius: 8px;
}
.forgot {
    margin-left: 20px;
}
</style> -->
<style lang="sass" scoped>
.my-card
  width: 800%
  max-width: 180px

</style>


<script>
import {
    defineComponent
}
from "vue"
export default defineComponent ({
    name : 'LoginLink'
})
</script>