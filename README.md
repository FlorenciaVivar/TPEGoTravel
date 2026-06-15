# TPEGoTravel

## Descripción
TPEGoTravel es una aplicación web para la gestión y visualización de viajes y aerolíneas. Permite listar viajes, ver detalles, agregar, modificar y eliminar viajes y aerolíneas, con control de acceso para usuarios autenticados.

## Vista previa del Proyecto

| Principal | Listado de Viajes | Detalle |
| :---: | :---: | :---: |
| <img src="./assets/img/Captura de pantalla 2025-08-14 211855.png" width="100%" alt="Vista 1"> | <img src="./assets/img/Captura de pantalla 2025-08-14 212240.png" width="100%" alt="Vista 2"> | <img src="./assets/img/Captura de pantalla 2025-08-14 212248.png" width="100%" alt="Vista 3"> |
| **Filtros** | **Panel Admin** | **Gestión** |
| <img src="./assets/img/Captura de pantalla 2025-08-14 212337.png" width="100%" alt="Vista 4"> | <img src="./assets/img/Captura de pantalla 2025-08-14 212353.png" width="100%" alt="Vista 5"> | <img src="./assets/img/Captura de pantalla 2025-08-14 212359.png" width="100%" alt="Vista 6"> |

## Tecnologías utilizadas
- PHP (con patrón MVC)
- Smarty como motor de plantillas
- MySQL para la base de datos
- Bootstrap 5 para el diseño responsive y estilizado
- Git para control de versiones

## Funcionalidades
- Visualización de viajes y aerolíneas.
- Búsqueda y filtrado de viajes por aerolínea.
- Panel de administración para agregar, editar y eliminar viajes y aerolíneas (requiere login).
- Gestión de imágenes para viajes y aerolíneas.
- Manejo de sesiones y autenticación básica.

## Instalación y configuración

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/FlorenciaVivar/WEB2TPE.git
   
2. Configurar el servidor local (por ejemplo, XAMPP) y copiar los archivos al directorio htdocs (o equivalente).

3. Crear la base de datos e importar las tablas y datos iniciales con el script SQL:

    - Puedes usar el script db_tpe.sql desde phpMyAdmin o línea de comandos.

    - También podés usar el script bash importar_db.sh para eliminar y crear la base de datos automáticamente.

4. Acceder a la aplicación vía navegador con la URL correspondiente, por ejemplo: http://localhost/TPEGoTravel.

## Credenciales de acceso (usuario administrador)

    email addres : admin@admin.com
    password: 123456
