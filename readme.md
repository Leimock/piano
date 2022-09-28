   # Empaquetado web

    Tengo ofuscación
    Tengo mimificación
    Tego compresion de imagenes
    Tree shaking
    Tengo preprocesadores de css (scss)
    Tengo frameworks de css (tailwind)
    Tengo frameworks web (react, vue)
    Uso de lenguajes que no sean javascrypt (typescript, jsx)
    Tengo mecanismos de optimizacion del codigo
    Servidor de pruebas
    Testing
    etc etc


   # Empaquetadores famosos

    webpack
    rollup
    wmr
    esbuilt
    parcel
    snowpack
   * vite


   # Pasos

   ## Crear un proyecto npm
   npm init --yes

   ## Añadir la dependencia con tone.js (dependencia de produccion)
   npm install tone

   ## Añadir el empaquetador parcel (dependencia de desarrollo)
   npm install --save-dev parcel


   ## Construimos y arrancamos la aplicacion
   npx parcel src/index.html
   npx parcel build src/index.html

   ## Añadimos la libreria react
   npm install react react-dom

   # Comitear a github
   git init
   git add .
   git commit -m "first commit"
   git remote add origin https://github.com/Leimock/piano.git
   git push origin master