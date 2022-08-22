<template>
<div>
  <v-row  align="top">
    <v-col>
      <v-card
         elevation="14"
         outlined>
           <v-list-item three-line>
            <v-list-item-content>
               <div class="text-overline mb-4">
                  <v-banner
                    single-line>
                     <v-icon
                       slot="icon"
                       color="green"
                       size="36">
                        mdi-account
                      </v-icon>
                        Sobre mim!
                  </v-banner>
               </div>
            <v-list-item-title class="text-h5 mb-1">
          </v-list-item-title>
           <v-card-text class="text--primary">
              <p>- Meu nome é asdasdaCristiano, mais conhecido como "Cris"! apesar de ter origens mineira moro em Jundiai (São Paulo) desde sempre, aos meus 18 anos resolvi sair da casa dos meus pais para buscar além da idependencia a reponsabilidade de como sería estar a mercê dos próprios erros e acertos!</p>
              <p>- Sempre me fascinou soluções capazes de coisas complexas de forma autônoma. Mas confesso que quando tive o primeiro contato com uma linha de código fiquei um pouco assustado(2016), mas ao passar das aulas aquilo parecia se tornar cada vez mais fácil e hoje aos {{idade}} anos minha maior paixão é desenvolver boas soluções!</p>
            </v-card-text>
        </v-list-item-content>
      </v-list-item>
      </v-card-actions>
      </v-card>
    </v-col>
    <v-col>
      <v-card
         elevation="14"
         outlined>
           <v-list-item three-line>
        <v-list-item-content>
          <div class="text-overline mb-4">
                  <v-banner
                    single-line>
                     <v-icon
                       slot="icon"
                       color="primary"
                       size="36">
                        mdi-application-braces-outline
                      </v-icon>
                        Técnicamente falando!
                  </v-banner>
               </div>
        </v-list-item-content>
      </v-list-item>
      <v-card-text class="text--primary">
      <p><v-icon slot="icon" color="primary"
                       size="17">
                        mdi-desktop-classic
                      </v-icon><b> Back-End: </b> 5 anos de experiência arquitetando diversas Applications Programming Interfaces(API's) com .Net Core 3+/Framework, Domain-Driven Design, Entity-Framework, Code-First, Indicator of Compromise(IoC), Identity-Framework, Token-JWT, API-Rest, SOAP(Simple Object Access Protocol), Microserviços, JOBS (Hangfire), Lambda, Active Directory(AD), Unit-Of-Work, Unit-Test.</p>
                      <p><v-icon slot="icon" color="primary"
                       size="17">
                        mdi-language-javascript
                      </v-icon><b> Front-End: </b> HTML, Css, Vue-JS, Nuxt, Java-Script, Angular, Type-Script, One Page Applications, Components, Rest Requests, Axios, Storage Controlling, Jquery.</p>
                      <p><v-icon slot="icon" color="primary"
                       size="17">
                        mdi-database-search
                      </v-icon><b> Banco de dados: </b> SQLServer, MySQL, Oracle, MongoDB, Relacionamentos, Triggers, Procedures, Views</p>
                      <p><v-icon slot="icon" color="primary"
                       size="17">
                        mdi-book-open-page-variant
                      </v-icon><b> Metodologias Ageis: </b> Scrum & Kamban</p>
                      </v-card-text>
      </v-card-actions>
      </v-card>
    </v-col>
    <v-col>
      <v-card
         elevation="14"
         outlined>
           <v-list-item three-line>
        <v-list-item-content>
          <div class="text-overline mb-4">
                  <v-banner
                    single-line>
                     <v-icon
                       slot="icon"
                       color="primary"
                       size="36">
                        mdi-controller-classic
                      </v-icon>
                        Hobbies!
                  </v-banner>
               </div>
        </v-list-item-content>
      </v-list-item>
      <v-card-text class="text--primary">
      <p>Apesar de passar a maior parte do tempo livre durante a semana estudando ou fazendo testes laboratoriais, ler livros que estimulam a criatividade e jogar jogos com boas histórias constumam ser coisas que realmente gosto de fazer para relaxar! dentre diversos livros considero os da J.K Rowling os meus prediletos, mesmo tendo tendência a gostar muito de mitologias e suas curiosidades. Indico MITOLOGIA NÓRDICA - NAIL GAIMAN e é claro toda a série de livros sobre Harry Potter!</p>
                      </v-card-text>
      </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
  </div>
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
