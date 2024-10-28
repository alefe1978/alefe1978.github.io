Archivos Patts. (Estos se crearon a partir del enlace https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
Un archivo .patt en Realidad Aumentada (RA) es un tipo de marcador que se utiliza para activar experiencias de RA.  Esencialmente, es un archivo de datos que describe un patrón visual único que la cámara de un dispositivo puede reconocer e interpretar para superponer contenido digital en el mundo real.

¿Cómo funciona?

Creación del marcador: Se crea una imagen con un patrón distintivo de alto contraste (generalmente en blanco y negro). Esta imagen se procesa para generar un archivo .patt que contiene la información esencial del patrón.
Integración en la aplicación de RA: El archivo .patt se integra en la aplicación de RA.
Detección del marcador: Cuando la cámara del dispositivo detecta el patrón en el mundo real (impreso o en una pantalla), la aplicación utiliza la información del archivo .patt para identificar el marcador y su orientación.
Superposición de contenido: Una vez que el marcador es reconocido, la aplicación superpone el contenido digital asociado (modelos 3D, animaciones, información, etc.) en la posición y orientación correctas en relación al marcador.
Características importantes de un archivo .patt:

Alto contraste: El patrón debe tener un alto contraste (generalmente blanco y negro) para facilitar la detección por parte de la cámara.
Características únicas: El patrón debe ser distintivo y rico en detalles para evitar confusiones con otros marcadores o elementos del entorno.
Robustez: El marcador debe ser robusto a variaciones de iluminación, ángulo de visión y oclusiones parciales.
Herramientas para crear archivos .patt:

AR.js Studio: Una herramienta online que permite crear marcadores .patt de forma sencilla.
Generador de marcadores de AR.js: Un script incluido en AR.js que permite generar marcadores a partir de imágenes.
Otras bibliotecas de RA: Muchas bibliotecas de RA ofrecen herramientas para crear y gestionar marcadores.
En resumen, un archivo .patt es un componente esencial en muchas aplicaciones de RA basadas en marcadores, ya que permite "anclar" el contenido digital al mundo real de forma precisa y confiable.
