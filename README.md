# esbuild

## Terminal preparando el proyecto

git clone https://github.com/Estebnlr/esbuild.git
cd esbuild 
code .
npm init -y

## Iniciemos esta aventura con ESBuild y React (con TypeScript)

# Instalemos el esbuild

npm install esbuild -D
# Instalemos algunos paquetes básicos para React

npm install react react-dom @types/react @types/react-dom typescript

# Inicialicemos el archivo config de TS y, aunque podamos hacer cambios desde el archivo tsconfig.json, le podemos pasar también esos cambios desde ya por parámetro

npx tsc --init --rootDir src --jsx react


## Para hacer deploy: Sube los cambios a github.

1. git add .
2. git commit -m "escribe comentario"
3. git push -u origin main

# Después, Escribe esto en la terminal

npm i gh-pages -D

# Ve al file de package.json y escribe dentro de los scripts en lo ultimo, esto:

"deploy": "gh-pages -d dist"

# Por ultimo, abre la termina y escribe

npm run deploy

# Confirma en tu repositorio de github, si todo está bien.

