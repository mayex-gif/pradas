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
              <h1>HARDWARE</h1>
            </div>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Qué es el Hardware?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Hardware es la parte física de un ordenador o sistema informático. Está formado por los componentes eléctricos, electrónicos, electromecánicos y mecánicos, tales como circuitos de cables y luz, placas, memorias, discos duros, dispositivos periféricos y cualquier otro material en estado físico que sea necesario para hacer que el equipo funcione.</p><br><br>
            <p>El término hardware viene del inglés, significa partes duras y su uso se ha adoptado en el idioma español sin traducción, siendo utilizado para para aludir a los componentes de carácter material que conforman un equipo de computación.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>Tipos de hardware según su función</h3>
            <v-divider class="mb-1"></v-divider>
            <ul><br>
            <li><strong>Hardware interno: </strong> Se trata de todo aquel componente físico que pueda clasificarse como hardware y que forme parte directamente del dispositivo.</li><br>
            <li><strong>Hardware externo: </strong> En este caso, consiste en el conjunto de componentes físicos que de nuevo se pueden clasificar como hardware, pero esta vez no forman parte del dispositivo principal, sino que funcionan como elementos complementarios a este.</li><br>
            <li><strong>Hardware híbrido: </strong> Por último nos quedaría este tipo de hardware, el cual funciona como un elemento de hardware que bien puede formar parte de forma directa en el dispositivo o bien puede hacerlo de forma indirecta siendo un elemento independiente. </li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <h3>Tipos de hardware según su objetivo</h3>
            <v-divider class="mb-1"></v-divider>
            <ul><br>
            <li><strong>De procesamiento. </strong> Es el centro de la unidad física, más conocida como ‘CPU’.</li><br>
            <li><strong>De almacenamiento. </strong> Se trata de las unidades que se encargan de almacenar datos.</li><br>
            <li><strong>De entrada. </strong> Consistiría en periféricos cuyo único objetivo es enviar datos. </li><br>
            <li><strong>De salida. </strong> En este caso se trata de un periférico que recibe datos.</li><br>
            <li><strong>Periféricos de mixtos. </strong> Este tipo de periféricos posee la característica de enviar y recibir datos.</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <br><br>  
        <center>
        <img style="width: 30%" src="https://cdn.goconqr.com/uploads/media/image/11560140/desktop_2c7e2d88-eb52-4393-b65b-ea3eeeb2ef57.gif">
        </center>
        <br><br><br><br>
        <v-list-item-content>
            <div class="text-center">
              <h1>SOFTWARE</h1>
            </div>
        </v-list-item-content>
        <v-list-item>
        <v-list-item-content>
            <h3> ¿Qué es el Software?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Se conoce como software, logicial o soporte lógico al sistema formal de un sistema informático, que comprende el conjunto de los componentes lógicos necesarios que hacen posible la realización de tareas específicas, en contraposición a los componentes físicos que son llamados hardware. La interacción entre el software y el hardware hace operativo un ordenador (u otro dispositivo), es decir, el software envía instrucciones que el hardware ejecuta, haciendo posible su funcionamiento.<br><br>Los componentes lógicos incluyen, entre muchos otros, las aplicaciones informáticas, tales como el procesador de texto, que permite al usuario realizar todas las tareas concernientes a la edición de textos; el llamado software de sistema, tal como el sistema operativo, que básicamente permite al resto de los programas funcionar adecuadamente, facilitando también la interacción entre los componentes físicos y el resto de las aplicaciones, y proporcionando una interfaz con el usuario</p>
            <p><br>En palabras sencillas el software es lo que permite que el hardware funcione. Es decir, son las rutinas lógicas, digitales e intangibles (que no puedes tocar) de tu equipo informático o móvil.</p>
        </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>Tipos de Software</h3>
            <v-divider class="mb-1"></v-divider>
            <ul><br>
              <li><strong>Software de Sistema: </strong>es el que permite que nuestro hardware funcione de forma correcta.</li><br>
              <li><strong>Software de Aplicación o Utilidad: </strong>se trata de las aplicaciones, programas y herramientas que utilizamos activamente de acuerdo a nuestras necesidades.</li><br>
              <li><strong>Software de Programación: </strong>es seguramente el más importante de todos, pues sin él no se podrían haber creado los distintos tipos de software que mencionamos ante. Es una clase de software básica para la informática y el desarrollo de aplicaciones.</li><br>
              <li><strong>Software Malicioso: </strong>se trata de un tipo de software que en realidad no está en ninguna categoría anterior, sino que tiene su propia categoría de tipo de software pues no es software de sistema, ni de aplicacion y menos de programación. EJ:Malware,Virus,etc.</li><br>
            </ul>
          </v-list-item-content>
        </v-list-item>
        <br><br>
        <center>
        <img style="width: 60%" src="https://img.tecnomagazine.net/2018/10/tipos-de-software-segun-funciones.jpg">
        </center>
        <br><br><br>
        <v-list-item last-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <br>
            <a href="https://es.wikipedia.org/wiki/Hardware">https://es.wikipedia.org/wiki/Hardware</a><br>
            <a href="https://www.significados.com/hardware/">https://www.significados.com/hardware/</a><br>
            <a href="https://es.wikipedia.org/wiki/Software">https://es.wikipedia.org/wiki/Software</a><br>
            <a href="https://tecnomagazine.net/tipos-de-software/">https://tecnomagazine.net/tipos-de-software/</a>
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

