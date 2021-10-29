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
            <h1 class="text-center">CONTRATO DE SOFTWARE</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué es un Contrato de Software?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>La generalización del uso de la programación informática, así como un escenario tecnológico en constante evolución, ha supuesto el surgimiento de una serie de figuras contractuales que no tienen prácticamente en común más que la singular naturaleza del objeto sobre el que orbitan.<br><br>
              De esta forma, la expresión “contrato de software informático” suele hacer referencia a todo contrato de software que tiene por objeto la venta, arrendamiento y/o prestación de servicios relativos a un sistema informático o a un elemento integrado o susceptible de estar incorporado en dicho sistema.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Ejemplos de Contratos de Software</h3>
            <v-divider class="mb-1"></v-divider>
            <ul>
              <br>
              <li>Contrato de licencia de software.</li><br>
              <li>Contrato de compraventa de licencia de software.</li><br>
              <li>Contrato de desarrollo.</li><br>
              <li>Contrato de soporte y contrato del software de mantenimiento.</li><br>
              <li>Contrato de prestación de servicios informáticos.</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
                <v-list-item four-line>
          <v-list-item-content>
            <h3>Partes del Contrato</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Deben constar los datos personales de las empresas o personas que celebran el contrato.<br><br>Es muy importante señalar que las partes hacen referencia a las empresas o profesionales que licencian el software y, por tanto, en el caso que una de las partes sea una empresa (sociedad mercantil) será necesario que la persona que firme el contrato en nombre de dicha empresa acredite que legalmente representa a la empresa y que tiene poderes suficientes para firmar el contrato.<br><br>En el contrato de Licencia de software el Licenciatario puede ser una empresa o también una persona física, mientras que en el Contrato de Distribución de Software, casi siempre es una empresa.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item five-line>
          <v-list-item-content>
            <h3>Objeto del Contrato</h3>
            <v-divider class="mb-1"></v-divider>
            <ul>
              <br>
              <li>El objeto del Contrato de Licencia es la autorización por parte del titular de los derechos de explotación (Licenciatario) a un Licenciante o cliente, a utilizar un determinado software en los términos establecidos en la licencia de uso.</li><br>
              <li>En el caso del Contrato de Distribución es la cesión de uso de esos derechos para que a vez el Distribuidor los ceda a los usuarios finales (Licenciatarios) en un territorio determinado.</li><br>
              <li>Desde el punto de vista del cliente o Licenciatario es interesante incluir en un anexo la descripción del producto, así como los manuales o las instrucciones y requerimientos del software.</li>
              <br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <v-list-item six-line>
          <v-list-item-content>
            <h3>Duracion</h3>
            <v-divider class="mb-1"></v-divider>
            <p>
              <br>Respecto a la duración del contrato, podrá incluirse una cláusula siempre que interese a las Partes por la naturaleza del software.
              <br><br>Según el tipo de software, puede no tener sentido establecer un periodo de tiempo ya que la evolución de los programas informáticos es muy rápida y en pocos años ya quedan obsoletos o salen nuevas versiones. No obstante, si la intención de las partes es establecer una determinada duración, debería tenerse en cuenta la posibilidad de establecer prórrogas.
              <br><br>En caso de establecerse una duración, normalmente es de 5 años, tanto en los contratos de Licencia como en los de Distribución.
            </p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item seven-line>
          <v-list-item-content>
            <h3>Enlaces externos</h3>
            <v-divider class="mb-1"></v-divider>
            <a href="https://evergreencompliance.com/contrato-de-software/"> https://evergreencompliance.com/contrato-de-software/ </a>
            <a href="https://www.globalnegotiator.com/blog/contrato-de-software-definicion-modelos/"> https://www.globalnegotiator.com/blog/contrato-de-software-definicion-modelos/ </a>
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


