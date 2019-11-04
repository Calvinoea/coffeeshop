<template>
  <div id="app">
    <v-app id="inspire">
      <!-- Sheet -->

      <div class="text-center">
        <v-sheet color="brown lighten-2" height="600">
          <!-- Toolbar-->
          <div>
            <v-toolbar flat color="transparent">
              <v-toolbar-title>
                <span class="font-weight-medium black--text" color="black">NOANSA</span>
                <br />
                <span class="caption black--text">Coffee Roasters</span>
              </v-toolbar-title>

              <v-spacer></v-spacer>

              <v-toolbar-items class="black--text">
                <v-btn text class="pa-md-6 black--text font-weight-thin">SHOP</v-btn>
                <v-btn text class="pa-md-6 black--text font-weight-thin">WHOLESALE</v-btn>
                <v-btn text class="pa-md-6 black--text font-weight-thin">LOCATIONS</v-btn>
                <v-btn text class="pa-md-6 black--text font-weight-thin">OUR STORY</v-btn>
                <v-icon class="pa-md-5" color="black">mdi-magnify</v-icon>
                <v-icon color="black">mdi-account-circle</v-icon>
              </v-toolbar-items>

              <template v-if="$vuetify.breakpoint.smAndUp">
                <v-btn icon>
                  <v-icon>mdi-magnify</v-icon>
                </v-btn>
                <v-btn icon>
                  <v-icon>mdi-delete-circle</v-icon>
                </v-btn>
                <v-btn icon>
                  <v-icon>mdi-plus-circle</v-icon>
                </v-btn>
              </template>
            </v-toolbar>
          </div>
          <!-- Text and Call to Action -->
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />
          <v-row align="center">
            <div align="center" class="offset-1">
              <span class="black--text font-weight-light" dark>PREMIUM COFFEE</span>
              <P class="black--text display-1">
                A cup of coffee is one of
                <br />the most important,
                <br />simple pleasures in life.
              </P>
              <div class="text-center">
                <v-btn rounded color="orange lighten-2" dark>
                  <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                  <span class="black--text">Shop Now</span>
                </v-btn>
              </div>
            </div>
            <br />
            <br />
            <br />
            <v-row align="center" class="offset-1">
              <v-avatar align="left" height="200" width="200" class="offset-1">
                <img
                  src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                  aspect-ratio="1"
                  class="grey lighten-2"
                  max-width="500"
                  max-height="300"
                />
              </v-avatar>
            </v-row>
          </v-row>
          <br />
          <div align="right">
            <v-icon light size="140" color="grey" right="150">mdi-dialpad</v-icon>
          </div>
        </v-sheet>
      </div>
      <div class="text-center">
        <v-sheet color="white" height="900">
          Hello, world! I'm a simple v-sheet
          <!-- Coffee Cards -->

          <!-- Coffee Cards-->

          <v-row>
            <!-- Coffee Card 1 -->
            <v-card round class="mx-auto" height="250" max-width="300" color="orange lighten-2">
              <v-card-text>
                <v-icon down color="black">mdi-leaf</v-icon>
                <br />
                <br />
                <br />
                <br />
                <div class="display-1 text--primary black--text">
                  <span class="black--text">
                    Qualify Coffee
                    <br />Cultivated by Good
                  </span>
                </div>
              </v-card-text>
            </v-card>
            <!-- Coffee Card 2 -->
            <v-card class="mx-auto elevation-0" height="250" max-width="300" color="white">
              <v-card-text>
                <v-icon align="left" color="black">mdi-glass-mug-variant</v-icon>
                <br />
                <br />
                <br />
                <br />
                <div class="display-1 text--primary black--text">
                  <span class="black--text">
                    Flavour single
                    <br />origin froth in
                    <br />spoon iced
                  </span>
                </div>
              </v-card-text>
            </v-card>
            <!-- Coffee Card 3 -->
            <v-card class="mx-auto elevation-0" height="250" max-width="300" color="white">
              <v-card-text>
                <v-icon align="left" color="black">mdi-flower-tulip-outline</v-icon>
                <br />
                <br />
                <br />
                <br />
                <div class="display-1 text--primary black--text">
                  <span class="black--text">
                    Milk grounds
                    <br />chicory beans
                    <br />single origin
                  </span>
                </div>
              </v-card-text>
            </v-card>
            <!-- Coffee Card 4-->
            <v-card class="mx-auto elevation-0" height="300" max-width="300" color="white">
              <v-card-text>
                <v-icon align="left" color="black">mdi-flower-poppy</v-icon>
                <br />
                <br />
                <br />
                <br />
                <div class="display-1 text--primary black--text">
                  <span class="black--text">
                    Coffee irish
                    <br />robusta spoon
                    <br />robust
                  </span>
                </div>
              </v-card-text>
            </v-card>
          </v-row>
          <br />
          <br />
          <br />
          <br />
          <!--Replacement-->
          <v-row align="center">
            <div align="center" class="offset-1">
              <span class="black--text font-weight-light" dark>PREMIUM COFFEE</span>
              <P class="black--text display-1 font-weight-light">
                Quality Coffee
                <br />Cultivated by Good
              </P>
              <p class="black--text">
                Our love for speciality coffee is never-ending. With over
                <br />365 days a year at origin working with the best growers
                <br />on the planet, only the best beans make the grade
              </p>
              <div class="text-center">
                <v-btn rounded color="orange lighten-2" dark>
                  <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                  <span class="black--text">Shop Now</span>
                </v-btn>
              </div>
            </div>
            <br />
            <br />
            <br />
            <v-row align="center" class="offset-1">
              <v-avatar align="left" height="200" width="200" class="offset-1">
                <img
                  src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                  aspect-ratio="1"
                  class="grey lighten-2"
                  max-width="500"
                  max-height="300"
                />
              </v-avatar>
            </v-row>
          </v-row>
        </v-sheet>
      </div>

      <!-- Thrid Sheet-->

      <div class="text-center">
        <v-sheet color="cream" height="800">
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />

          <!-- Text and Call to Action -->
          <div align="center">
            <p class="font-weight-light">BUY NOW</p>
            <span
              class="white--text black--text display-1 text--primary black--text"
              dark
            >Our Best Deal</span>
            <P dark>
              Coffee company with a straightforward mission to make an office
              <br />and on-the-go cup of coffee taht we'd like to drink ourselves
            </P>
            <div class="text-center">
              <v-btn rounded color="orange lighten-2" dark>
                <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                <span class="black--text">Shop Now</span>
              </v-btn>
            </div>
          </div>
          <br />
          <br />
          <br />
          <v-row align="center" class="offset-1">
            <v-avatar align="left" height="200" width="200" class="offset-1">
              <img
                src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                aspect-ratio="1"
                class="grey lighten-2"
                max-width="500"
                max-height="300"
              />
            </v-avatar>

            <v-avatar align="center" height="200" width="200" class="offset-1">
              <img
                src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                aspect-ratio="1"
                class="grey lighten-2"
                max-width="500"
                max-height="300"
              />
            </v-avatar>

            <v-avatar align="right" height="200" width="200" class="offset-1">
              <img
                src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                aspect-ratio="1"
                class="grey lighten-2"
                max-width="500"
                max-height="300"
              />
            </v-avatar>
          </v-row>
          <br />
          <br />
          <v-row align="left" class="offset-1">
            <div align="center" class="offset-1" left>
              <p>PLATINUM</p>
              <p>Noansa Platinum Blend</p>
              <v-btn rounded color="orange lighten-2" dark>
                <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                <span class="black--text">$30.00</span>
              </v-btn>
            </div>

            <div align="center" class="offset-2">
              <p>CLASSIC</p>
              <p>Noansa Classic Blend</p>
              <v-btn rounded color="orange lighten-2" dark>
                <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                <span class="black--text">$20.00</span>
              </v-btn>
            </div>

            <div class="offset-1">
              <p>GENERAL</p>
              <p>Noansa General Blend</p>
              <v-btn rounded color="orange lighten-2" dark>
                <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                <span class="black--text">$15.00</span>
              </v-btn>
            </div>
          </v-row>
        </v-sheet>
      </div>

      <!-- Fourth Sheet-->

      <div class="text-center">
        <v-sheet color="white" height="800">
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />

          <v-row align="center">
            <div align="center" class="offset-1">
              <span class="black--text" dark>PREMIUM COFFEE</span>
              <p class="black--text text--primary black--text">The Secret lies within the bean</p>
              <P class="black--text">
                You can't imagine a day without a cup of coffee and we
                <br />believe that your office and on-the-go coffee should never be a compromise.
              </P>
              <div class="text-center">
                <v-btn rounded color="orange lighten-2" dark>
                  <v-icon left color="brown darken-1">mdi-hand-pointing-right</v-icon>
                  <span class="black--text">Shop Now</span>
                </v-btn>
              </div>
            </div>
            <br />
            <br />
            <br />
            <v-row align="center" class="offset-1">
              <v-avatar align="left" height="200" width="200" class="offset-1">
                <img
                  src="https://wallup.net/wp-content/uploads/2016/05/25/177309-coffee-coffee_beans-brown-texture-748x468.jpg"
                  aspect-ratio="1"
                  class="grey lighten-2"
                  max-width="500"
                  max-height="300"
                />
              </v-avatar>
            </v-row>
          </v-row>
          <br />
          <div align="right">
            <v-icon light size="140" color="grey" right="150">mdi-dialpad</v-icon>
          </div>
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />
          <br />
          <div class="black--text">
            <p class="black--text display-1">#NOANSACOFFEE</p>
            <P class="font-weight-light">Coffee perfection since 1927.</P>
          </div>
        </v-sheet>
      </div>
      <v-sheet color="white" height="300">
        <!-- Picture Grid -->

        <!-- Old Pic-->
        <v-row>
          <v-col cols="12" sm="6" md="12" fill-height>
            <v-card color="white">
              <v-container fluid fill-height>
                <v-row no-gutters>
                  <v-col
                    v-for="n in 12"
                    :key="n"
                    class="d-flex child-flex"
                    cols="2"
                    fill-height
                    fill-width
                  >
                    <v-card flat tile class="d-flex">
                      <v-img
                        :src="`https://source.unsplash.com/featured/?{coffee},{cafe}=${n * 5 + 10}`"
                        :lazy-src="`https://source.unsplash.com/featured/?{coffee},{cafe}=${n * 5 + 10}`"
                        aspect-ratio="1"
                        class="grey lighten-2"
                      >
                        <template v-slot:placeholder>
                          <v-row class="fill-height ma-0" align="center" justify="center">
                            <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                          </v-row>
                        </template>
                      </v-img>
                    </v-card>
                  </v-col>
                </v-row>
              </v-container>
            </v-card>
          </v-col>
        </v-row>
      </v-sheet>
      <!-- Email Form -->
      <di class="offset-3">
        <p align="left" class="display-1">Would You Like to Hear From Us?</p>
        <p class="text-justify offset-1">Submit Your Email Address To Our Newsletter</p>
      </di>
      <form class="offset-3">
        <v-col cols="6">
          <div>
            <v-text-field
              class="text-right"
              justify-center
              align-center
              v-model="email"
              :error-messages="emailErrors"
              label="yourname@mail.com"
              required
              @input="$v.email.$touch()"
              @blur="$v.email.$touch()"
            ></v-text-field>
          </div>
        </v-col>
      </form>

      <!-- Footer-->
      <v-card height="150">
        <v-footer absolute class="font-weight-medium">
          <v-col cols="12">
            <strong
              class="font-weight-light text-left offset-1 overline grey--text"
            >All Rights Reserved ©</strong>
            <strong
              class="font-weight-light text-right offset-7 overline grey--text"
            >+436 701 32 43 92</strong>
          </v-col>
        </v-footer>
      </v-card>
    </v-app>
  </div>
</template>
<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo
  }
};
</script>
