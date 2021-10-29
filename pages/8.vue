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
            <p>Una sentencia ética es una declaración moral que elabora afirmaciones y define lo que es bueno, malo, obligatorio, permitido, etc. en lo referente a una acción o a una decisión.</p><br><br>
            <p>Por lo tanto, cuando alguien aplica una sentencia ética sobre una persona, está realizando un juicio moral. La ética, pues, estudia la moral y determina cómo deben actuar los miembros de una sociedad. Por lo tanto, se la define como la ciencia del comportamiento moral.<br><br>Claro que la ética no es coactiva, ya que no impone castigos legales (sus normas no son leyes). La ética ayuda a la justa aplicación de las normas legales en un Estado de derecho, pero en sí misma no es de castigo desde el punto de vista jurídico, sino que promueve una autorregulación.<br><br>
            <p><strong>La Etica puede dividirse en diversas ramas, entre las que se destacan:</strong></p>
            <ul><br>
              <li>La Etica Normativa (son las teorías que estudia la axiología moral y la deontología, por ejemplo).</li><br>
              <li>La Etica Aplicada (se refiere a una parte específica de la realidad, como la bioética y la ética de las profesiones).</li><br>
            </ul>
            <p><strong>Principales Características de la Ética:</strong></p>
            <ul><br>
              <li>Teórica o General: Por tener sus conocimientos especulativos puramente racionales, sobre los criterios o Normas de la moral.</li><br>
              <li>Práctica o Especial: Por estudiar los medios particulares, las virtudes, los deberes, etc.</li><br>
              <li>Ciencia Filosófica: Que actúa en el plano de los valores y la controversia.</li><br>
              <li>Forma de Conciencia: Se ocupa de algo muy abstracto "el debe ser".</li><br>
              <li>Establece principios universales: Busca formular explicaciones teóricas generales, aplicables en toda sociedad y todo tiempo.</li><br>
              <li>Enfoca la moral Como fenómeno: Toma en cuenta los valores, sean estos positivos o negativos, en cada época.</li><br>
              <li>Orienta el Comportamiento Moral: Señala las Normas adecuadas de la convivencia.</li><br>
              <li>Está presente en todo acto humano: Es UN elemento universal y básico de cohesión social.</li><br>
            </ul>
            <v-divider class="mb-1"></v-divider>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>¿Qué es Moral?</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Se trata de un conjunto de creencias, costumbres, valores y normas de una persona o de un grupo social, que funciona como una guía para obrar.<br><br> Es decir, la moral orienta acerca de qué acciones son correctas (buenas) y cuáles son incorrectas (malas).</p><br><br>
            <p><br>Según otra definición, la moral es la suma total del conocimiento que se adquiere sobre lo más alto y noble, y que una persona respeta en su conducta.<br><br>Las creencias sobre la moralidad son generalizadas y codificadas en una cierta cultura o en un grupo social determinado, por lo que la moral regula el comportamiento de sus miembros.<br><br>Por otra parte, la moral suele ser identificada con los principios religiosos y éticos que una comunidad acuerda respetar.<br>El conjunto de normas morales es denominado como moralidad objetiva (existen como hechos sociales más allá de que el sujeto decida acatarlas).<br>En cambio, los actos a través de los cuales la persona respeta o viola la norma moral conforman la moralidad subjetiva.<br><br>Cabe mencionar que la idea de responsabilidad moral aparece con el convencimiento de que el accionar del individuo siempre se realiza con un fin, a menos de que se encuentra inconsciente (ya sea por una enfermedad mental, un desequilibrio psicológico, los efectos de una droga, etc.). Se dice que una persona que hace uso de los valores morales de su sociedad puede forjarse un mejor destino.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item four-line>
          <v-list-item-content>
            <h3>Definición de Deontologia Profesional</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Es un sistema de autorregulación del que se dota una corporación profesional que por encomienda de la sociedad tiene reconocidas atribuciones propias en un campo determinado, con el fin de garantizar que las ejerce con sentido de responsabilidad y enfocándolas hacia la defensa del interés general.</p><br>
            <p><br>En cierto sentido, podría interpretarse como una contrapartida. Los arquitectos, como otras profesiones, gozamos de un área de actividad exclusiva, amparada por el currículo formativo inherente al título, y a cambio, si así puede decirse, devolvemos a la sociedad la confianza otorgada en forma de un conjunto de normas de conducta, adoptadas por propia iniciativa.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item last-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <br>
            <a href="http://ftp.campusvirtual.utn.ac.cr/objetos%20de%20aprendizaje%20profesores/exelearning%20etica%20profesional/eticaprofesional/index.html">http://ftp.campusvirtual.utn.ac.cr</a><br>
            <a href="https://www.cscae.com/index.php/presentacion/234-conoce-cscae/articulos-codigo/3972-0-que-es-la-deontologia-profesional">https://www.cscae.com/index.php/presentacion/234-conoce-cscae/articulos-codigo/3972-0-que-es-la-deontologia-profesional</a>
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
