# Comment Contribuer à l'Expérience "One Shot Prompt" 🚀

Merci de vouloir participer à cette expérience collaborative ! Le but est de tester les capacités de Gemini 3 Pro avec un **prompt unique** et de voir comment il réinterprète le design de sites web existants.

## 🧪 Le Concept

1.  On prend un **Prompt Unique**.
2.  On choisit un site web existant (connu ou local).
3.  On laisse l'IA générer une refonte "One Shot" (en une seule requête).
4.  On partage le résultat ici.

## 🛠 Comment participer ?

### 1. Récupérer le Prompt
Copiez le prompt disponible sur la page d'accueil (`index.html`) ou ci-dessous :

```text
Consulte et analyse le site web https://VOTRE_URL_ICI
Propose-moi une refonte "ultra-moderne, actuelle, inspirant au design audacieux".
Livrable : UN fichier HTML avec JS/CSS.
```

### 2. Générer la page
Soumettez ce prompt à Gemini 3 Pro.
*   **Important** : Ne faites pas de retouches manuelles majeures. Le but est de voir ce que le modèle sort "One Shot".

### 3. Ajouter votre fichier
1.  Créez un fichier HTML à la racine du projet (ex: `mon-projet.html`).
2.  Collez le code généré.

### 4. Mettre à jour la liste des projets
Ouvrez le fichier `projects.json` et ajoutez votre entrée dans le tableau :

```json
{
    "id": "mon-projet",
    "name": "Nom du Site",
    "description": "Une courte description du site refait.",
    "icon": "🎨",
    "author": "VotrePseudo",
    "gemini_url": "mon-projet.html",
    "original_url": "https://url-originale.com"
}
```
*   **id**: unique, en minuscule, sans espaces.
*   **icon**: un emoji représentatif.
*   **author**: Votre pseudo GitHub ou nom.

### 5. Soumettre une Pull Request (PR)
1.  Créez une nouvelle branche : `git checkout -b add-mon-projet`
2.  Commitez vos changements : `git commit -m "Add Mon Projet example"`
3.  Poussez et ouvrez une PR sur le dépôt.

---

## 📜 Règles
*   Respectez le [Code de Conduite](CODE_OF_CONDUCT.md).
*   Assurez-vous que le contenu généré n'est pas offensant.
*   Amusez-vous !

