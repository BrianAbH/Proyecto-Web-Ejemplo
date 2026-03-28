# Proyecto-Web-Ejemplo
Ejemplo comandos git

## Cambios Recientes
- Creado `index.html`: Página de tienda básica con productos de ejemplo.
- Creado `styles.css`: Estilos minimalistas para la página (fondo blanco, texto negro, diseño simple).
- Mejorado `styles.css`: Diseño responsivo, efectos hover, sombras sutiles, tipografía mejorada, layout con grid, animaciones de entrada (fade-in y slide-up), transiciones suaves, mejor accesibilidad con estados focus, y scroll suave.

## Cómo Clonar y Ejecutar el Proyecto Localmente

### Prerrequisitos
- Git instalado en tu sistema
- Un navegador web moderno (Chrome, Firefox, Safari, Edge)
- Opcional: Un servidor web local o extensión de servidor en tu editor

### Pasos para Clonar y Ejecutar

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/Proyecto-Web-Ejemplo.git
   cd Proyecto-Web-Ejemplo
   ```

2. **Abrir el proyecto:**
   - **Opción 1 (Más simple):** Abre directamente `index.html` en tu navegador
   - **Opción 2 (Recomendado):** Usa un servidor local:
     - Si tienes Python instalado: `python -m http.server 8000`
     - Si tienes Node.js: `npx http-server`
     - En VS Code: Usa la extensión "Live Server" y haz clic derecho sobre `index.html` → "Open with Live Server"

3. **Acceder a la aplicación:**
   - Si usas un servidor local, navega a `http://localhost:8000` (o el puerto indicado)
   - La página de tienda se cargará automáticamente

### Notas
- El proyecto es completamente responsivo y funciona en dispositivos móviles
- Los cambios en `styles.css` se aplicarán automáticamente al refrescar la página

## Ramas del Proyecto

El repositorio contiene las siguientes ramas organizadas por funcionalidad:

| Rama | Descripción |
|------|-------------|
| `main` | Rama principal con la versión estable del proyecto |
| `feature/diseño-responsivo` | Implementación del diseño responsivo y media queries |


### Descripción de Funcionalidades por Rama

- **main**: Contiene la versión estable del código con HTML, CSS y una estructura básica de tienda en línea
- **feature/diseño-responsivo**: Incluye grid layout, media queries y diseño adaptable a diferentes tamaños de pantalla

Para cambiar de rama, utiliza:
```bash
git checkout nombre-de-la-rama
```
