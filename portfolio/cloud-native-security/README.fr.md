Voici une version française fluide et professionnelle, adaptée au contexte de la sécurité "cloud native" :

# Les 5C de la sécurité cloud native

Le cadre de référence en cybersécurité repose sur les **cinq dimensions de la sécurité des applications distribuées à grande échelle**, qui intègrent :

* **Les bonnes pratiques de déploiement cloud**, telles que la méthodologie [Twelve-Factor App](https://12factor.net/fr/).
* **Les recommandations de durcissement (hardening) des configurations** du [CIS](https://www.cisecurity.org) et de l’[OWASP](https://owasp.org).
* **Le contrôle et la surveillance des déviances de licences open-source** (via [FOSSA](https://fossa.com)).

## Définitions

### 1. Clients

**Gestion des identités et des accès (IAM) :** Gestion de l'authentification et des autorisations pour chaque individu ou service intégré utilisant la plateforme.

### 2. Cloud, Co-location, Corporate Datacenter

**Sécurité de l'infrastructure :** Sécurisation du déploiement des charges de travail (*workloads*) et application du contrôle d'admission pour les configurations et les secrets. Cela inclut le durcissement des ressources, le filtrage granulaire du trafic réseau et la garantie de la confidentialité des échanges, tant en interne qu'en périphérie (*edge*) de la plateforme.

### 3. Cluster

**Sécurité de l'orchestration :** Sécurisation de la distribution, de la concurrence et de la tolérance aux pannes des charges de travail.

### 4. Compute & Containers

**Sécurité au runtime (exécution) :** Surveillance des charges de travail actives et neutralisation des actions non autorisées (ex : installation de paquets post-déploiement).

### 5. Code

**Gestion des vulnérabilités :** Analyse statique et dynamique continue (SAST/DAST) du code source et des bibliothèques tierces pour détecter les vulnérabilités.
