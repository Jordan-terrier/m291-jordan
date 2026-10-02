# Bilan e1-10

## Score 27 / 30

## Encore flou :

### 5.Un dépôt public, est-ce déjà un site que n’importe qui ouvre sur un téléphone ?
Réponse : Non. Public, ce n’est pas publié. Pages sert index.html à une autre adresse

### 25.Sans lancer d’abord (comme en e1-6) : que va afficher fruits.length ?
Écran → 3 Console → longueur : 3
.length, c’est le nombre d’étagères, pas les étiquettes dessus. Trois fruits → 3. L’erreur fréquente d’e1-6 : prédire la liste entière.
Vous pouvez lancer pour vérifier — à l’oral, le bouton Lancer sera fermé.

Réponse : 3.

### 29. Glissez Echo au-dessus de Fanfare. Pour que le dépôt parte, il manque souvent…

ÉTABLI — BOUT DE CODE
ÉCRAN + CONSOLE
liste.addEventListener("dragstart", … setData("text/id", id));
// pas de dragover + preventDefault
liste.addEventListener("drop", … getData("text/plain"));
21:40 Echo du Jura
18:00 Fanfare de Nyon
Réinitialiser la liste
Écran : l’ordre ne bouge pas (volontaire)
Console : prise : item-1

Réponse : preventDefault sur l’événement dragover, sinon drop ne part jamais.