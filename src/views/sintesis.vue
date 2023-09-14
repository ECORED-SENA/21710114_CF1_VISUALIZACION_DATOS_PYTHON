<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p La visualización de datos es muy importante hoy en día, ya que, gracias a estas proyecciones, se tienen en cuenta muchos análisis predictivos para la correcta toma de decisiones.

    p Esta necesidad de visualización, gracias a su gran importancia en el mundo informático, ha creado herramientas que ayudan a los desarrolladores a obtener un número considerable de estos datos que circulan, para poder armar patrones y generar grupos de datos que conlleven tendencias de fácil identificación.

    p Estas herramientas son muy prácticas e intuitivas para que las empresas puedan sustraer los resultados y generar objetivos específicos, que dirijan a un grupo de científicos de datos a orientar los caminos o direcciones a que se pretende llegar con estos análisis detallados. La ciencia de datos parte de un principio que dice “una imagen vale más que mil palabras”.

    p.mb-5 A continuación, podrá ver una síntesis gráfica de lo visto en el componente y esos aspectos claves que se debe llevar:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
