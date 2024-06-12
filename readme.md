### Rapport de Projet : Fria Furniture in Augmented Reality

---

#### Présentation Globale

**Fria Furniture in Augmented Reality** est une application mobile de planification de meubles en réalité augmentée, développée comme projet final à l'université d'Aix-Marseille. L'application permet aux utilisateurs de visualiser des modèles 3D de meubles dans leur espace réel grâce à la technologie ARCore et Sceneform de Google. Fria vise à révolutionner la manière dont les utilisateurs planifient et achètent des meubles en offrant une solution immersive et pratique qui élimine le besoin de se rendre physiquement dans les magasins.


---

#### Résumé du Travail

Le développement de Fria a suivi plusieurs étapes clés :

1. **Analyse et Définition des Exigences :**
   - Étude des applications similaires comme IKEA Place.
   - Collecte des exigences des utilisateurs potentiels via des questionnaires et des discussions.

2. **Conception du Système :**
   - Modélisation UML pour définir les entités et les interactions.
   - Conception de la base de données avec la méthode Merise.

3. **Développement et Intégration :**
   - Utilisation d'ARCore et Sceneform pour les expériences de réalité augmentée.
   - Intégration de Firebase pour la gestion des données et l'authentification.
   - Développement de l'interface utilisateur en Kotlin.
   - Téléchargement ou Création de modèles 3D et leur optimisation avec Blender.

4. **Tests et Validation :**
   - Tests fonctionnels pour vérifier la précision et la fiabilité.
   - Tests de performance pour assurer une expérience fluide.

5. **Documentation et Démonstration :**
   - Création de guides utilisateur et de documentation technique.
   - Réalisation de démos et de présentations pour illustrer les fonctionnalités.

---

#### Conclusion

Fria est une application innovante qui démontre comment la réalité augmentée peut améliorer l'expérience d'achat de meubles. En permettant aux utilisateurs de visualiser des meubles dans leur propre espace, Fria réduit les incertitudes et facilite les décisions d'achat. Le projet a atteint ses objectifs en offrant une solution pratique et immersive pour la décoration intérieure.

---

#### Bilan

**Difficultés Rencontrées :**
1. **Précision des Mesures :**
   - Les premières versions de l'application avaient des problèmes de précision dans la mesure des espaces.
   - **Solution :** Calibration des capteurs et ajustement des algorithmes.

2. **Gestion des Modèles 3D :**
   - Difficulté à gérer des modèles 3D complexes en temps réel.
   - **Solution :** Optimisation des modèles avec Blender.

3. **Compatibilité des Appareils :**
   - Problèmes de compatibilité avec certains appareils Android.
   - **Solution :** Tests et ajustements pour une compatibilité maximale.
4. **Base de donnés Firebase :**
   - Problème avec le manque de connaissances sur firbase.
   - **Solution :** Apprendre des vidéos éducatives et des sites Web spécialisés.
  
**Apports du Projet :**
- **Compétences Techniques :** Acquisition de compétences en développement AR, gestion de base de données et développement mobile.
- **Gestion de Projet :** Expérience dans la résolution de problèmes complexes .
- **Innovation et Créativité :** Exploration de nouvelles technologies pour résoudre des problèmes pratiques.

**À Refaire :**
- Consacrer plus de temps à la phase de conception pour anticiper les défis techniques.
- Adopter une approche itérative avec des tests utilisateurs dès les premières phases.
- Trouver une équipe.

---

#### Perspectives

1. **Extension de la Compatibilité :**
   - Rendre l'application compatible avec plus d'appareils pour élargir son accessibilité.

2. **Amélioration de l'Interface :**
   - Rendre l'interface utilisateur encore plus intuitive et ajouter des fonctionnalités de personnalisation.

3. **Fonctionnalités Avancées :**
   - Intégrer la réalité augmentée partagée pour permettre la collaboration en temps réel.
   - finir la fonction de favorite et les autre fonctions reste

4. **Expansion de la Base de Données :**
   - Enrichir la base de données avec de nouveaux modèles et catégories de meubles.
   - créer une base de donnés plus profisionnel.

---

#### Base de Données

L'application Fria télécharge l'ensemble des données de meubles sur Firebase. Chaque item dans la base de données suit un modèle spécifique, structuré comme suit :

```json
{
  "sizes": [
    0,
    0,
    0
  ],
  "details": {
    "description": ""
  },
  "category": "*",
  "price": 0,
  "color": "",
  "rendable": "models/*.glb",
  "images": [
    "images/*.jpg"
  ],
  "source": "",
  "model": ""
}
```

Cette structure permet de stocker les informations essentielles sur chaque meuble, incluant ses dimensions, sa description, sa catégorie, son prix, sa couleur, les fichiers rendables et les images associées.
