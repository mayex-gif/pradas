<template>
<div>
  <v-app>
    <h2 class="text-center" style="letter-spacing:20px ;font-size:40px  ;padding-top:18%; padding-bottom:1%; ">MARCO JURÍDICO</h2>
    <h3 class="text-center" style="letter-spacing:5px ;font-size:20px; padding-bottom: 1%;" >ACTIVIDADES INDUSTRIALES</h3>
    <v-divider class="mx-16"></v-divider>
    <v-divider class="mx-16"></v-divider>
    <p class="text-center mt-2" style="padding-top:1% ;letter-spacing:5px ;padding-bottom:22% ;">Instituto Superior Manuel de Falla - Técnico en Programación</p>
    <v-col style="padding-bottom:15%;">
      <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
        <v-card :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }" class="mx-auto mt-3" max-width="100%" tile>
          <v-list-item one-line>
            <v-list-item-content>
              <h3>¿Qué es el Marco Jurídico o Marco Legal?</h3>
              <v-divider class="mb-1"></v-divider>
              <p>El Marco Jurídico es el conjunto de leyes, reglas, legislaciones y cualquier otro instrumento con rango y de carácter legal, que son utilizados de forma secuencial y coherente, los cuales una vez aplicados permiten sustentar todas las actuaciones y actividades en materia legal. Los instrumentos de aspecto legal que son considerados en el marco jurídico están estructurados en diferentes categorías o rangos, estos instrumentos, son de forma general:</p>
              <ul><br>
                <li>Los reglamentos y las leyes: en esta categorización de instrumentos se incluyen la constitución de cada país, los códigos aplicables, y las diferentes leyes.</li><br>
                <li>Las Resoluciones y los decretos: en esta categoría se incluyen las diferentes resoluciones y decretos que son promulgados y que tienen vigencia en cada uno de los países.</li><br>
                <li>Las Proidencias de Iipo Administrativas: las cuales son emanadas de los diferentes órganos o entes con rango y autorización para desarrollar y promulgar es este tipo de instrumentos.</li><br>
                <li>Normas de uso generales: en esta categoría se incluyen las diferentes normativas que se derivan de las diferentes leyes o de las providencias de tipo administrativas.</li><br>
                <li>Instrumentos de tipo internacional: esta categoría está representada por los diferentes acuerdos o leyes que se rigen entre diversos países, para un mejor entendimiento y manejo de aspectos relacionados en materia legal.</li><br>
              </ul>  
              <p>Es de esta forma, que en el marco jurídico se evidencia la existencia de una amplia y diversa gama de leyes e instrumentos aplicados en materia legislativa, en donde dicho ámbito o alcance sirve de uso y aplicación para las diferentes gestiones y regimiento en materia legal, tanto para el gobierno como para los ciudadanos que hacen vida en un determinado país donde se contemplen y apliquen dichas regulaciones. 
              <br><br>Estos instrumentos pueden ser de tipo nacional pero también de tipo internacional, que son aquellos que se establecen entre los diferentes países para regular y unificar la materia legal y que permite el conocimiento de regulaciones entre ambas entidades, por ejemplo las leyes internacionales marítimas, son conocidas y aplicadas a nivel internacional y su contenido incluyendo las regulaciones, alcance y sanciones, son conocidos por todos los entes involucrados, sus términos y disposiciones son usados y aplicados por cada uno de ellos de forma similar.</p>
            </v-list-item-content>
          </v-list-item>
          <v-list-item enlace-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <br>
            <a href="https://www.enfoque-estrategico.com/8-que-es-el-marco-juridico">https://www.enfoque-estrategico.com/8-que-es-el-marco-juridico</a><br>
            <a href="https://www.aceproject.org/ace-es/topics/lf/onePage">https://www.aceproject.org/ace-es/topics/lf/onePage</a>
          </v-list-item-content>
        </v-list-item>
          <v-list-item two-line>
            <v-list-item-content>
              <h3 class="text-center">¿DESEA SEGUIR APRENDIENDO? ELIJA UN TEMA</h3>
              <v-divider class="mb-1"></v-divider>
            </v-list-item-content>
          </v-list-item>
          <div style="padding-left: 16%; padding-right: 16%;">
            <div class="d-flex justify-space-between pa-5">
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/1" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  LEYES
                </v-btn>
              </v-hover>
              <spacer></spacer>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/2" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  DERECHOS Y NORMAS
                </v-btn>
              </v-hover>
            </div>
            <div class="d-flex justify-space-between pa-5">
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary"  style="width: 45%;" to="/3" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  BIENES
                </v-btn>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/4" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  DERECHOS DE AUTOR
                </v-btn>
              </v-hover>
            </div>
            <div class="d-flex justify-space-between pa-5">
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/5" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  DELITOS INFORMATICOS
                </v-btn>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/6" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  CONTRATO DE SOFTWARE
                </v-btn>
              </v-hover>
            </div>
            <div class="d-flex justify-space-between pa-5 pb-10">
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/7" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  SUJETO DEL DERECHO
                </v-btn>
              </v-hover>
              <v-hover v-slot="{ hover }" open-delay="50" close-delay="50">
                <v-btn color="primary" style="width: 45%;" to="/8" :elevation="hover ? 15 : 10" :class="{ 'on-hover':hover }">
                  ETICA Y DEONTOLOGIA PROFESIONAL
                </v-btn>
              </v-hover>
            </div>
          </div>
        </v-card>
      </v-hover>
    </v-col>
  </v-app>
</div>
</template>
