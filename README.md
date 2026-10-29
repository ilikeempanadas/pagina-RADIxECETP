# RADIxECETP — versión local sin servidor

## Importante
Esta versión NO utiliza PHP, MySQL, XAMPP, API ni conexión externa. Los datos de demostración se guardan en `localStorage` del navegador desde `js/app.js`, bajo la clave `radixecetp_internal_db_v1`. Sirve para presentar y probar el funcionamiento en un solo navegador/equipo. No sincroniza información entre equipos y no es adecuada para almacenar datos personales reales.

## Cómo abrir
1. Descomprime la carpeta `RADIxECETP_Local`.
2. Abre `index.html` en un navegador moderno (Chrome, Edge o Firefox).
3. Ingresa con una de estas cuentas:
   - Administrador: `10010001` / `admin2026`
   - Docente: `10010009` / `12345678`
   - Estudiante: `1032445717` / `12345678`
4. Los cambios quedan guardados en el navegador. Si borras los datos del sitio o cambias de navegador, no se comparten automáticamente.

## Organización
- `index.html`: landing, formulario de acceso y estructura de la aplicación.
- `css/styles.css`: estilos y diseño adaptable.
- `js/app.js`: datos internos, inicio de sesión, navegación, dashboard, gráficas, calificaciones, anotaciones, apelaciones, acudientes, explorador de tablas y exportaciones.
- `assets/`: imágenes del proyecto.

## Funciones incluidas
- Dashboard administrativo con gráficas por rol y estado de apelaciones.
- Explorador de tablas locales para personas, grupos, materias, notas, anotaciones y asignaciones.
- Exportación de la tabla seleccionada a CSV y respaldo de la base interna a JSON.
- Docentes: registro de notas con descripción breve y anotaciones con tipo, fecha y descripción.
- Estudiantes: consulta de notas y anotaciones, envío de su versión/apelación y consulta de estado.
- Administrador: revisión y cambio del estado de apelaciones.
- Estudiantes: visualización de datos de madre, padre y acudiente.

## Nota de seguridad
Los datos y contraseñas de esta versión son demostrativos y se guardan en el navegador. No uses contraseñas reales ni información personal real. `localStorage` no reemplaza una base de datos segura ni un sistema de autenticación para producción.
