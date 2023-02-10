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
            <h1 class="text-center">SUJETO DE DERECHO</h1>
          </v-list-item-content>
        </v-list-item>
          <v-list-item two_five-line>
          <v-list-item-content>
            <h2>Concepto</h2>
            <v-divider class="mb-1"></v-divider>
            <p><strong>Sujeto</strong>, es un concepto que puede emplearse de diferentes formas. Puede tratarse de un individuo que, en un determinado contexto, carece de identificación o de denominación. También puede referirse a una categoría filosófica o a una función gramatical.</p><br><br>
            <p><strong>Derecho</strong>, por su parte, puede ser aquello que guía el accionar correcto, legítimo o adecuado de las personas. La noción también se asocia a las normas que expresan un ideal de justicia y que permiten regular la conducta y los vínculos humanos.</p><br><br>
            <p>Con estas definiciones, podemos comprender a qué se refiere la idea de sujeto de derecho. Se trata de aquel al que pueden imputársele derechos y obligaciones a través de la ley. Todas las personas, ya sean físicas o jurídicas, son sujetos de derecho.</p><br>
            <center><br><br><img style="width: 50%;" src="https://definicion.de/wp-content/uploads/2014/10/sujeto-de-derecho.jpg"></center>
          </v-list-item-content>
        </v-list-item>
          <v-list-item two_six-line>
          <v-list-item-content>
            <h2>Tipos de Sujeto de Derecho</h2>
            <v-divider class="mb-1"></v-divider><br>
            <p>Es importante conocer que los sujetos de derecho pueden ser de dos tipos:</p><br>
            <br><ul>
              <li>Sujetos de derechos individuales, que son los ciudadanos individuales que son capaces de adquirir derechos y obligaciones. También son conocidos como personas naturales o físicas.</li><br>
              <li>Sujetos de derechos colectivos, que son los que se vienen a constituir como personas jurídicas.</li>
            </ul>
            <br>
            <br><p><br>Es importante destacar, en este sentido, que las personas físicas o personas naturales son todos los integrantes de la especie humana. Cada ser humano, por el hecho de nacer, es un sujeto de derecho</p>
            <p><br>Las <strong>personas jurídicas</strong>, también denominadas personas morales, no son individuos, sino entidades creadas por personas físicas. Más allá de su naturaleza abstracta o ideal, también son sujetos de derecho.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Cuándo habrá sociedad?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Habrá sociedad comercial cuando dos o más personas en forma organizada, conforme a uno de los tipos previstos en esta ley se obliguen a realizar aportes para aplicarlos a la producción o intercambio de bienes o servicios participando de los beneficios y soportando las pérdidas. </p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Tipos de Sociedades</h3>
            <v-divider class="mb-1"></v-divider>
            <p class="ma-4"><strong> Sociedad colectiva:</strong> Una sociedad colectiva, es uno de los posibles tipos de sociedad mercantil. Se trata de una sociedad externa (que actúa y responde frente a terceros como una persona distinta de la de sus socios), que realiza actividades mercantiles o civiles bajo una razón social unificada, respondiendo los socios de las deudas que no pudieran cubrirse con el capital social.</p>
            <p class="ma-4"><strong> Sociedad en comandita simple:</strong> Es aquella que existe bajo una razón social y se componen de uno o varios socios comanditados o “gestores” o “generales” (responsables por la administración de la empresa, incluyendo todos sus activos personales y comerciales), y de uno o varios comanditarios.</p>
            <p class="ma-4"><strong> Sociedad de capital e industria:</strong> Es la constituida por uno o varios socios que aportan capital (socios capitalistas), con los mismos derechos y obligaciones que los integrantes de una sociedad colectiva, y uno o varios socios que ingresan con su industria solamente (socios industriales).</p>
            <p class="ma-4"><strong> Sociedad de responsabilidad limitada:</strong> Es un tipo de sociedad mercantil, en la cual la responsabilidad está limitada al capital aportado, y por lo tanto, en el caso de que se contraigan deudas, no responde con el patrimonio personal de los socios, sino al aportado en dicha empresa Limitada (LTDA). Presenta como una sociedad de tipo capitalista en la que el capital, que estará dividido en participaciones sociales, se integrará por las aportaciones de todos los socios, quienes no responderán personalmente de las deudas sociales.</p>
            <p class="ma-4"><strong> Sociedad en comandita por acciones:</strong> Es un híbrido entre una sociedad y una sociedad de responsabilidad limitada. El capital y la propiedad de la empresa se dividen entre los accionistas que tienen una responsabilidad limitada y uno o más socios que tienen la responsabilidad total por el resto de las deudas de la empresa. El socio (s) normalmente dirige las operaciones de la empresa, mientras que los accionistas son inversores pasivos.</p>
            <p class="ma-4"><strong> Sociedad anónima unipersonal:</strong> Es una empresa de carácter mercantilista, cualquiera que sea su objeto y dispone de un único socio, ya sea por el hecho de que así fue desde el momento de su constitución, o bien, porque finalmente todos los socios con los que contaba la empresa se quedaron reducidos finalmente a uno.</p>

          </v-list-item-content>
        </v-list-item>
        <center>
          <img style="width: 80%;" src="https://www.soyconta.com/wp-content/uploads/2019/09/tipos_sociedades_mercantiles.jpg" height="300px">
        </center>
        <v-list-item last-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <br>
            <a href="https://es.wikipedia.org/wiki/Sujeto_de_derecho">https://es.wikipedia.org/wiki/Sujeto_de_derecho</a><br>
            <a href="https://www.oas.org/juridico/PDFs/mesicic3_per_leysociedades.pdf">https://www.oas.org/juridico/PDFs/mesicic3_per_leysociedades.pdf</a>
            <a href="https://www.scotiabankcolpatria.com/educacion-financiera/finanzas-maestras/tipos-de-sociedades">https://www.scotiabankcolpatria.com/educacion-financiera/finanzas-maestras/tipos-de-sociedades</a>
            <a href="https://definicion.de/sujeto-de-derecho/">https://definicion.de/sujeto-de-derecho/</a>
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
