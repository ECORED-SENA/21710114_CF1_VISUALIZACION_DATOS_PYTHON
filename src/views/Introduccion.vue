<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.bg-c1
      .col-12
        .px-5.pt-5
          .row.align-items-center.mb-5(data-aos="fade-right")
            .col-lg-auto.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/intro/img1.svg', style="width: 190px" ,alt='').m-auto
            .col
              p.mb-0 La graficación de datos permite no solo una mejor visualización de estos sino una correcta interpretación de los mismos. Es por ello que se utilizan herramientas de proyección que permitan ver, a manera de cuadros y mapas, entre otras opciones, un panorama suficiente para determinar, de alguna manera, decisiones vitales para la empresa u orientar a un equipo a alcanzar algún objetivo. El siguiente video expone de forma introductoria lo que se desarrollará en este componente formativo:
          figure(data-aos="fade-left")
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/wMCDkknpUVw?si=PTwby29gam4YbDJz" title="Introducción a la estadística" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
            figcaption Video. Introducción a la estadística

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
