#########################################
########## Workflow RAG avec n8n#########
#########################################

##  Description

Ce projet présente un système de type **RAG (Retrieval-Augmented Generation)** construit avec n8n.

Le workflow permet de :

* Extraire le contenu de fichiers PDF
* Générer des embeddings (représentation vectorielle du texte)
* Stocker les données dans Supabase
* Rechercher les contenus les plus pertinents selon une requête utilisateur

---

##  Cas d’usage (Éducation)

Ce projet est conçu pour aider les élèves à réviser leurs cours.

Fonctionnalités :

* Poser des questions sur un cours
* Retrouver rapidement les parties importantes d’un document
* Obtenir des explications à partir des supports de cours

Exemple :

> Un élève demande : "Qu’est-ce que la stéréoisomérie ?"
> Le système retourne les passages pertinents du cours

---

##  Technologies utilisées

* n8n (automatisation des workflows)
* Supabase (base de données vectorielle)
* API LLM (génération d’embeddings et réponses)

---

##  Structure du projet

```
rag-n8n-workflow/
│
├── workflows/
│   └── rag-workflow.json
│
├── README.md
├── .env.example
```

---


##  Fonctionnement global

1. Import d’un document (PDF)
2. Extraction du texte
3. Transformation en embeddings
4. Stockage dans Supabase
5. Recherche par similarité via une requête utilisateur
6. Retour des contenus les plus pertinents

---

##  Améliorations futures

* Génération automatique de réponses complètes
* Interface utilisateur pour les élèves
* Optimisation de la recherche vectorielle
* Ajout de plusieurs documents

---

##  Auteur

Projet réalisé dans le cadre d’un apprentissage en automatisation et intelligence artificielle.

---

##  Contact

📧 Email :rharikasainarakotondranaivo@gmail.com
Disponible pour des opportunités en automatisation (n8n), data et IA.
