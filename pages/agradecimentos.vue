<template>
 <v-container
    class="fill-height"
    fluid
  >
    <v-fade-transition mode="out-in">
      <v-row >
        <v-col cols="6" >
          <v-card >
            <v-img 
              :src="require('./images/tali.jpeg')"
            ></v-img>
            <v-card-title >
              <div class="text-h6">Talita Miguel Machado</div>
              <li class="experience">A mulher mais inteligente e forte que já conheci, desde o inicio acreditou em mim e me manteve encorajado a evoluir e enfrentar meus medos.</li>
            </v-card-title>
          </v-card>
        </v-col>

        <v-col cols="6" >
          <v-card>
            <v-img class="colunas"
              :src="require('./images/ruan.jpg')"
            ></v-img>
            <v-card-title>
             <div class="text-h6">Ruan da Silva Pereira</div>
              <li class="experience">Um excelente profissional que apelidei de "Mestre", me passou a paixão de trabalhar com organização e eficiência!</li>
            
            </v-card-title>
          </v-card>
        </v-col>

        <v-col cols="6" >
          <v-card>
            <v-img class="colunas"
              :src="require('./images/jefferson.jpg')"
            ></v-img>
            <v-card-title>
             <div class="text-h6">Jefferson Islan Silva</div>
              <li class="experience">Meu tio por parte materna, me apresentou ao mundo de técnologia e o quão longe o conhecimento pode te levar!</li>
            
            </v-card-title>
          </v-card>
        </v-col>

         <v-col cols="6" >
          <v-card>
            <v-img class="colunas"
              :src="require('./images/fred.jpg')"
            ></v-img>
            <v-card-title>
             <div class="text-h6">Frederico Piamonteze Junior</div>
              <li class="experience">Grande admiração pela pessoa e respeito por este profissional, e também pela grande carga de conhecimento lessionada nos anos em que tive o prazer de ser seu aluno.</li>
            
            </v-card-title>
          </v-card>
        </v-col>
      </v-row>
    </v-fade-transition>
  </v-container>
</template>
<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      idade: ((new Date().getFullYear()) - 2001),
    }
  },
}
</script>
<style scoped>
 .experience{
  font-size: 70%;
  margin-left: 10%;
  margin-right: 10%;
  font-style: normal;
  font-weight: 300;
  }
</style>
