# **HTML AVANZADO**

---

## _COMENTARIOS E ICONOS_

- `<!--  -->` | usado para comentarios, forma de dejar notas o instrucciones a otros desarrolladores que vean el codigo. El navegador los ignora haciendo que no se renderice
- `<link rel=icon href=url-de-icono type=tipo-de-imagen >` | forma para personalizar el icono de un sitio web

## _METATAGS_

- Son elementos HTML que proporcionan información sobre una página web
- Se utilizan principalmente para especificar metadatos, como el título de la página, la descripción, palabras clave, autor, y la codificación de caracteres, entre otros, que son importantes para los motores de búsqueda y para mejorar la experiencia del usuario
- Los metatags no se muestran en la página web, pero son utilizados por los navegadores web y los motores de búsqueda para entender y clasificar el contenido de la página.

## _TEXTAREA Y LABELS_

- `textarea` | elemento que permite ingresar texto multilínea en un formulario web. Se utiliza para recopilar información extensa, como comentarios, mensajes largos o cualquier otro tipo de entrada de texto que requiera más espacio que un campo de entrada de texto estándar

- `label` | elemento que se utiliza para asociar texto descriptivo con un elemento de formulario, como un input, textarea o select. Proporciona una etiqueta legible por humanos que describe el propósito del campo de entrada, lo que mejora la accesibilidad y la usabilidad del formulario al proporcionar una referencia visual clara para los usuarios

## _SELECT, DATALIST Y OPTION_

- `select` | crea un menú desplegable que permite al usuario seleccionar una opción de una lista predefinida

- `datalist` | proporciona una lista de opciones sugeridas para un input, permitiendo al usuario seleccionar una de ella o ingresar su propia entrada

- `option` | define una opción dentro de un elemento _`select`_ o _`datalist`_, representando un elemento seleccionable por el usuario dentro de una lista desplegable

## _FIELDSET Y LEGEND_

- `fieldset` | se utiliza para agrupar elementos relacionados en un formulario y crear un contenedor visual y semántico para ellos

- `legend` | proporciona una etiqueta descriptiva para el contenido de un _`fieldset`_, explicando el propósito o la naturaleza del grupo de elementos dentro de ese fieldset

## _DETAILS Y SUMMARY_

- `details` | se usa para crear un contenido desplegable o colapsable en una página web, que puede contener información adicional que puede estar oculta inicialmente

- `summary` | se usa dentro de un _`details`_ y proporciona un encabezado o título para el contenido desplegable, que actúa como un control para abrir o cerrar el contenido

## _ENLACES (avanzado)_

- `Enlaces con atributo ID` | se utiliza para crear un vínculo a un elemento específico dentro de la misma página web. Esto se logra utilizando el valor del atributo id como destino del enlace. Cuando se hace clic en el enlace, el navegador se desplaza automáticamente hasta el elemento con el id correspondiente

- `download` | atributo que indica al navegador que el recurso al que apunta el enlace debe descargarse en lugar de mostrarse en el navegador. Cuando se utiliza este atributo, el navegador iniciará automáticamente la descarga del archivo al hacer clic en el enlace

- `rel="noopener"` | es una medida de seguridad que se utiliza para evitar que la página vinculada tenga acceso al contexto de la página que contiene el enlace. Ayuda a prevenir ataques de seguridad como el robo de sesión y la manipulación del historial del navegador

- `rel="noreferrer"` | indica al navegador que no debe enviar el encabezado "Referer" al abrir la página vinculada. Esto ayuda a proteger la privacidad del usuario al evitar que el sitio vinculado pueda rastrear la fuente del tráfico

- `rel="nofollow"` | indica a los motores de búsqueda que no sigan el enlace y no pasen autoridad de la página actual a la página vinculada. Se utiliza para evitar que el enlace afecte el ranking de la página en los resultados de búsqueda y para desalentar el spam de comentarios en los blogs y otros sitios web

- `href="mailto:gavdia1302@gmail.com"` | usado para enviar mensajes de correo a una direccion especifica, te abre tu correo y te posiciona para enviar mensajes de correo a la direccion indicada

- `href="tel:+51987654321"` | usado para directamente realizar una llamada al número indicado si estuvieras en un movil

## _TABLAS_

- `table` | elemento para empezar a crear una tabla

- `tr` | elemento que representa una fila en una tabla

- `th` | elemento que representa una celda de encabezado en una tabla

- `td` | elemento que representa una celda de datos en una tabla

- `caption` | elemento que proporciona un título o leyenda a una tabla

- `thead` | elemento que representa la sección de encabezado de una tabla

- `tbody` | elemento que representa la sección del cuerpo de una tabla

- `tfoot` | elemento que representa la sección del pie de una tabla

## _AUDIO Y VIDEO_

- `audio` | elemento que permite la reproducción de audio en una página web

- `video` | elemento que permite la reproducción de video en una página web

## _LAZY LOADING_

- `lazy loading` | es una técnica utilizada en desarrollo web para retrasar la carga de recursos no esenciales, como imágenes, scripts o iframes, hasta que sean necesarios. Esto ayuda a mejorar el rendimiento de la página al reducir el tiempo de carga inicial y la cantidad de datos transferidos, especialmente en páginas con mucho contenido multimedia

- `loading="lazy"` | es un atributo usado en elementos como `<img>` y `<iframe>` para especificar que los recursos asociados deben cargarse de forma diferida o perezosa. Esto significa que el navegador retrasará la carga de estos recursos hasta que estén cerca de entrar en la ventana de visualización del usuario, lo que ayuda a mejorar el rendimiento de la página al reducir la carga inicial y la carga de datos innecesarios

## _HTML OBSOLETO_

- **font**
- **center**
- **blink**
- **big**
- **strike**
- **tt**
- **u**
- **b**

## _HTML SEMANTICO_

- `header` | define la cabecera de un documento o sección

- `main` | define el contenido principal o central de un documento

- `footer` | define el pie de página de un documento o sección

- `nav` | define una sección de navegación

- `section` | define una sección genérica en un documento

- `article` | define un contenido independiente y autónomo, como un artículo, un post de blog, etc

- `aside` | define contenido que está relacionado con el contenido circundante, como barras laterales o notas adicionales

## _ACCESIBILIDAD WEB_

- Se refiere a la práctica de diseñar y desarrollar sitios web y aplicaciones de manera que sean accesibles y utilizables por todas las personas, incluidas aquellas con discapacidades

- Esto implica garantizar que el contenido sea perceptible, operable, comprensible y robusto para una amplia gama de usuarios, independientemente de sus habilidades o limitaciones físicas, cognitivas o sensoriales

---
