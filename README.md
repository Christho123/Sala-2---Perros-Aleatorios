# Sala-2---Perros-Aleatorios

# 🐶 Proyecto: App de Imágenes Aleatorias de Perros

Este proyecto tiene como finalidad crear una página web responsive que permita al usuario visualizar imágenes aleatorias de perros, con la opción de elegir una raza específica y descargar la imagen.

![Galería de Perros](https://th.bing.com/th/id/R.73132d6cdae0a932bc5f249e4a0e035f?rik=w4CDeY65chG9EA&riu=http%3a%2f%2fwww.anipedia.net%2fimages%2ffondos-pantalla-perros.jpg&ehk=3Yol%2bTcItscwWv4yW0swjDFiNzNn7rw7CuahOOd3ia4%3d&risl=&pid=ImgRaw&r=0)

---

## 🧠 Sprint Goal

Desarrollar una página web funcional y responsive que permita al usuario ver imágenes aleatorias de perros al hacer clic en un botón, con la opción adicional de seleccionar una raza específica.

---

## 🚀 Sprint Backlog

| Tarea                                                                                                      | Gadiel (G) | Edson (ER) | Christopher (CS) |
|------------------------------------------------------------------------------------------------------------|:----------:|:----------:|:----------------:|
| Crear estructura HTML: botón y contenedor para el selector de razas y descargar imagen                    |     X      |            |                  |
| Estilizar la página con diseño responsive                                                                  |     X      |            |                  |
| Utilizar la etiqueta `<select>` para cargar razas y actualizar imagen según la raza elegida desde la API  |     X      |            |                  |
| Usar fetch para obtener y mostrar lista de razas y subrazas desde la API                                  |            |     X      |                  |
| Usar fetch para mostrar imagen aleatoria o por raza seleccionada desde la API                             |            |            |        X         |
| Manejar errores y mostrar mensaje si falla la carga                                                       |            |            |        X         |
| Crear un evento que permita realizar la descarga de la imagen                                              |            |            |        X         |
| Subir proyecto a GitHub                                                                                    |            |     X      |                  |
| Documentar en el README.md                                                                                 |            |     X      |                  |

---

## 👥 Roles del Equipo

| Rol              | Nombre del integrante  | Función principal                                          |
|------------------|------------------------|------------------------------------------------------------|
| Scrum Master     | Alfredo Gonzales       | Supervisa el avance del equipo y organiza las reuniones    |
| Product Owner    | Diego Espinoza         | Establece las metas del proyecto y ordena las tareas       |
| Developer 1      | Gadiel Collazos        | Crea la interfaz y aplica el diseño responsivo             |
| Developer 2      | Christopher Sosa       | Programación JS: peticiones fetch, errores y descarga      |
| Developer 3      | Edson Rojas            | Obtención de datos desde la API y documentación            |

---

## 🛠 Tecnologías Utilizadas

- HTML  
- CSS  
- JavaScript  

---

## 📡 API Utilizada

Se usa la [Dog CEO API](https://dog.ceo/dog-api/) para obtener imágenes de perros:

- Obtener imagen aleatoria:  
  `https://dog.ceo/api/breeds/image/random`

- Obtener lista de razas:  
  `https://dog.ceo/api/breeds/list/all`

- Obtener imagen por raza (ejemplo con "retriever"):  
  `https://dog.ceo/api/breed/retriever/images/random`

---

## 🔗 Link de la Demo

[Ver demo en vivo](https://christho123.github.io/Sala-2---Perros-Aleatorios/html/index.html)

---

## 📘 Cómo usar la aplicación

1. **Abre el archivo `index.html` en tu navegador.**  
   Asegúrate de tener los archivos `styles.css` (en `css/`) y `app.js` (en `js/`) correctamente enlazados.

2. **Interfaz principal:**
   - Al cargar la página, verás una imagen aleatoria de un perro.
   - Usa el menú desplegable para seleccionar una raza (opcional).
   - Presiona **"Mostrar perro"** para actualizar la imagen.
   - Haz clic en **"Descargar imagen"** para guardar la foto en tu dispositivo.

3. **Características:**
   - ✅ Imágenes aleatorias desde la API.
   - ✅ Filtro por raza.
   - ✅ Botón para descargar la imagen.
   - ✅ Manejo de errores con mensajes visibles si ocurre un fallo en la carga.