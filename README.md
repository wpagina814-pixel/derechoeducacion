# Escape Room: Misión, recuperar una escuela segura

Juego web individual, responsive y en español.

## Publicarlo en GitHub Pages
1. Descomprimí el ZIP.
2. Creá un repositorio en GitHub y subí `index.html`, `styles.css` y `script.js` a la raíz.
3. Entrá en **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
5. Guardá. GitHub te dará la dirección pública del juego.

## Cómo funciona
- Cada alumno ingresa nombre y apellido.
- El cronómetro de 10 minutos comienza al iniciar la misión.
- Al llegar a cero, el juego se bloquea y muestra “¡Te quedaste sin tiempo!”.
- Hay actividades de selección, ordenamiento, relación de columnas y respuestas escritas.
- Al finalizar (o agotarse el tiempo), se calcula un puntaje de 1 a 10.
- El botón de correo prepara un email para `elisadiarte@huertosalta.edu.ar` con nombre, apellido, puntaje y todas las respuestas elegidas/escritas. El alumno debe tocar **Enviar** en su aplicación de correo.

## Importante
El puntaje automático corrige las preguntas cerradas y reconoce si las tres respuestas finales tienen una extensión mínima. Las respuestas abiertas requieren revisión docente para valorar su contenido. El puntaje es orientativo y se puede ajustar en `script.js`.

El juego usa un enlace `mailto:`. No envía mensajes automáticamente: abre la aplicación de correo configurada en el dispositivo con destinatario, asunto e informe preparados. El estudiante debe revisar y tocar **Enviar**. Para que funcione, el dispositivo debe tener una aplicación/cuenta de correo configurada. Los informes extensos pueden estar sujetos a límites del programa de correo o del navegador.
