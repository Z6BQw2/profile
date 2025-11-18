# Tommy Morales | AI & HPC Systems Researcher

<p align="left">
  <a href="mailto:tommy.morales@ensiie.eu"><img src="https://img.shields.io/badge/Email-tommy.morales@ensiie.eu-blue?style=flat-square" alt="Email"/></a>
  <!-- Vous pouvez ajouter d'autres badges si vous le souhaitez -->
</p>

Je suis un étudiant passionné par l'optimisation des systèmes d'IA, du niveau micro-architectural au niveau algorithmique. Mon objectif est de contribuer à la recherche fondamentale, principalement en Apprentissage par Renforcement (RL) et Traitement du Langage Naturel (NLP). Mes projets sont des explorations ciblées des briques fondamentales nécessaires pour innover dans ces domaines.

---

## Project Deep Dives

Ici, je donne plus de contexte sur la motivation et les résultats d'apprentissage de mes projets clés.

### IA

#### Réimplémentation

#### Small Worlds

#### MyAnimeList

#### NeuroSymbolique

#### Trajectoire de Balles

#### MarthQuakes

### HPC

#### Optimisation de FlashAttention-1 (CUDA)
*   **Objectif :** Atteindre une compréhension profonde des contraintes matérielles et architecturales des LLM en réimplémentant FlashAttention avec 7 niveaux d'optimisation progressifs (de la réduction parallèle au double-buffering et aux Tensor Cores).
*   **Avancement :** Implémentation de 7 degrés d'optimisation de "basiques" (ex: Réduction Parrallèle) à avancées (ex: DB), avec résultats proches de la primitive cuDNN (~65%). Etude de la consommation énergétique, du runtime et des limites de ces versions. Détermination d'une frontière de Pareto 'Énergie-Runtime'. Implémentation d'une 8e optimisation inconnue jusqu'alors.
*   **Résultat :** Au-delà de l'apprentissage de la programmation et de l'architecture GPU, ce projet a mené à l'identification d'un nouveau bottleneck et à la conception d'une 8ème optimisation (permutation in-register), validée indépendamment par la communauté de recherche (FlashAttention-4). Un rapport détaillé de 30 pages est disponible dans le [repository du projet](LIEN_VERS_LE_REPO).

#### Simulateur de Processeur Quantique (Python & ASM)
*   **Objectif :** Maîtriser les opérations sur les réseaux tensoriels et les systèmes probabilistes, des concepts fondamentaux pour la recherche avancée en IA (notamment en RL).
*   **Apprentissages clés :** Implémentation complète from-scratch d'un système de simulation quantique (structures de données complexes, produits tensoriels).
*   **Avancement :** Implémentation du système complet en raw-Python (Aka sans libraries simplificatrices type manipulation de tenseurs), implémentations des utils et des opérations complexes élémentaires en Assembleur. 
*   **Statut :** Mis en pause stratégiquement après avoir atteint l'objectif principal de compréhension des réseaux de tenseurs. La traduction complète en Assembleur offrait un retour sur investissement pédagogique décroissant.

#### Small Worlds Experiment (CUDA)
*   **Avancement :** Implémentation complète de la pipeline de traitement de donnée.

#### Assembleur x86 from Scratch (Hexadécimal)
*   **Objectif :** Comprendre l'interaction la plus fondamentale entre le code et l'architecture matérielle (Machine-Kernel, syntaxe ASM, fonctionnement d'un assembleur).
*   **Statut :** Le projet est en pause car j'ai atteint le niveau de connaissance bas niveau que je visais, une compétence essentielle pour le co-design matériel/logiciel en IA.

---
