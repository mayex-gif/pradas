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
            <h1 class="text-center">PROTECCION A LOS DERECHOS DE AUTOR</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h2>Derechos de Autor</h2>
            <v-divider class="mb-1"></v-divider><br>
            <h3>Ley Aplicable:</h3>
            <p>La Ley 11723-Ley de propiedad intelectual Argentina El derecho de propiedad de una obra científica, literaria o artística, comprende para su autor la facultad de disponer de ella, de publicarla, de ejecutarla, de representarla, y exponerla en público, de enajenarla, de traducirla, de adaptarla o de autorizar su traducción y de reproducirla en cualquier forma.</p>
            <h3>Objeto de Protección:</h3>
            <p>La protección del derecho de autor abarcará la expresión de ideas, procedimientos, métodos de operación y conceptos matemáticos, pero no esas ideas, procedimientos, métodos y conceptos en sí.</p>
            <h3>Titular del Derecho:</h3>
            <p>Son titulares del derecho de propiedad intelectual: a) El autor de la obra; b) Sus herederos o derechohabientes; c) Los que con permiso del autor la traducen, refunden, adaptan o modifican sobre la nueva obra intelectual resultante.</p>
            <h3>Tiempo de Protección:</h3>
            <p>Para el titular toda su vida y para los herederos 70 años desde la muerte del autor.</p>
            <h3>Ejemplos:</h3>
            <p>El libro, “La continuidad de los parques” de Julio Cortázar (1964).</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h2>Marca</h2>
            <v-divider class="mb-1"></v-divider><br>
            <h3>Ley Aplicable:</h3>
            <p>La Ley Nacional de Marcas y Designaciones 22.362[2], es la norma que regula integralmente el instituto marcario en nuestro país. En ella se establece lo que puede ser objeto de un registro marcario, y a su vez lo que no se considera marca y no puede ser registrado.</p>
            <h3>Objeto de Protección:</h3>
            <p>Todo tipo de signo que sirva para la distinción de un bien o servicio.</p>
            <h3>Titular del Derecho:</h3>
            <p>A cualquier persona humana o jurídica, a sus apoderados o agentes de la propiedad industrial matriculados. Los apoderados deberán comprender que los datos en la solicitud de Marcas tienen carácter de declaración jurada. El INPI tiene la facultad de requerir, de considerarlo, constancia del poder. No es necesario acompañarlo, pero si hacerse responsable de los datos declarados.</p>
            <h3>Tiempo de Protección:</h3>
            <p>El registro dura 10 años, pero puede ser renovado durante nuevos periodos consecutivos de 10 años en un plazo de 6 meses previos al vencimiento.</p>
            <h3>Ejemplos:</h3>
            <p>Coca-Cola, logotipo de Coca-Cola.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item four-line>
          <v-list-item-content>
            <h2>Patente de Invencion</h2>
            <v-divider class="mb-1"></v-divider><br>
            <h3>Ley Aplicable:</h3>
            <p>La ley es la 24481, las invenciones en todos los géneros y ramas de la producción conferirán a sus autores los derechos y obligaciones que se especifican en la presente ley. la titularidad del invento se acreditará con el otorgamiento de los siguientes títulos de propiedad industrial: a) patentes de invención; y b) certificados de modelo de utilidad.</p>
            <h3>Objeto de Protección:</h3>
            <p>La Patente de Invención protege todo nuevo producto o procedimiento, que ofrece una nueva manera de hacer algo o una nueva solución técnica a un problema. Puede ser objeto de Patente de Invención un procedimiento, un método de fabricación, una máquina o aparato o un producto</p>
            <h3>Titular del Derecho:</h3>
            <p>Una patente puede ser solicitada por personas físicas o morales. Podrá ser solicitada directamente por el inventor o por su causahabiente o a través de sus representantes.</p>
            <h3>Tiempo de Protección:</h3>
            <p>La patente tiene una duración de VEINTE años improrrogables, contados a partir de la fecha de presentación de la solicitud</p>
            <h3>Ejemplos:</h3>
            <p>El ratón del ordenador, patentado en 1970 por Douglas Engelbart y que sirvió como base para el desarrollo de tecnologías derivadas como el touchpad de los ordenadores portátiles.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item five-line>
          <v-list-item-content>
            <h2>Modelo de Utilidad</h2>
            <v-divider> class="mb-1"></v-divider><br>
            <h3>Ley Aplicable:</h3>
            <p>La ley es la 24481, las invenciones en todos los géneros y ramas de la producción conferirán a sus autores los derechos y obligaciones que se especifican en la presente ley. la titularidad del invento se acreditará con el otorgamiento de los siguientes títulos de propiedad industrial: a) patentes de invención; y b) certificados de modelo de utilidad.</p>
            <h3>Objeto de Protección:</h3>
            <p>Protegen invenciones, pero de menor valor creativo que una Patente y por tanto con menor actividad inventiva.</p>
            <h3>Titular del Derecho:</h3>
            <p>Toda persona física o jurídica, nacional o extranjera que tenga un domicilio real o legal en Argentina, puede obtener el registro de un modelo de utilidad.</p>
            <h3>Tiempo de Protección:</h3>
            <p>El modelo de Utilidad tiene una duración de DIEZ años improrrogables, contados a partir de la fecha de presentación de la solicitud.</p>
            <h3>Ejemplos:</h3>
            <p>Generalmente hablamos de una ventaja o mejor uso de una invención que ya existía. Por ejemplo, se puede dar a una máquina cortadora de césped una configuración o estructura que mejora la forma en la que corta el pasto localizado en las esquinas (de más difícil acceso).</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item six-line>
          <v-list-item-content>
            <h2>Diseño Industrial</h2><br>
            <v-divider class="mb-1"></v-divider><br>
            <h3>Ley Aplicable:</h3>
            <p>LEY N° 6.673- MODELO O DISEÑO INDUSTRIAL</p>
            <h3>Objeto de Protección:</h3>
            <p>El objeto de protección del Decreto-Ley 6673/63 es la obra que tiene por finalidad mejorar el aspecto del producto, de modo que se tiene en cuenta esta faz ornamental o estética con prescindencia de las potencialidades de uso o función del producto en cuestión.</p><br>
            <h3>Titular del Derecho:</h3>
            <p>El autor de un modelo o diseño industrial, y sus sucesores legítimos, tienen sobre él un derecho de propiedad y el derecho exclusivo de explotarlo, transferirlo y registrarlo, por el tiempo y bajo las condiciones establecidas por este decreto.</p><br>
            <h3>Tiempo de Protección:</h3>
            <p>Los Modelos/Diseños Industriales tienen una vigencia de cinco años a partir de la fecha del depósito y podrá ser prolongada por dos períodos consecutivos de la misma duración. En total son 15 años de protección.</p><br>
            <h3>Ejemplos:</h3>
            <p>Bicicleta con estilo futurista para Mazda por Rafael Crespo.</p><br>
          </v-list-item-content>
        </v-list-item>
        <br><br><br>
        <center>
          <img style="width: 95%;" src="https://www.criptonoticias.com/wp-content/uploads/2021/03/token-NFT-copyright-derechos-autor.jpg"><br><br><br>
        </center>
        <v-list-item seven-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <a href="https://www.argentina.gob.ar/justicia/derechodeautor"> https://www.argentina.gob.ar/justicia/derechodeautor</a><br>
            <a href="https://es.wikipedia.org/wiki/Derecho_de_autor"> https://es.wikipedia.org/wiki/Derecho_de_autor</a><br>
            <a href="https://www.argentina.gob.ar/justicia/derechofacil/leysimple/propiedad-intelectual#:~:text=La%20ley%20de%20propiedad%20intelectual,%2C%20literarias%2C%20art%C3%ADsticas%20o%20did%C3%A1cticas."> https://www.argentina.gob.ar/justicia/derechofacil/leysimple/propiedad-intelectual</a><br>
            <a href="https://vinculacion.conicet.gov.ar/que-es-una-patente-de-invencion/#:~:text=Una%20Patente%20de%20Invenci%C3%B3n%20es,directamente%20por%20medio%20del%20procedimiento"> https://vinculacion.conicet.gov.ar/que-es-una-patente-de-invencion/</a><br>
            <a href="https://trademark.marcaria.com/hc/es/articles/211141086--Cu%C3%A1l-es-la-diferencia-entre-marca-patente-y-derechos-de-autor-copyright-"> https://trademark.marcaria.com/hc/es/articles/211141086--Cu%C3%A1l-es-la-diferencia-entre-marca-patente-y-derechos-de-autor</a><br>
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


