# tp1-os
# TP1-os

EX 3.1 :
commande : 

mkdir exo
ls
cd exo ( on est dedans)
pwd ( il affiche le chemin absolue du fichier)
cd ..

           
Ex 3.2 :

commande :

cd exo
nano ( entre dans l'editeur de texte)
ctrl + o (pour donner un nom au fichier )
ctrl + x (quite l'éditeur)
mkdir essai2

Ex 3.3 :

commande :

cp es1 essai2
cd essai2
mv es1 es1-copie

Ex 3.4 :

commande :

la commande ls montre tous les fichiers et sous répertoires dans le repertoire où on se situe.
find es*

Ex 3.5 :

commande :
il est impossible de virer la confirmation.
rm -r (recurcif )

Ex 3.6 :

commande :

sed -n "51 p" ~/nomdufichier


Ex 3.7 :

commande :
permet de rechercher une chaine de caractères dans un fichier.


Ex 3.8 :

commande : 
il faut utiliser find -o (qui représente un ou)

Ex 3.9 :

commande : 
il faut utiliser find -mtime

Ex 3.10 :

commande : 
find . \( -name '*.o' -o -name '*.O' \) -exec rm {} \; 
