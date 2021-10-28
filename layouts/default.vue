<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" :mini-variant="miniVariant" clipped fixed app>
      <v-list-item-title class="text-h6 text-center my-3">
        Temas
      </v-list-item-title>
      <v-divider></v-divider>
      <v-list>
        <v-list-item v-for="(item, i) in menu" :key="i" :to="item.to" router exact>
          <v-list-item-action>
            <v-icon :color="item.color">{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
          <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
        <v-divider></v-divider>
      </v-list>
    </v-navigation-drawer>
    <v-navigation-drawer v-model="drawer2" right clipped fixed app>
      <v-list-item-title class="text-h6 text-center my-3">
        Ajustes
      </v-list-item-title>
      <v-divider></v-divider>
      <v-list class="flex">
        <v-list-item v-for="(item, i) in theme" :key="i">
          <v-list-item-icon>
            <v-icon class="mt-1">{{ item.icon }}</v-icon>
          </v-list-item-icon>
          <v-switch v-model="$vuetify.theme.dark" inset/>
        </v-list-item>
        <v-divider></v-divider>
      </v-list>
    </v-navigation-drawer>
    <div class="d-flex">
      <v-hover v-slot="{ hover }" open-delay="15" close-delay="15">
        <v-app-bar :elevation="hover ? 20 : 5" :class="{ 'on-hover':hover }" clipped-left clipped-right app>
          <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
          <v-toolbar-title v-text="title" />
          <v-spacer></v-spacer>
          <v-app-bar-nav-icon @click.stop="drawer2 = !drawer2"><v-icon>mdi-cog</v-icon></v-app-bar-nav-icon>
        </v-app-bar>
      </v-hover>
    </div>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer padless>
     <v-card flat tile class="pt-4 pb-1 light-blue lighten-1 white--text text-center" width="100%">
       <v-item v-for="(item,i) in icons" :key="i" class=" ma-auto mt-3 mb-1 light-blue " width="5%">
          <v-btn :to="item.to" class="mx-4 white--text" target="_blank" icon>
           <v-icon size="24px" >{{ item.icon }}</v-icon>
         </v-btn>
       </v-item>
       <v-card-text class="white--text pt-4">
           Página informática relacionada al marco jurídico de las actividades industriales - Técnico en Programación
        </v-card-text>
       <v-divider class="mt-4 mx-16 pb-1"></v-divider>
       <v-text class="flex text-center">
         &copy; {{ new Date().getFullYear() }} — <strong> Alcalde - Rodríguez - Viero </strong> — Vuetify
       </v-text>
      </v-card>
    </v-footer>
  </v-app>   
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      drawer2: false,
      menu: [
        {
          icon: 'mdi-bank',
          color: '',
          title: 'Marco Jurídico',
          to: '/'
        },
          {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Leyes',
          to: '/1'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Derechos y Normas',
          to: '/2'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Bienes',
          to: '/3'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Derechos de Autor',
          to: '/4'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Delitos Informaticos',
          to: '/5'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Contrato de Software',
          to: '/6'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Sujeto del Derecho',
          to: '/7'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Etica y Deontologia',
          to: '/8'
        }
      ],
      theme: [
        {
          icon: 'mdi-theme-light-dark',
        },
      ],
      icons: [
        {
          icon: 'mdi-school',
          to: 'https://institutomanueldefalla.edu.ar/',
        },
        {
          icon: 'mdi-github',
          to: 'https://github.com/mayex-gif/pradas',
        }
      ],

      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'MARCO JURÍDICO',
    }
  }
}
</script>
