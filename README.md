### Instalacion luego de clonar

2. Instalar dependencias
   `npm i`

3. Configurar Base de datos
   `npx prisma generate`
   `npx prisma migrate dev --name init`
   `npm run seed`

4. Correr el proyecto
   `npm run dev`