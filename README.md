# TypeScript
## conceptos basicos

## indice
1. 
2. 
3. 

------------

### iniciando en typescript
TypeScript es un lenguaje de programcion orientado a objetos creado por microsoft. Es llamado un superset de javascript lo cual significa que TypeScript fue escrito sobre javascrit agregandole funcionalidades nuevas (como tipos de datos). Pero otros superset se elejan del lenguaje en cuestion, pero TypeScript no lo hace.

Para poder comenzar a explorar este lenguaje necesitamos instalar nodejs:
en linux:
https://nodejs.org/es/download/package-manager/
en debian:
https://github.com/nodesource/distributions/blob/master/README.md#debinstall
```bash
# Usando debian como root
curl -sL https://deb.nodesource.com/setup_13.x | bash -
apt-get install -y nodejs
```
luego creamos una carpeta donde iniciaremos nuestra prueva:
```bash
cd Escritorio
mkdir pruevaType
```
creamos un archivo ejemplo.ts usando visual o el editor favorito de cada uno
luego creamos la siguiente linea
```javascript
console.lo("hola mundo");
```
luego para poder ejecutarlo creamos un documento html index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <script src="ejemplo.js"></script>
</head>
<body>
    
</body>
</html>
```
