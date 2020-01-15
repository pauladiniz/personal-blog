<template>
  <Layout>
    <div class="about">
      <div class="about__content">
        <p>Olá! Meu nome é <strong>Paula Diniz</strong>, tenho 26 anos e trabalho com desenvolvimento desde 2012/2013. Descobri minha paixão por tudo que envolve tecnologia aos 13 anos quando
          ganhei meu primeiro computador, fiz meu primeiro blog no Weblogger na metade de 2005 e a partir disso um universo se abriu! :) Sim, eu usei Front Page e fatiei muito layout no Fireworks! </p>
        <p>Apesar do amor pela internet, fui fazer Engenharia Civil na Universidade Presbiteriana Mackenzie, mas desisti faltando alguns semestres e migrei completamente pra área de T.I. Passei algum
          tempo da minha carreira em agências de publicidade, portanto eu sei fazer um belíssimo e-mail marketing e muitos, muitos hotsites! Passei por um e-commerce, um banco e atualmente trabalho no 
          Negocia Fácil, uma plataforma de cobrança digital onde usei e ainda uso <strong>VueJS</strong> para reescrever parte das aplicações</p>
        <p> Ah, eu também faço parte da organização do MeetupCSS - São Paulo!</p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Sobre'
  }
}
</script>

<style lang="stylus">
  .about
    display flex
    align-items center
    justify-content center
    &__content
      width 800px
  p {
    color: #696969; 
    font-size: 14px
  }
</style>