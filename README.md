# Cronómetro en JavaScript

Este es un ejemplo de un cronómetro simple implementado con HTML, CSS y JavaScript. Permite iniciar, detener y resetear el cronómetro con botones interactivos.

## Descripción

El cronómetro cuenta el tiempo en segundos. El funcionamiento incluye las siguientes características:

- **Iniciar/Parar**: Al hacer clic en el botón "Iniciar", el cronómetro comienza a contar en intervalos de 1 segundo. Al hacer clic nuevamente en "Parar", el cronómetro se detiene.
- **Resetear**: Al hacer clic en el botón "Poner a Cero", el cronómetro se reinicia y comienza desde 0.
  
## Estructura de Archivos

- **HTML (index.html)**: Contiene la estructura básica de la página, incluyendo los botones y el área donde se muestra el cronómetro.
- **CSS (cronometro.css)**: Estilos para la página y los botones (se espera que este archivo contenga estilos, aunque no se ha proporcionado).
- **JavaScript (en el mismo archivo HTML)**: Lógica que controla el funcionamiento del cronómetro. Se utilizan eventos `click` para manejar el inicio, detención y reseteo del cronómetro.

## Funcionalidad

1. **Contador de Segundos**: El cronómetro aumenta cada segundo.
2. **Botón de Iniciar/Parar**: Permite iniciar y detener el cronómetro.
3. **Botón de Resetear**: Resetea el cronómetro a 0.

## Requisitos

- Un navegador moderno que soporte HTML5, CSS3 y JavaScript.
- El archivo `cronometro.css` debe existir para el correcto estilo de los elementos (aunque no se ha proporcionado su contenido).

## Cómo usar

1. Abre el archivo `index.html` en tu navegador.
2. Haz clic en el botón "Iniciar" para comenzar el cronómetro.
3. Haz clic en el botón "Parar" para detenerlo.
4. Haz clic en el botón "Poner a Cero" para reiniciar el cronómetro.
