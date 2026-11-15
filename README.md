# Actividad grupal IPC: uso de github 

> [!IMPORTANT]
> Trabajo grupal del **Máster en Bioinformática (UNIR)**, asignatura IPC. Sirve para practicar el trabajo colaborativo con Git y GitHub: ramas, *pull requests*, *merges* y documentación

## Descripción del proyecto
Simulamos un proyecto bioinformático cuyo objetivo es **analizar la expresión génica de un conjunto de muestras a partir de datos de secuenciación de ARN**. El repositorio recoge todo el flujo: la obtención de las muestras, las buenas prácticas de laboratorio, el análisis de secuencias y algunos módulos complementarios (estructura de proteínas y visualización).

## Propósito
Aprender a organizar un proyecto científico en un repositorio compartido, de forma que cada miembro del equipo trabaje en su propia sección sin pisar el trabajo de los demás y que todo quede documentado y sea reproducible.

## Objetivos
- Estructurar un proyecto bioinformático en módulos independientes
- Practicar el flujo colaborativo de GitHub: *forks*, ramas, *commits*, *pull requests* y resolución de conflictos
- Documentar cada módulo con su propio `README.md`
- Desarrollar scripts básicos en Python y R para el análisis de secuencias y la visualización de datos

## Funcionalidades y estado de desarrollo

| Funcionalidad | Desarrollador | Estado de desarrollo |
|---|---|---|
| Estructura de proteínas | Adriana | En proceso |
| Búsqueda de ORFs y control de calidad | [nombre] | En proceso |
| Gestión de muestras | [nombre] | En proceso |
| Buenas Prácticas de Laboratorio | Angela | En proceso |
| Algoritmos basicos secuenciacion | Alberto | fase beta |
|bases de wet lab secuenciacion | Alberto |fase alfa |
| Farmacología | Andrea | En proceso |



## Instrucciones de uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/adrriianatv/Actividad-grupal-IPC.git
   cd Actividad-grupal-IPC
   ```
> [!NOTE]
> Clonar el repositorio descarga en tu ordenador una copia completa del proyecto, con todo su historial, para que puedas trabajar en local y luego sincronizar tus cambios con GitHub

2. Instala las dependencias:
   - **Python ≥ 3.8**: `pip install pandas matplotlib`
   - **R ≥ 4.0**
3. Ejecuta los scripts desde la raíz del repositorio, por ejemplo:
   ```bash
   python Secuenciación/find_ORF.py
   Rscript protein-design/grafico.r
   ```

### Información relevante

- Este es un proyecto académico: los datos y los scripts son ilustrativos y todavía no están listos para usarse en análisis reales
- Cada carpeta tiene su propio `README.md` con más detalle
- Distribuido bajo la licencia **GNU GPL v3.0**. Consulta el archivo [LICENSE](LICENSE)
