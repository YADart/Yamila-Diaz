# Template Lens

Por [FWebistes](productions.github.io)

## Instrucciones del sitio

Para agregar imagenes al sitio, entrar al [directorio de imagenes](./images) y dentro de este directorio se encuentran dos directorios mas, [fulls](./images/fulls) y [thumbs](./images/thumbs).

### Fulls

Fulls son las imagenes grandes que se ven al elegir una imagen. Las imagenes pueden tener un titulo, y este titulo seria el nombre de la imagen, puede desactivarse si se desea.

**Es muy importante que las imagenes tengan solo letras y numeros**, y, si se desea aunque no es muy recomendado, que contengan espacios.

Estas ocupan gran parte del sitio y se les aplica un zoom para que ocupen todo el ancho de su espacio, por ende si la imagen es alta, y no ancha, se va a ver solo una parte porque se va a aplicar un zoom. Es recomendable que estas imagenes tengan un tamaño de [aspecto de 16 : 9](https://pacoup.com/2011/06/12/list-of-true-169-resolutions/) (el link prove todas las opciones disponibles), pero el tamaño ideal seria **que la imagen sea 1920 pixeles de ancho y 1080 pixeles de alto**.

Un ejemplo, digamos que tenemos esta imagen:

![ejemplo](./readmeFiles/ejemplo.jpg)

Si subimos esta imagen, la cual es alta y no ancha, el sitio la modificaria para que se vea asi:

![alta](./readmeFiles/alta.jpg)

Lo correcto, para evitar eso, seria aplicar una edicion, para que se vea ancha, por ejemplo realizar algo asi:

![barco](./readmeFiles/barco.jpg)

Y en el sitio se veria asi:

![formateada](./readmeFiles/formateada.jpg)

### Thumbs

Los thumbs son un detalle muy importante. Son las miniaturas de las imagenes que se usan para mostrar las mismas al costado, si estas imagenes no son agregadas, se usan las imagenes grandes automaticamente, pero esto hace que el sitio tarde mucho mas en cargar (y si tarda mucho la gente puede irse antes de que termine) asi que es muy recomendado usar miniaturas para hacer que la carga sea muchisimo mas rapida.

Los requisitos para que los thumbs anden correctamente son los siguientes:
- Tienen que estar en la carpeta [thumbs](./images/thumbs).
- Tienen que tener **el mismo nombre que la imagen grande**, mismos caracteres y mayusculas.
- Tienen que tener todas el mismo tamaño, en lo posible 360 alto x 225 ancho, ya que las mismas son modificadas para que ocupen ese tamaño en una grilla, y si no tienen ese tamaño van a deformarse.

---

En caso de tener dudas, no duden en consultarme.