# 🎓 Curso Introductorio de R y RStudio - EECA

![R](https://img.shields.io/badge/R-4.0+-blue.svg)
![Quarto](https://img.shields.io/badge/Quarto-Reproducible-9cf)
![Status](https://img.shields.io/badge/Estado-Activo-green)

Bienvenido al **[repositorio del curso](https://olivertc24.github.io/Notebook_R_Rstudio/).** Este material está diseñado para estudiantes de la **Escuela de Estadística y Ciencias Actuariales**, utilizando **Quarto** para combinar teoría, código y visualización en documentos integrados.

## 📄 Descripción

El objetivo de este repositorio es proporcionar una base sólida en programación estadística. A diferencia de los scripts tradicionales, aquí utilizamos documentos `.qmd` (Quarto), lo que te permitirá ver el código y su resultado (gráficos, tablas) en un mismo lugar, simulando el flujo de trabajo real de un estadistico, científico de datos o actuario.

## 🛠️ Requisitos Previos

Para seguir este curso, asegúrate de tener instalado lo siguiente en este orden:

1.  **[R Base](https://cran.r-project.org/):** El lenguaje de programación.
2.  **[RStudio Desktop](https://posit.co/download/rstudio-desktop/):** El entorno de desarrollo (IDE). Las versiones recientes ya incluyen soporte para Quarto.
3.  **Paquetes necesarios:**
    Copia y pega esto en tu consola de RStudio para instalar las librerías base del curso:
    ```r
    install.packages(c("tidyverse", "quarto", "rmarkdown", "palmerpenguins"))
    ```

## 📚 Estructura del Curso

El contenido está dividido en 7 módulos secuenciales. Cada módulo es un archivo Quarto (`.qmd`) que puedes renderizar en tu computadora.

### **Módulo 1: Introducción a R y RStudio**
* `01_introduccion.qmd`
* Historia de R, el entorno IDE, consola vs. script, y configuración del directorio de trabajo (Proyectos).

### **Módulo 2: Sintaxis Básica y Tipos de Datos**
* `02_sintaxis_tipos.qmd`
* Variables, operadores aritméticos y lógicos. Tipos atómicos: `numeric`, `character`, `logical`, `integer`.

### **Módulo 3: Estructuras de Datos Esenciales**
* `03_estructuras.qmd`
* Vectores, Matrices, Listas y Data Frames. Indexación y subconjuntos (`[ ]`, `$`).

### **Módulo 4: Importación y Exportación**
* `04_importacion.qmd`
* Lectura de datos desde Excel, CSV y archivos de texto. Guardar resultados para informes externos.

### **Módulo 5: Manipulación de Datos**
* `05_manipulacion.qmd`
* Introducción al "Tidyverse". Uso de `dplyr` para filtrar, seleccionar, transformar y resumir información estadística.

### **Módulo 6: Visualización Avanzada**
* `06_visualizacion.qmd`
* Gramática de gráficos con `ggplot2`. Geometrías, facetas, escalas y personalización estética para informes profesionales.

### **Módulo 7: Programación Funcional**
* `07_funcional.qmd`
* Creación de funciones propias (`function()`), estructuras de control (`if`, `for`) y la familia `apply` vs `map`.

## 🚀 Cómo utilizar este material

1.  **Descarga el Proyecto:**
    * Clona el repositorio o descarga el ZIP (botón verde "Code").
2.  **Abre el Proyecto:**
    * Haz doble clic en el archivo `.Rproj`. Esto abrirá RStudio en el contexto correcto.
3.  **Renderizar (Compilar):**
    * Abre cualquier archivo `.qmd` (por ejemplo, `01_introduccion.qmd`).
    * Haz clic en el botón **Render** (ícono de flecha azul sobre el editor) para generar el documento HTML o PDF con la clase y los ejercicios resueltos.

## 🤝 Dudas y Contribuciones

Si tienes problemas con la instalación o algún ejercicio:
* Revisa la pestaña "Issues" en este repositorio.
* Consulta la documentación oficial de [Quarto](https://quarto.org/).

---
**Escuela de Estadística y Ciencias Actuariales**
*Repositorio docente para uso académico.*
