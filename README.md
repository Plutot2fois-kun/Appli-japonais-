# 会話けいこ · Kaiwa Keiko

Application d'entraînement à la conversation japonaise orale, pour un francophone débutant qui prépare un voyage au Japon.

## Fonctionnalités

- **10 scènes de la vie réelle** : konbini, ramen, izakaya, gare, boutique, hôtel, demander son chemin, pharmacie, taxi, small talk.
- **3 niveaux de difficulté** : très lent (phrases de 4 mots), normal, vitesse réelle avec les vraies tournures de service.
- **Conversation à voix haute** : reconnaissance vocale (japonais) via le micro, et synthèse vocale pour entendre chaque réplique, avec réécoute et mode ralenti.
- **Traduction masquée** : le français est caché derrière un panneau — essaie de comprendre d'abord.
- **Coach intégré** : corrections courtes en français (au plus 2 par tour) et notes culturelles.
- **3 suggestions de réponse** à chaque tour, du plus simple au plus naturel.
- Sans micro, on peut écrire sa réponse (rōmaji ou kana).

## Utilisation

1. Ouvrir `index.html` dans un navigateur (Chrome ou Safari recommandés — la reconnaissance vocale n'est pas disponible partout).
2. Entrer une clé API Anthropic (`sk-ant-…`), créée sur [console.anthropic.com](https://console.anthropic.com/). La clé est gardée uniquement dans le navigateur (localStorage) et n'est envoyée qu'à l'API Anthropic.
3. Choisir une scène et un niveau, puis appuyer sur le grand cercle pour parler.

⚠️ La clé API est utilisée directement depuis le navigateur : ne partage pas une page où ta clé est enregistrée, et utilise une clé dédiée avec une limite de dépense.
