# Accessibilité & Qualité Web

## Contexte et Objectifs
Ce projet consiste à concevoir une page vitrine responsive pour une entreprise fictive, en respectant les normes **WCAG 2.1 AA** et **RGAA**. Il se déroule en **quatre phases** intégrant des notions d’accessibilité, de qualité et d’optimisation web.

## Phases du Projet

### Phase 1 : Structure de Base
Création d'une page avec les éléments suivants :
- **Header** avec une navigation claire (liens ancrés).
- **Section "Valeurs"** avec trois icônes SVG personnalisées.
- **Formulaire de contact** (nom, email, message).
- **Tableau comparatif** (4 colonnes, 4 lignes, entête et pied de tableau).
- **Footer** contenant les mentions légales et liens utiles.

📌 **Validation** :
- Code conforme au **validateur W3C**.
- Hiérarchie des titres logique (**h1 > h2 > h3**).
- Utilisation des balises **sémantiques** (nav, main, section, etc.).

### Phase 2 : Accessibilité
Implémentation des bonnes pratiques d’accessibilité :
1. **Navigation clavier** : Focus visible sur les éléments interactifs et ordre de tabulation cohérent.
2. **Contenu multimédia** :
    - Alternatives textuelles pour images/icônes.
    - Sous-titres pour une vidéo de 30 secondes intégrée.
3. **ARIA** : Rôles appropriés (**role="navigation"** pour le header) et labels explicites pour le formulaire.

📌 **Test obligatoire** : Vérification avec **NVDA (Windows)** ou **VoiceOver (macOS)**.

### Phase 3 : Qualité Web
Optimisation du site sur trois axes :
- **Performance** : Score **Lighthouse > 90**, poids total < **500 Ko** (optimisation d'images, chargement différé).
- **SEO** : Meta-description pertinente et intégration de données structurées.
- **Compatibilité** : Affichage cohérent sur **Firefox, Chrome, Safari et mobile**.

📌 **Validation** : Utilisation d’une **checklist Opquast** pour garantir 15 critères qualité.

### Phase 4 : Validation Finale
Les livrables incluent :
- **Dépôt GitHub** avec code commenté, **README** et captures d’écran.
- **Rapport PDF** : Tests d’accessibilité, optimisations, plan d’amélioration.

## Évaluation
Le projet sera noté selon :
- **Validation WCAG 2.1 AA**.
- **Score Lighthouse**.
- **Qualité du code**.
- **Originalité et design**.

## Ressources Clés
- [Introduction à l'accessibilité (W3C)](https://www.w3.org/WAI/fundamentals/accessibility-intro/fr)
- [Documentation ARIA](https://web.dev/learn/accessibility/aria-html?hl=fr)
- [Checklist Opquast](https://checklists.opquast.com/fr/)
