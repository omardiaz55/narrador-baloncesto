# Narrador de Baloncesto - Aplicación Web

Esta es una aplicación web diseñada para mejorar la eficiencia de los narradores de baloncesto, permitiéndoles gestionar y visualizar los datos de los jugadores que están en la cancha durante un partido.

## Características principales

- **Gestión de jugadores**: Puedes ingresar los datos de todos los jugadores de ambos equipos y almacenarlos en el navegador para acceder a ellos más tarde.
- **Visualización de jugadores en la cancha**: Muestra una tabla con cinco jugadores en la cancha para cada equipo (equipo visitante y equipo en casa), separadamente.
- **Selección rápida**: Los jugadores que ya están almacenados pueden seleccionarse desde un menú desplegable, evitando la necesidad de volver a ingresar sus datos manualmente.
- **Almacenamiento local**: Utiliza LocalStorage para guardar los datos, lo que significa que la información no se perderá al actualizar la página.
- **Borrar base de datos**: Incluye un botón "Borrar base de datos" para eliminar los datos almacenados en LocalStorage.
- **Interfaz minimalista**: La interfaz es simple y limpia para reducir distracciones y facilitar la visualización rápida durante el juego.
- **Diseño responsivo**: La aplicación está optimizada para funcionar correctamente tanto en computadoras de escritorio como en dispositivos móviles.

## Cómo utilizar la aplicación

1. **Ingresar jugadores**: Ve a la sección de "Base de Datos de Jugadores" para ingresar los datos de los jugadores de ambos equipos.
2. **Asignar jugadores a la cancha**: Utiliza los menús desplegables para seleccionar a los jugadores que están en la cancha y mostrarlos en las tablas correspondientes a "Equipo Visitante" y "Equipo en Casa".
3. **Borrar base de datos**: Si deseas reiniciar los datos almacenados, presiona el botón "Borrar base de datos".

## Despliegue

Este proyecto está desplegado en [GitHub Pages](https://tu-usuario.github.io/narrador-baloncesto/) para acceder de forma remota. Puedes visitar la página web desde cualquier dispositivo con acceso a internet.

## Tecnologías utilizadas

- **HTML**: Estructura de la aplicación.
- **CSS**: Estilos para la visualización y diseño responsivo.
- **JavaScript**: Lógica de la aplicación, manejo del DOM y almacenamiento local con LocalStorage.

## Cómo clonar el proyecto

Si deseas clonar el proyecto para ejecutarlo localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/narrador-baloncesto.git
