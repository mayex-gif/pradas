<template>
  <v-app dark>
    <v-navigation-drawer v-model="drawer" :mini-variant="miniVariant" clipped fixed app>
      <v-list>
        <v-list-item v-for="(item, i) in menu" :key="i" :to="item.to" router exact>
          <v-list-item-action>
            <v-icon :color="item.color">{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <div class="d-flex">
      <v-hover v-slot="{ hover }" open-delay="15" close-delay="15">
        <v-app-bar :elevation="hover ? 20 : 5" :class="{ 'on-hover':hover }" clipped-left tile fixed app>
          <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
          <v-toolbar-title v-text="title" />
          <v-switch v-model="$vuetify.theme.dark"/>
        </v-app-bar>
      </v-hover>
    </div>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer padless>
      <v-text class="flex text-center">
        &copy; {{ new Date().getFullYear() }} — <strong>Alcalde - Rodríguez - Viero</strong> — Vuetify
      </v-text>
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
      menu: [
        {
          icon: 'mdi-bank',
          color: '',
          title: 'Marco Jurídico',
          to: '/marcojuridico'
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
          title: 'Derechos',
          to: '/2'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Alejo',
          to: '/3'
        },
                {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Naza',
          to: '/4'
        },
                {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Petito',
          to: '/5'
        },
        {
          icon: 'mdi-book-open-page-variant-outline',
          color: 'light-blue',
          title: 'Luisito',
          to: '/6'
        }

      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'MARCO JURÍDICO'
    }
  }
}
</script>
