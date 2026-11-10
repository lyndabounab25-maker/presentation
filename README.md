# Portfolio BTS SIO SISR
> **Solutions d'Infrastructure, Systèmes et Réseaux**  
> Administration Systèmes & Réseaux • Déploiement • Sécurité & Support

---

## 👩‍💻 Présentation & Accueil

Bienvenue sur mon portfolio professionnel réalisé dans le cadre de mon **BTS Services Informatiques aux Organisations (option SISR)**.

Ce portfolio regroupe mes compétences techniques acquises, les situations professionnelles développées lors de ma première année d'études et mon stage en milieu professionnel, ainsi que les éléments d'évaluation pour les épreuves **E4** et **E5** du BTS.

* **Parcours :** BTS SIO option SISR
* **Environnements maîtrisés :** Linux (Debian), Windows Server, Cisco IOS, Proxmox VE, Packet Tracer
* **Objectif professionnel :** Administration d'infrastructures réseaux, sécurisation des environnements postes et serveurs, support technique de proximité.

---

## 🛠️ Synthèse des Compétences de 1ère Année

| Pôle de compétences | Technologies et Protocoles mis en œuvre |
| :--- | :--- |
| **Réseaux & Commutation** | Adressage IPv4, VLANs, Trunking 802.1Q, EtherChannel (LACP/PAgP), Spanning Tree (STP/RSTP) |
| **Routage & Sécurité Réseau** | Routage dynamique (RIPv2), Translation d'adresses (NAT statique, NAT dynamique / PAT Overload) |
| **Systèmes & Services** | Debian Linux, Windows Client/Server, DNS (BIND9), Web (Apache2/Nginx), Partage de fichiers (Samba), SSH |
| **Gestion de Parc & Support** | Masterisation réseau (PXE, TFTP, DHCP), console d'administration NEOS, support utilisateur 2FA |

---

## 📁 Projets & Réalisations de Première Année

### 1. Stage en Milieu Professionnel : Médiathèque Colette (Numérithèque)
*Période : 18 mai 2026 au 26 juin 2026 (6 semaines)*

#### • Réalisation 1 : Masterisation réseau et durcissement des postes clients
* **Contexte :** Renouvellement, harmonisation et sécurisation du parc de postes Tout-en-Un (All-in-One) accessibles au public.
* **Missions & Actions :**
  * Création d'une image système de référence (OS Windows, pilotes matériels et applicatifs validés).
  * Capture sectorielle de l'image disque et déploiement via amorçage réseau (PXE, protocoles TFTP/DHCP).
  * Verrouillage des profils usagers à l'aide de la console centralisée NEOS afin d'interdire l'exécution d'exécutables non autorisés selon le principe du moindre privilège.
* **Compétences validées :** *Gérer le patrimoine informatique*, *Mettre à disposition des utilisateurs un service informatique*.

#### • Réalisation 2 : Support technique de proximité et accessibilité numérique
* **Contexte :** Assistance aux usagers de l'espace numérique et accompagnement de publics spécifiques (partenariat avec l'association *Les Papillons Blancs*).
* **Missions & Actions :**
  * Résolution des incidents d'accès utilisateur (notamment les blocages d'authentification à deux facteurs 2FA).
  * Adaptation ergonomique des interfaces sous Windows et Linux (loupe virtuelle, filtres de contrastes, raccourcis spécifiques).
  * Animation d'ateliers de sensibilisation aux menaces cyber (détection de courriels d'hameçonnage / phishing, hygiène des mots de passe).
* **Compétences validées :** *Répondre aux incidents et aux demandes d'assistance*, *Accompagner les utilisateurs*.

---

### 2. Projets Techniques & Travaux Pratiques Réseau (SIO 1)

#### • Projet A : Découverte et configuration du NAT/PAT et routage dynamique RIPv2
* **Environnement :** Cisco Packet Tracer
* **Objectif :** Interconnecter plusieurs sites distants partageant des plans d'adressage privés identiques et permettre la publication d'un serveur Web interne.
* **Missions & Actions :**
  * Configuration du NAT dynamique avec surcharge de ports (PAT/Overload) sur les interfaces routeurs pour faire communiquer le réseau interne avec l'extérieur.
  * Mise en œuvre d'une translation statique (Port Forwarding sur le port TCP 80) pour rendre le serveur Web privé accessible depuis une adresse IP publique.
  * Déploiement du routage dynamique avec RIPv2 (désactivation du résumé automatique avec `no auto-summary`).
* **Compétences validées :** *Traiter des demandes réseau et système*, *Sécuriser les flux informatiques*.

#### • Projet B : Étude et configuration de la résilience réseau (Spanning Tree Protocol)
* **Environnement :** Cisco Packet Tracer et commutateurs physiques
* **Objectif :** Éviter les boucles de commutation et les tempêtes de broadcast au sein d'une topologie avec liaisons redondantes.
* **Missions & Actions :**
  * Analyse des échanges de trames BPDU et observation de l'élection du commutateur racine (Root Bridge).
  * Configuration manuelle des priorités de pont par VLAN pour désigner le commutateur cœur de réseau comme racine.
  * Mesure des temps de reconvergence lors de la coupure d'un lien physique et passage sous RSTP (Rapid STP).
* **Compétences validées :** *Vérifier les conditions de la continuité d'un service informatique*, *Installer et configurer des éléments d'interconnexion*.

---

## 📊 Tableau de Synthèse des Situations Professionnelles (Épreuve E4 / E5)

| Intitulé de la Réalisation | Type / Cadre | Compétences Référentiel Mobilisées |
| :--- | :--- | :--- |
| **Mastering réseau & Sécurisation NEOS** | Stage 1ère année | Gérer le patrimoine informatique • Déployer un service |
| **Support utilisateur 2FA & Accessibilité** | Stage 1ère année | Répondre aux incidents • Accompagner les utilisateurs |
| **NAT/PAT & Routage dynamique RIPv2** | Formation SIO1 | Traiter des demandes réseau • Sécuriser un service |
| **Topologie anti-boucle & STP** | Formation SIO1 | Vérifier la continuité de service • Administrer le réseau |

---
*Portfolio BTS SIO SISR — Lynda BOUNAB*
