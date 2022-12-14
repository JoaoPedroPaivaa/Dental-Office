<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="Header.jpg" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="black--text text--darken-4 top">Bem vindos</h5>
          <h1 class="black--text">Clínica Odontologica</h1>
          <p class="grey--text">
            são três palavras-chaves que fazem toda a diferença na hora de montar um negócio próprio.<br/> Empreender é o principal fator que impulsiona o desenvolvimento econômico e social de um país. <br/> E por isso, quando o empreendedor se agarra a oportunidades e busca os recursos necessários <br/> aliados às três palavras-chaves, consegue transformar ideias em um negócio bom e lucrativo.
            <br />
            Dr. Joao Pedro Paiva!
          </p>
          <v-btn tile color="#000" dark> sobre nos </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    ></v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Implante Dental</h3>
                  <p class="grey--text ml-3 mt-6">
                    O implante constitui-se basicamente <br/> na introdução cirúrgica <br/> de um parafuso de <br/> titânio no osso alveolar<br/> (maxila ou mandíbula).
                  </p>
                  <v-btn color="" dark text>
                    Saiba mais
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark
                    ></v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Dentística</h3>
                  <p class="grey--text ml-3 mt-6">
                    A dentística, ou odontologia estética, <br/>é a especialidade odontológica<br/> que objetiva oferecer ao paciente uma <br/>perfeita saúde <br/>oral e a promoção de um sorriso harmonioso
                  </p>
                  <v-btn color="" dark text>
                    Saiba mais
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    ></v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Ortodontia</h3>
                  <p class="grey--text ml-3 mt-6">
                    O implante constitui-se basicamente <br/> na introdução cirúrgica <br/> de um parafuso de <br/> titânio no osso alveolar<br/> (maxila ou mandíbula).
                  </p>
                  <v-btn color="" dark text>
                    Saiba mais
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="white--text text--darken-4 mt-4 number">12</h1>
                  <h3 class="white--text mt-4">Anos de Experiencia</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="white--text text--darken-4">60+</h1>
                        <p class="grey--text">Clientes</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="white--text text--darken-4">1222+</h1>
                        <p class="grey--text">Clientes atendidos por mês</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="white--text text--darken-4">08</h1>
                        <p class="grey--text">Especialidades</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="white--text text--darken-4">10</h1>
                        <p class="grey--text">Profissionais qualificados</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="white--text">Especialidades</h4>
          <p class="black--text">Temos a melhor equipe de Profissionais para te atender</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="black" dark> Ver todos </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="3.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="black" dark text class="ml-n4"> Ortodontia </v-btn
          ><br />

          <v-btn color="#000" dark text class="ml-n4">
            Saiba mais
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="black" dark text class="ml-n4"> Importancia da visita ao Dentista </v-btn><br />

          <v-btn color="#000" dark text class="ml-n4">
            Saiba mais
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="6.png" contain max-height="80%"></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="5.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> OdontoPediatria </v-btn
          ><br />

          <v-btn color="#fff" dark text class="ml-n4">
            Saiba mais
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Cirurgia Ortognatica </v-btn><br />
          <v-btn color="#fff" dark text class="ml-n4">
            Saiba mais
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    Nossa clínica espera<br />você para uma avaliação
                  </h1>
                  <p class="grey--text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Eius nesciunt ducimus natus <br />
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#263" dark class="mt-16">
                    Contato
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Inicio</v-btn>
              <v-btn text>Especialidades</v-btn>
              <v-btn text>Sobre</v-btn>
              <v-btn text> contato</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #302e2e;
}
.bgColor2 {
  background-color: #302e2e;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>