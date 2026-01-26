# 🎵 AIMC (AI Musical Cure)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pacureok/AI-music-from-google-colab/blob/main/AIMC.ipynb)

**AIMC** significa **AI Musical Cure**. 

### 👁️ Nuestra Visión
La visión de este modelo es democratizar la creación musical mediante IA, **eliminando el problema de la gestión de dependencias complejas** y ofreciendo una interfaz **fácil de usar**. Queremos que el usuario se centre en la creatividad y no en la configuración técnica.

---

## 🚀 Instrucciones de Uso

Para obtener los mejores resultados, sigue el orden de ejecución estrictamente:

### 1. Preparación del Envío
* **Conexión T4:** Antes de empezar, asegúrate de conectar el entorno de ejecución a una **GPU T4** (En Colab: `Entorno de ejecución` > `Cambiar tipo de entorno de ejecución` > `T4 GPU`).

### 2. Instalación y Configuración (Sin complicaciones)
* **Ejecutar Celda 1:** Esta celda configura automáticamente todo el entorno, resolviendo cualquier conflicto de dependencias por ti.
* **Ejecutar Celda 2:** Carga el modelo de IA en la memoria de la GPU.

### 3. Generación con Base (Opcional)
Si deseas utilizar una canción propia como base para la IA:
* Sube un archivo **.mp3** a la carpeta de archivos de Colab (panel izquierdo).
* **Importante:** El nombre del archivo debe ser obligatoriamente `cancion.mp3`.
* **Ejecutar Celda 3:** Una vez subido el archivo, ejecuta esta celda.

### 4. Personalización del Prompt
Busca la sección de **"Prompt"** en el código y modifica el texto para describir lo que quieres escuchar (ejemplo: *"lo-fi beat, jazzy, chill vibes"*).

---

## 📋 Requisitos
- Cuenta de Google para acceder a Colab.
- Archivo `cancion.mp3` (solo si usas música de base).

---

## 📋 NOTA
- despues de la celda 1 renicia el entorno y ejucta celda 2 y 3 para que no de errores

---

## ⚖️ Licencia
Este proyecto está bajo la Licencia **Apache 2.0**.

---
*Nota: Este notebook está optimizado para ejecutarse en la nube con un solo clic.*
