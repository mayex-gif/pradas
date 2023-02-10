<template>
  <div style="padding-bottom:15%;">
    <div class="d-flex justify-space-between" :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'" flat tile>
      <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
        <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
          <v-btn color="$vuetify.theme.dark" nuxt to="/"><v-icon>mdi-chevron-left</v-icon></v-btn>
        </v-card>
      </v-hover>
    </div>
    <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
      <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" class="mx-auto mt-3" max-width="100%" tile>
        <v-list-item>
          <v-list-item-content>
            <h1 class="text-center">CONTACTO</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Quienes Somos?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Somos alumnos de 7mo Año de la Tecnicatura en Programacion del Instituto Manuel de Falla,Alta Gracia,Cordoba,Argentina</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Datos Personales</h3>
            <v-divider class="mb-1"></v-divider>
            <ul><br>
                <li><strong>Alcalde Alejo: </strong>alcaldealejo53@gmail.com</li><br>
                <li><strong>Rodriguez Tadeo: </strong>tadetortosa@gmail.com</li><br>
                <li><strong>Nazareno Viero: </strong>nazarenoviero@gmail.com</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
      </v-card>
    </v-hover>
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8146212242893305"
     crossorigin="anonymous"></script>
  </div>
</template>

<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  >.v-card__text
    color: #000
</style>
