<template>
  <v-app dark>
    
    </v-navigation-drawer>
    <v-app-bar
      fixed
      app
    >
    <p>
    <v-icon
                       slot="icon"
                       color="red"
                       size="26">
                        mdi-emoticon-excited-outline
                      </v-icon>
    Olá, eu sou Cris!</p>
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
     <a class="mr-3" href="https://www.linkedin.com/in/cristiano-henrique-machado-704957156/"><v-icon
                       slot="icon"
                       color="primary"
                       size="25">
                        mdi-linkedin
                      </v-icon>
                      </a>
                      <a class="mr-3" href="https://wa.me/11969100798"><v-icon
                       slot="icon"
                       color="blue"
                       size="25">
                        mdi-whatsapp
                      </v-icon></a>
                      <a class="mr-3" href="https://www.instagram.com/_crisdeveloper/"><v-icon
                       slot="icon"
                       color="purple"
                       size="25">
                        mdi-instagram
                      </v-icon></a>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      items: [
      ],
      miniVariant: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
