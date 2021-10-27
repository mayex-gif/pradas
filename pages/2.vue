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
            <h1 class="text-center">DERECHOS Y NORMAS</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué son los DERECHOS?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Derechos, en plural, es lo que se concede o reconoce a un sujeto de derecho (independientemente de que haya sido exonerado o no por él); a diferencia de derecho, en singular, que puede referirse a la ciencia jurídica, al ordenamiento jurídico o a un sistema jurídico. La justificación del disfrute o ejercicio de los distintos derechos por cada uno de los sujetos que los poseen puede basarse en muy distintas circunstancias: la herencia, la vecindad, la conquista, el trabajo, u otras. En este sentido, resulta un término difuso por resultar comprehensivo de diversas situaciones o relaciones jurídicas, por el contenido, objeto o sentido de lo reconocido o concedido, el titular o el eventual obligado (sujeto pasivo). La identificación del concepto de derechos con el de libertades se da en la expresión, muy común, derechos y libertades.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Distinciones</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Una aproximación puede ser el tipo de sujeto de derecho involucrado, que puede ser un sujeto individual (como el ser humano, la persona física, el ciudadano, nacional o miembro de un Estado, una nación o una sociedad civil, o una persona jurídica como tal), un sujeto colectivo (la nación, los pueblos, los trabajadores o las personas morales), o incluso un sujeto no humano (como diferentes especies de animales o la totalidad de la naturaleza). A partir de lo anterior, se suelen distinguir distintas categorías de derechos, tales como: los derechos subjetivos, los derechos permanentes y personalísimos, los derechos individuales (individual rights), los derechos fundamentales o derechos humanos, el derecho a la autodeterminación de los pueblos, los derechos de los trabajadores,1​ los denominados derechos de los animales, entre otros.2​</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item four-line>
          <v-list-item-content>
            <h3>Enlaces externos</h3>
            <v-divider class="mb-1"></v-divider>
            <a href="https://es.wikipedia.org/wiki/Derechos"> https://es.wikipedia.org/wiki/Derechos </a>
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

