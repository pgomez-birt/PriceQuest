# 📘 DWEC04 - Tarea de Evaluación

## 📝 Descripción general

Ponte en el papel de un programador freelance que ha identificado un nicho de mercado con potencial y decide diseñar una aplicación web que ofrece información para ese sector.

Para ello, vas a definir un proyecto que **utilizará una API como fuente de datos**.

### Requisitos generales

- La aplicación tendrá **libertad temática**, de manera que puedes elegir el proyecto que quieras desarrollar.

- **Asigna un nombre representativo** a tu proyecto. Por ejemplo:
  
  - **ExploraFauna**: portal dedicado a catalogar y clasificar animales de África, dirigido a investigadores y amantes de la naturaleza.
  - **BolsaSmart**: herramienta interactiva para visualizar información detallada sobre activos financieros, dirigida a pequeños inversores interesados en tomar decisiones informadas.

- El proyecto deberá **cumplir con las tres secciones** descritas en el apartado de ejercicios

- La **aplicación será multipágina**. Cuando necesites conservar información entre páginas, utiliza `Web Storage`.

- La aplicación deberá **respetar la arquitectura estudiada** en unidades anteriores.

- Puedes desarrollar la aplicación utilizando la gestión de eventos nativa de **JavaScript**, la de **jQuery** o una combinación de ambas tecnologías.

- Mientras se realiza una consulta a la API, muestra un **indicador de carga**. Si la petición falla, informa del error en la interfaz y evita que la aplicación quede en un estado inconsistente.

## 🎯 Objetivos de aprendizaje

- Desarrollar un frontend utilizando JavaScript.
- Consumir recursos de una **API REST**.
- Integrar en un mismo proyecto los conocimientos sobre **gestión de eventos** y **consultas HTTP** estudiados hasta el momento.

## 📚 Recursos

### Ejemplos

En el apartado de recursos encontrarás los siguientes materiales:

- Un [documento](./recursos/1-ejemplo-aplicacion-real.md) en el que se explican distintos tipos de interfaces a partir de una aplicación web real.
- Un [directorio](./recursos/interfaces) con ejemplos de las distintas interfaces en formato `.html`.

> [!TIP]
> 
> Puedes ejecutar los archivos `.html` haciendo doble clic sobre ellos o arrastrándolos a una ventana del navegador para probar las interfaces de ejemplo.

### Listado de APIs

Para facilitarte la elección de temática, en los recursos tienes un [documento](./recursos/2-lista-apis.md) con una selección de APIs que puedes utilizar.

- Si ninguna fuente de datos se adapta a tu proyecto, puedes crear tu propia API utilizando recursos como [Supabase](https://supabase.com/) o [Mockoon](https://mockoon.com/).
- Si necesitas generar datos sintéticos en formato JSON, puedes utilizar [esta herramienta](https://devpefer.com/tools).
- Si lo prefieres, puedes utilizar otra API de tu elección.

> [!TIP]
> 
> Utiliza **Postman** para comprobar los endpoints de la API que vas a utilizar, los datos que devuelve y los parámetros o métodos HTTP necesarios antes de integrarla en tu aplicación.

## 🛠️ Ejercicios

La aplicación web constará de **tres interfaces principales** organizadas de la siguiente manera.

### Ejercicio 1: Resumen

**Objetivo:** actuar como **página principal** de la aplicación, mostrando una colección de elementos con información organizada de manera clara.

**Requisitos:**

- Mostrar un **listado, catálogo o ranking** de elementos.
- Mostrar para cada elemento algunos **datos clave o indicadores relevantes [(KPIs)](https://es.wikipedia.org/wiki/Indicador_clave_de_rendimiento)**

### Ejercicio 2: Visualización de Datos

**Objetivo:** explorar o ampliar la información de un elemento seleccionado previamente en la interfaz de *Resumen*.

**Requisitos:** mostrar un **elemento interactivo**. Puedes elegir entre:

- **Gráfico**.
- **Tabla comparativa**.

> [!NOTE]
> 
> El elemento deberá reaccionar a la interacción del usuario y permitir acciones como consultar información adicional, filtrar, ordenar o seleccionar datos.
> 
> En las interfaces de ejemplo puedes ver distintas posibilidades, como consultar información al posicionarte sobre un gráfico o modificar el periodo temporal mostrado.

### Ejercicio 3: Funcionalidad Adicional

**Objetivo:** incorporar una funcionalidad adicional que permita al usuario interactuar con la aplicación.

Implementa **una de las siguientes opciones**:

- **Favoritos:** permite marcar y desmarcar elementos como favoritos y conservar esta selección. El usuario deberá poder consultar posteriormente los elementos guardados.
- **Filtros o búsqueda:** permite filtrar los elementos mostrados utilizando al menos **dos criterios** relacionados con los datos de la API. Los resultados deberán actualizarse en función de las opciones seleccionadas por el usuario.

---

> [!IMPORTANT]
> 
> Tanto en el **Ejercicio 2** como en el **Ejercicio 3** puedes implementar una funcionalidad diferente a las propuestas si se adapta mejor a la temática de tu aplicación.
> 
> En ese caso, consúltame previamente por correo electrónico para que pueda darte el visto bueno.
