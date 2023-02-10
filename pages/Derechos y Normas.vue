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
            <div class="text-center">
              <h1>DERECHOS</h1>
            </div>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué son los Derechos?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>El Derecho es un conjunto de principios y normas generalmente inspirados en ideas de justicia y orden, que regulan las relaciones humanas en toda sociedad y cuya observancia es impuesta de forma coactiva por parte de un poder público. El conjunto de principios y normas jurídicas de un Estado determinado constituye su ordenamiento jurídico. El derecho es el objeto de estudio de la ciencia del derecho. El derecho guarda una íntima conexión con la política, la economía, la sociología y la historia, y es el centro de problemas humanos complejos como la determinación de lo que es justo.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Derecho Objetivo y Derecho Subjetivo</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>El derecho Objetivo es el conjunto de normas jurídicas (leyes, reglamentos, entre otras) de carácter obligatorio, y que son creadas por el Estado para conservar el orden social. Siempre teniendo en cuenta la validez, es decir, si se ha llevado a cabo el procedimiento adecuado para su creación, independientemente de su eficacia y de su ideal axiológico (si busca concretar un valor como la justicia, la armonía, el bien común, etcétera).<br>
            <br>El derecho Subjetivo es la facultad que ha otorgado el ordenamiento jurídico a un sujeto (por ejemplo, derecho a la nacionalidad, derecho a la salud, derecho a demandar, derecho a manifestarse libre y pacíficamente, derecho a la libre expresión, derecho al sindicalismo, etc.)
            <br><br><u>El derecho Objetivo puede responder a distintas significaciones:</u></p><br>
            <ul><br>
            <li>El conjunto de reglas que rigen la convivencia de los hombres en sociedad.</li><br>
            <li>Norma o conjunto de normas que por una parte otorgan derechos o facultades y por la otra, correlativamente, establecen o imponen obligaciones.</li><br>
            <li>Conjunto de normas que regulan la conducta de los hombres, con el objeto de establecer un ordenamiento justo de convivencia humana. </li><br>
            </ul>
            <p><u>El Derecho Subjetivo se puede decir que es:</u></p><br>
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
            <p><br>Se diferencian en que los Derechos Humanos tienen un alcance universal, pues se reconocen a todas las personas en el mundo desde el momento de su nacimiento, los Derechos Fundamentales tienen un alcance nacional y, dependiendo del país, pueden variar.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item-content>
            <div class="text-center">
              <h1>NORMAS</h1>
            </div>
        </v-list-item-content>
        <v-list-item>
        <v-list-item-content>
            <h3> ¿Qué son las Normas?</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Se conoce como norma a la regla o un conjunto de estas, una ley, una pauta o un principio que se impone, se adopta y se debe seguir para realizar correctamente una acción o también para guiar, dirigir o ajustar la conducta o el comportamiento de los individuos.</p>
        </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>Tipos de Normas</h3>
            <v-divider class="mb-1"></v-divider>
            <ul><br>
              <li><strong>Normas Juridicas:</strong>Son reglas bilaterales que otorgan al mismo tiempo facultades y deberes, es decir, derechos y obligaciones. Al ser impuestas por el Estado por encima de los demás tipos de normas, se caracterizan por ser heterónomas, bilaterales, externas y, por supuesto, coercibles, así como en su momento pueden llegar a convertirse en coactivas.</li><br>
              <li><strong>Normas Morales:</strong>Son aquéllas que el ser humano realiza de forma consciente, libre y responsable, con el propósito de hacer el bien; son propias del ser humano y su sanción –el castigo que recibe la persona–, en caso de incumplimiento, es el remordimiento de conciencia. Se caracterizan por ser autónomas, unilaterales, internas e incoercibles.</li><br>
              <li><strong>Normas Religiosas:</strong>Son un conjunto de preceptos manifestados al hombre por Dios o dadas por la autoridad eclesiástica (Iglesia) para el bien común. Se caracterizan por ser heterónomas, unilaterales, internas e incoercibles.</li><br>
              <li><strong>Normas de Trato Social:</strong>Son las reglas creadas por la sociedad y provocan el rechazo por parte del grupo social de quien las incumple. Se caracterizan por ser heterónomas, unilaterales, externas e incoercibles.</li><br>
              <li><strong>Normas Tecnicas:</strong>Son reglas de conducta de tipo operativo o funcional que tratan de explicar el uso de una herramienta, objeto o maquinaria, a fin de aprovechar su fuerza, precisión, naturaleza o material con el que están hechos. Establece especificaciones sobre procesos de producción, resultado de la experiencia y desarrollo tecnológico, para la fabricación de determinados productos o servicios; útil para todos aquellos interesados en la actividad productiva, tales como fabricantes, consumidores, laboratorios, centros de investigación, etcétera.</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <center>
        <img style="width: 100%" src="https://pbs.twimg.com/media/DpwZB92WkAAAJ5U.jpg">
        </center>
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

