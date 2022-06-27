<template>
  <div class="container">
    <b-container>
      <img src="~/assets/ios.png" alt="ios icon" />
      <Nuxt-Link to="/conteudos"><img class="cancel" src="~/assets/cancel.png" alt="cancel icon" /></Nuxt-Link>
      <div>
        <img src="~/assets/Image2.png" />
        <b-button class="botao">#Saúde</b-button>
        <img class="icon-2" src="~/assets/Icon.png" alt="Icon salvar" />
        <img
          class="icon-3"
          src="~/assets/likeecomp.png"
          alt="Icon compartilhar"
        />
      </div>

      <div class="layout-2">
        <p class="conteudo-4">2 meses atrás</p>
        <h4 class="titulo-1-conteudo">Prática do exercício físico</h4>

        <p class="conteudo-3">Dicas para quem quer melhorar a rotina de</p>
        <p class="conteudo-3">exercícios físicos durante as férias.</p>
        <div class="conteudo-5">
          <p>• Diminua o ritmo dos exercícios, mas não pare totalmente.</p>
          <p>• Inclua exercícios nos passeios turísticos.</p>
          <p>• Envola a família nos passeios.</p>
          <p>• Cuide de sua alimentação.</p>
        </div>
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

      <div>
        <img class="ios-down" src="~/assets/iosDown.png" alt="Ios down" />
      </div>
      
    </b-container>
  </div>
</template>

<script>
export default {
  async asyncData({ route }) {
    const { id } = await route.params
    return { id }
  },

  data() {
    return {
      titulo: 'Conteudos',
      conteudo: [],
      salvos: [
        {
          id: 1,
          url: '~/assets/Image2.png',
          tempo: '2 meses atrás',
          titulo: 'Prática do exercício físico',
          titulo2:
            'Dicas para quem quer melhorar a rotina de exercícios físicos durante as férias.',
          conteudoS: [
            '• Diminua o ritmo dos exercícios, mas não pare totalmente.',
            '• Inclua exercícios nos passeios turísticos.',
            '• Envola a família nos passeios.',
            '• Cuide de sua alimentação.',
          ],
        },
      ],
    }
  },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@700&family=Darker+Grotesque&family=Inter:wght@300;400&family=Montserrat:wght@500&family=Poppins:wght@600&family=Roboto:ital,wght@0,500;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@700&family=Darker+Grotesque&family=Inter:wght@300;400&family=Montserrat:wght@500&family=Poppins:wght@600&family=Roboto:ital,wght@0,500;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@700&family=Darker+Grotesque&family=Inter:wght@300;400&family=Montserrat:wght@500&family=Poppins:wght@600&family=Roboto:ital,wght@0,400;0,500;1,400&display=swap');

.container {
  position: relative;
  width: 382.54px;
  height: 812px;
  align-items: center;
  padding-left: 0.3px;
  background: #ffffff;
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
  top: 53.34%;
  bottom: 10.71%;
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
  width: 343px;
  height: 8px;

  font-family: 'Roboto';
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

.conteudo-5 {
  position: absolute;
  width: 270px;
  height: 26px;
  left: 28px;
  top: 665px;
  padding-right: 40px;
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;

  letter-spacing: 0.25px;

  color: #000000;

  position: absolute;
  left: 9.15%;
  right: 7.2%;
  top: 40.34%;
  bottom: 10.71%;
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

.botao {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 10px;
  gap: 4px;

  width: 69px;
  height: 36px;

  color: #ffffff;
  background: #5946d2;
  border-radius: 20px;
  border-style: none;

  font-size: 12px;
  text-align: center;

  position: absolute;
  width: 67px;
  left: calc(50% - 67px / 2 - 136px);
  top: 47.78%;
  bottom: 47.78%;
}

.icon-2 {
  position: absolute;
  width: 27px;
  height: 27px;
  left: 230px;
  top: 392px;
}

.icon-3 {
  position: absolute;
  width: 88px;
  height: 40px;
  left: 270px;
  top: 386px;
}

.ios-down {
  position: absolute;
  width: 390px;
  height: 26px;
  left: calc(50% - 390px / 2 + 3.73px);
  bottom: 0px;
  top: 820px;
}

.cancel {
  position: absolute;
  width: 24px;
  height: 24px;
  left: 336px;
  top: 58px;
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
  padding-left: 170px;
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

