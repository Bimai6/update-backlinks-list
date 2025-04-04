# Generador de lista de backlinks 🚀

## Descripción 📝

El **Generador de lista de backlinks** es una herramienta interna diseñada para ayudar a saneamiento y normalización de listas de backlinks. La herramienta permite combinar una lista de dominios de un archivo TXT con una lista sin sanear de un archivo CSV. La aplicación transforma las URLs del archivo CSV a un formato específico, elimina duplicados, elimina líneas vacías, y genera una nueva lista limpia que se puede descargar.

Esta herramienta es útil para equipos de marketing, SEO o análisis que necesitan tener una lista de backlinks normalizada para su análisis o reporte.

## Características 🔧

- **Combina archivos TXT y CSV**:
  - El archivo TXT contiene una lista de dominios del mes anterior 📅.
  - El archivo CSV contiene una lista de dominios sin sanear del mes actual 🗓️.
- **Saneamiento de dominios**:
  - Se elimina la primera línea del archivo CSV ❌.
  - Se transforman las URLs al formato `domain:<dominio>`, eliminando cualquier ruta adicional 🌐.
  - Se eliminan los duplicados y las líneas vacías del archivo final 🚫.
- **Generación de archivo descargable**:
  - Al finalizar el saneamiento, se genera un archivo descargable con los dominios procesados 💾.

## Requisitos ✅

- Un navegador web moderno (como Google Chrome, Mozilla Firefox, etc.) 🌍.
- No se requiere ningún servidor o instalación adicional, ya que la herramienta funciona completamente en el navegador 🔒.

## Instrucciones de uso ⚙️

1. **Subir los archivos** 📤:
   - **Selecciona la lista del mes anterior (TXT)**: Este archivo debe contener los dominios ya saneados del mes anterior 📜.
   - **Selecciona la lista sin sanear del mes actual (CSV)**: Este archivo debe contener las URLs a procesar 📊.

2. **Generar nueva lista** 🔄:
   - Haz clic en el botón **"Generar nueva lista saneada"**. La aplicación procesará ambos archivos y limpiará las URLs según las reglas definidas ⚒️.
   
3. **Descargar el archivo procesado** ⬇️:
   - Después de que se haya procesado la lista, aparecerá un enlace de descarga. Haz clic en **"Descargar lista"** para obtener el archivo de texto con los dominios únicos y normalizados 📥.
