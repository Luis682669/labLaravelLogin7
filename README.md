<<<<<<< HEAD
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework. You can also check out [Laravel Learn](https://laravel.com/learn), where you will be guided through building a modern Laravel application.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
=======
# labLaravelLogin7
Nombre: Luis De Los Rios
8-1011-1708
Correo: luis.delosrios@utp.ac.pa
Curso: Desarrollo VII
Introducción  
 
Model-View-Controller (MVC) es a la vez un patrón de diseño y un patrón de arquitectura. Se considera más bien un patrón arquitectónico, ya que intenta resolver estos problemas en la aplicación y afecta a la aplicación por completo. Los patrones de diseño se limitan a resolver un problema técnico específico. 
MVC divide una aplicación en tres secciones lógicas principales: 
•	Modelo 
•	Ver 
•	Controlador 
El Model El componente gobierna y controla la(s) base(s) de datos de la aplicación. Es el único componente en MVC que puede interactuar con la base de datos, ejecutar consultas, recuperar, actualizar, eliminar y crear datos. No sólo eso, sino que también es responsable de garan zar la evolución de la estructura de la base de datos de una etapa a otra manteniendo un conjunto de migraciones de bases de datos. El Modelo responde a instrucciones provenientes del Controlador para realizar determinadas acciones en la base de datos. 
•	Controladores (app/H p/Controllers): Con enen la lógica de negocio y coordinan la interacción entre modelos y vistas. 
 
•	Rutas (routes/web.php): Definen las URL de la aplicación y enlazan cada ruta con un controlador o una vista. 
 
•	Vistas (resources/views): Archivos Blade que muestran la interfaz al usuario. 
 
•	Modelos (app/Models): Representan las tablas de la base de datos y permiten interactuar con ellas mediante Eloquent ORM. 
 
Base De Datos 
 
DB_CONNECTION=sqlite 
APP_URL=h p://localhost 
 
php ar san migrate 
 
Dificultades y Soluciones 
Error de versión de PHP: El composer.json requería PHP ^8.3, pero estaba instalada la versión 8.2.29. 
Solución: Actualizar PHP a la versión 8.3 o superior. 
 
Problema con Vite no reconocido: Al ejecutar npm run dev, aparecía el error "vite" no se reconoce como un comando interno o externo. 
Solución: Ejecutar npm install para reinstalar dependencias y eliminar la carpeta node_modules. 
 
Error de configuración del .env: Laravel no encontraba la base de datos. 
Solución: Configurar correctamente DB_CONNECTION=sqlite y crear el archivo database.sqlite. 
 
<img width="903" height="838" alt="image" src="https://github.com/user-attachments/assets/c24186d8-b9a8-46c6-9575-9ba991e5b5ec" />
<img width="903" height="1178" alt="image" src="https://github.com/user-attachments/assets/6892acde-892f-4cbd-8afd-560cbea93670" />
<img width="903" height="483" alt="image" src="https://github.com/user-attachments/assets/8c8dfc62-1dc0-470d-bec1-98c0c3495100" />


>>>>>>> 2acaed158cebc69f0a4ea2f5f3707b46e4a5e273
