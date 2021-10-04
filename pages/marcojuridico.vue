<template>
  <v-row justify="center" align="center">
    <v-col>
      <v-card class="text-center">
        <h1>Marco jurídico</h1>

            <div class="d-flex justify-space-between pa-4"
            :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'"
            flat
            tile>
              <v-btn  color="primary" nuxt to="/1">
                Leyes
              </v-btn>
              <v-btn  color="primary" nuxt to="/2">
                Derechos
              </v-btn>
              <v-btn  color="primary" nuxt to="/3">
                Alejo
              </v-btn>
              <v-btn  color="primary" nuxt to="/4">
                Naza
              </v-btn>
              <v-btn  color="primary" nuxt to="/5">
                Petito
              </v-btn>
              <v-btn  color="primary" nuxt to="/6">
                Luisito
              </v-btn>
            </div>

      </v-card>
    </v-col>
  </v-row>
</template>
