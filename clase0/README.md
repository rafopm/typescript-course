Instalación: en la raiz
npm install typescript --save-dev

Inicializar
npx tsc --init

Build:
Modificar configuración de tsconfig.json
 "rootDir": "./src", 
 "outDir": "./dist",  

npx tsc

Ejecución:
node src/index.js