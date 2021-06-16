# Prueba Técnica - Web Developer / Mobile Developer

#### ¿Qué se busca evaluar?
Principalmente los siguientes aspectos:
  + Creatividad para resolver los requerimientos
  + Buenas practicas
  + Eficiencia de los algoritmos entregados
  + Diseño interactivo (UX) 

## IMPORTANTE
1. Se requiere de una **cuenta de GitHub** para realizar este ejercicio.
2. **Antes de comenzar a programar:**
    * Realizar un `Fork` de este repositorio (https://github.com/Aly-System/test-developer.git).
    * Clonar el fork a su máquina local 
    * Crear un `branch` en su cuenta de GitHub utilizando su nombre completo.
3. **Al finalizar**, realizar un `Commit` de su proyecto, **enviar un `Pull Request` al branch con su NOMBRE**, y notificar a la siguiente dirección de correo electrónico  [rrhh@alysystem.com](mailto:rrhh@alysystem.com) con el asunto **Prueba Finalizada**.
4. Utilizar *React Hooks*

## EJERCICIO PRÁCTICO
**Objetivo:** Crear una aplicación que ayude a obtener una lista de usuarios y muestre la información de sus perfiles, explotando el API Rest pública de GitHub https://api.github.com/search/users?q=YOUR_NAME.

#### Requerimientos generales

1. La aplicación debe cumplir con los siguientes **requisitos funcionales:**

    - Crear una aplicación que incluya un campo de entrada texto y un botón, para que se pueda capturar el usuario y recuperar la información utilizando el API anteriormente indicada.

    - Mostrar los primeros 10 usuarios del resultado de la búsqueda, incluyendo su nombre de usuario (`'user.login'`) y el id (`'user.id'`) de cada registro.

    - Convertir cada Perfil de usuario en un enlace, para que al hacer clic en cada registro, navegue a una ruta que incluya la propiedad `'user.login'` como parámetro.

    - Crear un componente independiente en el que se lea el parámetro de la URL, y a continuación, obtenga los datos de dicho usuario mediante la siguiente API: https://api.github.com/users/YOUR_NAME

    - Incluir la imagen del usuario (`'avatar_url'`) y alguna otra información (de su elección) en el componente.

    - Incluir un validador que verifique que el texto de búsqueda de usuarios sea de un mínimo de 4 caracteres, y otro que NO permita realizar la búsqueda de la palabra **“react”**.

    - Integrar cualquier librería de gráficos que pueda encontrar y crear un gráfico de barras simple para mostrar el número de seguidores de los 10 primeros usuarios.

    - Incluir un componente para mostrar mensajes de Error en toda la aplicación.

2. **CSS:** Utilizar algún framework (de preferencia `Sass` ) para escribir los archivos CSS, tomando en cuenta la compatibilidad con distintos navegadores.

3. **Iconos:** Utilizar una librería para el manejo de iconos donde lo considere necesario (_se recomienda el uso de [Font Awesome](http://fontawesome.io/) o [Glyphicons](http://glyphicons.com/)._)
