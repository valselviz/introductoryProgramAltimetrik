## COMANDOS PARA COMMITEAR

comando para inicializar repositorio git
git init

comando para indicar que un archivo es válido y debería ser incluido en nuestro proximo commit
git add [ubicacion/del/archivo/nombre_del_archivo]

comando para indicar que todos los archivos en el proyecto son válidos
git add .

comando para commitear (guardar el estado del proyecto o de un archivo)
git commit


## COMANDOS PARA REVISAR EL ESTADO DE LAS COSAS

comando para ver el estado del proyecto
git status

comando para mostrar historial de commits
git log

comando para ver mis distintas branches
git branch

command to see the edited lines of code
**git diff**




## COMANDOS PARA MANIPULAR BRANCHES

comando para moverse a una branch
git checkout [nombreDelBrach]

comando para crear una branch
git checkout -B [nombreDelBrach]

comando para borrar una branch
git checkout -D [nombreDelBrach]

comando para traer a mi branch los cambios de otra branch
git merge [nombreDeLaOtraBranch]


## COMANDOS PARA SINCRONIZAR CON REPOSITORIO REMOTO

comando para subir mi branch
git push

commando para actualizar mi branch (descargar el ultimo estado)
git pull




## OTROS COMANDOS DE GIT

comando para descartar archivos no commiteados en un proyecto
git reset --hard



## EDITOR DE TEXTO VI
para entrar en el modo insercion de texto de VI
i

para salir del modo insercion de texto de VI
esc

para guardar y cerrar VI
:wq