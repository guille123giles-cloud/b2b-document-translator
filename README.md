# Plataforma B2B de Traducción Documental 📄🌍

Esta es una aplicación web serverless diseñada para traducir documentos legales y técnicos (PDF a Word) manteniendo estrictamente el formato, las tablas y la estructura original.

## 🚀 Características Principales
* **Traducción Integral:** Conversión de PDF a Word preservando el layout original.
* **Procesamiento Concurrente:** Implementación de `concurrent.futures` para manejar múltiples hilos, reduciendo el tiempo de procesamiento y evitando bloqueos de red (Rate Limits).
* **Escaneo Profundo:** Uso de XPath para la manipulación precisa de árboles XML dentro de los documentos.
* **Despliegue Cloud:** Lista para usar en Streamlit Cloud.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Streamlit, PyPDF2, pdf2docx, concurrent.futures.
* **Procesamiento de Datos:** XML (XPath).

## 📦 Instalación y Uso
1. Clonar el repositorio.
2. Instalar dependencias: `pip install -r requirements.txt`.
3. Ejecutar la app: `streamlit run app.py`.

---
*Proyecto desarrollado por [Guillermo Giles](https://github.com/guille123giles-cloud)*
