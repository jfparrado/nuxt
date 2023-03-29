# nuxt

creacion de un nuevo proyecto
npm install --save nuxt
npx create-nuxt-app first_app
entrar a la carpeta creada y darle a npm run dev
entrar a settings, extensions, vetur: format > Default Formatter: HTML se selecciona none
Ir a layouts.vue y ponerle al div encima de nuxt un id asi id="app"
reemplazar ahi los estilos por unos nuevos
Ir a pages, index.vue y borrar todo. lueg poner
<template>

<div>
<h1>Events</h1>
</div>
</template>
npm run dev
nuxt start

La carpeta de components tiene los vue components
layouts para las vistas
pages se usa para las rutas
En store van los Vuex files
En static van los
en assets van cosas que no has sido compiladas. estilos, imagenes, fuentes
En plugins van los plugins que corren antes de cargar la app
En middleaare corren funcinnes que corren antes de renderizar el layout

Nuxt va a autogenerar las rutas basado en el nobre de los archivos en el directorio de pages ej: create.js , la rua sera /create

Para crear links se usa
<nuxt-link to="/">texto</nuxt-link>

Universal mode
al pedir una url renderiza .vue en .html de forma muy rapida.

cuando en la pantalla se ve renderizado un link de una vez va trayendo el contenido de html de ese link antes de correr js

Puede crear meta descriptions por default
