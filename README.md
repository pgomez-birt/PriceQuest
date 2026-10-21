# 📘 DWEC04 - Tarea de Evaluación

## 📝 Descripción general

Ponte en el papel de un programador freelance que ha identificado un nicho de mercado con potencial y decide diseñar una aplicación web que ofrece información para ese sector.

Para ello, vas definirás un proyecto que **utilizará una API como fuente de datos**. 

##### Requisitos

- La aplicación tendrá **libertad temática**, de manera que puedes elegir el proyecto que quieras desarrollar.

- **Asígnale un nombre representativo**. Ejemplos:
  
  - *<u>ExploraFauna</u>*: portal dedicado a catalogar y clasificar animales de África. Dirigido a investigadores y amantes de la naturaleza.
  
  - *<u>BolsaSmart</u>*: herramienta interactiva para visualizar información detallada sobre activos financieros. Diseñada para pequeños inversores interesados en tomar decisiones informadas.

- El proyecto deberá **cumplir con las tres secciones** descritas en el apartado de ejercicios; dos comunes y una tercera de tu elección. 

- La **aplicación será multipágina**. Cuando sea necesario conservar información entre páginas utiliza el `Web Storage`.

- La aplicación deberá **respetar la arquitectura estudiada** en UDs anteriores.

- La aplicación puede ser desarrollada utilizando las gestión de eventos nativa de JavaScript, la de jQuery o ambas tecnologías.

## 🎯 Objetivos de aprendizaje

- _Desarrollar un frontend utilizando tecnología JavaScript_
- _Consumir recursos de una API Rest._
- *Integrar en un proyecto los conocimientos sobre gestión de eventos y consultas HTTP estudiados hasta el momento.*

## 📚 Recursos

##### Ejemplos

En el apartado de recursos tienes los siguientes ejemplos:

- [Documento](./recursos/1-ejemplo-aplicacion-real.md) explicando los tipos de interfaces sobre una aplicación web real.

- [Directorio](./recursos/interfaces) con ejemplos de las distintas interfaces en formato `.html`

> [!TIP]
> 
> Ejecuta los ficheros `.html` haciendo doble click o arrastrandolos en una ventana de navegador para que puedas probar las interfaces de ejemplo.

##### Listado de APIs

Para facilitarte el trabajo de selección de temática, en los recursos te facilito un [documento ](./recursos/2-lista-apis.md)con una lista de APIs.

- Si ninguna fuente de datos se adapta a tu proyecto, puedes crear tu propia API con recursos como: [*Supabase*](https://supabase.com/) o [*Mockon*](https://mockoon.com/). 

- Si necesitas crear datos sintéticos en formato JSON puedes utilizar [esta](https://devpefer.com/tools) herramienta.

- Si prefieres utiliza otra API de tu elección. 

> [!TIP]
> 
> Utiliza Postman para comprobar los endpoints de la API que vas a utilizar, los datos que devuelve y los parámetros o métodos HTTP necesarios.

## 🛠️ Ejercicios

La aplicación web constará de **dos interfaces principales y una funcionalidad adicional** organizadas de la siguiente manera:

#### Ejercicio 1: Resumen

- **Objetivo**: Actuar como **página principal** ofreciendo una lista de elementos con información organizada de manera clara.

- **Requisitos**:
  
  - Mostrar un listado, catálogo o ranking de elementos.
  
  - Para cada elemento mostrar datos clave o [KPIs](https://es.wikipedia.org/wiki/Indicador_clave_de_rendimiento).
  
  - Mientras se realiza una consulta a la API, muestra un indicador de carga. Si la petición falla, informa del error en la interfaz y evita que la aplicación quede en un estado inconsistente.

#### Ejercicio 2: Visualización de Datos

- **Objetivo**: Explorar o ampliar la información de un elemento seleccionado en el *Resumen*. 

- **Requisitos**: Mostrar un **elemento interactivo** a elegir entre:
  
  - Gráfico.
  
  - Tabla comparativa.

> [!NOTE]
> 
> El elemento deberá reaccionar a la interacción del usuario, permitiendo acciones consultar información adicional, filtrar, ordenar o seleccionar datos.
> 
> En la aplicación de ejemplo te muestro cómo puedes: posicionarte sobre el gráfico ver información del activo, filtrar en función a la temporalidad etc.

#### Ejercicio 3: Funcionalidad Extra

- **Objetivo**: Incorporar una funcionalidad adicional.

Implementa **una de las siguientes opciones**:

- **Filtros o búsqueda:** Permite filtrar los elementos mostrados utilizando al menos dos criterios relacionados con los datos de la API. Los resultados deberán actualizarse en función de las opciones seleccionadas por el usuario..

- **Favoritos:** Permite marcar y desmarcar elementos como favoritos y conservar esta selección mediante Web Storage. El usuario deberá poder consultar posteriormente los elementos guardados.

--- 

> [!IMPORTANT]
> 
> Tanto en el ejercicio 2 como en el ejercicio 3 puedes programar una funcionalidad diferente a las que te propongo si esta que se adapta mejor a la temática de tu aplicación.
> 
> Consúltame por correo electrónico para que te de el visto bueno.
