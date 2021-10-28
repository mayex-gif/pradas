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
            <p><br>El derecho es un conjunto de principios y normas generalmente inspirados en ideas de justicia y orden, que regulan las relaciones humanas en toda sociedad y cuya observancia es impuesta de forma coactiva por parte de un poder público. El conjunto de principios y normas jurídicas de un Estado determinado constituye su ordenamiento jurídico. El derecho es el objeto de estudio de la ciencia del derecho. El derecho guarda una íntima conexión con la política, la economía, la sociología y la historia, y es el centro de problemas humanos complejos como la determinación de lo que es justo.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Derecho objetivo y derecho subjetivo</h3>
            <v-divider class="mb-1"></v-divider>
            <p>El derecho objetivo es el conjunto de normas jurídicas (leyes, reglamentos, entre otras) de carácter obligatorio, y que son creadas por el Estado para conservar el orden social. Siempre teniendo en cuenta la validez, es decir, si se ha llevado a cabo el procedimiento adecuado para su creación, independientemente de su eficacia y de su ideal axiológico (si busca concretar un valor como la justicia, la armonía, el bien común, etcétera).<br><br>El derecho subjetivo es la facultad que ha otorgado el ordenamiento jurídico a un sujeto (por ejemplo, derecho a la nacionalidad, derecho a la salud, derecho a demandar, derecho a manifestarse libre y pacíficamente, derecho a la libre expresión, derecho al sindicalismo, etc.)
            <br><br><u>El derecho objetivo puede responder a distintas significaciones:</u></p><br>
            <ul><br>
            <li>El conjunto de reglas que rigen la convivencia de los hombres en sociedad.</li><br>
            <li>Norma o conjunto de normas que por una parte otorgan derechos o facultades y por la otra, correlativamente, establecen o imponen obligaciones.</li><br>
            <li>Conjunto de normas que regulan la conducta de los hombres, con el objeto de establecer un ordenamiento justo de convivencia humana. </li><br>
            </ul>
            <p><u>El derecho subjetivo se puede decir que es:</u></p><br>
            <ul><br>
            <li>La facultad que tiene un sujeto para ejecutar un acto con determinada conducta o abstenerse de ella, o para exigir de otro sujeto el cumplimiento de su deber.</li><br>
            <li>La facultad, la potestad o autorización que conforme a la norma jurídica tiene un sujeto frente a otro u otros sujetos, ya sea para desarrollar su propia actividad o determinar la de aquellos.</li><br>
            <li>Es una concesión de autoridad otorgada por una norma jurídica una persona o grupo en virtud de la cual queda legitimada para desplegar una determinada conducta sobre una o más personas o cosas.</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <h3>¿Cuál es la diferencia entre los Derechos Humanos y los Derechos Fundamentales?</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Se diferencian en que los derechos humanos tienen un alcance universal, pues se reconocen a todas las personas en el mundo desde el momento de su nacimiento, los derechos fundamentales tienen un alcance nacional y, dependiendo del país, pueden variar.</p>
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

