<template>
    <q-page class="linear-gradient(to right top, #051937, #004d7a, #008793, #00bf72, #a8eb12) main" style="width: 90%; padding: auto; min-height: 600px;" >
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
            <div class="col" style="text-align: justify;">
                <div class="q-pa-md" style="margin: auto; padding: 50px; margin-top: 50px;">
                    <q-video :ratio="16/9" src="https://www.youtube.com/embed/k3_tw44QsZQ?rel=0"/>
                </div>
                <div class="text text-bold" style="margin-left: 50px">Explore a World of Knowldge and Advance</div>
                <div class="text text-bold q-pb-lg" style="margin-left: 50px">Your Career from Anywhere, Anytime.</div>
                <div class="col" style="margin-left: 60%; margin-bottom: 20px;">
                <q-btn size="22px" class="q-px-l q-py-xs" color="primary" style="border-radius: 12px" label="GET SUBSCRIBED" />
                </div>
            </div>
         
        </div>
    </q-page>
</template>
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
    name : 'BannerLink'
})
</script> -->