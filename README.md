# TP-SousDomaine

### **Exercice TP : Recherche d'un sous-domaine sur un site web**

**Objectif** : Vous travaillez en tant que développeur backend pour une grande entreprise de vente en ligne. Les URLs des produits suivent un schéma où elles contiennent des sous-domaines pour chaque catégorie. Votre tâche est de développer un algorithme qui peut catégoriser les URLs selon leur sous-domaine et également de trouver des produits similaires.

#### **Énoncé**:

Voici un échantillon d'URLs:

```
[
    "https://homme.site.com/pantalon-bleu",
    "https://femme.site.com/robe-rouge",
    "https://homme.site.com/veste-noire",
    "https://enfant.site.com/jouet-voiture",
    "https://homme.site.com/pantalon-noir",
    "https://femme.site.com/robe-bleue"
]
```

Vous devez être capable de:

1. Extraire le sous-domaine (par exemple "homme", "femme", "enfant") de chaque URL.
2. Classer ces URLs par catégories basées sur le sous-domaine.
3. Proposer une liste d'URLs similaires pour une URL donnée (par exemple, en comparant les mots dans l'URL).

**Exigences** :

1. Créez un dictionnaire où la clé est le sous-domaine et la valeur est une liste d'URLs appartenant à ce sous-domaine.
2. Pour une URL donnée, vous devez être capable de renvoyer les URLs similaires. Par similarité, nous entendons les URLs ayant des mots communs.

**Consignes** :

1. **Extraction** : Créez une fonction pour extraire le sous-domaine d'une URL.
2. **Catégorisation** : Créez une fonction pour classer les URLs par sous-domaine.
3. **Similarité** : Créez une fonction pour trouver les URLs similaires.

Votre réponse doit être rédigée en pseudo-code.

