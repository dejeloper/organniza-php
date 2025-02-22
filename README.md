# Organizza - Control de Compras del Hogar

![Estado del Proyecto](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![Versión](https://img.shields.io/badge/versión-0.1.0-blue)
![PHP](https://img.shields.io/badge/PHP-8.0%2B-purple)
![Laravel](https://img.shields.io/badge/Laravel-10.x-red)

Organizza es una aplicación web desarrollada con PHP, Laravel y Filament, diseñada para gestionar y controlar las compras del hogar de manera eficiente.

<!-- ![Dashboard Preview](docs/images/dashboard-preview.png) -->

## Tecnologías Utilizadas

-   **PHP**: Lenguaje de programación principal.
-   **Laravel**: Framework para desarrollo backend.
-   **Filament**: Panel de administración moderno basado en Laravel.
-   **MySQL**: Base de datos relacional para almacenar la información.
-   **TailwindCSS**: Para estilización y diseño moderno.

## Características

-   Registro y gestión de compras del hogar.
-   Panel de administración intuitivo con Filament.
-   Reportes y estadísticas sobre los gastos.
-   Multiusuario con roles y permisos.

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto en tu máquina local:

### Requisitos Previos

-   PHP 8+
-   Composer
-   Node.js y NPM
-   MySQL
-   Servidor web (Apache o Nginx)

### Pasos de Instalación

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/dejeloper/organniza-php.git
    cd organzza
    ```
2. Instalar dependencias de Laravel:
    ```bash
    composer install
    ```
3. Configurar variables de entorno:
    ```bash
    cp .env.example .env
    ```
    Edita el archivo `.env` y configura la base de datos.
4. Generar la clave de aplicación:
    ```bash
    php artisan key:generate
    ```
5. Migrar la base de datos:
    ```bash
    php artisan migrate --seed
    ```
6. Instalar dependencias frontend:
    ```bash
    npm install && npm run build
    ```
7. Levantar el servidor de desarrollo:
    ```bash
    php artisan serve
    ```

## Estructura del Proyecto

```
organniza/
├── app/
│   ├── Http/          # Controladores y Middleware
│   ├── Models/        # Modelos de la aplicación
│   └── Filament/      # Recursos y páginas de Filament
├── database/
│   ├── migrations/    # Migraciones de la base de datos
│   └── seeders/      # Seeders para datos de prueba
├── resources/
│   ├── views/        # Vistas Blade
│   ├── css/         # Archivos CSS
│   └── js/          # Archivos JavaScript
└── routes/           # Definición de rutas
```

## FAQ

**P: ¿Puedo usar Organizza en mi negocio?**
R: Organizza está diseñado principalmente para uso doméstico, aun no se tiene esa visión.

**P: ¿Cómo puedo contribuir al proyecto?**
R: Puedes contribuir abriendo issues, proponiendo mejoras o enviando pull requests.

**P: ¿Existe una versión móvil?**
R: Está en desarrollo. Mientras tanto, la interfaz web es responsive.

## Guía de Contribución

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### Estándares de Código

-   Seguimos PSR-12 para PHP
-   Utilizamos Laravel Pint para el formateo de código
-   Los commits deben seguir el formato Conventional Commits

## Roadmap

### Q2 2024 (Abril - Junio)

-   [ ] Configuración inicial del proyecto
    -   [ ] Implementación de autenticación y autorización
    -   [ ] Configuración de roles y permisos básicos
    -   [ ] Estructura base de la base de datos
-   [ ] Funcionalidades core
    -   [ ] CRUD de productos
    -   [ ] CRUD de categorías
    -   [ ] Gestión básica de compras
-   [ ] Panel administrativo con Filament
    -   [ ] Dashboard inicial
    -   [ ] Gestión de usuarios
    -   [ ] Reportes básicos

### Q3 2024 (Julio - Septiembre)

-   [ ] Mejoras en la gestión de compras
    -   [ ] Sistema de listas de compras
    -   [ ] Historial detallado de compras
    -   [ ] Comparador de precios básico
-   [ ] Sistema de presupuestos
    -   [ ] Presupuestos mensuales
    -   [ ] Alertas de límites de gastos
    -   [ ] Categorización de gastos
-   [ ] Mejoras en reportes
    -   [ ] Gráficos interactivos
    -   [ ] Exportación de datos
    -   [ ] Análisis de tendencias

### Q4 2024 (Octubre - Diciembre)

-   [ ] Características avanzadas
    -   [ ] Sistema de notificaciones
    -   [ ] Recordatorios de compras
    -   [ ] Integración con calendario
-   [ ] Optimizaciones
    -   [ ] Mejoras de rendimiento
    -   [ ] Optimización de consultas
    -   [ ] Caché y almacenamiento
-   [ ] Preparación para escalabilidad
    -   [ ] Documentación técnica
    -   [ ] Tests automatizados
    -   [ ] CI/CD pipeline

## Seguridad

Si descubres alguna vulnerabilidad de seguridad, por favor envía un email a security@organniza.com en lugar de usar el sistema de issues.

## Soporte

-   📫 Email: jhonatanguerrero@outlook.com
<!-- -   💬 Discord: [Unirse al servidor](https://discord.gg/organniza) -->
-   📖 [Documentación](https://docs.organniza.dejeloper.com)
-   🐛 [Reportar un bug](https://github.com/dejeloper/organniza-php/issues)

## Uso

1. Accede a la aplicación en `http://localhost:8000`.
2. Inicia sesión con el usuario administrador.
3. Registra compras, revisa reportes y administra usuarios.

## Despliegue

Próximamente será desplegado en: [organniza.dejeloper.com](http://organniza.dejeloper.com).

## Contribución

Si deseas contribuir, abre un issue o un pull request en el repositorio.

## Repositorio

El código fuente está disponible en: [GitHub](https://github.com/dejeloper/organniza-php)

## Licencia

Este proyecto está bajo la licencia MIT. Puedes utilizarlo libremente, pero **no está permitido lucrar con él**.

---

✨ ¡Muchas gracias por tu valioso apoyo a este proyecto! Tu contribución es muy importante para nosotros. ✨
