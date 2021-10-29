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
            <h1 class="text-center">SUJETO DEL DERECHO</h1>
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
      </v-card>
    </v-hover>

  </div>
</template>

<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  >.v-card__text
    color: #000
</style>
