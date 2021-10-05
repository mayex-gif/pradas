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
          <div class="text-center">
            <v-menu transition="fade-transition">
              <template v-slot:activator="{ on, attrs }">
                <v-btn v-bind="attrs" v-on="on">
                  <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                  <path fill="currentColor" d="M12,15.5A3.5,3.5 0 0,1 8.5,12A3.5,3.5 0 0,1 12,8.5A3.5,3.5 0 0,1 15.5,12A3.5,3.5 0 0,1 12,15.5M19.43,12.97C19.47,12.65 19.5,12.33 19.5,12C19.5,11.67 19.47,11.34 19.43,11L21.54,9.37C21.73,9.22 21.78,8.95 21.66,8.73L19.66,5.27C19.54,5.05 19.27,4.96 19.05,5.05L16.56,6.05C16.04,5.66 15.5,5.32 14.87,5.07L14.5,2.42C14.46,2.18 14.25,2 14,2H10C9.75,2 9.54,2.18 9.5,2.42L9.13,5.07C8.5,5.32 7.96,5.66 7.44,6.05L4.95,5.05C4.73,4.96 4.46,5.05 4.34,5.27L2.34,8.73C2.21,8.95 2.27,9.22 2.46,9.37L4.57,11C4.53,11.34 4.5,11.67 4.5,12C4.5,12.33 4.53,12.65 4.57,12.97L2.46,14.63C2.27,14.78 2.21,15.05 2.34,15.27L4.34,18.73C4.46,18.95 4.73,19.03 4.95,18.95L7.44,17.94C7.96,18.34 8.5,18.68 9.13,18.93L9.5,21.58C9.54,21.82 9.75,22 10,22H14C14.25,22 14.46,21.82 14.5,21.58L14.87,18.93C15.5,18.67 16.04,18.34 16.56,17.94L19.05,18.95C19.27,19.03 19.54,18.95 19.66,18.73L21.66,15.27C21.78,15.05 21.73,14.78 21.54,14.63L19.43,12.97Z" /></svg>
                </v-btn>
              </template>
              <v-list>
                <v-list-item v-for="(item, i) in theme" :key="i" :to="item.to" router exact>
                  <v-list-item-action>
                    <v-icon :icon="item.icon">{{ item.icon }}</v-icon>
                  </v-list-item-action>
                  <v-switch v-model="$vuetify.theme.dark" v-label="mdi-theme-light-dark"/>
                </v-list-item>
              </v-list>
            </v-menu>
          </div>
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
        }

      ],
      theme: [
        {
          icon: 'mdi-theme-light-dark',
        },
      ],

      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'MARCO JURÍDICO'
    }
  }
}
</script>
