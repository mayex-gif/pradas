<template>
  <div>
    <div class="d-flex" :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'" flat tile>
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
            <h1 class="text-center">LEYES</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué es la ley?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>La ley (en latín, lex, legis) es una norma jurídica dictada por el legislador, es decir, un precepto establecido por la autoridad competente, en que se manda o prohíbe algo en consonancia con la justicia, cuyo incumplimiento conlleva a una sanción.1​Según el jurista panameño César Quintero, la ley es una «norma dictada por una autoridad pública que a todos ordena, prohíbe o permite, y a la cual todos deben obediencia». Por otro lado, el jurista venezolano Andrés Bello definió la ley como «una declaración de la voluntad soberana que, manifestada en la forma prescrita por la Constitución, manda, prohíbe o permite». Para Bello, lo decisivo para calificar un acto de ley es la forma en que se gesta y no la naturaleza de la disposición en él contenida.2​En general, las leyes son normas que regulan la convivencia social de una nación.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Consideraciones</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Las leyes son delimitadoras del libre albedrío de las personas dentro de la sociedad. Se puede decir que la ley es el control externo que existe para la conducta humana, las normas que rigen nuestra conducta social. Constituye una de las principales fuentes del derecho.</p>
          </v-list-item-content>
        </v-list-item>

        <v-list-item last-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <a href="https://es.wikipedia.org/wiki/Ley"> https://es.wikipedia.org/wiki/Ley </a>
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
