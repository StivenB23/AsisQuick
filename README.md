# Sistema de Gestión de Incidencias en Aulas y Equipos de Cómputo

## Descripción
Este es un sistema de gestión de incidencias diseñado para una institución académica. El software permite a los docentes y usuarios reportar problemas en los ambientes de clase y equipos de cómputo de manera eficiente, facilitando su seguimiento y resolución. El objetivo principal es asegurar condiciones óptimas para el desarrollo de las actividades académicas.

## Funcionalidades Principales
- **Notificación de Incidencias**: Permite a los usuarios reportar problemas en los ambientes de clase y equipos de cómputo.
- **Seguimiento de Incidencias**: Los usuarios pueden verificar el estado de las incidencias desde su notificación hasta su resolución.
- **Alertas Automáticas**: Notificaciones automáticas sobre el estado de las incidencias, resolución, tiempos estimados, y responsables.
- **Gestión Administrativa**: Panel de control para visualizar estadísticas sobre el estado general de aulas y equipos, tiempos de respuesta, y eficiencia.
- **Roles y Permisos**: Control de acceso mediante diferentes roles (docentes, técnicos, administradores).
- **Reportes y Análisis**: Visualización de patrones recurrentes y análisis de desempeño.
- **Acceso desde Móviles**: Compatible con dispositivos móviles y tablets.
- **Seguridad**: Autenticación de usuarios y control de accesos para proteger la información.

## Tecnologías Utilizadas
- **Backend**: PHP con el framework **Laravel**
- **Frontend**: Blade, HTML5, CSS3, JavaScript
- **Base de Datos**: MySQL
- **Servidor Web**: Apache
- **Metodología de Desarrollo**: SCRUM
- **Gestión de Proyecto**: Jira

## Requisitos Previos
1. PHP 8.0+
2. Composer
3. MySQL 5.7+
4. Apache Web Server
5. Laravel

## Instalación
1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/StivenB23/AsisQuick
2. Instala las dependencias de PHP con Composer:
   ```bash
    cd AsisQuick
    composer install
3. Configura el archivo .env:
   ```bash
    cp .env.example .env
    php artisan key:generate
4. Configura la base de datos en el archivo .env y luego migra las tablas:
   ```bash
    php artisan migrate
5. Inicia el servidor de desarrollo:
   ```bash
    php artisan serve
6. Accede a la aplicación a través de http://localhost:8000.




