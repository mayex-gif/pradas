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
            <h1 class="text-center">DELITOS INFORMATICOS</h1>
          </v-list-item-content>
        </v-list-item>
        <v-list-item two-line>
          <v-list-item-content>
            <h3>¿Que es un delito informático?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Un delito informático es todo delito llevado a cabo mediante equipos informáticos o a través de Internet.
            Los delitos informáticos son actividades ilícitas o antijurídicas que:
            Se cometen mediante el uso de entornos digitales, redes, blockchain, computadoras, sistemas informáticos u otros dispositivos de las nuevas tecnologías de información y comunicación (la informática es el medio o instrumento para realizar un hecho antijurídico).
            Tienen por objeto causar daños, provocar pérdidas o impedir el uso de sistemas informáticos (delitos informáticos).</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item three-line>
          <v-list-item-content>
            <h3>¿A que se llama Delincuencia informática y Abuso Informático?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>Se le llama así al conjunto de comportamientos dignos de reproche penal que tienen por instrumento o por objeto a los sistemas o elementos de técnica informática, o que están en relación significativa con ésta, pudiendo presentar múltiples formas de lesión de variados bienes jurídicos.</p>
          </v-list-item-content>
        </v-list-item>
        <v-list-item four-line>
          <v-list-item-content>
            <h3>¿Qué es la seguridad informática?</h3>
            <v-divider class="mb-1"></v-divider>
            <p>La seguridad informática es el conjunto de técnicas y métodos que se utilizan para proteger tanto la información como los equipos informáticos en donde esta se encuentra almacenada ya sean estos individuales o conectados a una red frente a posibles ataques accidentales o intencionados.</p>
            <br><br><br>
            <p><strong>Se clasifican en:</strong></p>
            <p class="ma-4"><strong> SEGURIDAD FÍSICA:</strong> Es aquella que tiene relación con la protección del computador mismo, vela por que las personas que lo manipulan tengan la autorización para ello, proporciona todas las indicaciones técnicas para evitar cualquier tipo de daños físicos a los equipos informáticos.</p>
            <p class="ma-4"><strong> SEGURIDAD DE DATOS:</strong> Es la que señala los procedimientos necesarios para evitar el acceso no autorizado, permite controlar el acceso remoto de la información, en suma, protege la integridad de los sistemas de datos.</p>
            <p class="ma-4"><strong> BACK UP Y RECUPERACIÓN DE DATOS:</strong> Proporciona los parámetros básicos para la utilización de sistemas de recuperación de datos y Backup de los sistemas informáticos. Permite recuperar la información necesaria en caso de que ésta sufra daños o se pierda.</p>
            <p class="ma-4"><strong> DISPONIBILIDAD DE LOS RECURSOS:</strong> Este cuarto componente procura que los recursos y los datos almacenados en el sistema puedan ser rápidamente accesibles para la persona o personas que lo requieren. Permite evaluar constantemente los puntos críticos del sistema para así poderlos corregir de manera inmediata.</p>
            <p class="ma-4"><strong> LA POLÍTICA DE SEGURIDAD:</strong> Conjunto de normas y criterios básicos que determinan lo relativo al uso de los recursos de una organización cualquiera.</p>
            <p class="ma-4"><strong> ANÁLISIS FORENSE:</strong> El Análisis Forense surge como consecuencia de la necesidad de investigar los incidentes de Seguridad Informática que se producen en las entidades. Persigue la identificación del autor y del motivo del ataque. Igualmente, trata de hallar la manera de evitar ataques similares en el futuro y obtener pruebas periciales.</p>
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


