# Sistema Gestión de Bienes COSEDE

## Descripción  
Sistema de gestión de bienes desarrollado bajo la arquitectura de capas, que permite el registro, consulta y administración de activos para COSEDE. Incluye un panel web responsivo, API REST y servicios de integración con contenedores Docker.

---

## Arquitectura MVC
1. **Presentación**  
   - Laravel Blade (templates) y Tailwind CSS/Vite  
   - Componentes JavaScript (ES Modules)  

2. **Aplicación**  
   - Controladores HTTP (Laravel Controllers)  
   - Rutas definidas en `routes/web.php` y `routes/api.php`  

3. **Dominio / Negocio**  
   - Modelos Eloquent (`app/Models`)  
   - Repositorios y servicios de negocio (`app/Services`)  

4. **Infraestructura**  
   - Base de datos PostgreSQL  
   - Contenedores Docker para base de datos y entorno  
   - Configuración de colas y jobs (`config/queue.php`)  

---

## Tecnologías Utilizadas

- **Lenguaje y Framework**  
  - PHP 8.x, [Laravel 10.x](https://laravel.com/)  
- **Frontend**  
  - JavaScript (ES6+)  
  - Tailwind CSS  
  - Vite (bundler y dev server)  
  - npm / Node.js  
  - PostCSS  
- **Base de Datos**  
  - PostgreSQL  
- **Contenedores y DevOps**  
  - Docker & Docker Compose  
- **Gestión de dependencias y pruebas**  
  - Composer  
  - PHPUnit  
  - SonarQube (análisis de calidad)  
- **Control de versiones**  
  - Git & GitHub  

---

## Requisitos Previos

- PHP ≥ 8.1  
- Composer  
- Node.js ≥ 16.x y npm  
- Docker ≥ 20.x & Docker Compose  
- PostgreSQL ≥ 14.x  

---

## Instalación y Puesta en Marcha

1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/LeoSandov/SistemaGestionBienesCOSEDE.git
   cd SistemaGestionBienesCOSEDE
