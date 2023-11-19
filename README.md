# Descripción laboratorio
Abrí mi terminal y situé el directorio de mi repo local.
Cree una carpeta con el nombre del repo local: Laboratorio-Git 
Inicie el repo abriendo la carpeta del repo en visual studio code y usando el comando [git init .]
Cree un repositorio desde Github (incluí un readme): Repo-Git-Remote, copié la SSH, y conecté los repositorios con [git remote add origin git@github.com:Barbrastk/Repo-Git-Remote.git]
Confirmé que estuvieran los repos bien conectados con 
[git remote -v 
(#) Verify new remote]
Creé un archivo index.html 
Creé un commit -m, con el mensaje de la acción realizada
(-Duda que consultar: Primero intenté hacer un git push, pero me daba error, me decía que primero debía hacer un git pull. Cuando intentaba esto, tb me daba error. Resolví esto con el comando [git pull origin main --allow-unrelated-histories]. Me gustaría saber que hago mal en este punto.)
Una vez hecho lo anterior, pude subir los cambios al repositorio en GitHub con [git push origin main]
Comprobé en mi repositorio remoto que este todo ok
Creé una rama llamada "development" y me situé en ella con el comando [git checkout -b development]
Realicé cambio en el h1 del archivo index.html
Stageié los  cambios desde comando visual studio code
Hice el commit con el mensaje descriptivo desde los comandos de visual studio code 
Hice un git status
Hice un git push origin main
Comprobé que en el repo remoto vaya todo ok
Modifiqué el archivo readme con todos mis pasos para hacer este ejercicio(staged/commited/pushed)
Volví a la rama main
Hice un merge de la rama development a la rama main
Hice un push de los cambios al repo en GitHub
Comprobé que en el repo remoto este todo correcto