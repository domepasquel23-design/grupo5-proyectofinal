# Desarrollo del proyetco final

# Integrantes:
# Domenica Pasquel
# Santiago Sulca

# Descripción

Este proyecto consiste en una página web desarrollada utilizando HTML5 y CSS3.

El objetivo es aplicar conceptos de estructura semántica, accesibilidad, tablas, formularios, CSS Grid y diseño responsive.

## Instrucciones de uso

1. Descargar o clonar el proyecto.
2. Abrir la carpeta del proyecto.
3. Abrir el archivo "index.html" y revisar el codigo en html y css.
4. En Visual Studio Code usar la extensión Live Server para visualizar la página.

# Árbol de archivos

proyecto/
│
├── index.html
├── style.css
├── README.md
└── .gitignore


# Guía de usuario

Al ingresar a la página se muestra un encabezado con el título principal y un menú de navegación.

El usuario puede acceder a las diferentes secciones:

* Inicio
* Productos
* Galería
* Acerca de
* Contacto

En la sección Productos se encuentra una tabla con información ficticia.

En la sección Galería se muestran cuatro elementos organizados mediante CSS Grid.

La sección Acerca de contiene información sobre el proyecto.

Finalmente, la sección Contacto contiene un formulario donde el usuario puede ingresar su nombre, correo electrónico y mensaje.

La página también está adaptada para dispositivos móviles mediante media queries.

# Accesibilidad

Para mejorar la accesibilidad del proyecto se utilizaron etiquetas HTML semánticas como:

* `header`
* `nav`
* `main`
* `section`
* `footer`

También se agregaron atributos `alt` a las imágenes y etiquetas `label` asociadas correctamente con los campos del formulario.

La estructura de encabezados sigue un orden lógico:

```text
h1
 ├── h2
 │    └── h3
 ├── h2
 ├── h2
 └── h2
```

## Validación

El código HTML y CSS fue revisado utilizando los validadores oficiales de W3C.

Se corrigieron errores y advertencias encontradas durante el proceso de validación.

## Reflexión colaborativa

Durante el desarrollo del proyecto aprendimos la importancia de trabajar de manera organizada y colaborativa.

La construcción de la página permitió aplicar conocimientos de HTML y CSS de una manera práctica. Al principio, la estructura de la página era sencilla, pero progresivamente se fueron incorporando nuevas secciones como la tabla, la galería, el formulario y la sección Acerca de.

Uno de los aspectos más importantes fue comprender la utilidad de HTML semántico. Utilizar etiquetas como `header`, `nav`, `main`, `section` y `footer` permite organizar mejor el contenido y facilita que otras personas y herramientas puedan comprender la estructura de la página.

También aprendimos la importancia de la accesibilidad. Agregar textos alternativos a las imágenes y utilizar correctamente las etiquetas `label` permite que la página pueda ser utilizada por una mayor cantidad de personas.

Otro aprendizaje importante fue el diseño responsive. Mediante CSS Grid y media queries conseguimos que la página pueda adaptarse a diferentes tamaños de pantalla, especialmente a dispositivos móviles.

El trabajo colaborativo también permitió identificar errores que individualmente podrían haber pasado desapercibidos. Revisar el código entre los integrantes ayudó a mejorar la estructura, corregir problemas de estilos y comprender mejor el funcionamiento de HTML y CSS.

Finalmente, la validación mediante W3C permitió comprobar que el código cumpliera con estándares web y ayudó a detectar errores que no siempre son visibles directamente en el navegador.

En conclusión, este proyecto permitió reforzar los conocimientos técnicos y, al mismo tiempo, desarrollar habilidades de organización, revisión de código y trabajo colaborativo.