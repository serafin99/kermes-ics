# La kermés de las Ciencias Sociales

Rosco, Preguntados y muro colectivo para el repaso previo al final de Introducción a las Ciencias Sociales.

**Serafin Gonzalez - Adscripto** · 2026

Contenido didáctico propio bajo [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es). Se permite compartir y adaptar con crédito, sin fines comerciales y bajo la misma licencia. El alcance y las excepciones se detallan en [LICENCIA.md](LICENCIA.md); el texto oficial está en [LICENSE](LICENSE).

**[Entrar a la actividad](https://serafin99.github.io/kermes-ics/?sala=C4EC7B)**

## Cómo se conservan las respuestas

GitHub Pages publica la sala de juegos. Los envíos se guardan en el servicio de la actividad, en una base compartida: no dependen de que un docente tenga abierta la página. Se mantiene la misma sala, C4EC7B, y sus registros anteriores.

- La participación es anónima. Cada navegador recibe un código aleatorio, sin nombre ni comisión.
- Las respuestas y fundamentaciones son privadas. Los docentes consultan el panel mediante su enlace reservado y pueden descargar una planilla CSV.
- El muro permanece visible para quienes entren a la sala. Su alias es opcional.
- La página muestra si quedan envíos pendientes y permite reintentarlos.

El enlace reservado docente se entrega por separado. No está en este repositorio ni debe publicarse en el aula virtual.

## Archivos

- `index.html`: página lista para GitHub Pages, con sus imágenes y estilos incorporados.
- `GUIA_DOCENTE.md`: recorrido, reglas y lectura de los resultados.
- `fuentes.zip`: componentes editables, banco de preguntas, imágenes con créditos y herramienta de construcción de la versión estática. No contiene respuestas de estudiantes ni accesos docentes.

## Actualizaciones

Para reconstruir, descomprimir `fuentes.zip`, instalar las dependencias con `npm install` y ejecutar `npm run build`. Reemplazar después el `index.html` del repositorio por el de `github-dist/`. Requiere Node.js 22.13 o superior.

La versión estática se comunica con el servicio existente mediante HTTPS y controles de acceso para cada recorrido y el panel docente. El servicio debe seguir publicado para guardar y consultar registros. GitHub Pages, por sí solo, no almacena los envíos.

## Contenido y créditos

66 preguntas con explicaciones y referencias; 24 letras del rosco; cruces entre unidades y casos hipotéticos de análisis. Los textos de la cátedra no se redistribuyen. Las imágenes mantienen los créditos y las licencias indicadas en la trastienda de la página y en `data/credits.json` dentro de las fuentes.
