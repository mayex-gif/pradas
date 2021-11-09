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
        <div align="center" style="aling-items: center; item-aling: center;" class="pb-15"><img src="https://i0.wp.com/biblioteca.todoelderecho.com/wp-content/uploads/2021/01/delitos-informaticos.jpg?fit=700%2C479&ssl=1">
        <p><strong>Hacker</strong> analizando informacion</p></div>
        <v-divider class="mb-1"></v-divider>
        <v-list-item five-line>
         <v-list-item-content>
            <h3>Ejemplos de Delitos Informaticos</h3>
             <ul>
              <li>
                <p class="ma-4"><strong>Estafa: </strong> Este tipo de delito se comete a través del robo de identidad. Los criminales utilizan técnicas como el spam, webs falsas o softwares ilegales para engañar a las víctimas y robarles las contraseñas o claves personales. De esta manera, acceden a información confidencial. Un ejemplo de ello es el acceso a datos bancarios.</p>
              </li>
              <li>
                <p class="ma-4"><strong>Hackeo: </strong> Este delito se considera muy grave, ya que el hacker intenta obtener acceso a cuentas personales con la ayuda de un ordenador. Con ello consigue robar información confidencial y puede llegar afectar a los negocios de una empresa.</p>
              </li>
              <li>
                <p class="ma-4"><strong>Acoso: </strong> Mucha actividad en internet es anónima y uno de los delitos más comunes es el acoso, afectando sobre todo a los adolescentes. Por ejemplo, se recomienda que no acepten a personas desconocidas en sus redes sociales. Si el acoso se vuelve una amenaza, se pueden tomar acciones legales.</p>
              </li>
              <li>
                <p class="ma-4"><strong>Suplantacion de Identidad: </strong> Relacionado con lo anterior, la suplantación de identidad sucede cuando la estafa tiene éxito y el criminal obtiene acceso a la información personal. Una vez obtenida, el criminal puede realizar compras, llegando a arruinar a la víctima, o hacerse pasar por la persona a quien ha robado los datos.</p>
              </li>
              <li>
                <p class="ma-4"><strong>Extorsion :</strong> Este delito sucede cuando alguien utiliza internet para extorsionar dinero a una persona o empresa. La extorsión se comete de distintas formas. Por ejemplo, el criminal puede tener acceso a información personal y amenazar con exponerla a menos que pague cierta cantidad de dinero a cambio. Los delincuentes también pueden llevar a cabo algún tipo de ataque cibernético para luego exigir un pago para detenerlo. Por este motivo, es muy importante tener un antivirus y proteger las cuentas bancarias y personales con contraseñas de alta dificultad.</p>
              </li>
            </ul>
            </v-list-item-content>
            </v-list-item>
          <v-list-item last-line>
          <v-list-item-content>
            <h3>Enlaces Externos</h3>
            <v-divider class="mb-1"></v-divider>
            <br>
            <a href="https://es.wikipedia.org/wiki/Delito_inform%C3%A1tico">https://es.wikipedia.org/wiki/Delito_inform%C3%A1tico</a><br>
            <a href="https://escuelacienciasjuridicas.com/delitos-informaticos-mas-comunes/">https://escuelacienciasjuridicas.com/delitos-informaticos-mas-comunes/</a>
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


