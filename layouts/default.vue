<template>
  <v-app dark>
    <v-navigation-drawer
      v-model="drawer"
      :mini-variant="miniVariant"
      clipped
      fixed
      app
    >
      <v-list>
        <v-list-item
          v-for="(item, i) in menu"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon :color="item.color">{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar
      clipped-left
      fixed
      app
    >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />

      <v-toolbar-title v-text="title" />
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{new Date().getFullYear()}}</span>

      <v-text>Alcalde - Rodríguez - Viero</v-text>

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
          color: 'black',
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
