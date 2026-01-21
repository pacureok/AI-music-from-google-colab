# 🎵 AIMC (AI Musical Cure)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pacureok/AI-music-from-google-colab/blob/main/AIMC.ipynb)

**AIMC** son las siglas de **AI Musical Cure**. Este proyecto permite generar o transformar música utilizando Inteligencia Artificial para crear experiencias sonoras únicas desde Google Colab.

---

## 🚀 Instrucciones de Uso

Para obtener los mejores resultados, sigue el orden de ejecución estrictamente:

### 1. Preparación del Entorno
* **Conexión T4:** Antes de empezar, asegúrate de conectar el entorno de ejecución a una **GPU T4** (En Colab: `Entorno de ejecución` > `Cambiar tipo de entorno de ejecución` > `T4 GPU`). Esto es fundamental para que el procesamiento de audio sea rápido.

### 2. Instalación y Configuración
* **Ejecutar Celda 1:** Instala todas las librerías necesarias y dependencias del sistema.
* **Ejecutar Celda 2:** Carga el modelo de IA en la memoria de la GPU.

### 3. Generación con Base (Opcional)
Si deseas utilizar una canción propia como base para la IA:
* Debes subir un archivo en formato **.mp3** a la carpeta de archivos de Colab (icono de la carpeta a la izquierda).
* **Importante:** El nombre del archivo debe ser obligatoriamente `cancion.mp3`.
* **Ejecutar Celda 3:** Una vez subido el archivo, ejecuta esta celda.

### 4. Personalización del Prompt
Dentro del código de la celda de generación, busca la sección de **"Prompt"** y modifica el texto entre comillas para describir el estilo que deseas (ejemplo: *"lo-fi beat, jazzy, chill vibes"*).

---

## 📋 Requisitos
- Cuenta de Google para acceder a Colab.
- Archivo `cancion.mp3` (si se usa la función de base musical).

---

## ⚖️ Licencia
Este proyecto está bajo la Licencia **Apache 2.0**. Puedes usar, modificar y distribuir este código siguiendo los términos de dicha licencia.

---
*Nota: Este notebook está diseñado para ser ejecutado en la nube. No se recomienda su ejecución local sin una GPU compatible.*
