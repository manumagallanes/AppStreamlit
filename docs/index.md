# AppStreamlit - Eliminador de Fondo de Imágenes

**AppStreamlit** es una aplicación web desarrollada con [Streamlit](https://streamlit.io/) que permite remover automáticamente el fondo de cualquier imagen cargada por el usuario. Utiliza inteligencia artificial para segmentar la imagen y devolverla con fondo transparente.

## 🎯 Objetivo

Facilitar la edición de imágenes eliminando el fondo con un solo clic, sin necesidad de herramientas complejas como Photoshop.

## ⚙️ Funcionalidades

- Carga de imágenes (formatos comunes como `.jpg`, `.png`)
- Procesamiento automático con IA
- Visualización del resultado
- Descarga de la imagen sin fondo

## 🧠 Tecnologías utilizadas

- Python
- Streamlit
- RemBG (motor de eliminación de fondo basado en IA)
- Pillow para manejo de imágenes

## 🗂️ Estructura del proyecto

```
AppStreamlit/
├── app.py                 # Aplicación principal en Streamlit
├── requirements.txt       # Lista de dependencias
├── media/                 # Carpeta con imágenes de ejemplo
├── logo.png               # Logo mostrado en la app
├── README.md              # Descripción general del proyecto en GitHub
├── LICENSE                # Licencia Apache 2.0
```

## 🚀 Cómo ejecutar la app

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/manumagallanes/AppStreamlit.git
   cd AppStreamlit
   ```

2. Instalá las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutá la app:

   ```bash
   streamlit run app.py
   ```

4. Abrí el navegador en: [http://localhost:8501](http://localhost:8501)

## 📥 Resultado esperado

Una interfaz simple donde podés subir una imagen, visualizarla sin fondo y descargarla directamente en formato `.png`.

## 📄 Licencia

Este proyecto está bajo la licencia Apache 2.0. Ver el archivo `LICENSE` para más detalles.
