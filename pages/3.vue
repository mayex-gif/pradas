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
            <h1 class="text-center">BIENES</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué son los Bienes?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>El término Bienes es el plural de la palabra bien; se refieren a cualquier cosa, tangible o intangible, que sea útil para el hombre y le satisfaga, directa o indirectamente, algún deseo o necesidad individual o colectiva, o que contribuya al bienestar de los individuos.
            <br><br>Los Bienes son objetos útiles o provechosos que le generan un cierto valor o utilidad a quien los usa o posee. En sentido económico, los bienes son producidos para ser intercambiados; de esta manera, un bien es una mercancía.
            <br><br>Los Bienes pueden ser materiales o inmateriales y pueden ser demandados por personas físicas o jurídicas. El término deriva del latín bene, que significa «bien».
            <br><br>Para que un bien sea considerado económico, debe requerir cierta demanda por un determinado mercado, ser escaso y limitado y además tener un valor de intercambio.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content two-line>
            <h3>¿Cómo se clasifican los Bienes?:</h3>
            <v-divider class="mb-1"></v-divider>
            <p><br>Existen diferentes tipos de bienes, entre ellos:</p>
            <p class="ma-4"><strong> Bienes Inmuebles:</strong> aquellos que no pueden moverse del sitio en donde están o en donde fueron construidos. Esto comprende edificios, casas, oficinas, tierras y otros.</p>
            <p class="ma-4"><strong> Bienes Muebles:</strong> aquellos que pueden ser trasladados de un sitio a otro, algunos de manera más fácil o económica. Esto comprende computadoras, televisores, autos, etc.</p>
            <p class="ma-4"><strong> Bienes de Consumo:</strong> aquellos destinados a un consumidor final. Este tipo de bien no tiene el objetivo de ser utilizado en un proceso productivo para elaborar otros bienes, sino que será utilizado por el consumidor. Por ejemplo, zapatos o autos.</p>
            <p class="ma-4"><strong> Bienes Intermedios:</strong> aquellos que se fabrican para ser utilizados como materia prima en procesos productivos, para obtener otros bienes que también pueden ser intermedios o finales. Por ejemplo, una tela, la cual es fabricada para elaborar ropa.</p>
            <p class="ma-4"><strong> Bienes de Capital:</strong> aquellos que también se emplean para producir, aunque a diferencia de los bienes intermedios, los bienes de capital comprenden maquinarias, herramientas y otros que son útiles para el proceso de elaboración del producto. Además, suelen tener un impacto importante en la eficiencia con la que se realiza el proceso.</p>
            <p class="ma-4"><strong> Bienes Públicos:</strong> aquellos que no tienen propiedad o cuya propiedad pertenece al Estado, por ejemplo, un parque en la vía pública.</p>
            <p class="ma-4"><strong> Bienes Privados:</strong> aquellos que cuentan con un título de propiedad o pertenecen a solo una persona, por ejemplo, una casa.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Ejemplos:</h3>
            <v-divider class="mb-1"></v-divider>
            <ul>
              <li><strong>Bienes Muebles:</strong>   Sillas, muebles, escritorios.</li><br>
              <li><strong>Bienes Inmuebles:</strong>   Departamentos, oficinas y casas.</li><br>
              <li><strong>Bienes de Consumo:</strong>   Libros, revistas, diarios.</li><br>
              <li><strong>Bienes Intermedios:</strong>   Una plancha de madera es un bien intermedio que se emplea para producir una mesa (bien final).</li><br>
              <li><strong>Bienes de Capital:</strong>   Joyas y bienes preciosos.</li><br>
              <li><strong>Bienes Públicos:</strong>    Son la defensa, la seguridad, la justicia, un medioambiente limpio, servicio de relaciones exteriores, entre otros.</li><br>
              <li><strong>Bienes Privados:</strong>   Una casa, un automóvil.</li><br>
            </ul> 
          </v-list-item-content>
        </v-list-item>
        <v-list-item style="aling-items: center; item-aling: center;" class="pb-15" four-line>
          <v-card class="mx-auto pa-5">
            <img src="https://conceptodefinicion.de/wp-content/uploads/2015/03/bienes.jpg">
            <p><strong>Bienes</strong> Muebles, Inmuebles, de Consumo, Intermedios, de Capital, Públicos, Privados</p>
            <v-divider></v-divider> 
          </v-card>
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


