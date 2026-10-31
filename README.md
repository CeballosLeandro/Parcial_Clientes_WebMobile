# Vivi Show 🎬

Aplicación web para buscar películas y series, consultar sus detalles y guardar títulos favoritos.

## Tecnologías utilizadas

- React
- Vite
- JavaScript
- CSS
- React Router
- API de OMDb

## Instalación

1. Clonar o descargar el proyecto.
2. Abrir una terminal en la carpeta del proyecto.
3. Instalar las dependencias:

```bash
npm install
```

4. Crear un archivo `.env` en la raíz del proyecto, tomando como referencia `.env.ejemplo`.
5. Completar las variables de entorno con los datos correspondientes:

```env
VITE_API_URL=https://www.omdbapi.com
VITE_API_KEY=TU_API_KEY
VITE_TITULO=Vivi Show
```

## Ejecutar el proyecto

Iniciar el servidor de desarrollo con:

```bash
npm run dev
```

Luego abrir en el navegador la dirección que muestra la terminal.

## Funcionalidades

- Buscar películas y series.
- Filtrar resultados por tipo y año.
- Navegar entre páginas de resultados.
- Consultar información detallada de cada título.
- Agregar y quitar películas de favoritos.
- Mantener los favoritos guardados mediante localStorage.
- Navegar entre las diferentes secciones de la aplicación.

## Decisiones de desarrollo

- Se utilizó React para construir una interfaz basada en componentes reutilizables.
- Se utilizó React Router para administrar la navegación.
- Se creó un hook para realizar búsquedas y otro para obtener datos de la API.
- Los favoritos se guardan en localStorage para conservarlos al recargar la página.
- Las variables de entorno permiten configurar la API sin escribir la clave directamente en los componentes.
- Se utilizaron estilos CSS adaptables a diferentes tamaños de pantalla.

