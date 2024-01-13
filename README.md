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




