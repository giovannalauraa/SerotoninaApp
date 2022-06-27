<template>
  <div class="container">
    <menuHamburguer> </menuHamburguer>
    <b-container>
      <img src="~/assets/ios.png" alt="ios icon" />
      <div class="texto-fundo">
        <h3 class="titulo">Conteúdos</h3>
        <img class="grupo-2" src="~/assets/grupo2.png" alt="grupo 2" />
        <img class="grupo-3" src="~/assets/grupo5.png" alt="grupo 5" />
      </div>

      <div class="layout-1">
        <img class="image" src="~/assets/img1.png" alt="Imagem um" />
        <p class="conteudo-4">2 meses atrás</p>
        <NuxtLink to="/1">
          <h4 class="titulo-1-conteudo">Prática do exercício físico</h4>
        </NuxtLink>

        <p class="conteudo-3">
          Dicas para quem quer melhorar a rotina de <br /><br />exercícios
          físicos durante as férias.
        </p>
        <NuxtLink to="/1"><b-button class="botao-saude">#Saúde</b-button> </NuxtLink>
        <img class="icon-2" src="~/assets/Icon.png" alt="Icon salvar" />
        <img
          class="icon-3"
          src="~/assets/likeecomp.png"
          alt="Icon compartilhar"
        />
      </div>

      <div class="layout-2">
        <img class="image-2" src="~/assets/img2.png" alt="Imagem dois" />
        <p class="conteudo-4">6 meses atrás</p>
        <h4 class="titulo-1-conteudo">Together</h4>

        <p class="conteudo-3">
          Veja métodos para melhorar sua eficiência<br /><br />no trabalho !
        </p>
      </div>

      <div class="caixa-baixo">
    <div class="footer">
      <img class="metas" src="~/assets/emoji_events.png" alt="trofeu" />

      <NuxtLink to="/tarefas-1"><img class="dns" src="~/assets/dns.png" alt="dns" /></NuxtLink>

      <NuxtLink to="/conteudos"><img class="conteudos" src="~/assets/search.png" alt="lupa" /></NuxtLink>
    </div>
   
    <div class="footer-2">
      <p class="texto-metas">Metas</p>
      <p class="texto-dns">Tarefas</p>
      <p class="texto-conteudos">Conteúdos</p>
    </div>
   </div>


    <!--  <div>
        <img class="ios-down" src="~/assets/iosDown.png" alt="Ios down" />
      </div> -->
      5
    </b-container>
  </div>
</template>

<script>
import menuHamburguer from '~/components/menuHamburguer.vue'

export default {
  components: { menuHamburguer },
  name: 'index-Tela',
}



</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@700&family=Darker+Grotesque&family=Inter:wght@300;400&family=Montserrat:wght@500&family=Poppins:wght@600&family=Roboto:ital,wght@0,500;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@700&family=Darker+Grotesque&family=Inter:wght@300;400&family=Montserrat:wght@500&family=Poppins:wght@600&family=Roboto:ital,wght@0,400;0,500;1,400&display=swap');

.container {
  position: relative;
  width: 382.54px;
  height: 812px;
  align-items: center;
  z-index: 1;
  background: #ede7fa;
}

.texto-fundo {
  position: absolute;
  width: 383px;
  height: 67px;
  left: 0px;
  top: 38px;

  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.texto-fundo-down {
  position: absolute;
  width: 383px;
  height: 67px;
  left: 0px;
  top: 720px;

  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.image {
  width: 321px;
  height: 144px;
  text-align: center;
}

.image-2 {
  width: 320px;
  height: 144px;
  text-align: center;
}

.titulo {
  position: absolute;
  width: 192px;
  height: 40px;
  left: 100px;
  top: 20px;

  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-size: 30px;
  line-height: 36px;
  color: #000000;
  text-align: center;
}

.layout-1 {
  width: 321px;
  height: 300px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;

  position: absolute;
  left: 8.89%;
  right: 7.2%;
  top: 20.81%;
  bottom: 41.13%;

  background: #c9bef4;
  border-radius: 12px;
}

.layout-2 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;

  position: absolute;
  left: 9.15%;
  right: 7.2%;
  top: 60.34%;
  bottom: 10.71%;

  background: #c9bef4;
  border-radius: 12px;
}

.grupo-2 {
  position: absolute;
  width: 285px;
  height: 34px;
  left: 34px;
  top: 80px;
}

.grupo-3 {
  position: absolute;
  width: 41px;
  height: 32px;
  left: 330px;
  top: 82px;
}

.conteudo-3 {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 10px;
  letter-spacing: 0.25px;
  color: rgba(28, 27, 31, 0.6);
}

.conteudo-4 {
  width: 289px;
  height: 8px;

  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-size: 11px;
  line-height: 16px;

  line-height: 16px;
  color: rgba(28, 27, 31, 0.6);

  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
}

.titulo-1-conteudo {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  color: #1c1b1f;
  flex: start;
  flex-direction: row;
}

.buscar {
  left: 28px;
  top: 123px;
}

.botao-saude {
  display: flex;
  flex-direction: row;
  /*padding: 10px;*/
  margin-left: 10px;
  width: 69px;
  height: 36px;

  color: #ffffff;
  background: #5946d2;
  border-radius: 20px;
  border-style: none;

  font-size: 13px;
  text-align: center;
  font-style: 'Inter', sans-serif;
}

.icon-2 {
  position: absolute;
  width: 27px;
  height: 27px;
  left: 180px;
  top: 250px;
}

.icon-3 {
  position: absolute;
  width: 88px;
  height: 40px;
  left: 214px;
  top: 243px;
}

.ios-down {
  position: absolute;
  width: 390px;
  height: 26px;
  left: calc(50% - 390px / 2 + 3.73px);
  bottom: 0px;
}

.footer {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  padding-top: 800px;
  padding-right: 18px;

}

.footer-2 {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  padding-top: 0.2px;
  padding-left: 10px;

}


.texto-fundo {
  position: absolute;
  width: 383px;
  height: 67px;
  left: 0px;
  top: 38px;

  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.caixa-baixo {
  position: absolute;
  width: 383px;
  height: 67px;
  left: 0px;
  top: 750px;
  padding-bottom: 0px;
  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.texto-fundo-down {
  position: absolute;
  width: 383px;
  height: 67px;
  left: 0px;
  top: 720px;

  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.metas {
  width: 34px;
  height: 34px;
  left: 43px;
  top: 720px;
  top: 10px;
  position: absolute;
  top: 10px;
  
}

.conteudos {
  width: 30px;
  height: 30px;
  left: 305px;
  top: 720px;
  top: 10px;
  position: absolute;
}

.texto-metas {
  width: 40px;
  height: 16px;
  left: 40px;
  top: 805px;
  position: absolute;
  top: 45px;
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.1px;

  color: rgba(28, 27, 31, 0.6);
}

.texto-conteudos {
  width: 69px;
  height: 16px;
  left: 286px;
  position: absolute;
  top: 45px;
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.1px;
  padding-left: 8px;
  color: rgba(26, 27, 27, 0.6);
}

.dns {
  width: 33px;
  height: 33px;
  left: 173px;
  top: 10px;
  position: absolute;
}

.texto-dns {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;

  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  position: absolute;
  top: 45px;
  padding-right: 10px;


  color: rgba(28, 27, 31, 0.6);
}
</style>
