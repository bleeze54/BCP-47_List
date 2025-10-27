# BCP-47_List

> Une collection de listes au format **JSON** pour les balises de langue standard **BCP-47**.

## 🧐 À propos

Ce dépôt fournit une ressource simple et facilement intégrable pour la gestion de l'identification des langues dans vos projets. Il contient des listes complètes des balises de langue conformes à la norme **BCP-47** (Best Current Practice 47), un standard largement utilisé pour la localisation (i18n).

Les données sont structurées en JSON pour une intégration facile dans n'importe quel environnement de développement (JavaScript, Python, PHP, etc.).

---

## 📦 Contenu du Dépôt

Le dépôt est composé des fichiers JSON suivants :

| Fichier | Description | Format d'exemple |
| :--- | :--- | :--- |
| **`langage.json`** | Contient la liste principale des balises BCP-47, souvent avec une description ou un nom associé. | `{"fr": "Français", "en-US": "English (United States)", ...}` |
| **`language_fallbacks.json`** | Fournit les structures de **fallback** (repli) linguistique, essentielles pour la gestion des préférences de langue. Cela permet de définir le chemin de repli d'une balise spécifique vers une balise plus générique (ex: `en-GB` replie vers `en`). | `{"en-GB": "en", "es-419": "es", ...}` |

---

## 🚀 Utilisation

Pour intégrer ces données dans votre projet :

### 1. Cloner le Dépôt

Vous pouvez cloner le dépôt pour obtenir tous les fichiers :

```bash
git clone [https://github.com/bleeze54/BCP-47_List.git](https://github.com/bleeze54/BCP-47_List.git)
