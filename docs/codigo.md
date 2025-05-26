
---

### 📄 `docs/codigo.md`

```markdown
# Estructura del Código

A continuación, se describe la estructura del proyecto y los componentes principales del código.

## 📁 Archivos principales

### `app.py`

Contiene el flujo completo de la aplicación Streamlit:

- Configura la interfaz de usuario.
- Permite la carga de imágenes.
- Llama al motor de RemBG para remover el fondo.
- Muestra y permite descargar el resultado.

### `requirements.txt`

Lista de dependencias necesarias para ejecutar la app, incluyendo:

- `streamlit`
- `rembg`
- `Pillow`

Instalación recomendada:

```bash
pip install -r requirements.txt
