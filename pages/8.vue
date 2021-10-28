<template>
  <div>

    <div class="d-flex justify-space-between" :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'" flat tile>
      <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
        <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
          <v-btn color="$vuetify.theme.dark" nuxt to="/"><v-icon>mdi-chevron-left</v-icon></v-btn>
        </v-card>
      </v-hover>
    </div>

    <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
      <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" class="mx-auto mt-3" max-width="%90" tile>
        <v-list-item>
          <v-list-item-content>
            <h1 class="text-center">ETICA Y DEONTOLOGIA</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Que es Ètica?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Una sentencia ética es una declaración moral que elabora afirmaciones y define lo que es bueno, malo, obligatorio, permitido, etc. en lo referente a una acción o a una decisión.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>¿Qué es Moral?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Se trata de un conjunto de creencias, costumbres, valores y normas de una persona o de un grupo social, que funciona como una guía para obrar. Es decir, la moral orienta acerca de qué acciones son correctas (buenas) y cuáles son incorrectas (malas).</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item four-line>
          <v-list-item-content>
            <h3>Definición de Deontologìa profesional</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Es un sistema de autorregulación del que se dota una corporación profesional que por encomienda de la sociedad tiene reconocidas atribuciones propias en un campo determinado, con el fin de garantizar que las ejerce con sentido de responsabilidad y enfocándolas hacia la defensa del interés general.</p>
          </v-list-item-content>
        </v-list-item>
      </v-card>
    </v-hover>

  </div>
</template>

<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  >.v-card__text
    color: #000
</style>
