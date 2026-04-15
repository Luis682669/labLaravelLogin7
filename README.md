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


