# Script para creación de estructura básica de carpetas.

Script de Unix y Windows para crear en un directorio/carpeta nuevo una estructura básica de directorios/carpetas para proyectos de desarrollo.

## Pasos:
1. Crear el directorio de desarrollo.
2. Abrir el directorio de desarrollo en VSCode (file / open folder).
3. Abrir la terminal en VSCode: 
	```
	Comando de Teclado EN: Ctrl + Shift + `
	Comando de Teclado ES: Ctrl + ñ
	 ```
4. Copiar el script que corresponde a tu sistema.
5. Pegar en la terminal.

## PowerShell (Windows)
``` powershell
# Crea directorios
New-Item -ItemType Directory -Path .\public, .\src, .\views, .\public\css, .\public\js, .\public\imgs, .\src\routes, .\src\controllers, .\src\models, .\src\db, .\views\partials

# Crea archivos
New-Item -ItemType File -Path .\.gitignore, .\public\home.html, .\public\css\styles.css, .\public\js\script.js, .\src\app.js, .\src\db\dbconnection.js, .\src\routes\home.routes.js, .\src\controllers\home.controller.js, .\src\models\home.model.js, .\views\partials\header.hbs, .\views\partials\footer.hbs
```

## UNIX (Linux/Mac)
```unix
mkdir public src views public/css public/js public/imgs src/routes src/controllers src/models src/db views/partials ; touch .gitignore public/css/styles.css public/home.html public/js/script.js src/app.js src/db/dbconnection.js src/routes/home.routes.js src/controllers/home.controller.js views/partials/header.hbs views/partials/footer.hbs
```
