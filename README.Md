# Panel de administracion y tablas 
## por: Arnaldo 

## archivo admin.html
Formulario
Tabla de libros
Tabla de solicitudes


## archivo boton.js
FUNCIÓN EDITAR

FUNCIÓN GUARDAR CAMBIOS

FUNCIÓN CANCELAR

FUNCIÓN ELIMINAR

FUNCIÓN PARA AGREGAR LIBROS
Obtener los datos del formulario
Crear una nueva fila
Crear las celdas
Mostrar la portada
Mostrar información
Crear botón editar
Crear botón eliminar
Limpiar formulario

FUNCIÓN PARA AGREGAR LIBROS
Obtener los datos del formulario
Crear una nueva fila
Crear las celdas
Mostrar la portada
Mostrar información
Crear botón editar
Crear botón eliminar
Limpiar formulario


Para exponer tu parte de **BiblioWeb – Panel de Administración**, te recomiendo utilizar términos técnicos de desarrollo web, pero acompañarlos de explicaciones sencillas. Así demuestras que entiendes lo que construiste y no solamente que copiaste el código.

Te dejo las ideas más importantes que puedes mencionar.

# 1. ¿Cuál es la función de mi módulo?

Puedes comenzar explicando:

> Mi responsabilidad dentro del proyecto es el desarrollo del panel de administración, una interfaz que permite visualizar y organizar la información relacionada con los libros registrados en la plataforma y las solicitudes recibidas de los usuarios.

**Palabras técnicas que puedes utilizar:**
- **Interfaz administrativa:** espacio desde el cual se organiza y consulta información.
- **Gestión de información:** organización y visualización de los datos.
- **Estructura HTML:** organización de los elementos que componen la página.
- **Diseño responsivo:** adaptación de la página a diferentes tamaños de pantalla.

# 2. Formulario de registro de libros

En esta sección puedes explicar que desarrollaste un formulario para representar el ingreso de nuevos libros al sistema.

Los campos que contiene son:

- Título.
- Autor.
- Portada (URL).
- Descripción.
- Categoría.

**Frases que puedes mencionar:**

- «El formulario permite estructurar los datos necesarios para registrar un libro».
- «Utilicé etiquetas HTML para identificar cada campo de información».
- «Los campos de entrada permiten representar la captura de datos por parte del administrador».

**Términos técnicos importantes:**

| Código | Función |
|---|---|
| `<form>` | Estructura el formulario. |
| `<label>` | Identifica cada campo. |
| `<input>` | Permite ingresar información. |
| `<textarea>` | Permite escribir textos más extensos. |
| `<select>` | Permite seleccionar una categoría. |
| `<button>` | Representa una acción mediante un botón. |

# 3. Tabla de libros registrados

Esta es una de las partes más importantes de tu módulo.

Puedes explicarla así:

> Se implementó una tabla HTML para organizar visualmente los libros registrados. Su estructura permite identificar información como la portada, el título, el autor, la categoría y las acciones disponibles.

**Conceptos técnicos que debes conocer:**

| Código | Función |
|---|---|
| `<table>` | Crea la tabla. |
| `<thead>` | Contiene los encabezados. |
| `<tbody>` | Contiene los registros. |
| `<tr>` | Representa una fila. |
| `<th>` | Representa un encabezado. |
| `<td>` | Contiene los datos de cada fila. |

También puedes mencionar:

- **Organización tabular:** presentación de información mediante filas y columnas.
- **Acciones administrativas:** botones que representan opciones como editar y eliminar.
- **Visualización de datos:** forma en que se presenta la información al administrador.

# 4. Tabla de solicitudes recibidas

Esta sección permite visualizar las solicitudes de préstamo realizadas por los usuarios.

Puedes decir:

> Se desarrolló una segunda tabla destinada al seguimiento visual de las solicitudes recibidas. Esta contiene información como el identificador de la solicitud, el libro solicitado, el nombre del usuario, su correo electrónico, un comentario y el estado de la solicitud.

Un concepto importante es el **estado de la solicitud**.

Por ejemplo:
- Pendiente.
- Aprobada.
- Rechazada.

En tu proyecto se representa el estado «Pendiente».

**Frase técnica para destacar:**

«Esta tabla facilita la consulta y organización de las solicitudes, permitiendo identificar rápidamente su información y estado».

# 5. ¿Por qué utilizamos Bootstrap?

Esta pregunta podría aparecer durante la exposición.

Puedes responder:

> Utilizamos Bootstrap como framework de diseño para agilizar la construcción de la interfaz. Nos permite implementar componentes y clases prediseñadas que facilitan la organización visual y la adaptación del contenido a diferentes dispositivos.

Algunas clases que debes conocer:

| Clase | Función |
|---|---|
| `container` | Organiza y centra el contenido. |
| `card` | Crea tarjetas o contenedores visuales. |
| `form-control` | Da formato a los campos de entrada. |
| `btn` | Establece el diseño de los botones. |
| `table` | Aplica estilos a las tablas. |
| `table-striped` | Alterna los colores de las filas. |
| `table-hover` | Resalta las filas al pasar el cursor. |
| `table-responsive` | Permite adaptar las tablas a pantallas pequeñas. |

# 6. Preguntas que podrían hacerte

Te recomiendo prepararte para estas preguntas:

**1. ¿Qué es el panel de administración?**

Es una interfaz que permite al administrador consultar y organizar la información de los libros y las solicitudes de los usuarios.

**2. ¿Qué diferencia existe entre `<thead>` y `<tbody>`?**

`<thead>` contiene los encabezados de la tabla, mientras que `<tbody>` contiene los registros o datos.

**3. ¿Qué es Bootstrap?**

Es un framework de CSS que facilita el diseño de páginas web mediante clases y componentes prediseñados.

**4. ¿Qué significa que una página sea responsiva?**

Significa que su contenido se adapta a diferentes tamaños de pantalla, como computadores, tabletas y celulares.

**5. ¿Los botones de editar y eliminar realizan modificaciones reales?**

En la versión de nuestro proyecto, los botones representan visualmente las acciones administrativas, pero no ejecutan modificaciones reales sobre una base de datos.

**6. ¿Qué diferencia hay entre HTML y Bootstrap?**

HTML proporciona la estructura y el contenido de la página, mientras que Bootstrap permite darle diseño y mejorar su presentación.

---

# 7. Datos importantes para destacar durante tu exposición

Estas son algunas frases que te pueden ayudar a sonar más técnico sin complicar tu explicación:

- «El módulo está construido principalmente con HTML5 y Bootstrap 5».
- «Se implementó una estructura organizada mediante contenedores, formularios y tablas».
- «Se separó la información en dos secciones principales: libros registrados y solicitudes recibidas».
- «Se utilizaron componentes de interfaz para mejorar la presentación y la experiencia del usuario».
- «La estructura permite mantener una organización clara y facilita futuras mejoras del sistema».

### Una recomendación importante

No afirmes que tu panel almacena información, modifica libros o procesa solicitudes automáticamente si esas funciones no están implementadas. Según el alcance que hemos venido trabajando, tus tablas son **estáticas**, es decir, muestran información de ejemplo mediante HTML.

---

## 8. Una pequeña exposición que puedes practicar

Mi parte del proyecto corresponde al desarrollo del panel de administración de BiblioWeb.

Este módulo tiene como objetivo proporcionar una interfaz para la consulta y organización de la información de los libros y las solicitudes realizadas por los usuarios.

Para su construcción utilicé HTML5, que permite definir la estructura de la página, y Bootstrap 5, que facilita el diseño y la presentación visual de los componentes.

El panel está dividido principalmente en tres secciones. La primera es un formulario para representar el registro de libros, con campos como título, autor, portada, descripción y categoría.

La segunda sección es una tabla de libros registrados, donde se organiza la información mediante filas y columnas. También se incluyen botones visuales para representar las acciones de editar y eliminar.

Finalmente, tenemos una tabla de solicitudes recibidas, que permite consultar los datos de los usuarios, el libro solicitado y el estado de cada solicitud.

En conclusión, mi módulo busca ofrecer una interfaz organizada, clara y fácil de utilizar para la administración de la información de la biblioteca.

**Mi consejo:** aprende especialmente a explicar qué hacen `<form>`, `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<td>` y las clases de Bootstrap. Si dominas esos conceptos, tendrás una buena base para responder preguntas sobre tu parte del proyecto.