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
            <p>Una ley es una regla o norma jurídica de carácter obligatorio dictada por la autoridad competente de un territorio. Tiene como fin permitir o prohibir alguna acción de los individuos con el objetivo de regular las conductas humanas y lograr una convivencia armoniosa dentro de una sociedad.</p>
            <br><br>
            <p>Son de carácter coercitivo, esto significa que en caso de que la leyes no sean cumplidas, la fuerza pública tiene el deber y obligación de sancionar a la persona o institución correspondiente. Por eso, muchas veces lo individuos deben someterse a las leyes a pesar de no estar de acuerdo con ellas.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Caracteristicas</h3>
            <v-divider class="mb-1"></v-divider>
            <ul>
              <li>
                <p class="ma-4"><strong> Impersonales:</strong> Las leyes no son nominales, es decir, no van dirigidas a personas en concreto, sino que se dirigen a la sociedad en conjunto.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Obligatorias:</strong> Las leyes tienen carácter vinculante. Es decir, tienen fuerza obligatoria para con los ciudadanos. Es obligatorio respetar y cumplir con la ley.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Abstactas:</strong> Las leyes no recogen supuestos concretos, sino que hablan de un supuesto general donde se pueden entender dentro los demás casos concretos y sus particularidades.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Generales:</strong> Las leyes son dictadas para que sean cumplidas por toda la población a la que hace referencia dicha ley en su regulación.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Publicas:</strong> Las leyes deben ser publicadas para que sean de posible conocimiento por toda la población, sin la cual no se podría exigir su obligado cumplimiento.</p>
              </li>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <h4>Tipos de leyes:</h4>
            <v-divider class="mb-1"></v-divider>
            <h4>Según el modo:</h4>
            <br><br>
            <ul>
              <li><p><strong>Leyes permisivas:</strong> Permiten al sujeto realizar determinadas acciones.</p></li>
              <li><p><strong>Leyes prohibitidas:</strong> Sancionan al sujeto que lleva a cabo determinados comportamientos.</p></li>
            </ul>
            <h4>Según el rango:</h4>
            <br><br>
            <ul>
              <li><p><strong>Leyes orgánicas:</strong> Regulan los derechos fundamentales y libertades públicas y requieren de una mayoría en el órgano legislativo para ser aprobadas.</p></li>
              <li><p><strong>Leyes ordinarias:</strong> Regulan materias específicas que no afectan los  fundamentos de las leyes orgánicas por lo que requieren de una minoría simple en el órgano legislativo para ser aprobadas.</p></li>
            </ul>
            <h4>Según el origen o sentido</h4>
            <br><br>
            <ul>
              <li><p><strong>Leyes formales:</strong> Normas formuladas por el poder legislativo independientemente de su contenido</p></li>
              <li><p><strong>Leyes materiales:</strong> Normas generales y obligatorias que emanan de otras autoridades competentes. </p></li>
            </ul>
            
            <h4>según el ámbito de aplicación</h4>
            <br><br>
            <ul>
              <li><p><strong>Leyes federales:</strong> Se promulgan y tienen validez en todo el territorio de una nación.</p></li>
              <li><p><strong>Leyes locales:</strong> Son promulgadas por el órgano legislativo de una provincia o estado y tienen validez solo en ese territorio.</p></li>
            </ul>

            <h3>Caracteristicas de las leyes</h3>
            <v-divider class="mb-1"></v-divider>
             <ul>
              <li>
                <p class="ma-4"><strong> Impersonales:</strong> Las leyes no son nominales, es decir, no van dirigidas a personas en concreto, sino que se dirigen a la sociedad en conjunto.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Obligatorias:</strong> Las leyes tienen carácter vinculante. Es decir, tienen fuerza obligatoria para con los ciudadanos. Es obligatorio respetar y cumplir con la ley.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Abstactas:</strong> Las leyes no recogen supuestos concretos, sino que hablan de un supuesto general donde se pueden entender dentro los demás casos concretos y sus particularidades.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Generales:</strong> Las leyes son dictadas para que sean cumplidas por toda la población a la que hace referencia dicha ley en su regulación.</p>
              </li>
              <li>
                <p class="ma-4"><strong> Publicas:</strong> Las leyes deben ser publicadas para que sean de posible conocimiento por toda la población, sin la cual no se podría exigir su obligado cumplimiento.</p>
              </li>
            </ul>

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
