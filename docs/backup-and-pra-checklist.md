# Sauvegardes 3-2-1, Tests de Restauration & PRA

Repères pratiques pour garantir la résilience des données et la capacité de reprise après sinistre ou cyberattaque.

## Checklist Essentielle

* **Règle 3-2-1 :** conserver plusieurs copies des données critiques sur des supports distincts, incluant au moins une copie isolée / hors ligne afin de limiter l'impact d'une compromission ou d'un chiffrement malveillant.
* **Chiffrement & Intégrité :** chiffrer les sauvegardes sensibles au repos, protéger l'accès aux supports/stockages et contrôler régulièrement l'intégrité des archives.
* **Objectifs de Reprise (RTO / RPO) :** formaliser les délais maximaux d'interruption et la perte de données acceptable pour chaque service critique.
* **Tests de Restauration Planifiés :** rejouer périodiquement des scénarios de restauration complets ou ciblés pour valider l'efficacité réelle des sauvegardes et des procédures PRA.
* **Articulation PCA / PRA :** distinguer le maintien temporaire en mode dégradé (PCA) de la reconstruction/remise en service structurée (PRA), avec mise à jour après chaque test ou incident.
