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
   ![image](https://github.com/user-attachments/assets/c54707e8-4b42-4671-8da3-405ade5f774a)


3. **Postman Instalado**:  
   Descarga [Postman](https://www.postman.com/downloads/). o trabaja desde el entorno en la misma pagina.
   Clic en Workspace como se indica con el rectangulo verde
   ![image](https://github.com/user-attachments/assets/dd9fad93-b4fe-4b21-bd9b-b3b78fc59ae3)


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

![image](https://github.com/user-attachments/assets/1ccfba79-cd63-4c38-8546-0287822e5958)

---

## 📦 Ejemplo de Request (JSON)

### Paso 4: Enviar datos en el body
1. Ve a la pestaña **Body**.
2. Selecciona **raw** y **JSON**.
3. Ingresa este ejemplo:

![image](https://github.com/user-attachments/assets/3da99589-02ce-4025-881b-ea286ebce8b6)

