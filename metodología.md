# Pero... ¿Cómo hemos hecho todo esto?

![metodologia-estrategia-contenidos-coronavirus](https://user-images.githubusercontent.com/90325917/145499554-cbe8bdf3-1e19-467a-a47a-f1f059a8f9f8.jpg)

### No ha sido sencillo ni mucho menos, pero aquí podrás leer un resúmen de la metodología:

- En primer lugar me he asegurado de tener en mi *tree* los elementos necesarios.
- He traspasado bootstrap-min.css y sticky-footer-navbar.css dentro de mi carpeta css.
- Además hemos introducido js bootstrap.bundle.min.js dentro de la carpeta js.
- Mientras tanto, me he creado los siguientes archivos en lenguaje *markdown* desde **Github**:
  - **inicio.md**
  - **metodología.md**
- Por otro lado, he ido convirtiendo a través de la herramienta **Pandoc** el lenguaje a *html5*.
- Me he creado colateralmente los siguientes documentos en lenguaje html:
  - **inicio.html**
  - **metodología.html**
- A través del *index.html* me he creado con el comando **cp** varias copias:
  - **cabecera.html**
  - **pie.html**
- Entre todos estos procesos iniciales también hemos convertido el lenguaje markdown de las cuatro prácticas iniciales a html:
  - **practica1.html**
  - **practica2.html**
  - **practica3.html**
  - **practica4.html**
- Para que finalmente al utilizar el comando *cat*, juntemos cabecera, práctica y pie.
  - **practica1final.html**
  - **practica2final.html**
  - **practica3final.html**
  - **practica4final.html**
- Respecto a los detalles, he modificado el *title* del index.html a **Mipágina web | Gonzalo**
- En *Fixed navbar*, hemos hecho varios procedimientos:
  - Primero hemos cambiado los nombres de la cabecera, creando espacio para dos clases más y borrando una de faceta invisible.
  - En segundo lugar hemos cambiado el nombre a Práctica 1, 2, 3 y 4 y hemos adjuntado su html delante para correlacionarlo.
    - *Lo mismo ha ocurrido con este mismo documento!!*
  
