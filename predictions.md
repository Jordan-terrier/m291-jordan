# 1 - Afficher 
document.getElementById("out1").textContent = "Bonjour la classe";
## Prédiction : "Bonjour la classe"

## Résultat : Bonjour la classe

# 2 - Calculer 
let a = 4;
let b = 3;
let total = a + b;
document.getElementById("out2").textContent = total;
## Prédiction : "7"

## Résultat : 7

# 3 - Compter
let fruits = ["pomme", "poire", "kiwi"];
document.getElementById("out3").textContent = fruits.length;
## Prédiction : "3"

## Résultat : 3

# 4 - Condition 
let note = 5;
let texte;
if (note >= 4) {
  texte = "suffisant";
} else {
  texte = "insuffisant";
}
document.getElementById("out4").textContent = texte;
## Prédiction : "suffisant"

## Résultat : suffisant

# 5 - Boucle simple
let message = "";
for (let i = 1; i <= 3; i = i + 1) {
  message = message + i + " ";
}
document.getElementById("out5").textContent = message;
## Prédiction : "1, 2, 3"

## Résultat : 1 2 3

# 6 - Clic
let n = 0;
document.getElementById("b6").addEventListener("click", function () {
  n = n + 1;
  document.getElementById("out6").textContent = n;
});
## Prédiction : “0,1,2,3,4,..."

## Résultat : 0 1 2 3 4...