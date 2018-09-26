<template>
  <div>
    <section>
      <v-parallax 
        src="/images/hero.jpg" 
        height="600">
        <v-layout
          column
          align-center
          justify-center
          class="white--text"
        >
          <img
            src="/images/vuetify.png"
            alt="Vuetify.js"
            height="200">
          <h1 class="white--text mb-2 display-1 text-xs-center">Inspirity </h1>
          <div class="subheading mb-3 text-xs-center">time to live your dreams</div>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-layout
        column
        wrap
        class="my-5"
        align-center
      >
        <v-flex
          xs12
          fill-height>
          <v-container grid-list-xl>
            <v-layout
              row
              wrap
              align-center>
              <v-flex
                xs12
                md4>
                <v-card class="elevation-0 transparent">
                  <v-img
                    src="/images/welcome/card1.jpg"
                    aspect-ratio="2.75"
                  />
                  <v-card-title
                    primary-title
                    class="layout justify-center">
                    <div class="headline text-xs-center">Come sail with us!</div>
                  </v-card-title>
                  <v-card-text>
                    Join us, Olivier and Brenda, as we adventure around the globe exploring wonderful 
                    places on Inspirity, ​ our very comfortable Catamaran a Lagoon 470. We ask for a 
                    small fee to cover food and expenses. Much less than chartering a boat and you get 
                    an experienced captain and first mate to make your holiday a memory that will last a lifetime!
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex
                xs12
                md4
                fill-height>
                <v-card class="elevation-0 transparent">
                  <v-img
                    src="/images/welcome/card2.jpg"
                    aspect-ratio="2.75"
                  />
                  <v-card-title
                    primary-title
                    class="layout justify-center">
                    <div class="headline text-xs-center">Come sail with us!</div>
                  </v-card-title>
                  <v-card-text>
                    Olivier was twelve years old when he decided he was going to own a boat and sail the world. 
                    It took 37 years before he was to realize his dream. 
                    It all started April 2009 with a sail from Las Palmas in Mallorca (Spain).
                    Since 1970 Olivier has sailed more than 60,000 nautical miles, the North Sea, Mediterranean, 
                    Atlantic, Cape Horn and across the South and North Pacific.
                    “ Inspirity was my dream, I am living that dream. What a great pleasure it is for me to share my dream with others. For me my happiest moments come from helping others, relax, breathe and recharge in nature's beautiful surroundings" 
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex
                xs12
                md4
                fill-height>
                <v-card class="elevation-0 transparent">
                  <v-img
                    src="/images/welcome/card3.jpg"
                    aspect-ratio="2.75"
                  />
                  <v-card-title
                    primary-title
                    class="layout justify-center">
                    <div class="headline text-xs-center">French Polynesia to British Columbia, Canada</div>
                  </v-card-title>
                  <v-card-text>
                    In June of 2017 Olivier, Brenda and crew helpers Michael (from Tofino, BC) 
                    and Karen (from the UK) sailed from Tahiti to British Columbia Canada. 
                    Together we sailed 7,500 Km, you can read about the journey in our blog. 
                    Inspirity will summer over 2017 in breathtaking BC. 
                    Come join us before we leave for a once in a lifetime experience. 
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>
        </v-flex>
      </v-layout>
    </section>

    <section>
      <v-parallax
        src="/images/section.jpg"
        height="380">
        <v-layout
          column
          align-center
          justify-center
          fill-height>
          <div class="headline white--text mb-3 text-xs-center">Web development has never been easier</div>
          <em>Kick-start your application today</em>
          <v-btn
            class="blue lighten-2 mt-5"
            dark
            large
            href="/pre-made-themes"
          >
            Get Started
          </v-btn>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-container grid-list-xl>
        <v-layout 
          row
          wrap
          justify-center
          class="my-5">
          <v-flex
            xs12 
            sm4>
            <v-card class="elevation-0 transparent">
              <v-card-title 
                primary-title 
                class="layout justify-center">
                <div 
                  class="headline">Company info</div>
              </v-card-title>
              <v-card-text>
                Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
              </v-card-text>
            </v-card>
          </v-flex>
          <v-flex
            xs12 
            sm4 
            offset-sm1>
            <v-card class="elevation-0 transparent">
              <v-card-title 
                primary-title 
                class="layout justify-center">
                <div class="headline">Contact us</div>
              </v-card-title>
              <v-card-text>
                Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
              </v-card-text>
              <v-list class="transparent">
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">phone</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>777-867-5309</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">place</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>Chicago, US</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon class="blue--text text--lighten-2">email</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>john@vuetifyjs.com</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
              </v-list>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
