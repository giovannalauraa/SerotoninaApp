<template>
  <div class="container">
    <b-container>
    <menuHamburguer> </menuHamburguer>
    <img src="~/assets/ios.png" alt="ios icon" />
    <div class="texto-fundo">
      <h3 class="titulo">Tarefas</h3>
      <img class="tabs" src="~/assets/Tabs.png" alt="Tabs icon" />
    </div>

    <div>
      <img class="plus" src="~/assets/Plus.png" alt="plus icon" />
      <p class="criar-lista">Criar Lista</p>
    </div>

  <div class="caixa-baixo">
    <div class="footer">
      <img class="metas" src="~/assets/emoji_events.png" alt="trofeu " />

      <img class="dns" src="~/assets/dns_2.png" alt="dns" />


      <NuxtLink to="/conteudos"
        ><img class="conteudos" src="~/assets/search.png" alt="lupa"
      /></NuxtLink>

        <div>
        <img class="ios-down" src="~/assets/iosDown.png" alt="Ios down" />
      </div> 

    </div>

    <div>
      <p class="texto-metas">Metas</p>
      <p class="texto-dns">Tarefas</p>
      <p class="texto-conteudos">Conteúdos</p>
       
    </div>
    
  </div>

    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Conteúdos',
      pessoas: [],
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
  background: #ede7fa;
  padding-left: 0.2px;
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
  padding-left: 168px;
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

.ios-down {
  position: absolute;
  width: 390px;
  height: 26px;
  left: calc(50% - 390px / 2 + 3.73px);
  bottom: 0px;
  top: 80px;
 
}

.plus {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 24px;

  position: absolute;
  width: 80px;
  height: 80px;
  left: 156px;
  top: 320px;
}

.criar-lista {
  position: absolute;
  width: 103px;
  height: 19px;
  left: 152px;
  top: 400px;

  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 22px;

  color: rgba(0, 0, 0, 0.75);
}
.tabs {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 0px;

  position: absolute;
  width: 383px;
  height: 48px;
  top: 80px;
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
</style>
