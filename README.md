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
- Hay dos botones de envío: uno prepara un email para `elisadiarte@huertosalta.edu.ar` y otro prepara un WhatsApp para `+54 9 387 415-8909`. Ambos incluyen nombre, apellido, puntaje y todas las respuestas elegidas/escritas. El alumno debe tocar **Enviar** en cada aplicación. Para enviarlo por ambos medios, debe usar los dos botones.

## Importante
El puntaje automático corrige las preguntas cerradas y reconoce si las tres respuestas finales tienen una extensión mínima. Las respuestas abiertas requieren revisión docente para valorar su contenido. El puntaje es orientativo y se puede ajustar en `script.js`.

El juego no envía mensajes automáticamente: abre el correo configurado o WhatsApp con el informe preparado. El estudiante debe revisar y tocar **Enviar** en cada aplicación. Para el correo, el dispositivo debe tener una aplicación/cuenta configurada. Los informes extensos pueden estar sujetos a límites del programa de correo, WhatsApp o navegador.


## Actualización del caso final
El último desafío presenta una situación ficticia de trato irrespetuoso, falta de escucha y evaluación que podría estar influida por cuestiones personales. Invita a identificar derechos y pensar vías seguras para pedir ayuda y solicitar criterios de evaluación claros, sin señalar ni insultar a personas.
