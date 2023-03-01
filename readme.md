Pour implémenter des changements sur le site en ligne maththeprinter.github.io, il faut que 
1/ Je modifie les fichiers locaux sur mon depot local
2/ en utilisant l'invite de commande intégrée à VScode (ctrl + ù)


Etapes automatisées de mise en ligne / commit + push des changements, en renommant le fichier deploy.bat (qui est une commande executable windows)

hugo

git add .

git commit -m "rebuild $(date)"

git push origin main