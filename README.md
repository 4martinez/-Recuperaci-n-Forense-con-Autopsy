# 🔍 Proyecto Forense: Recuperación de Imágenes desde Imagen de Disco (.dd)

**Autor:** Álvaro Martínez Cutillas  
**Fecha:** Abril 2025  
**Herramienta utilizada:** Autopsy v4.17.0  
**Tipo de fuente:** Imagen forense de disco (`image.dd`)  
**Entorno:** Laboratorio simulado 

---

## 🎯 Objetivo

Analizar una imagen forense de disco y recuperar archivos gráficos (imágenes) utilizando una metodología forense estructurada con la herramienta Autopsy.

---

## 🛠️ Herramientas y Procedimiento

### 🔧 Herramienta: Autopsy

Autopsy es una herramienta de análisis forense de código abierto. Se utilizó para:

- Cargar y procesar la imagen `image.dd`  
- Identificar tipos de archivos  
- Recuperar imágenes ocultas  
- Visualizar metadatos  
- Generar informes del análisis

---

### 🧪 Procedimiento

1. **Creación del caso:**  
   Caso nuevo “Imagenes_5” creado como usuario único en Autopsy.

2. **Carga de imagen forense:**  
   Se seleccionó el archivo `image.dd` como fuente de análisis.

3. **Selección de módulos:**  
   - File Type Identification  
   - Picture Analyzer  
   - Embedded File Extractor  
   - PhotoRec Carver

4. **Análisis del contenido:**  
   Se localizaron 18 archivos de imagen dentro del sistema de archivos montado.

5. **Extracción de evidencia:**  
   Se recuperaron manualmente 5 imágenes relevantes.

---

## 🖼️ Imágenes recuperadas

- `56178862f8cb60c5c8e373b876661a43.jpg`  
- `figura-leonardo-las-tortugas-ninja-18-cm.jpeg`  
- `Michelangelo_1990_promo_sample.jpeg`  
- `Raphael_TMNT_2007.jpeg`  
- `TMNT_1990_Donatello_IMG_0048.jpeg`

---

## ✅ Resultados

La extracción fue exitosa. Se validó la capacidad de Autopsy para recuperar archivos gráficos ocultos en un entorno forense simulado.

---

## 🔐 Conclusión

Autopsy demostró ser eficaz para entornos educativos y prácticos. Su facilidad para clasificar archivos, extraer evidencia y trabajar con imágenes `.dd` lo convierte en una herramienta ideal para investigadores forenses y analistas en formación.

---

## 📎 Nota

Este proyecto fue desarrollado con fines educativos, en entorno simulado, como parte de un ejercicio práctico de análisis forense digital. No contiene datos reales ni evidencia de casos reales.

---

Este proyecto fue realizado como parte de un proceso formativo. La máquina analizada es de acceso público y el contenido aquí compartido es de elaboración propia, con fines educativos y demostrativos.

