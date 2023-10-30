<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 EDA y tratamiento para datos
    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img1.png', style="width: 450px" ,alt='').m-auto
      .col-lg-8
        p EDA significa, en inglés, #[em Exploratory Data Analysis], lo cual hace referencia a una de las primeras cosas que tiene que realizar el científico de datos cuando revisa por primera vez un archivo en formato .CSV. Él debe saber comprender, descubrir posibles patrones y distribuciones estadísticas que puedan ser útiles más adelante, siempre y cuando se tenga un objetivo claro, que sepa lo que se quiere hacer con los datos, y por tanto comprender a dónde se quiere llegar con su interpretación.
        p.mb-0 EDA es una primera aproximación a los datos. Ahora bien, suponiendo que se tiene una muestra de datos suficiente, entonces, lo más seguro es que, con gran rapidez, se tenga una pregunta alusiva para poder dar inicio al proyecto. Resumiendo, lo que hace EDA es poder tener en una hora, o máximo un día, los datos para poder sacar conclusiones y poder decir al usuario si se prosigue o no con el proyecto. En caso de que el proyecto continúe, esto da más tiempo para poder determinar si se aplicarán modelos de #[em machine learning].
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario1.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/img1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Trabajar con EDA
                  p.text-small Hablando de programación y recordando que se está trabajando con Python, se encuentra con librerías denominadas Pandas, que ayudarán a manipular los datos, leerlos y transformarlos. Otra de las técnicas que le ayudará con Pandas es la visualización de los datos. Un ejemplo de ello se presenta en el anexo.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Anexo_1_Trabajar_con_EDA.pdf')" target="_blank")
                    span(style="color: #12263F !important") Ver PDF
                    i.fas.fa-link(style="color: #12263F !important")
    Separador
    #t_3_1
    .titulo-segundo.color-acento-contenido
      h2 3.1 Aprendizaje supervisado para regresiones
    p Cuando se habla de #[em machine learning] se hace referencia de una de las ciencias de la computación, como la inteligencia artificial, que dice que los algoritmos cada vez aprenden y se auto programan basándose en experiencias, tal como lo hacen los seres humanos.
    p.mb-5 Existen métodos de clasificación y regresión que hacen parte de una de las ramas del #[em machine learning], más conocidos como el aprendizaje automático supervisado; estos se organizan bajo cuatro algoritmos en los que se fundamenta el #[em machine learning]:
    .row.justify-content-center.mb-5
      .col-auto.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img2.svg', style="width: 250px" ,alt='').m-auto
      .col-md-8.col-lg-6.bg-c8.mb-4.mb-lg-0
        .p-4
          ul.lista-ul.mb-0
            li.mb-0
              i.lista-ul__vineta
              span #[b #[i Machine Learning supervisado.]]
            li.mb-0
              i.lista-ul__vineta
              span #[b #[i Machine Learning no supervisado.]]
            li.mb-0
              i.lista-ul__vineta
              span #[b #[i Machine Learning semisupervisado.]]
            li.mb-0
              i.lista-ul__vineta
              span #[b #[i Machine Learning por refuerzo.]]
    .row.align-items-center
      .col-lg-8.mb-4.mb-lg-0
        p El aprendizaje supervisado trabaja con datos que ya se encuentran etiquetados y que se conoce la respuesta de destino; con base en datos históricos, busca datos relacionados en campos especiales, denominados objetivo sujeto a datos de entrada o parámetros. A partir de estos históricos, el algoritmo aprende a etiquetar los datos de salida. Hoy en día, el aprendizaje supervisado es utilizado en dos campos: el de clasificación, como detección de fraude, y el de regresión, como el meteorológico.
        .row.align-items-center.bg-c2
          .col-md-auto.px-lg-0.pt-4.pt-md-0
            figure
              img(src='@/assets/curso/tema3/img3.svg', style="width: 120px" ,alt='').m-auto
          .col
            .p-4
              p.mb-0 Entonces, se entiende que las regresiones lineales hacen parte de los algoritmos de aprendizaje supervisado que se utilizan en las ciencias de datos, como #[em machine learning], y en estadística.
      .col-lg-4
        figure
          img(src='@/assets/curso/tema3/img2.png', style="width: 450px" ,alt='').m-auto
    Separador
    #t_3_2
    .titulo-segundo.color-acento-contenido
      h2 3.2 Aprendizaje supervisado para clasificación
    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img4.svg', style="width: 450px" ,alt='').m-auto
      .col-lg-8
        p Cuando se habla de aprendizaje supervisado, se hace referencia al entrenamiento que se realiza a los algoritmos con datos etiquetados con la respuesta correcta; cuantos más datos tenga el conjunto, más acertado y rápidamente aprende el algoritmo. Una vez concluido el entrenamiento, se le asignan nuevos datos, pero estos ya sin las etiquetas de las respuestas correctas. Este algoritmo utiliza la experiencia que obtuvo en el ejercicio anterior para apuntar o predecir un resultado.
        p.mb-0 Para construir un modelo de #[em machine learning], no es solamente ir a escoger un algoritmo de aprendizaje o una librería de #[em machine learning]; esto conlleva una serie de pasos que involucran lo siguiente:
    .row.bg-c1
      .col-12
        .p-5
          .row
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema3/img5.svg', style="width: 320px" ,alt='').m-auto
            .col-lg-8
              .row
                .col-lg-6.mb-2.mb-lg-0
                  .row.m-1
                    .col-12.bg-c10.mb-3
                      .p-3
                        p.mb-0 #[b 1. Recolectar los datos]
                    .col-12.bg-c10.mb-3
                      .p-3
                        p.mb-0 #[b 2. Procesar los datos]
                    .col-12.bg-c10
                      .p-3
                        p.mb-0 #[b 3. Explorar los datos]
                .col-lg-6
                  .row.m-1
                    .col-12.bg-c10.mb-3
                      .p-3
                        p.mb-0 #[b 4. Entrenar el algoritmo]
                    .col-12.bg-c10.mb-3
                      .p-3
                        p.mb-0 #[b 5. Evaluar el algoritmo]
                    .col-12.bg-c10
                      .p-3
                        p.mb-0 #[b 6. Utilizar el modelo]

    p.mb-5 Las librerías que utilizan Python para #[em machine learning] son las mismas que se mencionaron al inicio de este documento, no es necesario volver a nombrarlas, pero sí se nombrarán los algoritmos más utilizados en la ciencia de datos:
    .row.justify-content-center.mb-5
      .col-lg-6.bg-c8.mb-4.mb-lg-0
        .p-4
          ul.lista-ul.mb-0
            li.mb-0
              i.lista-ul__vineta
              span #[b Regresión lineal.]
            li.mb-0
              i.lista-ul__vineta
              span #[b Regresión logística.]
            li.mb-0
              i.lista-ul__vineta
              span #[b Árboles de decisión.]
            li.mb-0
              i.lista-ul__vineta
              span #[b Random Forest.]
            li.mb-0
              i.lista-ul__vineta
              span #[b SVM (Máquinas de Vectores de Soporte).]
            li.mb-0
              i.lista-ul__vineta
              span #[b KNN]
            li.mb-0
              i.lista-ul__vineta
              span #[b K-Means]
      .col-lg-auto
        figure
          img(src='@/assets/curso/tema3/img3.png', style="width: 460px" ,alt='').m-auto
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario1.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/img1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Ejemplos de aprendizaje supervisado
                  p.text-small Estos algoritmos se pueden aplicar a la gran mayoría de problemas con datos, gracias a las librerías que tiene Python, como scikit-learn. Se muestran algunos ejemplos en el anexo.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Anexo_2_Ejemplos_de_aprendizaje_supervisado.pdf')" target="_blank")
                    span(style="color: #12263F !important") Ver PDF
                    i.fas.fa-link(style="color: #12263F !important")
    Separador
    #t_3_3
    .titulo-segundo.color-acento-contenido
      h2 3.3 Aprendizaje no supervisado y simulación
    .row.mb-4
      .col-lg-8.mb-4.mb-lg-0
        p Mientras que en el aprendizaje supervisado se tienen salidas con etiquetas para el entrenamiento de los algoritmos, en el no supervisado no se sabe qué resultado esperar; de esa manera, entender el no supervisado se convierte en un ejercicio intuitivo, pues con este modelo es difícil saber si se ha realizado un trabajo exitoso o si aún es posible extraer datos de él.
        p En el aprendizaje no supervisado, el reto es agrupar segmentos de datos, a eso se le llama #[em clustering] de datos, cuyo objetivo es encontrar grupos homogéneos de datos, ya que esta homogeneidad permite realizar análisis de comportamiento de estos grupos, para así poder sacar conclusiones y sacar posibles futuros datos. Estos algoritmos se basan en la distancia entre observaciones; los algoritmos más utilizados en el aprendizaje no supervisado son:
        .row
          .col-12.bg-c5
            .p-3
              .row.justify-content-center
                .col-auto.bg-c10.m-1
                  .p-4
                    p.text-center.mb-0 #[b Agrupamiento por K-medias]
                .col-auto.bg-c10.m-1
                  .p-4
                    p.text-center.mb-0 #[b Agrupamiento jerárquico]
      .col-lg-4
        figure
          img(src='@/assets/curso/tema3/img4.png', style="width: 460px" ,alt='').m-auto
    p.mb-5 Por último, y para explicar este método, se desarrolla un ejercicio donde se utilizarán pocas variables, las cuales, poco a poco, se irán incrementando. Observe el paso a paso de este ejercicio:
    .row.justify-content-center
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul1")
          .row(titulo="Identificación de coordenadas")
            .col-12
              p Este ejercicio lo haremos con #[b K = 2].
              p.mb-4 Supongamos se tiene un grupo de jugadores de fútbol en un campo y se logra obtener una fotografía desde la parte de arriba para poder identificar sus coordenadas (la variable 1 sería el eje X y variable 2 sería el eje Y). Por la altura, no se alcanza a distinguir de qué equipo es cada uno de los jugadores, por ese motivo, se pintarán todos de negro.
              figure.mb-4
                img(src='@/assets/curso/tema3/img5.png', style="width: 660px" ,alt='Captura de pantalla de los datos representando los jugadores de futbol en la cancha.').m-auto
              figure
                img(src='@/assets/curso/tema3/img6.png', style="width: 660px" ,alt='Captura de pantalla de los datos representando los jugadores de futbol en la cancha.').m-auto
          .row(titulo="Ubicación de centroides")
            .col-12
              p.mb-4 El modelo permite agrupar, a partir de la identificación de centroides. Se puede ubicar la cantidad de centroides como grupos, lo cuales se identificarán así para este ejemplo. Se sabe que hay dos equipos, entonces se utilizarán 2 centroides, el algoritmo k-medias colocará estos dos puntos centroides de forma aleatoria en el plano; se procede a calcular la distancia entre cada centro y los demás puntos del plano, y si está más cerca de un centroide, lo asigna al “uno”, de lo contrario, lo asigna al centroide “dos”.
              figure
                img(src='@/assets/curso/tema3/img7.png', style="width: 660px" ,alt='Captura de pantalla mostrando la identificación de centroides en un plano cenital.').m-auto
          .row(titulo="Agrupamiento jerarquico")
            .col-12
              p Por otro lado, el agrupamiento jerárquico hace referencia a otro método de agrupamiento de datos, a diferencia del k-medias, este nos muestra la cantidad de datos de combinaciones posibles de acuerdo con la jerarquía de las distancias entre puntos.
          .row(titulo="Graficación del algoritmo")
            .col-12
              p Ahora bien, se utilizará el mismo ejemplo anterior del equipo de fútbol, con la diferencia de que esta vez se enumerará cada jugador para obtener una mejor visualización.
              p Su funcionamiento consiste en buscar los puntos con las distancias más cortas y agruparlos, y busca otros dos puntos con la menor distancia y realiza la pregunta: ¿es la distancia entre estos dos grupos más corta que la distancia de los grupos creados con anterioridad?
              p Si la respuesta es “SÍ”, los agrupará, de lo contrario, agrega los puntos al grupo ya creado con anterioridad.
              p.mb-4 Observemos el algoritmo gráficamente. Los puntos 1 y 2 tienen la jerarquía más baja puesto que se tiene la distancia más corta. El algoritmo sigue su búsqueda para los puntos más cercanos (el 9 y el 12) y realiza la comparación con el punto medio del 1 y el 2, por lo que se decide la creación de un nuevo grupo con una jerarquía más alta, y así lo hace sucesivamente.
              figure
                img(src='@/assets/curso/tema3/img8.png', style="width: 660px" ,alt='Captura de pantalla mostrando los puntos más cercanos y su jerarquía.').m-auto

</template>

<script>
export default {
  name: 'Tema3',
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
