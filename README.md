# Manjaro

## Configuration de Manjaro sur mon PC Lenovo Ideadpad 330-15ARR

### 1. À faire dès la distribution installée
RAS

## Lignes de commande à connaître
### 1. Pacman
#### a) Mises à jour
* sudo pacman -Syu (mettre à jour son systèmes et les logiciels)

#### b) Supprimer un logiciel et des dépendances
* sudo pacman -R 'nom du logiciel' (supprimer le logiciel sans ses dependances)
* sudo pacman -Qdtq | sudo pacman -Rs - (supprimer les dependances non utilisées, faire le ménage)
