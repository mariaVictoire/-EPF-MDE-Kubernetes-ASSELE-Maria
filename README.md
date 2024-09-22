# Kubernetes Training

Bienvenue dans mon dépôt Git qui regroupe les travaux pratiques réalisés dans le cadre de ma formation sur Kubernetes. Ce document présente une vue d'ensemble des trois TPs, ainsi que leur objectif, leur structure, et les étapes clés de chaque exercice.

## Introduction

Ce dépôt contient les trois TP axés sur la découverte, l’approfondissement et l’implémentation de GitOps avec Kubernetes. Chacun des TP a pour but de me familiariser avec les concepts fondamentaux et avancés de Kubernetes, en passant par le déploiement d’applications, la gestion de clusters, et la mise en œuvre de pratiques DevOps avec GitOps.

## Contenu du dépôt
Le dépôt est structuré de manière à séparer chaque TP dans son propre répertoire. Voici un aperçu de ce que vous trouverez :

1. **Day 1 - Discovery**  
   **Objectif :**  
   Ce premier TP est une introduction à Kubernetes. Il m’a permis de comprendre les bases de Kubernetes, comme l'installation et l'utilisation de `kubectl`, ainsi que la gestion des premières ressources (Pods, Deployments, Services).  

   * Extrait du resultat final


2. **Day 2 - Deep Dive**  
   **Objectif :**  
   Ce TP va plus loin dans l'utilisation de Kubernetes avec un focus sur les opérateurs et les Custom Resources Definitions (CRD). J'ai également manipulé des concepts tels que les StatefulSets et l’intégration d'outils de monitoring.  

   * Extrait du resultat final



3. **Day 3 - GitOps**  
   **Objectif :**  
   Ce dernier TP porte sur l'implémentation de GitOps avec ArgoCD et Helm. J’ai appris à automatiser le déploiement continu en utilisant Git comme source de vérité pour l'état du cluster Kubernetes.  

   * Extrait du resultat final



## Comment utiliser ce dépôt

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/mariaVictoire/EPF-MDE-Kubernetes-ASSELE-Maria.git

   ```
2. **Configurer Kubernetes** :  
   Assurez-vous que `kubectl` est installé et que vous avez accès à un cluster Kubernetes pour tester les configurations.
   
3. **Installer les dépendances** :  
   - Helm est requis pour le TP GitOps.
   - ArgoCD est nécessaire pour la synchronisation GitOps.
   
   Vous pouvez installer Helm via :
   ```bash
   sudo apt-get install helm
   ```

4. **Déploiement** :  
   Pour chaque TP, naviguez dans le dossier correspondant et appliquez les ressources Kubernetes :
   ```bash
   kubectl apply -f <fichier.yaml>
   ```

## Conclusion

Ce dépôt regroupe l'ensemble de mes expériences avec Kubernetes au travers de ces trois TPs. Chaque TP m’a permis de consolider mes compétences dans l’administration de clusters Kubernetes et l’implémentation de pratiques GitOps pour des déploiements continus.

N’hésitez pas à me contacter si vous avez des questions ou suggestions sur l’un de ces exercices.

---
