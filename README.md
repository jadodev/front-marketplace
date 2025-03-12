# FrontMarketplace

## Estructura del proyecto.
```plaintext
📦 src
 ┣ 📂 app                     # Carpeta principal de la aplicación
 ┃ ┣ 📂 components            # Componentes reutilizables
 ┃ ┃ ┣ 📂 card-product        # Componente de tarjeta de producto
 ┃ ┃ ┃ ┣ 📜 card-product.component.css
 ┃ ┃ ┃ ┣ 📜 card-product.component.html
 ┃ ┃ ┃ ┣ 📜 card-product.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 card-product.component.ts
 ┃ ┃ ┣ 📂 cart-icon           # Icono del carrito de compras
 ┃ ┃ ┃ ┣ 📜 cart-icon.component.css
 ┃ ┃ ┃ ┣ 📜 cart-icon.component.html
 ┃ ┃ ┃ ┣ 📜 cart-icon.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 cart-icon.component.ts
 ┃ ┃ ┣ 📂 cart                # Carrito de compras
 ┃ ┃ ┃ ┣ 📜 cart.component.css
 ┃ ┃ ┃ ┣ 📜 cart.component.html
 ┃ ┃ ┃ ┣ 📜 cart.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 cart.component.ts
 ┃ ┃ ┣ 📂 header              # Encabezado de la aplicación
 ┃ ┃ ┃ ┣ 📜 header.component.css
 ┃ ┃ ┃ ┣ 📜 header.component.html
 ┃ ┃ ┃ ┣ 📜 header.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 header.component.ts
 ┃ ┃ ┣ 📂 information-before-payment  # Información previa al pago
 ┃ ┃ ┃ ┣ 📜 information-before-payment.component.css
 ┃ ┃ ┃ ┣ 📜 information-before-payment.component.html
 ┃ ┃ ┃ ┣ 📜 information-before-payment.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 information-before-payment.component.ts
 ┃ ┃ ┣ 📂 insufficient-funds-modal    # Modal de fondos insuficientes
 ┃ ┃ ┃ ┣ 📜 insufficient-funds-modal.component.css
 ┃ ┃ ┃ ┣ 📜 insufficient-funds-modal.component.html
 ┃ ┃ ┃ ┣ 📜 insufficient-funds-modal.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 insufficient-funds-modal.component.ts
 ┃ ┃ ┣ 📂 order-summary        # Resumen de la orden
 ┃ ┃ ┃ ┣ 📜 order-summary.component.css
 ┃ ┃ ┃ ┣ 📜 order-summary.component.html
 ┃ ┃ ┃ ┣ 📜 order-summary.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 order-summary.component.ts
 ┃ ┃ ┣ 📂 payment-success-modal # Modal de pago exitoso
 ┃ ┃ ┃ ┣ 📜 payment-success-modal.component.css
 ┃ ┃ ┃ ┣ 📜 payment-success-modal.component.html
 ┃ ┃ ┃ ┣ 📜 payment-success-modal.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 payment-success-modal.component.ts
 ┃ ┃ ┣ 📂 products             # Lista de productos
 ┃ ┃ ┃ ┣ 📜 products.component.css
 ┃ ┃ ┃ ┣ 📜 products.component.html
 ┃ ┃ ┃ ┣ 📜 products.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 products.component.ts
 ┃ ┃ ┣ 📂 search              # Barra de búsqueda
 ┃ ┃ ┃ ┣ 📜 search.component.css
 ┃ ┃ ┃ ┣ 📜 search.component.html
 ┃ ┃ ┃ ┣ 📜 search.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 search.component.ts
 ┃ ┃ ┣ 📂 slider              # Carrusel de imágenes
 ┃ ┃ ┃ ┣ 📜 slider.component.css
 ┃ ┃ ┃ ┣ 📜 slider.component.html
 ┃ ┃ ┃ ┣ 📜 slider.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 slider.component.ts
 ┃ ┣ 📂 pages                 # Páginas principales de la aplicación
 ┃ ┃ ┗ 📂 home                # Página de inicio
 ┃ ┃ ┃ ┣ 📜 home.component.css
 ┃ ┃ ┃ ┣ 📜 home.component.html
 ┃ ┃ ┃ ┣ 📜 home.component.spec.ts
 ┃ ┃ ┃ ┗ 📜 home.component.ts
 ┃ ┣ 📂 services              # Servicios de la aplicación
 ┃ ┃ ┣ 📂 payment             # Servicio de pagos
 ┃ ┃ ┣ 📂 serviceCart         # Servicio del carrito de compras
 ┃ ┃ ┗ 📂 serviceProduct      # Servicio de productos
 ┃ ┃ ┗ 📂 serviceSearch       # Servicio de búsqueda
 ┃ ┣ 📜 app.component.css
 ┃ ┣ 📜 app.component.html
 ┃ ┣ 📜 app.component.spec.ts
 ┃ ┣ 📜 app.component.ts
 ┃ ┣ 📜 app.config.ts         # Configuración de la aplicación
 ┃ ┣ 📜 app.routes.ts         # Configuración de rutas
 ┣ 📜 index.html              # Página principal de la aplicación
 ┣ 📜 main.ts                 # Punto de entrada de la aplicación
 ┣ 📜 styles.css              # Estilos globales
 ┣ 📜 .editorconfig           # Configuración del editor
 ┣ 📜 .gitignore              # Archivos y carpetas a ignorar en Git
 ┣ 📜 Dockerfile              # Archivo para construir la imagen Docker
 ┗ 📜 README.md     
```
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












