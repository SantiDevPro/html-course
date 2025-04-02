# **HTML AVANZADO** 🌐

Bienvenido a la guía de **HTML Avanzado**. Este documento está diseñado para ayudarte a profundizar en conceptos avanzados de HTML, con explicaciones claras y ejemplos prácticos. Ideal para quienes ya tienen conocimientos básicos y desean llevar sus habilidades al siguiente nivel.

---

## _📌 COMENTARIOS E ICONOS_

| Elemento                                                 | Descripción                           |
| -------------------------------------------------------- | ------------------------------------- |
| `<!--  -->`                                              | Define comentarios en el código HTML. |
| `<link rel=icon href=url-de-icono type=tipo-de-imagen >` | Define el ícono de un sitio web.      |

## _⚙ METATAGS_

- `meta` proporciona metadatos sobre la página web
- Por ejemplo descripción, palabras clave, autor, codificación de caracteres, etc.
- No se muestran en la página, pero son útiles para navegadores y motores de búsqueda.

### Ejemplo:

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

> **Nota:** El atributo `viewport` es esencial para que las páginas sean responsivas en dispositivos móviles.

## _📄 TEXTAREA Y LABELS_

| Etiqueta   | Descripción                                                                                    |
| ---------- | ---------------------------------------------------------------------------------------------- |
| `textarea` | Permite ingresar texto en varias líneas dentro de un formulario.                               |
| `label`    | Proporciona una descripción o leyenda para un campo de formulario, mejorando la accesibilidad. |

### Ejemplo:

```html
<form>
  <label for="coment">Dejanos tu comentario:</label>
  <textarea
    id="coment"
    cols="30"
    rows="10"
    placeholder="Escribe aquí"
  ></textarea>
  <button type="submit">Enviar</button>
</form>
```

## _📁 SELECT, DATALIST Y OPTION_

| Etiqueta   | Descripción                                                                       |
| ---------- | --------------------------------------------------------------------------------- |
| `select`   | Crea un menú desplegable que permite al usuario seleccionar una opción.           |
| `datalist` | Proporciona una lista de opciones sugeridas para un campo de entrada (`<input>`). |
| `option`   | Define una opción dentro de un elemento `<select>` o `<datalist>`.                |

### Ejemplo:

```html
<select name="fruta">
  <option value="manzana">Manzana</option>
  <option value="uva">Uva</option>
  <option value="papaya">Papaya</option>
</select>
<input list="bebidas" id="bebida" />
<datalist id="bebidas">
  <option value="chicha morada"></option>
  <option value="maracuyá"></option>
  <option value="limonada"></option>
</datalist>
```

## _📍 FIELDSET Y LEGEND_

| Etiqueta   | Descripción                                                                            |
| ---------- | -------------------------------------------------------------------------------------- |
| `fieldset` | Agrupa elementos relacionados en un formulario, creando contenedor visual y semántico. |
| `legend`   | Proporciona una etiqueta descriptiva para un `<fieldset>`.                             |

### Ejemplo:

```html
<form>
  <fieldset>
    <legend>Datos Personales</legend>
    <input type="text" name="nombre" />
    <input type="number" name="edad" />
  </fieldset>
  <fieldset>
    <legend>Datos Adicionales</legend>
    <input type="email" name="correo" />
    <input type="number" name="movil" />
  </fieldset>
</form>
```

## _🔍 DETAILS Y SUMMARY_

| Etiqueta  | Descripción                                                                          |
| --------- | ------------------------------------------------------------------------------------ |
| `details` | Crea un contenido desplegable o colapsable que puede contener información adicional. |
| `summary` | Proporciona un encabezado o título para el contenido dentro de `<details>`.          |

### Ejemplo:

```html
<details>
  <summary>Perro</summary>
  <p>El mejor amigo del hombre.</p>
</details>
```

## _🔗 ENLACES (avanzado)_

| Elemento                             | Descripción                                                                                  |
| ------------------------------------ | -------------------------------------------------------------------------------------------- |
| `Enlaces con atributo ID`            | Crea un enlace a un elemento específico dentro de la misma página usando el atributo `id`.   |
| `download`                           | Indica que el recurso enlazado debe descargarse en lugar de abrirse.                         |
| `rel="noopener"`                     | Evita que la página enlazada acceda al contexto de la página actual, mejorando la seguridad. |
| `rel="noreferrer"`                   | Evita que se envíe el encabezado "Referer" al sitio enlazado, protegiendo la privacidad.     |
| `rel="nofollow"`                     | Indica a los motores de búsqueda que no sigan el enlace ni transfieran autoridad.            |
| `href="mailto:gavdia1302@gmail.com"` | Abre el cliente de correo predeterminado para enviar un correo a la dirección especificada.  |
| `href="tel:+51987654321"`            | Permite realizar una llamada telefónica al número especificado (en dispositivos móviles).    |

## _📈 TABLAS_

| Etiqueta  | Descripción                                         |
| --------- | --------------------------------------------------- |
| `table`   | Define una tabla en HTML.                           |
| `tr`      | Representa una fila dentro de una tabla.            |
| `th`      | Define una celda de encabezado dentro de una tabla. |
| `td`      | Define una celda de datos dentro de una tabla.      |
| `caption` | Proporciona un título o leyenda para una tabla.     |
| `thead`   | Agrupa las filas de encabezado de una tabla.        |
| `tbody`   | Agrupa las filas del cuerpo de una tabla.           |
| `tfoot`   | Agrupa las filas del pie de una tabla.              |

### Ejemplo:

```html
<table>
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Edad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Hugo</td>
      <td>Lee</td>
    </tr>
  </tbody>
</table>
```

## _🔈 AUDIO Y VIDEO_

| Etiqueta | Descripción                                             |
| -------- | ------------------------------------------------------- |
| `audio`  | Permite reproducir archivos de audio en una página web. |
| `video`  | Permite reproducir archivos de video en una página web. |

### Ejemplo:

```html
<audio src="/media/cm-intro.mp3" controls autoplay muted></audio>
<video src="/media/html-video.mp4" controls autoplay muted loop>
  Tu navegador no soporta video
</video>
```

## _💡 LAZY LOADING_

- `lazy loading` | Técnica para retrasar la carga de recursos no esenciales (como imágenes o videos) hasta que sean necesarios.

- `loading="lazy"` | Atributo que indica que un recurso (como una imagen) debe cargarse de forma diferida.

## _❌ HTML OBSOLETO_

| Etiqueta | Descripción                                                |
| -------- | ---------------------------------------------------------- |
| `font`   | Cambiaba el estilo del texto (color, tamaño, etc.).        |
| `center` | Centraba el contenido.                                     |
| `blink`  | Hacía que el texto parpadeara.                             |
| `big`    | Aumentaba el tamaño del texto.                             |
| `strike` | Aplicaba un tachado al texto.                              |
| `tt`     | Mostraba texto en una fuente monoespaciada.                |
| `u`      | Subrayaba el texto.                                        |
| `b`      | Aplicaba negrita al texto. Ahora reemplazado por <strong>. |

## _✔ HTML SEMANTICO_

| Etiqueta  | Descripción                                                              |
| --------- | ------------------------------------------------------------------------ |
| `header`  | Define la cabecera de un documento o sección.                            |
| `main`    | Define el contenido principal de un documento.                           |
| `footer`  | Define el pie de página de un documento o sección.                       |
| `nav`     | Define una sección de navegación.                                        |
| `section` | Define una sección genérica en un documento.                             |
| `article` | Define contenido independiente, como un artículo o post de blog.         |
| `aside`   | Define contenido relacionado, como barras laterales o notas adicionales. |

## _👨‍🦯 ACCESIBILIDAD WEB_

- Práctica de diseñar sitios web para que sean utilizables por todas las personas, incluidas aquellas con discapacidades. Implica garantizar que el contenido sea perceptible, operable, comprensible y robusto.

---
