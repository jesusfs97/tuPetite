## Miembros del equipo
-Ismael
-Jesus
-Yordani

## Para agregar tu repositorio de github
git remote add origin url_de_repositorio_de_github

##Para chechar tus repositorios
git remote -v

te da algo parecido ->
origin  https://github.com/YordaniBonilla/tuPetite.git (fetch)
origin  https://github.com/YordaniBonilla/tuPetite.git (push)
##para ver ramas
git branch

##Para Crear una rama/branch 
git branch nombre_del_branch

##Para cambiarte de una rama a otra
git checkout nombre_del_branch

##shortcut : crear nueva rama y cambiarte a esa misma rama a la vez
git checkout -b nombre_del_branch

##Para borrar una rama 
git branch -d nombre_de_la_rama_a_borrar
##Para inicializar un nuevo repositorio de git
git init
##Para agregar cambios en nuestros archivos
<!--Para indicar un solo archivo-->
git add nombre_del_archivo
<!--Para agregar todos los archivos usamos el (.) periodo -->
git add .
##Para agregar tus cambios en el repositorio local (esta dentro det git folder que se crea cuando hacemos git init)
git commit -m 'tu mensaje'
<!--alternativamente puedes usar-->
git commit -am 'que hace el git add y commit a la vez'

##Para mandar tu repositorio local a github
git push origin master

##Para mandar tu rama/branch a github
git push origin nombre_de_rama

##Cuando mandas tu rama a github deves unirla con un pull request a tu master antes de hacer lo siguiente
##Para unirla a tu master 
git pull origin master





