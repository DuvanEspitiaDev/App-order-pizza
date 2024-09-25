*App-order-pizza*

Tecnologías Utilizadas

Este proyecto está desarrollado usando las siguientes tecnologías:

- React: Librería de JavaScript para construir interfaces de usuario.
- React Hooks: Manejo del estado y otros efectos secundarios sin la necesidad de escribir clases.
- React Router: Manejo de las rutas de la aplicación.
- Tailwind CSS: Framework de utilidades CSS para un desarrollo rápido y responsivo.
- React Redux: Manejo del estado global de la aplicación.
  - Redux Toolkit: Conjunto de herramientas oficiales de Redux para simplificar el desarrollo.

Instalación

Sigue los siguientes pasos para instalar el proyecto en tu máquina local:

1. Clona el repositorio:

   
   git clone https://github.com/usuario/nombre-del-proyecto.git
 

2. Entra en el directorio del proyecto:


   cd App-order-pizza
  

3. Instala las dependencias:


   npm install

 Uso

Para iniciar la aplicación en modo de desarrollo, dado que esta en vite, debes hacer la correcta configuración de entorno:


npm run dev

Estructura del Proyecto

src/
├── features/
│   ├── cart/        # Lógica y componentes relacionados con el carrito de compras
│   ├── menu/        # Gestión del menú de productos
│   ├── order/       # Funcionalidad relacionada con los pedidos
│   ├── services/    # Servicios de API o lógica de negocio
│   └── user/        # Gestión de usuarios (registro, autenticación, etc.)
├── ui/              # Componentes relacionados con la interfaz de usuario
├── utils/           # Funciones utilitarias y helpers
├── App.jsx          # Componente raíz de la aplicación
├── index.css        # Estilos globales usando Tailwind CSS
├── main.jsx         # Punto de entrada principal
├── store.js         # Configuración del store de Redux
  

Licencia

Este proyecto fue desarrollado como parte del curso "The Ultimate React Course" de Jonas Schmedtmann en Udemy. Está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
