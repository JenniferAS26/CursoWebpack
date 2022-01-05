# CursoWebpack

# Pasos para crear el proyecto
- 1. git init -> inicializar el repositorio
- 2. npm init (opcional -y para la configuracion por defecto)
- 3. code . -> para inicializar Visual Studio Code
- 4. Crear carpera src
    - 4a. index.js -> punto de entrada del proyecto

# Instalacion de Webpack
- 1. npm install webpack webpack-cli -D 
    - webpack-cli: para trabajar con comandos dentro de nuestra terminal
    - -D: para guardarlo como una dependencia de desarrollo
    - Enter para proceder con la instalacion
    - Hasta esta parte no hemos instalado Webpack de manera global, solo en nuestro proyecto
- 2. npx webpack
    - Va a leer nuestro proyecto e identificar el archivo index o todos los archivos JavaScript y nos va a preparar nuestro proyecto
- 3. Volvemos a nuestro editor de codigo
    - Sin ningun archivo de configuracion ya detecto que tenemos un archivo index.js 
    - Creo una carpeta dist y un archivo main.js que tiene el codigo resultante
- 4. npx webpack --mode development 
    - para activar el modo desarrollo
- 4. npx webpack --mode production 
    - para activar el modo produccion

#

