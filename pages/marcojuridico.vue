<template>
  <v-row justify="center" align="center">
    <v-col>
      <v-card class="text-center">
        <h1>Marco jurídico</h1>


            <div class="d-flex justify-space-between pa-3" :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'" flat tile>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/1">
                    LEYES
                  </v-btn>
                </v-card>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/2">
                    DERECHOS
                  </v-btn>
                </v-card>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/3">
                    ALEJO
                  </v-btn>
                </v-card>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/4">
                    NAZARENO
                  </v-btn>
                </v-card>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/5">
                    PETITO
                  </v-btn>
                </v-card>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                  <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/6">
                    LUISITO
                  </v-btn>
                </v-card>
              </v-hover>
            </div>



      </v-card>
    </v-col>
  </v-row>
</template>

<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  background-color: rgba(#FFF, 0.8)
  >.v-card__text
    color: #000
</style>
