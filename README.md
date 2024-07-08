# Proyecto de Login con React y Vite

Este proyecto es una aplicación de login simple construida con React y Vite. Permite a los usuarios autenticarse con un usuario y contraseña hardcodeados y acceder a una ruta protegida si las credenciales son correctas.

## Descripción de los Componentes

### `App.jsx`

Este componente principal configura las rutas de la aplicación y gestiona el estado de autenticación.

- **Rutas:**
  - `/login`: Muestra el componente `Login`.
  - `/protected`: Muestra el componente `Protected` si el usuario está autenticado.
  - Redirección: Redirige a `/login` por defecto si no está autenticado.

### `Login.jsx`

El componente de login que maneja la autenticación y redirección.

- **Estado:**
  - `username`: Guarda el nombre de usuario ingresado.
  - `password`: Guarda la contraseña ingresada.

- **Funciones:**
  - `handleLogin`: Verifica las credenciales al hacer submit.
    - Si son correctas, establece el estado de autenticación y redirige a `/protected`.
    - Si son incorrectas, muestra una alerta y limpia los campos del formulario.

### Tecnologías Utilizadas

- **React:** Biblioteca de JavaScript para construir interfaces de usuario.
- **Vite:** Herramienta de construcción rápida para aplicaciones web modernas.
- **react-router-dom:** Librería para manejar el enrutamiento en aplicaciones React.

## Uso

1. **Ejecutar la Aplicación:**
   - Ejecuta el servidor de desarrollo.
   - Abre tu navegador y navega a la URL local para interactuar con la aplicación.

Este README proporciona una visión general del proyecto y explica cómo están estructurados los componentes principales y las tecnologías utilizadas.
