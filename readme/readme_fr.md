# Reddit Video Parser Tool 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Français-yellow.svg)

## 📋 Présentation du Projet

**Reddit Video Parser Tool** est un utilitaire basé sur le web conçu pour assister les éducateurs, les chercheurs et les apprenants individuels dans l'analyse technique de contenus vidéo accessibles publiquement sur la plateforme Reddit, à des fins d'archivage et d'étude conformément aux principes d'« usage loyal » (Fair Use). Cet outil se concentre sur la fourniture d'un support technique épuré et efficace pour des scénarios non commerciaux, tels que la collecte de cas pédagogiques, la recherche sur les réseaux sociaux, l'analyse de la culture numérique et la gestion des connaissances personnelles.

🔗 **Démo en Ligne**: [https://twittervideodownloaderx.com/reddit_downloader_fr](https://twittervideodownloaderx.com/reddit_downloader_fr)

> ⚠️ **Avis Important**: Ce projet est développé exclusivement à des fins d'apprentissage technique et de recherche. Les utilisateurs sont tenus de respecter les lois applicables en matière de droit d'auteur et les conditions d'utilisation des plateformes, de respecter les droits des créateurs originaux, et de s'abstenir d'utiliser cet outil pour toute activité portant atteinte à la propriété intellectuelle ou violant les politiques de la plateforme.

---

## ✨ Fonctionnalités Principales

- 🔗 **Reconnaissance Intelligente des Liens**: Analyse automatiquement les liens de publications Reddit, les liens vidéo directs et autres formats
- 📥 **Adaptation de la Qualité**: Présente les options de résolution disponibles basées sur les métadonnées de source (sous réserve de la disponibilité de la plateforme)
- 📱 **Compatibilité Multi-Appareils**: Design responsive optimisé pour les navigateurs de bureau et mobiles
- 🔐 **Conception Axée sur la Confidentialité**: Aucun journal d'activité utilisateur stocké ; aucun contenu analysé conservé sur les serveurs
- ⚡ **Léger et Rapide**: Logique de traitement centrée sur le client minimisant la dépendance au serveur pour des réponses rapides
- 🔄 **Maintenance Active**: Mises à jour régulières pour s'adapter aux changements du frontend de la plateforme et assurer une fonctionnalité continue
- 💬 **Extraction de Métadonnées**: Extraction optionnelle des informations publiques telles que le titre de la publication, l'auteur, le sous-reddit (uniquement à des fins d'annotation de recherche)

---

## 🚀 Guide de Démarrage Rapide

### Étape 1: Obtenir le Lien de la Vidéo
1. Ouvrez le site web ou l'application Reddit
2. Localisez la **publication vidéo accessible publiquement** que vous souhaitez analyser
3. Cliquez sur « Partager » → « Copier le lien », ou copiez directement l'URL de la publication depuis la barre d'adresse du navigateur

### Étape 2: Soumettre pour Analyse
1. Accédez à : `https://twittervideodownloaderx.com/reddit_downloader_fr`
2. Collez le lien copié dans le champ de saisie prévu à cet effet
3. Cliquez sur le bouton « Démarrer l'Analyse »

### Étape 3: Consulter les Résultats
1. Attendez que le système termine l'analyse technique (généralement quelques secondes)
2. Examinez l'aperçu des métadonnées vidéo et des informations disponibles
3. Procédez aux actions suivantes selon les indications (uniquement à des fins d'apprentissage personnel)

---

## 💡 Formats de Liens Pris en Charge

```
✅ Modèles d'URL recommandés :
- https://www.reddit.com/r/subreddit/comments/xxxxx/video_title/
- https://old.reddit.com/r/subreddit/comments/xxxxx/
- https://v.redd.it/xxxxxxxxxxx/

❌ Scénarios actuellement non pris en charge :
- Publications définies comme "utilisateurs invités uniquement" ou supprimées
- Contenu restreint nécessitant une authentification ou une connexion pour y accéder
- Vidéos protégées par une gestion avancée des droits numériques (DRM)
- Contenu violant les directives communautaires de Reddit
```

---

## ⚙️ Architecture Technique

| Composant | Implémentation | Description |
|-----------|---------------|-------------|
| **Frontend** | HTML5 + CSS3 + Vanilla JS | Sans framework pour un chargement rapide, haute compatibilité |
| **Gestionnaire de Requêtes** | Node.js / Python Backend | Asynchrone non bloquant, support haute concurrence, fonctionnement stable |
| **Analyseur de Contenu** | Expressions Régulières + Analyse DOM + API Reddit | Extrait uniquement les métadonnées publiques ; aucun contournement de chiffrement, respect des autorisations |
| **Couche de Sécurité** | HTTPS + Assainissement des Entrées + Limitation de Débit | Prévention des abus, garantie de la stabilité du service, protection de la confidentialité des utilisateurs |
| **Déploiement** | Docker + Accélération CDN | Nœuds distribués mondialement pour un accès à faible latence, mise à l'échelle élastique |

---

## ⚠️ Déclaration de Conformité et d'Utilisation Responsable

Cet outil fonctionne strictement selon les principes de **neutralité technique** et d'**usage loyal**. Veuillez observer les directives suivantes :

### ✅ Cas d'Utilisation Autorisés
- 📚 Établissements d'enseignement analysant des cas de diffusion sur les réseaux sociaux à des fins académiques
- 🔬 Échantillonnage, annotation et recherche culturelle de contenus vidéo numériques dans le cadre de projets de recherche
- 🗂️ Chercheurs individuels organisant des documents de référence pour l'inspiration (avec attribution appropriée)
- 🌐 Accès hors ligne à des fins d'apprentissage dans des régions à connectivité Internet limitée
- 📊 Observation et enregistrement non commerciaux de phénomènes culturels numériques

### ❌ Activités Interdites
- 🚫 Utilisation du contenu analysé pour une distribution commerciale, une redistribution secondaire ou une monétisation du trafic
- 🚫 Suppression des informations de l'auteur original ou des filigranes et republication du contenu comme œuvre originale
- 🚫 Scraping massif, collecte automatisée de données ou perturbation des opérations de Reddit
- 🚫 Tentative de contournement des contrôles d'accès pour visualiser un contenu non public ou restreint
- 🚫 Utilisation pour diffuser du contenu illégal, portant atteinte aux droits ou violant les directives communautaires

### 📜 Cadre de Référence Juridique
- Code de la propriété intellectuelle français, art. L.122-5 (exceptions au droit d'auteur)
- Règlement général sur la protection des données (RGPD) pour les aspects confidentialité
- Politique de Contenu et Conditions d'Utilisation de la plateforme Reddit
- Principes judiciaires internationalement reconnus d'« usage loyal » (Fair Use)

> 📌 **Avertissement**: Les développeurs n'assument aucune responsabilité en cas d'utilisation abusive de cet outil. En utilisant ce logiciel, vous reconnaissez avoir lu, compris et accepté de respecter les conditions décrites ci-dessus.

---

## 🤝 Contribuer

Nous accueillons avec plaisir les contributions de la communauté pour aider à améliorer ce projet :

```bash
# 1. Forkez le dépôt
# 2. Créez une branche de fonctionnalité
git checkout -b feature/amelioration

# 3. Validez vos modifications
git commit -m "feat: optimisation de la logique de reconnaissance des liens Reddit"

# 4. Pushez et ouvrez une Pull Request
git push origin feature/amelioration
```

**Directives de Contribution**:
- Respectez les conventions de style de code ESLint / Prettier
- Incluez des tests unitaires pour les nouvelles fonctionnalités lorsque cela est applicable
- Utilisez des messages de commit clairs et descriptifs en français ou en anglais
- Documentez les nouvelles fonctionnalités à la fois dans les commentaires de code et dans les mises à jour du README
- Assurez-vous que les soumissions passent les vérifications de code de base avant envoi

---

## 🐛 Signaler des Problèmes

Vous avez rencontré un bug ou avez une suggestion d'amélioration ?

1. Consultez d'abord l'onglet [Issues](../../issues) pour éviter les doublons
2. Lors de la création d'un nouveau problème, veuillez inclure :
   - Nom et version du navigateur
   - Instructions de reproduction étape par étape
   - Comportement attendu vs. comportement réel
   - Captures d'écran ou journaux d'erreur (le cas échéant)
   - Exemple de lien de publication Reddit (avec informations sensibles anonymisées)
3. Notre équipe examine les soumissions régulièrement et répondra dans les meilleurs délais

---

## 📄 Licence

Ce projet est distribué sous la **Licence MIT**. Vous êtes libre d'utiliser, de modifier et de distribuer ce logiciel, à condition de conserver la notice de droit d'auteur originale et les termes de la licence.

```
MIT License

Copyright (c) 2024 Reddit Video Parser Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Remerciements

- Gratitude envers la communauté open source pour la fourniture de composants techniques robustes et d'inspiration
- Appréciation envers les utilisateurs et chercheurs universitaires qui contribuent par leurs précieux retours
- Reconnaissance envers les créateurs Reddit dont le travail enrichit la valeur du contenu de la culture Internet

---

> 📬 **Support et Contact**: Pour toute demande de collaboration technique ou question relative à la conformité, veuillez soumettre un ticket via GitHub Issues. Nous nous efforçons de répondre rapidement à toutes les demandes légitimes.

*Ce projet n'est pas affilié, approuvé ni sponsorisé par Reddit Inc. ou l'une de ses filiales. Toutes les marques commerciales, logos et noms de marque sont la propriété de leurs détenteurs respectifs. Cet outil fournit uniquement un support technique d'analyse et n'effectue aucun stockage, distribution ou revendication de propriété sur le contenu de tiers.*