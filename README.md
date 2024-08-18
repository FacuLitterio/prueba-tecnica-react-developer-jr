# Prueba Técnica — React Developer Jr.

## Objetivo

El objetivo de esta prueba técnica es evaluar tus habilidades en el desarrollo front-end utilizando React. Queremos ver cómo manejas las tecnologías y herramientas que formarían parte de tu día a día, así como tu capacidad para resolver problemas y crear una solución funcional y bien estructurada.

## Desarrollo del Proyecto

1. **Repositorio**: Clona este repositorio para poder modificarlo y completar la prueba.
3. **Configuración**: Puedes utilizar `Vite` para inicializar el proyecto y `TypeScript` para el desarrollo.

## Prueba Técnica

Usando React, debes crear una aplicación sencilla que realice un `fetch` a una API y muestre la información obtenida en una tabla. La aplicación debe cumplir con los siguientes requisitos:

### Funcionalidades

1. **Fetch de Datos**:
   - Realiza una petición a la API: [Random Users API](https://api.freeapi.app/api/v1/public/randomusers) para obtener una lista de usuarios.
   - Muestra los datos de los usuarios en una tabla.

2. **Ordenación**:
   - La tabla debe contener dos botones para ordenar los datos por el `ID` de los usuarios:
     - **Ascendente**: Ordena los usuarios de menor a mayor ID.
     - **Descendente**: Ordena los usuarios de mayor a menor ID.

### Componentes

1. **Tabla de Usuarios**:
   - Muestra la siguiente información de cada usuario:
     - `ID`
     - `Nombre Completo` (`first_name` y `last_name`)
     - `Email`
     - `Ciudad`
     - `País`

2. **Botones de Ordenación**:
   - Los botones deben estar claramente visibles y permitir la ordenación de los usuarios en la tabla por su `ID`.

## Requisitos de Stack

Para el desarrollo de la aplicación debes utilizar:

- **React** / **React Hooks**
- **CSS** (o similar) para los estilos
- **TypeScript**

## Instalación y Ejecución

Sigue estos pasos para configurar y ejecutar la aplicación en tu entorno local:

1. **Clonar el Repositorio:**

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio

2. **Instalar Dependencias:**

   ```bash
   npm install

3. **Ejecutar la Aplicacion en Modo Desarrollo:**

   ```bash
   npm run dev

¡Happy Coding!