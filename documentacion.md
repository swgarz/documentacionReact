# Documentación React 

## Creando la carpeta del repositorio
create-react-app nombredelproyecto

# correr proyecto
npm start, el proyecto corre en el localhost:3000, detener el proyecto una vez que vimos que funcionó

# Guardar los cambios en git y conectar el proyecto con github

## Ahora hay que instalar el modulo gh-pages en la terminal
npm i gh-pages

## ir al archivo package.json y agregar esta linea debajo del atributo "private" (agregar en cualquier parte antes de las dependencias)

#### "homepage": "http://swgarz.github.io/parrillas", (swgarz es mi nombre de usuario en github y al final el nombre del proyecto
 en el mismo archivo en la sección de scripts agregar estos dos scripts
 
#### "predeploy": "npm run build",
#### "deploy": "gh-pages -d build",

### agregamos los cambios a git, commit y push. 

## Por último agregamos esta linea de codigo a la terminal
npm run deploy


