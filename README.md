# FrontMarketplace

## Video.
[![Video de YouTube](miniatura.png)](https://youtu.be/0HygzS95JYQ)

# Proyecto Angular: Marketplace

Este proyecto es una aplicación frontend desarrollada en **Angular** que sigue una estructura **modular y escalable**, diseñada para facilitar el mantenimiento y la expansión del código.

## Endpoint del Frontend

La aplicación está desplegada en S3 + Amplify y puede ser accedida a través del siguiente enlace:

**Frontend Tienda:** [https://staging.d2bc1j4y9fmfbf.amplifyapp.com/home](https://staging.d2bc1j4y9fmfbf.amplifyapp.com/home)

## Despliegue Local con Docker

Para ejecutar el proyecto localmente, puedes utilizar Docker. A continuación, se detallan los pasos necesarios para desplegar la aplicación en tu entorno local.

### Requisitos Previos

- **Docker** instalado en tu máquina. Puedes descargarlo desde [aquí](https://www.docker.com/get-started).

### Pasos para Desplegar el Proyecto

1. **Clona el repositorio** en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git](https://github.com/jadodev/front-marketplace.git
   ```

2.**Ingresa a la raíz del proyecto en tu terminal y ejecuta 

```bash
  docker build -t marketplace .
```

3**Al terminar el proceso ejecuta el siguiente comando para iniciar la aplicacion:

```bash
  docker run -p 4200:80 marketplace
```
### Funcionalidad:

#### Esta app permite almacenar productos en el carrito, filtrar productos y hacer compras con la tarjeta propia de **Bank Inc** , pero primero debes registrarte en [https://staging.d1pxievg15tb8f.amplifyapp.com/auth](https://staging.d1pxievg15tb8f.amplifyapp.com/auth).











