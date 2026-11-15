# Estructura de proteínas

Esta sección reúne ejemplos de los formatos de archivo más usados en biología estructural, sobre todo en crio-microscopía electrónica (cryo-EM), además de scripts introductorios en Python y R

> [!IMPORTANT]
> Los archivos son ejemplos ilustrativos: muestran cómo es cada formato por dentro, pero no contienen datos reales!!
## Archivos de ejemplo

- **`*.mrc`**: mapa 3D de densidad electrónica --> guarda una rejilla de vóxeles (como los píxeles de una imagen, pero en 3D), cada uno con un valor de densidad --> es el formato estándar de la cryo-EM para micrografías y mapas reconstruidos, y se visualiza en programas como ChimeraX

- **`procesamiento.star`**: archivo de texto organizado en tablas --> el programa RELION lo usa para guardar los metadatos del procesamiento de cryo-EM, como la posición de cada partícula y la micrografía de la que procede

- **`estructura.pdb`**: modelo atómico de una proteína, con una línea por átomo que indica el residuo, la cadena y sus coordenadas x, y, z en Å --> es el formato clásico para guardar y compartir estructuras, ya vengan de cristalografía, crio-EM o predicción (por ejemplo, AlphaFold)


## Scripts

- **`design-trial.py`**: archivo de ejemplo en Python para el diseño de proteínas.
- **`grafico.r`**: ejemplo básico de visualización de datos en R.
