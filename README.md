# 📘 DWEC04 - Tarea de Evaluación

## 📝 Descripción general

Ponte en el papel de un programador freelance que ha identificado un nicho de mercado con potencial y decide diseñar una aplicación web que ofrece información para un sector utilizando una API como fuente de datos.

Para ello, vas a definir un proyecto y a asignarle un nombre representativo como:

- *<u>ExploraFauna</u>*: portal dedicado a catalogar y clasificar animales de África. Dirigido a investigadores y amantes de la naturaleza.

- *<u>BolsaSmart</u>*: herramienta interactiva para visualizar información detallada sobre activos financieros. Diseñada para pequeños inversores interesados en tomar decisiones informadas.

##### Requisitos

- La aplicación tendrá **libertad temática**, de manera que puedes elegir el proyecto que quieras desarrollar.

- El proyecto deberá cumplir con las tres secciones descritas en el apartado de ejercicios; dos comunes y una tercera de tu elección. 

- La aplicación será multipágina. Cuando sea necesario conservar información entre páginas, como el elemento seleccionado por el usuario, utiliza Web Storage.

- La aplicación deberá respetar la arquitectura estudiada en el módulo.

- La aplicación puede ser desarrollada utilizando las gestión de eventos nativa del DOM, jQuery o ambas tecnologías.

- **Gestión de peticiones:** mientras se realiza una petición a la API, muestra al usuario un indicador de carga. Si la petición falla, informa del error en la interfaz y evita que la aplicación quede en un estado inconsistente.

## 🎯 Objetivos de aprendizaje

- _Desarrollar un frontend utilizando JavaScript nativo, jQuery o una combinación de ambas tecnologías_
- _Consumir recursos de una API Rest._
- *Integrar en un proyecto los conocimientos sobre gestión de eventos y consultas HTTP estudiados hasta el momento.*

## 📚 Recursos

##### Ejemplo

En el apartado de recursos tienes un [documento ](./recursos/1-ejemplo-aplicacion.md)con una web de ejemplo explicando paso a paso todas las interfaces.

##### Listado de APIs

Para facilitarte el trabajo de selección de temática, en los recursos te facilito un [documento ](./recursos/2-lista-apis.md)con una lista de APIs.

Por un lado,  tienes un listado de APIs con información de acceso libre que puedes utilizar. Por otro lado, si ninguna fuente de datos te sirve, puedes crear tu propia API de manera fácil y sencilla en alguna de las plataformas propuestas. Para acabar, si lo  necesitas, te facilito un recurso para crear datos sintéticos en formato JSON.

Además, si lo prefieres, puedes utilizar otra API de tu elección que no figure entre los recursos facilitados. En ese caso, antes de comenzar el desarrollo, comprueba que puedes acceder a sus datos, que dispones de los permisos o credenciales necesarios y que ofrece la información suficiente para cumplir los requisitos de la tarea.

> [!TIP]
> 
> Utiliza Postman para comprobar los endpoints de la API que vas a utilizar, los datos que devuelve y los parámetros o métodos HTTP necesarios.

La combinación de varias APIs también está permitida.

## 🛠️ Ejercicios

La aplicación web constará de dos interfaces principales y una funcionalidad adicional:

- Resumen

- Visualización de Datos

- Extra

#### Ejercicio 1: Resumen

- **Objetivo**: Actuar como **página principal o punto de entrada** a la aplicacion ofreciendo una lista de elementos con información organizada de manera clara.

- **Requisitos**:
  
  - Mostrar un listado, catálogo o ranking de elementos obtenidos de la API..
  
  - Mostrar, para cada elemento, algunos de los datos o indicadores más relevantes obtenidos de la API, como [KPIs](https://es.wikipedia.org/wiki/Indicador_clave_de_rendimiento)

> [NOTE!]
> Al seleccionar uno de los elementos del listado, guarda la información necesaria para identificarlo y redirige a la página de *Visualización de Datos*.

#### Ejercicio 2: Visualización de Datos

- **Objetivo**: **Ampliar información sobre un elemento de la lista** cuando se pulsa sobre este. 

- **Requisitos**: Mostrar al menos un **elemento interactivo**. En esta categoría se pueden incluir, entre otros:
  
  - **Gráfico**.
  
  - **Tabla comparativa**.
  
  - Otro de tu elección.

> [NOTE!]
> 
> El elemento deberá reaccionar a la interacción del usuario, permitiendo acciones como consultar información adicional, filtrar, ordenar, seleccionar datos, modificar el periodo mostrado o interactuar con sus elementos.
> 
> En la aplicación de ejemplo te muestro cómo puedes: posicionarte sobre el gráfico ver información del activo, filtrar en función a la temporalidad etc.

#### Ejercicio 3: Funcionalidad Extra

- **Objetivo**: Iincorporar una funcionalidad adicional que permita al usuario interactuar con los datos de la aplicación.

Implementa **una de las siguientes opciones**:

- **Filtros o búsqueda:** Permite filtrar los elementos mostrados utilizando al menos dos criterios relacionados con los datos de la API. Los resultados deberán actualizarse en función de las opciones seleccionadas por el usuario..

- **Favoritos:** Permite marcar y desmarcar elementos como favoritos y conservar esta selección mediante Web Storage. El usuario deberá poder consultar posteriormente los elementos guardados.
