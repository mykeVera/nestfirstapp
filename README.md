*** NEST JS REST API - [] SIMULA DDBB ***

Nestjs, Tu primer aplicacion Backend desde cero
https://www.youtube.com/watch?v=7fOjuCGE_jk&ab_channel=FaztCode

* 1. Instalar nest js de forma globla

npm i -g @nestjs/cli

* 2. Iniciar un proyecto nuevo (nestfirstapp)

nest new project-name

* Lista todos los comando a ejecutar con nest js

nest 

* 3. Generamos un nuevo modulo (taks)

nest generate module taks

* 4 Generamos un nuevo controlador (taks) --no-spec -> para no crear archivo testing

nest generate controller tasks --no-spec

* 5 Generamos un nuevo servicio (taks) --no-spec -> para no crear archivo testing

nest generate service tasks --no-spec

* 6 Creamos una entidad en la carpeta del modulo

task.entity.ts

* 7 Instalamos uuid para generar id unicos (opcional)

npm i uuid
npm i --save-dev @types/uuid -D

* 8 Se crea una carpeta manual (dto) y dentro un archivo

dto -> task.dto.ts

* 9 Instalamos validation de nest

npm i --save class-validator class-transformer

* 10 Para que funcionen las validaciones agregar el codigo en main.ts

 app.useGlobalPipes(new ValidationPipe());

 * 11 Recuerda, el codigo que para ejecutar en ambiente desarrollo es:

 npm run start:dev

 * 12 Para ejecutar el buid para produccion es: (Genera la carpeta de producción)

npm run build

* 13 Y para ejecutar la aplicacion en produccion:

npm start




