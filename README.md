# 🖧 Étude et documentation d’un réseau domestique

**Auteur :** Célian Crochat  
**Formation :** BUT Réseaux et Télécommunications  
**Projet :** Analyse, documentation et organisation d’un réseau domestique  
**Surface étudiée :** Environ 120 m² répartis sur deux niveaux

---

## 📌 Présentation du projet

Ce projet consiste à étudier et à documenter l’infrastructure réseau d’un logement comprenant plusieurs équipements informatiques, des consoles de jeux, des téléviseurs, des smartphones et des caméras de surveillance.

L’objectif est de représenter le fonctionnement du réseau, d’identifier les équipements connectés, de présenter les technologies utilisées et d’analyser les performances des connexions filaires et sans fil.

Cette documentation rassemble les informations relatives à l’architecture du réseau, aux normes techniques, à l’adressage IP, aux équipements actifs et passifs, ainsi qu’à la couverture Wi-Fi.

Le projet permet notamment de mettre en pratique des notions abordées en Réseaux et Télécommunications : Ethernet, Wi-Fi, IPv4, IPv6, DHCP, DNS, NAT, adressage réseau et analyse des performances.

## 🎯 Objectifs

- Recenser les équipements présents sur le réseau domestique.
- Distinguer les connexions filaires Ethernet des connexions Wi-Fi.
- Identifier les adresses IP et les adresses MAC des équipements.
- Documenter les services réseau utilisés.
- Étudier la répartition des répéteurs Wi-Fi sur les deux niveaux.
- Mesurer et comparer les performances des connexions réseau.
- Représenter l’architecture physique et logique du réseau.
- Identifier des pistes d’amélioration en matière de performances, de couverture et de sécurité.

## 🏠 1. Présentation de l’infrastructure

Le réseau étudié couvre une surface d’environ 120 m² répartie sur deux niveaux :

- **Premier étage :** ordinateurs portables, ordinateur fixe, téléviseurs, consoles et répéteurs Wi-Fi.
- **Rez-de-chaussée :** ordinateur portable, ordinateur fixe, console et répéteur Wi-Fi.
- **Extérieur :** deux caméras de surveillance sans fil.

La box Internet constitue le point central de l’infrastructure. Les équipements sont connectés soit par câble RJ45, soit par Wi-Fi, selon leur emplacement et leur usage.

L’architecture combine ainsi des connexions filaires, privilégiées pour la stabilité et les équipements de jeu, et des connexions sans fil, utilisées notamment par les appareils mobiles et les téléviseurs.

## 📐 2. Normes et technologies réseau

### 2.1 Wi-Fi

| Fonction | Technologie ou norme documentée |
|---|---|
| Norme Wi-Fi visée | Wi-Fi 7 — IEEE 802.11be |
| Compatibilité avec les anciennes générations | IEEE 802.11a/b/g/n/ac/ax |
| Sécurité Wi-Fi | WPA3 |

La norme Wi-Fi 7 correspond à la génération IEEE 802.11be. Elle apporte notamment des améliorations en matière de débit, de latence et d’utilisation du spectre radio.

La compatibilité avec les générations précédentes dépend des capacités réelles de la box et des appareils utilisés. La documentation indique la norme visée, sans confirmer que tous les équipements installés prennent en charge le Wi-Fi 7.

### 2.2 Ethernet

| Fonction | Norme documentée |
|---|---|
| Réseau Ethernet Gigabit sur cuivre | IEEE 802.3ab |
| Ethernet Gigabit sur fibre | IEEE 802.3z |
| Support physique utilisé dans le logement | Câbles RJ45 |

Ethernet permet de connecter les équipements compatibles au réseau local à travers une liaison filaire.

Dans cette infrastructure, les connexions RJ45 sont notamment utilisées pour les ordinateurs fixes et les consoles. Elles permettent de bénéficier d’une liaison généralement plus stable et moins sensible aux perturbations radio que le Wi-Fi.

### 2.3 Sécurité réseau

| Fonction | Technologie ou référence |
|---|---|
| Protection du Wi-Fi | WPA3 |
| Traduction d’adresses réseau | NAT — RFC 3022 |
| Contrôle d’accès réseau | IEEE 802.1X, référence mentionnée dans la documentation |
| Protocole IPv6 | RFC 8200 |

Ces technologies couvrent plusieurs aspects de la sécurité et du fonctionnement d’un réseau : protection des communications sans fil, traduction d’adresses et gestion des accès.

Leur présence dans la documentation ne signifie pas nécessairement que toutes ces fonctionnalités sont activées ou configurées sur la box. Leur état réel doit être vérifié dans l’interface d’administration de l’équipement.

## 🧰 3. Inventaire des équipements

### 3.1 Premier étage

| Équipement | Système | Connexion | Utilisation |
|---|---|---|---|
| PC portable 1 | Windows | Wi-Fi | Bureautique |
| PC portable 2 | Windows | Wi-Fi | Bureautique |
| PC fixe 1 | Windows | RJ45 | Poste fixe |
| TV 1 | Android TV | Wi-Fi | Streaming |
| TV 2 | Android TV | Wi-Fi | Streaming |
| Console 1 | Orbis OS | RJ45 | Jeux en ligne |
| Console 2 | Orbis OS | RJ45 | Jeux en ligne |
| Répéteur Wi-Fi | Non précisé | Sans fil | Extension de la couverture |

### 3.2 Rez-de-chaussée

| Équipement | Système | Connexion | Utilisation |
|---|---|---|---|
| PC portable 3 | macOS | Wi-Fi | Bureautique |
| PC fixe 2 | Windows | RJ45 | Poste fixe |
| Console 3 | Xbox OS | RJ45 | Jeux en ligne |
| Répéteur Wi-Fi | Non précisé | Sans fil | Extension de la couverture |

### 3.3 Caméras de surveillance

Deux caméras sont recensées dans la documentation :

| Équipement | Emplacement | Connexion | Fonction |
|---|---|---|---|
| Caméra 1 | Extérieur nord | Wi-Fi | Détection de mouvement |
| Caméra 2 | Extérieur sud | Wi-Fi | Détection de mouvement |

Les caméras permettent d’étendre le système de surveillance à l’extérieur du logement. Leur qualité de connexion dépend notamment de la couverture Wi-Fi, de la distance avec le point d’accès et des obstacles rencontrés par le signal radio.

## 🗺️ 4. Adressage IP et identification des équipements

La documentation recense des adresses IPv4, des adresses IPv6 et des adresses MAC associées à plusieurs équipements.

Ces informations permettent de distinguer les appareils présents sur le réseau et de faciliter leur identification lors d’opérations de diagnostic.

- **Adresse IPv4 :** adresse utilisée pour la communication au sein d’un réseau IPv4.
- **Adresse IPv6 :** adresse appartenant à la nouvelle génération du protocole IP.
- **Adresse MAC :** identifiant de couche liaison utilisé par une interface réseau.

Le tableau détaillé de la documentation originale comporte notamment des postes informatiques, des consoles, des caméras, des smartphones, une télévision et la box.

Pour une publication publique, il est préférable de ne pas exposer les adresses MAC réelles ni l’intégralité du plan d’adressage du réseau domestique. Un inventaire anonymisé suffit à illustrer le travail réalisé.

**Point de vigilance :** les adresses IPv4 transcrites dans le document commencent par `192.56.16.x`. Cette plage n’est pas une plage privée IPv4 standard. Il faut vérifier les adresses d’origine avant de publier le plan d’adressage ou de reproduire la configuration.

Les plages privées IPv4 couramment utilisées sont notamment `192.168.0.0/16`, `10.0.0.0/8` et `172.16.0.0/12`.

## 📡 5. Réseau Wi-Fi et répéteurs

### 5.1 Répartition des répéteurs

La documentation mentionne deux répéteurs Wi-Fi associés à la couverture du logement.

| Équipement | Emplacement indiqué | Bande documentée | Canal |
|---|---|---|---|
| Répéteur 1 | Premier étage | 2,4 GHz | Automatique |
| Répéteur 2 | Premier étage | 2,4 GHz | Automatique |

Les répéteurs ont pour fonction d’étendre la couverture sans fil et de faciliter la connexion des appareils éloignés de la box.

Pour optimiser leur positionnement, il convient de vérifier la qualité du signal reçu depuis la box, plutôt que de placer un répéteur directement dans une zone où le signal est déjà très faible.

La répartition exacte des équipements devra être confirmée si les répéteurs sont effectivement installés à des emplacements différents de ceux indiqués dans le tableau d’origine.

### 5.2 Services réseau

| Service | État indiqué dans la documentation | Fonction |
|---|---|---|
| DHCP | Activé | Attribution automatique des paramètres IP |
| DNS | Serveurs par défaut de Bouygues | Résolution des noms de domaine |
| UPnP | Activé | Demandes automatiques de configuration de certains services réseau |

Le DHCP simplifie la configuration des équipements en leur attribuant automatiquement des paramètres réseau.

Le DNS permet notamment de traduire un nom de domaine en adresse IP.

UPnP facilite la configuration de certains équipements et applications, mais peut également présenter des risques de sécurité lorsqu’il est activé sans contrôle. Il est donc pertinent de vérifier si son utilisation est nécessaire.

### 5.3 Passerelle et attribution des adresses

La documentation mentionne les valeurs suivantes dans la rubrique « Passerelle DHCP » :

`196.56.16.2 ; 196.56.16.100`

Le rôle exact de ces deux valeurs n’est pas suffisamment précisé dans le document pour les interpréter avec certitude. Elles doivent être vérifiées dans l’interface de la box : adresse de passerelle, début et fin de plage DHCP, ou autres paramètres.

## 📊 6. Analyse des performances réseau

Les mesures suivantes sont indiquées dans la documentation d’origine.

| Type de connexion | Débit descendant | Débit montant | Latence moyenne |
|---|---:|---:|---:|
| Ethernet RJ45 | 932,80 Mbit/s | 935,82 Mbit/s | Environ 5 ms |
| Wi-Fi | 199 Mbit/s | 161 Mbit/s | Environ 15 ms |

### 6.1 Connexion Ethernet

Les mesures Ethernet montrent un débit proche de 1 Gbit/s dans les conditions du test.

Ce résultat est cohérent avec une liaison Gigabit Ethernet et indique une bonne utilisation de la capacité théorique de cette interface.

Une latence moyenne d’environ 5 ms est également favorable aux usages sensibles au délai, comme les jeux en ligne et les communications interactives.

### 6.2 Connexion Wi-Fi

Les mesures Wi-Fi indiquent un débit descendant de 199 Mbit/s et un débit montant de 161 Mbit/s.

La latence moyenne mesurée est d’environ 15 ms. Ces performances peuvent convenir à de nombreux usages domestiques, notamment le streaming, la navigation et les jeux en ligne.

Le Wi-Fi reste cependant davantage dépendant de l’environnement radio : distance, murs, interférences, bande de fréquence et nombre d’appareils connectés.

### 6.3 Comparaison

D’après les valeurs relevées, la connexion Ethernet offre un débit supérieur et une latence plus faible que le Wi-Fi lors des tests documentés.

Ces résultats sont indicatifs et ne constituent pas une mesure universelle de la qualité de chaque technologie. Pour une comparaison rigoureuse, les tests doivent être réalisés dans des conditions identiques, en répétant les mesures et en précisant les outils utilisés.

## 🔌 7. Équipements passifs

La documentation cite un câble RJ45 reliant une console à la box dans la chambre 3.

Le câblage constitue une partie importante de l’infrastructure physique. Il permet d’établir les liaisons Ethernet entre les équipements et la box ou les équipements d’interconnexion éventuels.

Pour compléter cette partie, il serait utile de préciser la catégorie du câble utilisé, sa longueur approximative et le type de liaison réalisé.

## 🧭 8. Architecture du réseau

L’étude distingue deux représentations complémentaires.

### 8.1 Schéma physique

Le schéma physique représente l’emplacement des équipements et les liaisons matérielles : box, appareils filaires, répéteurs et équipements sans fil.

Il permet de comprendre comment l’infrastructure est répartie dans le logement.

**À ajouter :** le schéma physique issu de la documentation originale.

Emplacement conseillé dans le dépôt : `docs/schema-physique.png`

### 8.2 Schéma logique

Le schéma logique représente l’organisation des communications et les relations entre les équipements réseau.

Il peut notamment faire apparaître la box, la passerelle, le réseau local, les clients connectés en Ethernet ou en Wi-Fi et les services réseau utilisés.

**À ajouter :** le schéma logique issu de la documentation originale.

Emplacement conseillé dans le dépôt : `docs/schema-logique.png`

Ces deux schémas doivent être ajoutés sous forme d’images dans le dépôt GitHub pour être affichés directement dans cette documentation.

## 🔐 9. Sécurité et pistes d’amélioration

L’étude de cette infrastructure permet d’identifier plusieurs points à vérifier ou à améliorer :

- Vérifier l’utilisation effective de WPA3 et la qualité du mot de passe Wi-Fi.
- Contrôler les paramètres d’administration de la box et modifier les identifiants par défaut s’ils sont encore utilisés.
- Vérifier la nécessité d’UPnP et désactiver ce service s’il n’est pas requis.
- Vérifier la cohérence du plan d’adressage IPv4 et les paramètres de la passerelle.
- Confirmer les équipements qui utilisent réellement IPv6.
- Vérifier la couverture Wi-Fi dans les pièces éloignées et à l’extérieur.
- Comparer les performances à plusieurs emplacements et à différents moments.
- Éviter d’exposer les adresses MAC, les informations précises d’adressage et les détails de configuration du réseau personnel dans un dépôt public.

Ces points constituent des pistes d’analyse. Ils ne signifient pas que des vulnérabilités ont été confirmées.

## 🧪 10. Méthodologie de vérification proposée

Pour renforcer la qualité de la documentation, les vérifications suivantes peuvent être effectuées :

1. Relever les paramètres IPv4 et IPv6 de quelques appareils représentatifs.
2. Vérifier l’adresse de la passerelle et la plage d’attribution DHCP depuis la box.
3. Confirmer le type de connexion de chaque équipement.
4. Mesurer le débit descendant, le débit montant et la latence en Ethernet puis en Wi-Fi.
5. Répéter les mesures à plusieurs endroits du logement.
6. Vérifier les canaux, les bandes et le positionnement des répéteurs.
7. Mettre à jour les schémas physique et logique à partir des paramètres vérifiés.

## 🧠 11. Compétences mobilisées

Ce projet illustre plusieurs compétences techniques liées aux réseaux informatiques :

- Identification et inventaire des équipements réseau.
- Compréhension des architectures physiques et logiques.
- Notions d’adressage IPv4 et IPv6.
- Compréhension des services DHCP et DNS.
- Différenciation des connexions Ethernet et Wi-Fi.
- Lecture et interprétation de mesures de débit et de latence.
- Sensibilisation aux mécanismes de sécurité réseau.
- Rédaction d’une documentation technique structurée.

## 📁 12. Organisation du dépôt

Une organisation possible du dépôt GitHub est la suivante :

```text
SAE-1.02/
├── README.md
├── documentation Célian Crochat.pdf
└── docs/
    ├── schema-physique.png
    └── schema-logique.png
```

Cette structure permet de conserver le document original et de proposer un README accessible directement depuis la page principale du dépôt.

## ✅ Conclusion

Ce projet propose une vue d’ensemble d’un réseau domestique comprenant plusieurs équipements répartis sur deux niveaux, des connexions filaires et sans fil, des répéteurs Wi-Fi et des caméras de surveillance.

L’inventaire, la documentation des services réseau, les schémas et les mesures de performances permettent de mieux comprendre le fonctionnement de l’infrastructure et de mettre en pratique des notions essentielles de réseaux et télécommunications.

Il constitue également une base pour approfondir l’analyse de la couverture Wi-Fi, la cohérence de l’adressage IP, la sécurité des équipements et l’optimisation des performances.

---

*Documentation réalisée dans le cadre d’un travail autour des réseaux informatiques et des télécommunications.*
