# 📚 Formation Scala & Apache Spark

[![Déploiement automatique](https://github.com/votre-username/scala-spark-course/actions/workflows/deploy.yml/badge.svg)](https://github.com/votre-username/scala-spark-course/actions/workflows/deploy.yml)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Déployé-brightgreen)](https://votre-username.github.io/scala-spark-course/)

Formation complète pour maîtriser la programmation fonctionnelle et le traitement de données à grande échelle avec Scala et Apache Spark.

## 🎯 Objectifs de la formation

- **Maîtriser Scala** : Syntaxe, programmation fonctionnelle, concepts avancés
- **Apache Spark** : RDD, DataFrames, Datasets, optimisations
- **Big Data** : Traitement distribué, streaming, machine learning
- **Cloud** : Déploiement sur Azure, AWS avec Databricks

## 📖 Modules de formation


| Module | Titre | Durée | Status |
|--------|-------|-------|--------|
| 1️⃣ | [Introduction aux Paradigmes de Programmation](Module%201%20-%20Introduction%20aux%20Paradigmes%20de%20Programmation.html) | 3h | ✅ |
| 2️⃣ | [Mettre en place l'environnement pour Scala](Module%202%20-%20Mettre%20en%20place%20l'environnement%20pour%20Scala.html) | 2h | ✅ |
| 3️⃣ | [Introduction à Scala](Module%203%20-%20Introduction%20à%20Scala.html) | 6h | ✅ |
| 4️⃣ | [Fondements théoriques de Spark : RDD, DataFrame, Dataset](Module%204%20-%20Fondements%20théoriques%20de%20Spark%20-%20RDD,%20DataFrame,%20Dataset.html) | 5h | ✅ |
| 5️⃣ | [Pratiquer Spark : RDD, DataFrame & Dataset en Scala/PySpark](Module%205%20-%20Pratique%20Spark%20-%20RDD,%20DataFrame%20&%20Dataset.html) | 8h | ✅ |
| 6️⃣ | [Approfondissement en Programmation Fonctionnelle](Module%206%20-%20Approfondissement%20en%20Programmation%20Fonctionnelle.html) | 6h | ✅ |
| 7️⃣ | [Spark Streaming et introduction au Machine Learning](Module%207%20-%20Spark%20Streaming%20et%20introduction%20au%20Machine%20Learning.html) | 7h | ✅ |
| 8️⃣ | [Introduction à Databricks et SparkSQL sur le Cloud (Azure, AWS)](Module%208%20-%20Introduction%20à%20Databricks%20et%20SparkSQL%20sur%20le%20Cloud.html) | 5h | ✅ |

**Durée totale : ~42 heures** | **100+ exercices pratiques**

## 🏆 **FORMATION COMPLÉTÉE !**

### ✅ **TOUS LES MODULES TERMINÉS** 
🎉 **8 modules sur 8** | **42 heures de contenu** | **Formation 100% complète !**

🚀 **Stack technique maîtrisée :**
- ✅ **Scala** : Syntaxe, programmation fonctionnelle, patterns avancés
- ✅ **Spark Core** : RDD, DataFrame, Dataset + optimisations 
- ✅ **Spark Streaming** : Structured Streaming + intégration Kafka
- ✅ **MLlib** : Pipelines ML + prédictions temps réel
- ✅ **Cloud Computing** : Databricks, Azure, AWS + Data Lakehouse

🎯 **Projets industriels réalisés :**
- 📊 ETL e-commerce complet
- 🛡️ Détection de fraude temps réel  
- 🏗️ Data Lakehouse multi-cloud
- 🤖 ML pipelines avec MLflow

## 🚀 Démarrage rapide

### Consulter en ligne
La formation est automatiquement déployée sur GitHub Pages :
👉 **[Accéder au cours](https://votre-username.github.io/scala-spark-course/)**

### Développement local

1. **Cloner le projet**
   ```bash
   git clone https://github.com/votre-username/scala-spark-course.git
   cd scala-spark-course
   ```

2. **Lancer un serveur local**
   ```bash
   # Option 1: Python
   python -m http.server 8000
   
   # Option 2: Node.js
   npx http-server
   
   # Option 3: PHP
   php -S localhost:8000
   ```

3. **Ouvrir dans le navigateur**
   ```
   http://localhost:8000
   ```

## 🛠️ Structure du projet

```
scala-spark-course/
├── 📄 index.html                    # Page d'accueil
├── 📄 template-module.html          # Template pour les modules
├── 📄 Module 6 - Approfondissement...html  # Modules existants
├── 📁 .github/workflows/
│   └── 📄 deploy.yml               # Action GitHub pour déploiement
├── 📁 scripts/
│   └── 🐍 generate-modules.py      # Générateur de modules
├── 📁 assets/ (optionnel)
│   ├── 📁 images/
│   ├── 📁 css/
│   └── 📁 js/
└── 📄 README.md
```

## 🔧 Outils de développement

### Générateur de modules

Le script `generate-modules.py` permet de créer rapidement de nouveaux modules :

```bash
# Générer un module spécifique
python scripts/generate-modules.py 1

# Générer tous les modules
python scripts/generate-modules.py --all

# Écraser les fichiers existants
python scripts/generate-modules.py --all --force

# Générer la configuration JSON
python scripts/generate-modules.py --config
```

### Personnaliser un module

1. **Modifier la configuration** dans `scripts/generate-modules.py`
2. **Régénérer le module** : `python scripts/generate-modules.py <numéro>`
3. **Éditer le contenu** dans le fichier HTML généré

### Template personnalisé

Le fichier `template-module.html` contient la structure de base :
- **Design responsive** avec Bootstrap 5
- **Coloration syntaxique** avec Highlight.js
- **Table des matières** automatique
- **Navigation** entre modules
- **Thème cohérent** avec CSS personnalisé

## 🎨 Fonctionnalités

### ✨ Interface moderne
- 🎨 **Design épuré** avec Bootstrap 5
- 🌈 **Thème cohérent** rouge/bleu
- 📱 **Responsive design** pour mobile/desktop
- 🔄 **Animations fluides** et transitions

### 💻 Expérience développeur
- 🔍 **Coloration syntaxique** Scala avec Highlight.js
- 📑 **Table des matières** automatique et interactive
- 🔗 **Navigation fluide** entre les sections
- ⬆️ **Bouton retour en haut** 

### 📚 Contenu pédagogique
- 🎯 **Accordéons interactifs** pour les questions
- 💡 **Sections colorées** : questions, réponses, explications
- 🧩 **Exercices pratiques** avec solutions
- 📊 **Suivi de progression**

## 🚀 Déploiement automatique

Le projet utilise **GitHub Actions** pour le déploiement automatique :

### Configuration
1. **Activer GitHub Pages** dans les paramètres du repository
2. **Source** : GitHub Actions
3. **Branche** : `main` ou `master`

### Workflow automatique
- ✅ **Validation HTML** des fichiers
- 🔗 **Vérification des liens** internes
- 🗺️ **Génération du sitemap** automatique
- 📤 **Déploiement** sur GitHub Pages
- 📧 **Notifications** de statut

### Variables d'environnement (optionnelles)
```yaml
# Dans GitHub Secrets
CUSTOM_DOMAIN: votre-domaine.com  # Domaine personnalisé
GOOGLE_ANALYTICS: GA-XXXXXXXXX   # Google Analytics
```

## 🤝 Contribution

### Ajouter du contenu

1. **Fork** le projet
2. **Créer une branche** : `git checkout -b nouvelle-fonctionnalite`
3. **Modifier le contenu** des modules HTML
4. **Tester localement** avec un serveur HTTP
5. **Commit** : `git commit -m "Ajout de contenu pour le module X"`
6. **Push** : `git push origin nouvelle-fonctionnalite`
7. **Pull Request** vers la branche principale

### Standards de qualité

- ✅ **HTML valide** (validation automatique)
- 🎨 **Cohérence visuelle** avec le design existant
- 📖 **Clarté pédagogique** du contenu
- 💻 **Code fonctionnel** et testé
- 📱 **Compatibility mobile**

### Signaler des problèmes

Utilisez les [Issues GitHub](https://github.com/votre-username/scala-spark-course/issues) pour :
- 🐛 Signaler des bugs
- 💡 Proposer des améliorations
- ❓ Poser des questions
- 📝 Suggérer du contenu

## 📋 TODO et roadmap

### Phase 1 : Contenu de base ✅
- [x] Structure du projet
- [x] Template de modules
- [x] Page d'accueil
- [x] Module 6 (Programmation Fonctionnelle)
- [x] Déploiement automatique

### Phase 2 : Modules complets 🔄
- [ ] Module 1 : Paradigmes de programmation
- [ ] Module 2 : Environnement Scala  
- [ ] Module 3 : Introduction Scala
- [ ] Module 4 : Fondements Spark
- [ ] Module 5 : Pratique Spark

### Phase 3 : Modules avancés ⏳
- [ ] Module 7 : Streaming & ML
- [ ] Module 8 : Cloud & Databricks
- [ ] Exercices interactifs
- [ ] Quiz et évaluations

### Phase 4 : Améliorations 💡
- [ ] Mode sombre/clair
- [ ] Recherche dans le contenu
- [ ] Téléchargement PDF
- [ ] Commentaires et discussions
- [ ] Certificats de completion

## 📞 Support et contact

- 📧 **Email** : votre-email@exemple.com
- 💬 **Discussions** : [GitHub Discussions](https://github.com/votre-username/scala-spark-course/discussions)
- 🐛 **Issues** : [GitHub Issues](https://github.com/votre-username/scala-spark-course/issues)
- 🔗 **LinkedIn** : [Votre Profil](https://linkedin.com/in/votre-profil)

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">

**📚 Formation Scala & Apache Spark**

*Créé avec ❤️ pour la communauté Scala*

[🏠 Accueil](https://votre-username.github.io/scala-spark-course/) • 
[📖 Modules](https://votre-username.github.io/scala-spark-course/) • 
[🤝 Contribuer](CONTRIBUTING.md) • 
[📧 Contact](mailto:votre-email@exemple.com)

⭐ **N'oubliez pas de donner une étoile si ce projet vous aide !** ⭐

</div>
