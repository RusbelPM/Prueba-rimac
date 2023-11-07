## Sustentación del Proyecto - RIMAC FRONT END CHALLENGE
## Presentación
Esta propuesta aborda un proyecto de desarrollo de aplicación web frontend diseñada para simplificar el proceso de cotización y selección de seguros de vida. La solución proporciona una interfaz amigable y transparente que facilita la comprensión y la toma de decisiones de los potenciales clientes.

## Problema a Resolver
El proyecto se origina debido a la alta tasa de abandono de aplicaciones de seguros de vida, generalmente causada por interfaces engorrosas, aburridas y difíciles de entender.

## Solución
Nuestra solución busca simplificar la cotización de seguros de vida de manera directa y sencilla, eliminando los obstáculos que generan la pérdida de potenciales clientes.

## Análisis del Proyecto
Este proyecto se enfoca en desarrollar un sistema de cotización de planes de seguro de salud. La estructura se basa en tres páginas:

## Página 1: Seguro de Salud Flexible
La página "Seguro de Salud Flexible" tiene como objetivo principal registrar a un posible cliente, permitiéndole:

Seleccionar el tipo de documento (DNI, CE).
Ingresar el número de su documento.
Ingresar su número de celular.
Aceptar la política de privacidad.
Aceptar la política de comunicaciones comerciales.
Utilizar el botón "Cotizar Aquí".
Página 2: Planes
En esta etapa del proyecto, se presta especial atención a la aplicación de TDD (Test-Driven Development) para garantizar la calidad del desarrollo.

Página 3: Resumen
Requisitos Técnicos
Dadas las restricciones del entorno de aplicación, se han seleccionado las siguientes tecnologías y recursos:

Lenguaje de programación: JavaScript.
Biblioteca React/React-DOM.
Biblioteca React-Router-DOM.
TypeScript para el tipado de JavaScript.
Preprocesador de CSS: Sass.
Biblioteca react-router-dom para la navegación entre componentes.
Redux Toolkit.
Instalación
A continuación, se presentan las instrucciones de instalación para las principales dependencias del proyecto:

Pruebas con Jest y Testing Library
js
Copy code
npm install --save-dev jest
npm install --save-dev @testing-library/react
npm install --save-dev @testing-library/jest-dom
React Router DOM
js
Copy code
npm install react-router-dom
Axios
js
Copy code
npm install axios
Redux Toolkit
js

npm install react-redux
npm install @reduxjs/toolkit
Desarrollo de la Solución
En el desarrollo de esta solución, se ha optado por utilizar la herramienta Vite, que ofrece una rápida compilación y permite el uso de TypeScript sin configuraciones complejas. Además, se ha implementado Gulp como automatizador de tareas para compilar archivos Sass y generar archivos CSS para cada componente. El archivo .gitignore se ha creado con la herramienta gitignore.io.

Estructura de Carpetas
La estructura del proyecto se organiza siguiendo una metodología centrada en TDD y diseño atómico. A continuación, se presenta la estructura de carpetas utilizada:


RIMAC-FRONTEND-CHALLENGE/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   │   ├── fonts/
│   │   ├── images/
│   ├── components/
│   │   ├── Atoms/
│   │   ├── Molecules/
│   │   ├── Organisms/
│   │   ├── Pages/
│   │   └── Templates/
│   ├── redux/
│   │   ├── slices/
│   ├── styles/
│   │   ├── scss/
│   ├── utils/
│   ├── services/
│   ├── App.js
│   ├── index.js
│   ├── index.css
│   ├── services/
│   ├── types/
│   ├── assets/
│   ├── config/
├── .eslintrc
├── .gitignore
├── gulpfile.js
├── index.html
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
├── .prettierrc
├── .babelrc
