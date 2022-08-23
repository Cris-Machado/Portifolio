<template>
  <v-card-text class="py-0">
      <v-timeline
        align-top
        dense
      >
      <v-timeline-item
          color="#FFDB58"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>Performa_IT, jun de 2021 - momento</strong>
              <div class="text-caption">
                Desenvolvedor Full-Stack Pleno
              </div>
            </v-col>
            <v-col>
              <div class="text-caption">
                <li>Desenvolvimento de soluções do zero para diversos clientes, com maior foco em Back-End aplicando princípios fortes do CleanCode/S.O.L.I.D.</li>
                <li>Competências: Simple Access Object Protocol · Application Progra · Domain-Driven Design (DDD) · Test Driven Development · Skrum · Clean Code</li>

              </div>
              </v-col>
          </v-row>
        </v-timeline-item>
         <v-timeline-item
          color="red"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>Edenred Brasil, mar de 2021 - jun de 2021</strong>
              <div class="text-caption">
                Desenvolvedor Backend .Net Pleno
              </div>
            </v-col>
            <v-col>
              <div class="text-caption">
                <li>*Desenvolvimento de aplicações de automação para sustentação e implantação para rotina de manipulação de cartões e pagamentos</li>
                <li>Front-end: MVC, Angular | Back-End: .Net Core 5(DDD)/SQLServer</li>

              </div>
              </v-col>
          </v-row>
        </v-timeline-item>
        <v-timeline-item
          color="#df8028"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>Solistica, set de 2020 - mar de 2021</strong>
              <div class="text-caption">
                Desenvolvedor Full-Stack Júnior
              </div>
            </v-col>
            <v-col>
              <div class="text-caption">
                <li>Analise e desenvolvimento de Aplicações para Logística Web</li>
                <li>Front-end: MVC/JQuery/Bootstrap | Back-end: .Net Core(DDD)/SQLServer</li>

              </div>
              </v-col>
          </v-row>
        </v-timeline-item>
        <v-timeline-item
          color="#daa520"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>Goldsoft  Informatica, mai de 2019 - set de 2020</strong>
              <div class="text-caption">
                Desenvolvedor Full-Stack Júnior
              </div>
            </v-col>
            <v-col>
              <strong>Experiencias:</strong>
              <li>Desenvolvimento de sistemas (Delphi 2010, 2007/Oracle) e .NET Framework</li>
              <li>Desenvolvimento de Aplicações para COMEX com Front-end: VueJS | Back-end: .Net Core (Padrão DDD) / SQLServer</li>
            </v-col>
          </v-row>
        </v-timeline-item>

        <v-timeline-item
          color="teal lighten-3"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>Bitbyte Informatica, nov de 2018 - mai de 2019</strong>
              <div class="text-caption">
                Desenvolvedor Android Trainee 
              </div>
            </v-col>
            <v-col>
              <strong>Experiencias:</strong>
              <li>Tinha como função desenvolver automações mobile para varejo como cardápios eletrônicos, auto-atendimento e lançamento de comandas!</li>
              <li>Front-end: Java/SQLite(Android Studio) | Back-end: Java/Firebird</li>
            </v-col>
          </v-row>
        </v-timeline-item>

        <v-timeline-item
          color="yellow"
          small
        >
          <v-row class="pt-1 experience">
            <v-col cols="7">
              <strong>GZ Sistemas, nov de 2017 - nov de 2018</strong>
              <div class="text-caption">
                Estágio 
              </div>
            </v-col>
            <v-col>
              <strong>Experiencias:</strong>
              <div class="text-caption">
                <li>A princípio fui contratado para agregar a equipe de suporte ao cliente prestando ajudas técnicas no dia-a-dias, porém ao passar cerca de 2 meses houve uma seleção de um novo desenvolvedor e tive a honra de ser selecionado</li>
                <li>Desenvolvimento de novas rotinas e JAVA, construção de relatórios com iReport faziam parte da minha rotina assim como prestar rápidos ajustes a pedido da equipe de análise.</li>
              </div>
            </v-col>
          </v-row>
        </v-timeline-item>
      </v-timeline>
    </v-card-text>
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
  font-size: 100%;
  margin-left: 10%;
  margin-right: 10%;
}
</style>
