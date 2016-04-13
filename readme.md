install git
install livereload
install editor de texto

git init -->> crea repositorio git .git
git add file 
git add -A
git commit -m "Version inicial"
git config --global user.name "luna"
git config --global user.email "andrea.22.agu@gmail.com"
git config --global color.ui true
git config --global --list
git help 
git help add
git help commit 
git help push
git log --graph  Opciones adicionales para ver los commits 
git log --graph --abbrev-commit --decorate  mas informacion de los commit
git checkout (id del commit) llegar a un commit
git checkout -b (Nombre de rama) crea una nueva rama
git branch Verifica en que rama estoy ubicado
git checkout nombre rama para ir a una rama especifica
git diff file Diferencias que existen segun los cambios.
git merge (rama) Hace una fusion de las ramas
gitk Interfaz amigable para visualizar las ramas.

git remote add origin https://github.com/luna1105/CapacitacionOpa.git
git push -u origin master