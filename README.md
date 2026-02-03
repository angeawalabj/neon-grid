# ✨ Jour 1 : Interactive Neon Grid

### 💡 Le Concept
Une grille minimaliste composée de centaines de petits carrés. Au repos, l'interface est sombre et uniforme. Au passage de la souris, les cellules s'illuminent instantanément et s'éteignent lentement, créant une traînée lumineuse fluide qui suit les mouvements de l'utilisateur.

---

### 🛠️ Fiche Technique
| Composant | Technologie / Logique |
| :--- | :--- |
| **Structure** | HTML5 / Divs générées par boucle JS |
| **Style** | CSS Flexbox & Box-Shadow (Glow effect) |
| **Logique** | Génération DOM dynamique |
| **Effet Clé** | **Transitions CSS Asymétriques** (0s in / 2s out) |

---

### 🧠 Ce que ce projet démontre
* **Manipulation du DOM** : Création efficace de 400 éléments via une boucle `for` en JavaScript pour garder le HTML propre.
* **Maîtrise du Temps CSS** : Compréhension de la propriété `transition` pour gérer différemment l'état "actif" et l'état "passif", créant une illusion de physique (refroidissement progressif).
* **Feedback Utilisateur** : Création d'une micro-interaction satisfaisante qui récompense le mouvement.

---

### 🧪 Playground (Paramètres à modifier)
Pour changer le comportement de l'animation, ouvrez `style.css` ou la balise `<style>` :

1.  **Changer la couleur** : Modifiez le `#00fffc` dans `.square:hover` pour du rouge, du vert, etc.
2.  **Changer la durée de la traînée** : Modifiez `transition: 2s` dans `.square`. Essayez `0.5s` (rapide) ou `5s` (très lent).
3.  **Changer la densité** : Dans le JS, modifiez `const SQUARES = 400` et ajustez la CSS `max-width` du container.

---

### 📈 Progression Personnelle
**Défi du jour :** Aligner parfaitement les carrés pour qu'ils forment une grille solide sans espaces blancs indésirables.
**Apprentissage clé :** J'ai appris que l'on pouvait manipuler la perception de vitesse uniquement avec du CSS, sans utiliser de bibliothèques d'animation lourdes.
