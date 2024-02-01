# Zalando Scraper & Database Poster

## Descripción

Este proyecto está diseñado para realizar web scraping en el sitio web de Zalando, extrayendo información sobre productos, y posteriormente, realizar publicaciones (POST) en una base de datos. Con esta herramienta, puedes mantener actualizada una base de datos local con detalles de productos específicos de Zalando.

## Características Principales

- **Web Scraping Eficiente:** Utiliza técnicas avanzadas para extraer información precisa sobre productos desde la plataforma Zalando.
- **Integración con Base de Datos:** Publica la información extraída en una base de datos para su almacenamiento y análisis.
- **Configuración Personalizada:** Ofrece opciones de configuración para adaptarse a diferentes necesidades y preferencias.
- **Registro Detallado:** Proporciona un registro detallado de las operaciones realizadas, facilitando el seguimiento y la depuración.

## Uso

1. **Instalación de Dependencias:**
   ```bash
   pip install -r requirements.txt

2. **Ejecución:**
- Crea el archivo de configuración .env para especificar los siguientes datos:
  - Url de la API para publicar los datos en nuestra Base de Datos(URL_API)
  - Id del chat de telegram(CHAT_ID) 
  - Link del bot de telegram que publicara los mensajes en el chat especificado(LINK_TELEGRAM) 

3. **Ejecución:**
   ```bash
   python zalando_scraper.py

- El scraper generará un archivo EXCEL con los datos extraídos en el directorio de salida especificado

4. **Resultados:**
- Encuentra los resultados y registros en los archivos de salida y en la base de datos configurada.

## Contribuciones
Las contribuciones son bienvenidas! Si encuentras algún problema o tienes ideas para mejoras, por favor, abre un issue o envía un pull request.

## Licencia
Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
