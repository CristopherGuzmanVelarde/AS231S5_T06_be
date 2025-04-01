# 🚀 Guía: Uso de Google Translate 113 API en Postman
![image](https://github.com/user-attachments/assets/6dec1e9e-d083-4718-8b1b-b52c8043add6)

Documentación paso a paso para probar el endpoint de traducción con **POST** en Postman.

![image](https://github.com/user-attachments/assets/2c3bd8dc-0cee-4605-ae3d-7db0a7f59ad6)


---

## 🔑 Requisitos Previos
1. **Cuenta en RapidAPI**:  
   Regístrate en [RapidAPI](https://rapidapi.com/auth/sign-up) y suscríbete al plan gratuito de [Google Translate 113](https://rapidapi.com/robust-api-robust-api-default/api/google-translate113).

2. **API Key**:  
   Copia tu clave desde el panel de RapidAPI:  
   ![Donde encontrar la API Key](https://i.imgur.com/JfK2bnG.png)

3. **Postman Instalado**:  
   Descarga [Postman](https://www.postman.com/downloads/).

---

## 📡 Configuración en Postman

### Paso 1: Crear una nueva solicitud
1. Haz clic en **New** > **Request**.
2. Nómbrala (ej. `Translate EN to ES`).

### Paso 2: Configurar el request
| Campo               | Valor |
|---------------------|-------|
| **Método HTTP**     | `POST` |
| **URL**             | `https://google-translate113.p.rapidapi.com/api/v1/translator/text` |

### Paso 3: Añadir headers
En la pestaña *Headers*, agrega:

| Key                | Value |
|--------------------|-------|
| `X-RapidAPI-Key`   | Tu API Key |
| `Content-Type`     | `application/json` |

![Headers en Postman](https://i.imgur.com/8mDfL3x.png)

---

## 📦 Ejemplo de Request (JSON)

### Paso 4: Enviar datos en el body
1. Ve a la pestaña **Body**.
2. Selecciona **raw** y **JSON**.
3. Ingresa este ejemplo:

```json
{
  "from": "en",
  "to": "es",
  "text": "Hello world, this is a test"
}

{
  "trans": "Hola mundo, esto es una prueba",
  "from": "en",
  "to": "es"
}
