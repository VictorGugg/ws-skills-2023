# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

### - l'état (_state_) pour contrôler l'affichage d'un composant ✔️

``` javascript
import { useState } from 'react';

const [someState, setSomeState] = useState(initialValueOfState)
```

***

### - les composants enfants et les _props_ qu'on leur passe ✔️

``` javascript
<Component prop={someState.value}>
```
Les composants sont des morceaux de code que l'on va retrouver à plusieurs reprises dans le code. On les définit à un endroit (souvent dans un dossier */components*) pour pouvoir les appeller où on en a besoin, autant de fois que nécessaire (par exemple : une carte utilisateur, une navBar etc)
On peut leur passer en 'props' des informations dynamiques correspondant au composant (par exemple : `prop={user.name}` )

***

- le déclenchement d'instructions en fonction des actions de l'utilisateur ❌ / ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
