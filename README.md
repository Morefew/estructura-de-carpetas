# Script para creación de estructura básica de carpetas.

Script de Unix y Windows para crear una estructura básica de carpetas para proyectos de desarrollo. Copiar y Pegar en la terminal.


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
