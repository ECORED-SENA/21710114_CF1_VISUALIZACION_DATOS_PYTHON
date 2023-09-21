<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Python y Colab
    p.mb-5 Colab, también conocido como "Colaboratory", permite programar y ejecutar Python en su navegador, con las siguientes ventajas:
    .row.justify-content-center.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img1.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b No requiere configuración]
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img2.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b Da acceso gratuito a GPU]
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img3.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b Permite compartir contenido fácilmente]
    .row.align-items-center.mb-5
      .col-lg-3.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img1.png', style="width: 350px" ,alt='').m-auto
      .col-lg-9
        p Colab puede facilitar su trabajo, ya sea estudiante, científico de datos o investigador de IA. Google Colaboratory es un entorno gratuito de Jupyter Notebook que no requiere configuración y que se ejecuta completamente en la nube. En ese sentido, Python permite diferentes ambientes en la programación, como la orientada a objetos y la funcional, pero lo más relevante de esta parte es que se utiliza como un lenguaje de scripts o intérprete.
        p Python tiene una funcionalidad de un modo interactivo, que trabaja de la mano con un intérprete de línea de comando que, al lanzar una orden, se obtiene un resultado. En sus inicios, las funcionalidades se quedaron limitadas con IPython, que más adelante evolucionó a Jupyter. Jupyter es un entorno que permite desarrollar líneas de Python dinámicamente, funciona como una aplicación local, donde se emula la función cliente servidor y posibilita la ejecución de código; de esa manera, su interactividad posibilita la interpretación de su código de manera tal que pareciera la lectura de un documento a los ojos de cualquier persona.
        p.mb-0 En el siguiente recurso se observa la implementación y ejecución de Colab.


    .tarjeta.tarjeta--azul.mb-5
      .p-4.p-lg-5
        SlyderA(tipo="b")
          .row
            .col-lg-6.mb-4.mb-lg-0
              p #[b Acceso a Google Colaboratory]
              p Google Colab es de carácter gratuito y para acceder a él, no es más que entrar a nuestra cuenta de Google, hacer clic derecho en nuestro drive, ir al botón de nuevo y luego al submenú de más para seleccionar Colaboratory; creando así un nuevo cuaderno.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/img2.png', style="width: 450px" ,alt='').m-auto
          .row
            .col-lg-6.mb-4.mb-lg-0
              p #[b Cuaderno de Google Colaboratory]
              p Una vez creado el apartado, se ha creado un cuaderno, que no es más que un documento que contiene código ejecutable, como Python; ese va a ser nuestro entorno de trabajo para Python y tiene un aspecto como el que se aprecia en la imagen. En la parte superior izquierda se puede cambiar el nombre del documento; en tanto su extensión (*.ipynb), viene de IPython Notebook, esto hace que nos permita ejecutar cuadernos tanto en IPython como en Jupyter y Colab.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/img3.png', style="width: 450px" ,alt='').m-auto
          .row
            .col-lg-6.mb-4.mb-lg-0
              p #[b Codificando el cuaderno]
              p La composición de un cuaderno está dada por celdas, ya que estas son la mínima parte de ejecución dentro de un cuaderno, es ahí donde escribimos nuestro código y lo ejecutamos, se puede realizar pulsando el botón de play ubicado a la izquierda de la línea o celda. Una vez realizada la ejecución, en la celda inferior, encontraremos el resultado de la ejecución inmediatamente anterior.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/img4.png', style="width: 450px" ,alt='').m-auto
          .row
            .col-lg-6.mb-4.mb-lg-0
              p #[b Ejecución]
              p Se puede observar que las celdas de Colab son independientes, pero todas ellas trabajan con el mismo kernel; hay que recordar que un kernel es el corazón de un sistema operativo, pero, a su vez, no solo es el núcleo de un sistema, sino también un programa que controla todos los accesos al procesador y a la memoria.
              p Aunque el kernel, que gobierna todas las celdas, es único, las celdas se pueden ejecutar independientemente o estar conectadas por variables que se representen en diferentes partes del documento. La forma de ejecución que hace Colab es de abajo hacia arriba, y el número que aparece en la parte izquierda hace referencia al orden de ejecución.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/img5.png', style="width: 450px" ,alt='').m-auto
          .row
            .col-lg-6.mb-4.mb-lg-0
              p #[b Versión de Python]
              p Normalmente, un cuaderno en Colab utiliza el kernel con la versión de Python 3, pero si se quiere cambiar la versión de Python a la versión 2, se puede realizar ingresando al menú archivo y nos da la opción en ese apartado.
            .col-lg-6
              figure
                img(src='@/assets/curso/tema1/img6.png', style="width: 450px" ,alt='').m-auto
    .row.justify-content-center
      .col-lg-10
        .row.align-items-center.bg-c2
          .col-md-auto.px-lg-0.pt-4.pt-md-0
            figure
              img(src='@/assets/curso/tema1/img4.svg', style="width: 100px" ,alt='').m-auto
          .col
            .p-4
              p.mb-0 Como se ha visto, gracias a Google Colaboratory, se pueden llevar de manera más sencilla proyectos con esta útil y potente herramienta; estos entornos Colab son muy utilizados por la comunidad de desarrolladores a nivel mundial.
    Separador
    #t_1_1
    .titulo-segundo.color-acento-contenido
      h2 1.1 Listas y estructuras
    .row.align-items-center.mb-4
      .col-lg-8.mb-4.mb-lg-0
        p Python tiene un número considerable de estructuras de datos; es por eso que se dice que las listas no son más que estructuras de datos con unas características especiales, ya que permiten almacenar cualquier tipo de datos en ellas, tales como caracteres, enteros, cadenas.
        p Entonces, una lista es un arreglo donde es posible ingresar cualquier tipo de datos, y estos están indexados para un fácil acceso.
        .row
          .col-12.bg-c3
            .p-4
              .titulo-sexto.color-acento-contenido
                p.mb-0 #[b Figura 1]. Listas
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | print lista[0] # 1
                      | print lista[1] # 2.5
                      | print lista[2] # DevCode
                      | print lista[3] # [5,6]
                      | print lista[3][0] # 5
                      | print lista[3][1] # 6
                      | print lista[1:3] # [2.5, 'DevCode']
                      | print lista[1:6] # [2.5, 'DevCode', [5, 6], 4]
                      | print lista[1:6:2] # [2.5, [5, 6]]

              //figure
                img(src='@/assets/curso/tema1/img8.png', style="width: 450px" ,alt='').m-auto
      .col-lg-4
        figure
          img(src='@/assets/curso/tema1/img7.png', style="width: 450px" ,alt='').m-auto
    p.mb-4 De esta manera, se observa cómo se pueden insertar listas dentro de otra; por eso se dice que una lista no es más que una estructura de datos firme. Para emplear correctamente este tipo de dato, es necesario conocer lo métodos y las diferentes operaciones que con la lista pueden realizar, tal como se presenta en la siguiente imagen:
    .row.justify-content-center.mb-4
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 2]. Ejemplo de lista

          .row.justify-content-center
            .col-auto
              pre
                code.language-python
                  | my_list = [2, 5, 'DevCode', 1.2, 5]

          //figure
            img(src='@/assets/curso/tema1/img9.png', style="width: 450px" ,alt='').m-auto

    p.mb-5 Teniendo en cuenta el ejemplo anterior, a continuación se muestran los métodos que son más importantes y propios de las listas:
    .row.mb-5
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Append()]
              p Permite agregar nuevos elementos a una lista. Se puede agregar cualquier tipo de elemento a una lista, pero si agregamos una lista dentro de otra, simplemente se va a agregar como un solo elemento.
              p Ejemplo de Append
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.append(10) # [2,5,'DevCode',1.2,5,10]
                      | my_list.append([2,5]) # [2,5,'DevCode',1.2,5,[2,5]]
              //figure
                img(src='@/assets/curso/tema1/img10.png', style="width: 450px" ,alt='').m-auto
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Extend()]
              p Este método es importante y se diferencia de append, ya que agrega cualquier elemento tal como listas, pero este método agrega los elementos de una lista como elementos de la lista principal de donde está siendo agregado.
              p Ejemplo de Extend()
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.extend([2,5]) # [2,5,'DevCode',1.2,5,2,5]
              //figure
                img(src='@/assets/curso/tema1/img11.png', style="width: 450px" ,alt='').m-auto
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Remove()]
              p Este método tiene la propiedad de remover. Solo afecta a la lista de donde esté siendo invocado. En la imagen, se observa que se está removiendo el elemento 2 de la lista que tiene como nombre my_list.
              p Ejemplo de Remove()
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.remove(2) # [5, 'DevCode', 1.2, 5]
              //figure
                img(src='@/assets/curso/tema1/img12.png', style="width: 400px" ,alt='').m-auto
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Index()]
              p Este método solo devuelve el número del índice de lo que se le digite como parámetro. En este ejemplo, se está preguntando por el índice de la cadena DevCode en la lista My_list, cuyo resultado es 2.
              p Ejemplo con Index()
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.index('DevCode') # 2
              //figure
                img(src='@/assets/curso/tema1/img13.png', style="width: 300px" ,alt='').m-auto
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Count()]
              p La función de este método es sencilla, solo muestra la cantidad de veces que un elemento de una lista se repite. En el parámetro de este método, se dice que nos muestre cuántas veces aparece el número 5 en la lista my_list. Devuelve 2.
              p Ejemplo de Count()
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.count(5) # 2
              //figure
                img(src='@/assets/curso/tema1/img14.png', style="width: 300px" ,alt='').m-auto
      .col-xl-6
        .row.mx-1.my-3
          .col-12.bg-c4
            .p-4
              p.mb-0 #[b Reverse()]
              p Reorganiza los elementos de una lista, los invierte.
              p Ejemplo de Reverse()
              .row.justify-content-center
                .col-auto
                  pre
                    code.language-python
                      | my_list.reverse() # [5,1.2,'DevCode',5,2]
              //figure
                img(src='@/assets/curso/tema1/img15.png', style="width: 400px" ,alt='').m-auto
    .row.justify-content-center
      .col-lg-10
        .row.align-items-center.bg-c2
          .col-md-auto.px-lg-0.pt-4.pt-md-0
            figure
              img(src='@/assets/curso/tema1/img6.svg', style="width: 120px" ,alt='').m-auto
          .col
            .p-4
              p.mb-0 Se han mencionado los métodos más utilizados en Python, uno de los lenguajes de programación predilectos hoy por hoy por la comunidad desarrolladora del mundo, por su gran versatilidad y facilidad de interpretación, lo que también lo ha llevado a grandes controversias por esta misma comunidad.
    Separador
    #t_1_2
    .titulo-segundo.color-acento-contenido
      h2 1.2 NumPy
    p.mb-5 Como se vio en el anterior ítem, si se va a trabajar con Notebook en Google Colab, se debe saber que NumPy ya está instalado en el mismo.
    .row.justify-content-center.mb-5
      .col-md-7.col-lg-auto.px-0
        figure
          img(src='@/assets/curso/tema1/img16.png', style="width: 440px" ,alt='').m-auto
      .col-md-7.col-lg-6.bg-c5
        .p-4
          p.mb-0 Según NumPy v1.19 Manual (2022), NumPy es el paquete fundamental para la computación científica en Python. Es una biblioteca de Python que proporciona un objeto de matriz multidimensional, varios objetos derivados (como matrices y matrices enmascaradas) y una variedad de rutinas para operaciones rápidas en matrices, que incluyen manipulación matemática, lógica de formas, clasificación, selección, E/S, transformadas discretas de Fourier, álgebra lineal básica, operaciones estadísticas básicas, simulación aleatoria y mucho más.
    p.mb-5 Con base en este concepto, NumPy es imprescindible para la predicción. En el campo de los datos o ciencia de datos, circulan en las redes millones de datos todos los días, por eso, herramientas como esta se vuelven cada vez más importantes para ayudar a los desarrolladores o a los científicos de datos a tomar lo más relevante de ellos y convertirlo en información útil, que permita una predicción exacta.
    .row.justify-content-center.mb-5
      .col-lg-10
        .row
          .col-12.bg-c6
            .p-4
              p.mb-0 NumPy es una poderosa herramienta que no solamente es utilizada en la parte científica, sino como una recolectora de grandes flujos de datos, y gracias a eso, se puede conectar con múltiples bases de datos, un punto más a su favor, que la hacen más atractiva; de hecho, hay librerías, como Pandas, que están construidas sobre NumPy. Una de sus principales características es el manejo rápido de datos y el manejo de estructuras, que lo denominan por medio de arrays o arreglos, lo que en Python se llaman listas, pero opera los datos de una manera más ligera y eficiente.
    p.mb-5 La forma de almacenar los datos en NumPy es por medio de arreglos, lo que en Python son listas. La diferencia es que NumPy lo hace de una manera más rápida; el método invocado para la asignación de estos dato es array(), perteneciente a la librería NumPy. De esa manera, es posible ver, a continuación, cómo se estructura un arreglo en NumPy:
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 3]. Arreglo en NumPy
          .row.justify-content-center
            .col-auto
              pre
                code.language-python
                  | import numpy as np
                  |
                  | sample_list = [1, 2, 3]
                  |
                  | np.array(sample_list)
          //figure
            img(src='@/assets/curso/tema1/img17.png', style="width: 250px" ,alt='').m-auto
    p El resultado de la última línea de código será algo como #[b array&lpar;&lsqb;1,2,3&rsqb;&rpar;]. NumPy tiene dos tipos de arreglos que son: matrices y vectores.
    p.mb-5 Los vectores son sencillos y son arreglos unidimensionales que manejan una sintaxis sencilla, como la que se muestra en la siguiente figura.
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 4]. Vectores
          .row.justify-content-center
            .col-auto
              pre
                code.language-python
                  | my_vector = np.array(['este', 'es', 'un', 'vector'])
          //figure
            img(src='@/assets/curso/tema1/img18.png', style="width: 390px" ,alt='').m-auto
    p.mb-5 Las matrices son unos arreglos bidimensionales y su sintaxis es un poco más compleja; sin embargo, su sintaxis se realiza invocando el método np.array(), como se ve a continuación
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 5]. Matrices

          .row.justify-content-center
            .col-auto
              pre
                code.language-python
                  | my_matrix = [[1,2,3],[4,5,6],[7,8,9]]
                  | np.array(my_matrix)
          //figure
            img(src='@/assets/curso/tema1/img19.png', style="width: 390px" ,alt='').m-auto
    p Los arreglos de NumPy se pueden expandir para trabajar con matrices de uno, dos o más dimensiones; las operaciones que se pueden hacer con esta librería son extensas y es por eso que se mostrarán algunas de las más utilizadas, para ver cómo es el trabajo y la sintaxis correcta utilizando NumPy. Es común que las listas de Python tengan gran similitud con los arreglos de NumPy, pero su gran diferencia radica en que son más rápidos, menos pesados y permiten generar arrays n-dimensionales.
    p.mb-5 Los arrays pueden variar en sus presentaciones unidimensional o vector, bidimensional o matriz y tensor.
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 6]. Tensor
          .row.justify-content-center
            .col-auto
              figure
                img(src='@/assets/curso/tema1/img20.png', style="width: 490px" ,alt='').m-auto
                figcaption Nota. Tomado de Kumar (2020).
    p.mb-5 Para crear un array con NumPy, se puede lograr a través de una lista o con una lista de listas, y la sintaxis para crearlo es np.array(My_list), y de la misma forma que las listas, es posible acceder a un valor por medio de los índices.
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 7]. Array
          figure
            img(src='@/assets/curso/tema1/img21.png', style="width: 450px" ,alt='').m-auto
    p.mb-5 Utilizando los conceptos anteriores, cuando se trabaja con Google Colab, es posible dibujar una gráfica invocando las librerías Matplotlib y NumPy, con el código que se aprecia a continuación:
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 8]. Dibujando una gráfica
          figure
            img(src='@/assets/curso/tema1/img22.png', style="width: 650px" ,alt='').m-auto
    p.mb-5 De igual forma, también se puede trazar gráficas fácilmente con Python al tener las herramientas correctas e invocando las librerías correspondientes. La siguiente es otra gráfica, la cual se obtiene con Matplotlib y NumPy:
    .row.justify-content-center
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 9]. Dibujando una gráfica
          figure
            img(src='@/assets/curso/tema1/img23.png', style="width: 550px" ,alt='').m-auto
    Separador
    #t_1_3
    .titulo-segundo.color-acento-contenido
      h2 1.3 Condicionales y panda
    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img24.png', style="width: 450px" ,alt='').m-auto
      .col-lg-8
        p Según Datacarpentry.org (2001), “Un DataFrame es una estructura de datos con dos dimensiones, en la cual se pueden guardar datos de distintos tipos (como caracteres, enteros, valores de punto flotante, factores y más) en columnas”.
        p Es similar a una hoja de cálculo o una tabla de SQL, o el data.frame de R. Un DataFrame siempre tiene un índice (con inicio en 0). El índice refiere a la posición de un elemento en la estructura de datos. Resulta un poco complicado hablar de Pandas y sus condicionales sin antes hablar un poco de lo que es un Dataframe. Sin más preámbulos, un Dataframe es un marco de trabajo, donde se estipulan unos parámetros para poder ingresar los datos y estos, a su vez, ser representados con estilo. Estos datos son etiquetados, tanto en filas como en columnas.
        p.mb-0 A continuación se expone cómo es posible realizar lo indicado:
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/dkUlltYfeMo?si=JFNwLGKWFCpmfuIf" title="Condicionales y Pandas" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Condicionales y Pandas
    Separador
    #t_1_4
    .titulo-segundo.color-acento-contenido
      h2 1.4 Funciones y paquetes
    p Los paquetes son partes de código que aumentan la operabilidad de Python. Un paquete se ve como una carpeta con varios contenidos entre archivos y carpetas con sus respectivas extensiones Python (.py); la utilidad de los paquetes en la ciencia de datos es la facilidad de reutilizar código, permitiendo usar clases y objetos, que fácilmente pueden ser usados por otros módulos, y organizarlos de una mejor manera en namespaces.
    p.mb-5 Se demuestra esto a través del siguiente ejemplo:
    .row
      .col-lg-6
        .row.mx-1.my-3
          .col-12.bg-c7
            .p-4
              .row.align-items-center.mb-4
                .col-auto.px-0
                  figure
                    img(src='@/assets/curso/tema1/img7.svg', style="width: 40px" ,alt='').m-auto
                .col
                  p.mb-0 #[b Se podría definir un módulo de operaciones (.py) con las funciones de suma() y resta().]
              figure
                img(src='@/assets/curso/tema1/img25.png', style="width: 450px" ,alt='').m-auto
      .col-lg-6
        .row.mx-1.my-3
          .col-12.bg-c7
            .p-4
              .row.align-items-center.mb-4
                .col-auto.px-0
                  figure
                    img(src='@/assets/curso/tema1/img8.svg', style="width: 40px" ,alt='').m-auto
                .col
                  p.mb-0 #[b Una vez se haya definido ese módulo, se puede importar en otro archivo utilizando import, e importar lo que contenga.]
              figure
                img(src='@/assets/curso/tema1/img26.png', style="width: 450px" ,alt='').m-auto
      .col-lg-6
        .row.mx-1.my-3
          .col-12.bg-c7
            .p-4
              .row.align-items-center.mb-4
                .col-auto.px-0
                  figure
                    img(src='@/assets/curso/tema1/img9.svg', style="width: 40px" ,alt='').m-auto
                .col
                  p.mb-0 #[b Ahora bien, si se prefiere, se pueden importar los módulos de interés.]
              figure
                img(src='@/assets/curso/tema1/img27.png', style="width: 450px" ,alt='').m-auto
      .col-lg-6
        .row.mx-1.my-3
          .col-12.bg-c7
            .p-4
              .row.align-items-center.mb-4
                .col-auto.px-0
                  figure
                    img(src='@/assets/curso/tema1/img10.svg', style="width: 40px" ,alt='').m-auto
                .col
                  p.mb-0 #[b También, se puede importar todo el módulo utilizando “*” y no mimodulo.*. De esta forma, se pueden agrupar funciones en paquetes y que estos puedan ser utilizados por otros módulos.]
              figure
                img(src='@/assets/curso/tema1/img28.png', style="width: 450px" ,alt='').m-auto
    Separador
    #t_1_5
    .titulo-segundo.color-acento-contenido
      h2 1.5 Visualización y #[i analytics]
    .row.align-items-center.mb-4
      .col-lg-5.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img29.png', style="width: 450px" ,alt='').m-auto
      .col-lg-7
        p La presentación de los datos no es algo que toque dejar pasar por desapercibido, ya que la parte visual ayuda, en gran medida, a una buena interpretación de estos, realizando grandes esfuerzos también para poder llevar a cabo una buena depuración e integración, que si no se hace de manera correcta, el usuario no va a estar contento con la interpretación o simplemente no va a entender lo que se quiere orientar; de ahí parte la importancia de la visualización analítica de los datos.
        .row.bg-c2
          .col-auto.px-0
            figure
              img(src='@/assets/curso/tema1/img11.svg', style="width: 70px" ,alt='').m-auto
          .col
            .row
              .col-12
                .p-4
                  p.mb-0 La visualización de la información tiene tres componentes inexorables para poder concluir con éxito un análisis, los cuales son narrativa, diseño y estadística; estas tres etapas deben ir de la mano para poder dar una buena orientación a la hora de plasmar visualmente y no perderse en el intento.
    p.mb-5 Una excelente interpretación visual debe tener los siguientes ingredientes:
    .row.justify-content-center.mb-5
      .col-lg-10.bg-c8
        .p-4
          ul.lista-ul.mb-0
            li.mb-0
              i.lista-ul__vineta
              | #[b Identificar relaciones, las sentencias y los patrones.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Inspeccionar datos para deducir nuevas tendencias o conocimientos.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Mejorar el entendimiento de una idea o tendencia.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Interpretar de manera concreta la observación de evidencias reales y su variabilidad en el tiempo.]
            li.mb-0
              i.lista-ul__vineta
              | #[b Posibilitar retener una idea.]
    p Los anteriores tips son los necesarios a tener presente a la hora de realizar una visualización precisa de lo que se quiere realmente mostrarle al cliente y que este interprete de manera eficaz.
    p Es importante determinar que para analizar datos tubulares en Python se debe hacer uso de las librerías de análisis de datos denominadas Pandas, las cuales generan gráficos de alta calidad con Matplotlib; adicionalmente, se asocian con bibliotecas que usan arrays de NumPy, que, como se sabe, es otra biblioteca de Python.
    p.mb-5 Al trabajar con Python, este no carga las bibliotecas, este proceso toca hacerlo con el enunciado import, para acceder a las funciones de la biblioteca; la sintaxis es la siguiente: import nombredelabiblioteca; además de eso, se le puede agregar una abreviación para no digitar los comandos con nombres extensos, de la siguiente manera, as abreviación.
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 10]. Sintaxis
          figure
            img(src='@/assets/curso/tema1/img30.png', style="width: 280px" ,alt='').m-auto
    p.mb-5 Los Dataframe juegan una importante función en la lectura de datos y, sobre todo, en la selección de los mismos. Cuando se tenga el archivo con la información que se desea tomar lectura, de extensión .CSV, que es la extensión para abrir directamente desde un Dataframe, se realiza de la siguiente manera:
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 11]. Dataframe
          figure
            img(src='@/assets/curso/tema1/img31.png', style="width: 550px" ,alt='').m-auto
    p.mb-5 En cuanto a la visualización de datos, después de introducir parámetros según el requerimiento o los datos que son objeto de proyección, aquí se visualizan mediante la librería plotnine:
    .row.justify-content-center.mb-5
      .col-10.bg-c3
        .p-4
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 12]. Visualización mediante plotnine
          figure
            img(src='@/assets/curso/tema1/img32.png', style="width: 850px" ,alt='').m-auto
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario1.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/img13.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Gráficos con plotnine
                  p.text-small Para ampliar el conocimiento, se sugiere ingresar al siguiente enlace, el cual contiene ejercicios e información de valor sobre analítica de datos.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(href="https://datacarpentry.org/python-ecology-lesson-es/07-visualization-ggplot-python.html" target="_blank")
                    span(style="color: #12263F !important") Visitar enlace
                    i.fas.fa-link(style="color: #12263F !important")

</template>

<script>
import Prism from 'prismjs'
import 'prismjs/components/prism-python'
import 'prismjs/themes/prism-okaidia.css'
export default {
  name: 'Tema1',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
    window.Prism = window.Prism || {}
    window.Prism.manual = true
    Prism.highlightAll()
  },
  updated() {
    this.$aosRefresh()
    window.Prism = window.Prism || {}
    window.Prism.manual = true
    Prism.highlightAll()
  },
}
</script>
<style lang="sass"></style>
