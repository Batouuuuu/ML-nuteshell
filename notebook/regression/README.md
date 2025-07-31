#  Régression : Objectifs & Types

## Objectif d'une régression

La régression est une méthode d'analyse statistique ou de machine learning qui permet :

- d’**étudier la relation** entre une ou plusieurs variables explicatives (X) et une variable cible (Y),
- de **prédire** la valeur de la variable cible pour de nouvelles données.

En d’autres termes, elle permet de comprendre **comment Y évolue** en fonction de X, et d’**anticiper de nouveaux résultats** à partir de cette relation.

---

##  Les différents types de régression

On distingue plusieurs types de régressions selon la **nature de la variable à prédire** :

### 🔢 1. Pour prédire une variable numérique (régression continue)

- **Régression linéaire**  
  Modèle : `f(x) = ax + b`  
  → Utilisée lorsque la relation entre X et Y est **linéaire** (droite).

- **Régression polynomiale**  
  Modèle : `f(x) = ax² + bx + c` (ou d’un degré supérieur)  
  → Utilisée quand la relation entre X et Y suit une **courbe** plutôt qu’une droite.

### 🔤 2. Pour prédire une variable catégorielle (régression binaire ou multiclasse)

- **Régression logistique**  
  → Utilisée pour prédire des **valeurs discrètes** (ex : 0 ou 1, oui ou non, classe A ou B).  
  Elle modélise la **probabilité** qu’un échantillon appartienne à une classe.

---

## ✅ Exemples d’usages

- 📈 Prédire le prix d’un appartement selon sa surface, son emplacement, etc. → **Régression linéaire**
- ✉️ Prédire si un email est un spam ou non → **Régression logistique**

---

## 📎 Notes

- La **régression polynomiale** est une extension de la régression linéaire permettant de mieux modéliser des relations non linéaires.
- La **régression logistique** utilise une fonction sigmoïde pour produire une probabilité comprise entre 0 et 1.

