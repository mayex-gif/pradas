<template>
  <v-row justify="center" align="center">
    <v-col>

      <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
        <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" class="mx-auto mt-3" max-width="100%" tile>
          <h1 class="text-center">MARCO JURÍDIO</h1>
          <v-list-item one-line>
            <v-list-item-content>
              <h3>¿Qué es el marco jurídico o marco legal?</h3>
              <v-divider class="mb-1"></v-divider>
              <p>El marco jurídico o marco legal nos proporciona las bases sobre las cuales las instituciones construyen y determinan el alcance y naturaleza de la participación política. El marco legal de una elección, y especialmente los temas relacionados con la integridad de la misma, regularmente se encuentran en un buen número de provisiones regulatorias y leyes interrelacionadas entre sí.</p>
            </v-list-item-content>
          </v-list-item>
          <v-list-item two-line>
            <v-list-item-content>
              <h3 class="text-center"> ELIJA UN TEMA</h3>
              <v-divider class="mb-1"></v-divider>
            </v-list-item-content>
          </v-list-item>
          <div class="d-flex justify-space-between pa-3" :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'" flat tile>
            <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
              <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" >
                <v-btn color="primary" class="font-weight-medium text-center text-subtitle-1" nuxt to="/1">
                  LEYES
                </v-btn>
              </v-card>                </v-hover>
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

          <v-list-item last-line>
            <v-list-item-content>
              <h3>Enlaces externos</h3>
              <v-divider class="mb-1"></v-divider>
              <a href="https://es.wikipedia.org/wiki/Ley"> https://es.wikipedia.org/wiki/Ley </a>
            </v-list-item-content>
          </v-list-item>


        </v-card>
      </v-hover>
    </v-col>
  </v-row>
</template>

<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  >.v-card__text
    color: #000
</style>
