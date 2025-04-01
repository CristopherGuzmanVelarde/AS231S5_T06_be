🌍 Google Translate 113 API Lab

Traducción de texto usando la API - Sube tus propias imágenes a Imgur

🔥 Características Principales

✅ Traducción en tiempo real con POST

✅ Soporte para más de 100 idiomas

✅ Plan gratuito (50 requests/día)

✅ Ejemplos listos para Postman y código

🚀 Guía: Uso de Google Translate 113 API en Postman

Documentación paso a paso para probar el endpoint de traducción con POST en Postman.

(Captura: Interfaz de Postman para pruebas de API)

🔑 Requisitos Previos

Cuenta en RapidAPI:Regístrate en RapidAPI y suscríbete al plan gratuito de Google Translate 113.

API Key:Copia tu clave desde el panel de RapidAPI:

Postman Instalado:Descarga Postman.

📡 Configuración en Postman

🛠 Paso 1: Crear una nueva solicitud

Haz clic en New > Request.

Nómbrala (ej. Translate EN to ES).

🔧 Paso 2: Configurar el request

Campo

Valor

Método HTTP

POST

URL

https://google-translate113.p.rapidapi.com/api/v1/translator/text

📝 Paso 3: Añadir headers

En la pestaña Headers, agrega:

Key

Value

X-RapidAPI-Key

Tu API Key

Content-Type

application/json



📦 Ejemplo de Request (JSON)

📨 Paso 4: Enviar datos en el body

Ve a la pestaña Body.

Selecciona raw y JSON.

Ingresa este ejemplo:

{
  "from": "en",
  "to": "es",
  "text": "Hello world, this is a test"
}

🚀 Funcionalidades de la API

La API de Google Translate 113 permite realizar las siguientes operaciones:

🔄 POST Translate text → Traducción de un solo texto de un idioma a otro especificado.

📑 POST Batch Translation → Traducción de múltiples textos en una sola solicitud, optimizando tiempos y recursos.

🛠 POST Translate JSON → Traducción de estructuras en formato JSON manteniendo la jerarquía del contenido.

🌐 POST Translate HTML → Traducción de contenido HTML, preservando etiquetas y estructura del documento.

🕵️ POST Detect Language → Detección automática del idioma de un texto sin necesidad de especificar el idioma de origen.

🌍 GET Supported Languages → Obtiene la lista de idiomas compatibles con la API para traducción y detección.
