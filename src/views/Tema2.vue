<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Introducción a la estadística
    p.mb-5 Hoy en día, es común escuchar el término Big Data y, con eso, la necesidad de conocer acerca de la probabilidad y estadística como elementos imprescindibles. Los temas de minería de datos, machine learning, más los millones de datos con los que se cuenta a diario, es lo que hoy se conoce como la ciencia de datos en conjunto. En este mundo, Python es el lenguaje potente que más permite trabajar con los datos y analizarlos de manera estadística.
    .row.justify-content-center.mb-5
      .col-lg-10
        .row.align-items-center.bg-c2
          .col-md-auto.px-lg-0.pt-4.pt-md-0
            figure
              img(src='@/assets/curso/tema2/img1.svg', style="width: 100px" ,alt='').m-auto
          .col
            .p-4
              p.mb-0 Según López Briega (2018), la estadística suele ser definida como la ciencia de aprender de los datos o como la ciencia de obtener conclusiones en la presencia de incertidumbre.
    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema2/img1.png', style="width: 450px" ,alt='').m-auto
      .col-lg-8
        p Se relaciona principalmente con la recolección, análisis e interpretación de datos, así como con la efectiva comunicación y presentación de los resultados basados en esos datos; estos últimos entendiéndose como cualquier clase de información grabada.
        p.mb-0 La estadística juega un rol importante en muchas disciplinas científicas; de allí que ha jugado un papel importante en la toma de decisiones, pues existe innumerable información valiosa entre los datos. La estadística brinda opciones o métodos para extraer esta información adecuadamente y entenderla, verificando la calidad de esta. Se encuentra dividida en dos ramas: estadística descriptiva y estadística inferencial, como se ve en el siguiente video:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.mb-5 Las siguientes son algunas actividades básicas en el análisis estadístico:
    .row.justify-content-center
      .col-lg-6.bg-c8.mb-4.mb-lg-0
        .p-4
          ul.lista-ul.mb-0
            li.mb-0
              i.lista-ul__vineta
              | #[b Diseño del análisis.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Exploración de datos.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Armado del modelo.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Realizar estimaciones.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Contraste de la hipótesis.]
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img2.png', style="width: 590px" ,alt='').m-auto
    Separador
    #t_2_1
    .titulo-segundo.color-acento-contenido
      h2 2.1 Análisis descriptivo
    p.mb-5 Para exponer la particularidad de los datos, es necesario tener diferentes medidas, estas son algunas de ellas:
    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-botones.p-4
        p #[b Media aritmética]
        p Indica el resultado de haber sumado todos los datos y dividirlos por el total de los elementos sumados. Se representa por la letra griega μ. Dicho de otra manera, si tenemos una muestra de n valores Xi, la media aritmética μ, es la suma de los valores divididos por el número de elementos, así:
        figure
          img(src='@/assets/curso/tema2/img2.svg', style="width: 160px" ,alt='').m-auto
      .tarjeta.color-acento-botones.p-4
        p #[b Desviación respecto a la media]
        p La definición puntual de la desviación respecto a la media enfatiza en la diferencia en el valor absoluto entre cada valor de la variable estadística y la media aritmética.
        figure
          img(src='@/assets/curso/tema2/img3.svg', style="width: 160px" ,alt='').m-auto
      .tarjeta.color-acento-botones.p-4
        p #[b Varianza]
        p Es la media aritmética del cuadrado de las desviaciones respecto a la media de una distribución estadística. La varianza intenta describir la dispersión de los datos. Se representa como σ2.
        figure
          img(src='@/assets/curso/tema2/img4.svg', style="width: 160px" ,alt='').m-auto
      .tarjeta.color-acento-botones.p-4
        p #[b Desviación típica]
        p Es la raíz cuadrada de la varianza. Se representa con la letra griega σ.
        figure
          img(src='@/assets/curso/tema2/img5.svg', style="width: 160px" ,alt='').m-auto
      .tarjeta.color-acento-botones.p-4
        p #[b Moda]
        p La moda es el valor que tiene mayor frecuencia absoluta. Se representa con M0.
      .tarjeta.color-acento-botones.p-4
        p #[b Mediana]
        p Es el valor que ocupa el lugar central de todos los datos cuando estos están ordenados de menor a mayor. Se representa con x˜
      .tarjeta.color-acento-botones.p-4
        p #[b Correlación]
        p Indica el resultado de haber sumado todos los Trata de establecer la relación o dependencia que existe entre las dos variables que intervienen en una distribución bidimensional. Es decir, determinar si los cambios en una de las variables influyen en los cambios de la otra. En caso de que suceda, diremos que las variables están correlacionadas o que hay correlación entre ellas. La correlación es positiva cuando los valores de las variables aumentan juntos; y es negativa cuando un valor de una variable se reduce cuando el valor de la otra variable aumenta.
      .tarjeta.color-acento-botones.p-4
        p #[b Covarianza]
        p Es el equivalente de la varianza aplicado a una variable bidimensional. Es la media aritmética de los productos de las desviaciones de cada una de las variables respecto a sus medias respectivas. La covarianza indica el sentido de la correlación entre las variables: si σxy>0, la correlación es directa; si σxy<0, la correlación es inversa.
        figure
          img(src='@/assets/curso/tema2/img6.svg', style="width: 240px" ,alt='').m-auto
      .tarjeta.color-acento-botones.p-4
        p #[b Valor atípico]
        p Es una observación que se aleja demasiado de la moda; está muy lejos de la tendencia principal del resto de los datos. Pueden ser causados por errores en la recolección de datos o medidas inusuales. Generalmente, se recomienda eliminarlos del conjunto de datos.
    p.mb-4 Como se observa, el análisis descriptivo se plantea para dar algún tipo de respuesta a algún planteamiento formulado al inicio del requerimiento estadístico; sin embargo, lo que busca este tipo de análisis estadístico es realizar una recolección de datos y tratar de organizarlos a manera representativa por medio de gráficos y medios visuales de fácil interpretación para el usuario, y así poder extraer las características que más representen a un grupo de datos, para luego trazar una tendencia de ellos.
    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema2/img3.png', style="width: 450px" ,alt='').m-auto
      .col-lg-8
        .row.bg-c2.mb-3
          .col-auto.px-0
            figure
              img(src='@/assets/curso/tema2/img7.svg', style="width: 70px" ,alt='').m-auto
          .col
            .row
              .col-12
                .p-4
                  p.mb-0 De esta manera, hoy se puede decir que es un método que va de la mano con los sucesos y se enfoca en ellos, recolectando información y conectando los datos entre sí, de manera que sea posible conformar una información precisa y contundente; gracias a este tipo de análisis, se puede saber más acerca de una población en especial y tomar algún tipo de determinación según la información, tanto cualitativa como cuantitativa.
        p.mb-0 Python maneja unas librerías que facilitan el manejo de las matemáticas y la estadística; no es la excepción y, para fortuna de todos, la comunidad de Python es tan grande que es normal siempre encontrar librerías que solucionan cualquier situación. En ese orden de ideas, Python ofrece un abanico de librerías que ayudan a la solución de problemas estadísticos y de probabilidad; las librerías ideales para este tipo de ejercicios son las siguientes:
    .row.justify-content-center
      .col-12.bg-c3
        .p-4
          figure
            img(src='@/assets/curso/tema2/img8.svg', style="width: 950px" ,alt='').m-auto
    Separador
    #t_2_2
    .titulo-segundo.color-acento-contenido
      h2 2.2 Inferencia estadística
    .row.align-items-center.mb-5
      .col-md-auto
        figure
          img(src='@/assets/curso/tema2/img9.svg', style="width: 170px" ,alt='').m-auto
      .col
        p.mb-0 Según López Briega (2018), “La estadística inferencial estudia cómo sacar conclusiones generales para toda la población a partir del estudio de una muestra y el grado de fiabilidad o significación de los resultados obtenidos. Sus principales herramientas son el #[b muestreo, la estimación de parámetros y el contraste de hipótesis”].
    .row.justify-content-center.mb-5
      .col-md-7.col-lg-auto.px-0
        figure
          img(src='@/assets/curso/tema2/img4.png', style="width: 440px" ,alt='').m-auto
      .col-md-7.col-lg-6.bg-c5
        .p-4
          p.mb-0 La probabilidad aporta componentes fuertes para trabajar con la estadística inferencial, teniendo entre los datos una posibilidad de reducción de errores cuando se está examinando su comportamiento en el tiempo. Cuando se habla de inferencia, se habla de concluir desde supuestos particulares o generalizados.
    p Hay dos métodos para la inferencia estadística:
    .row.justify-content-center.mb-5
      .col-11.col-md-10.col-lg-6
        .row.h-100
          .col-12.bg-c9
            .p-4
              figure.mb-4
                img(src='@/assets/curso/tema2/img10.svg', style="width: 440px" ,alt='').m-auto
              p.mb-0 #[b Métodos de estimación de parámetros]
              p.mb-0 Consisten en asignar un valor al parámetro caracterizado en un conjunto de datos que son el objeto de estudio. Cuando se habla de estimación, también se está contemplando la posibilidad de errores; para la reducción de estos, hay que puntualizar intervalos de confianza.
      .col-11.col-md-10.col-lg-6
        .row.h-100
          .col-12.bg-c9
            .p-4
              figure.mb-4
                img(src='@/assets/curso/tema2/img11.svg', style="width: 440px" ,alt='').m-auto
              p.mb-0 #[b Métodos de contraste de hipótesis]
              p.mb-0 Tienen como objetivo comprobar si una estimación corresponde a los valores poblacionales. Cuando se hace un contraste de hipótesis, siempre hay dos supuestos: la hipótesis nula y la hipótesis alternativa.
    .row.justify-content-center
      .col-lg-10
        .row.bg-c2
          .col-auto.px-0
            figure
              img(src='@/assets/curso/tema2/img13.svg', style="width: 70px" ,alt='').m-auto
          .col
            .row
              .col-12
                .p-4
                  p.mb-0 Cuando se traslada la estadística inferencial al plano de desarrollo en Python, se está hablando de invocar las librerías que se estudiaron en los anteriores ítems realizando básicamente las mismas operaciones, pero con distintos objetivos, dependiendo del criterio con que se utilicen.
    Separador
    #t_2_3
    .titulo-segundo.color-acento-contenido
      h2 2.3 Aprendizaje no supervisado
    .row.align-items-center.mb-5
      .col-lg-3.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema2/img5.png', style="width: 440px" ,alt='').m-auto
      .col-lg-9
        p Los algoritmos de lenguajes no supervisados son un conjunto de datos sin etiquetas y desordenados, que no tienden a indicar nada; estos métodos de aprendizaje no supervisado no se pueden aplicar a problemas de clasificación o de regresión, porque no se sabe el resultado que van a arrojar; sin embargo, el aprendizaje sin supervisión se dice que puede descubrir la estructura subyacente de los datos.
        .row.bg-c2.mb-3
          .col-auto.px-0
            figure
              img(src='@/assets/curso/tema2/img14.svg', style="width: 70px" ,alt='').m-auto
          .col
            .row
              .col-12
                .p-4
                  p.mb-0 Los algoritmos de aprendizaje sin supervisión permiten realizar operaciones más robustas que los supervisados, de esta manera, los supervisados son usados para analizar cadenas de datos que tienen concordancia y similitud en un grupo de datos.
        p.mb-0 El aprendizaje no supervisado lo que realiza es tratar de analizar patrones que no sean reconocidos en los datos; la gran mayoría de veces, los datos son aproximaciones que el aprendizaje supervisado puede acertar, lo que hace que sean más usados en la aplicación de problemas en el mundo real.
    .row.justify-content-center.mb-5
      .col-md-7.col-lg-auto.px-0
        figure
          img(src='@/assets/curso/tema2/img6.png', style="width: 440px" ,alt='').m-auto
      .col-md-7.col-lg-6.bg-c5
        .p-4
          p.mb-0 El momento de utilizar el aprendizaje no supervisado es cuando no se tiene conocimiento de los datos que van a resultar. Trasladándolo al mundo real, es como vender un producto totalmente nuevo a un mercado incierto, donde la compañía no tiene ninguna experiencia; pero si lo que busca es comprender alguna información dentro de sus clientes existentes, el aprendizaje supervisado es la opción.
    p.mb-5 Las razones por las cuales se utiliza el aprendizaje no supervisado son las siguientes:
    .row.justify-content-center
      .col-lg-10.bg-c8
        .p-4
          ul.lista-ul.mb-0
            li.mb-0
              i.lista-ul__vineta
              | #[b Se encuentra con todo tipo de patrones desconocidos en los datos.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Ayuda a encontrar datos útiles para la categorización.]
            li.mb-0
              i.lista-ul__vineta
              | #[b La facilidad para encontrar datos no etiquetados.]

</template>

<script>
import SlyderF from '@/components/SlyderF.vue'
export default {
  name: 'Tema2',
  components: { SlyderF },
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
