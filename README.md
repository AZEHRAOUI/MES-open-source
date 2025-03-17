# MES Open Source - Supervision industrielle

![MES Logo](assets/images/mes-logo.png)

## 🏭 Description

MES Open Source est un système de Manufacturing Execution System complet et open source conçu pour la supervision industrielle et la gestion des machines en environnement de production. Ce projet permet la collecte, l'analyse et la visualisation de données en temps réel, offrant une solution accessible pour l'Industrie 4.0.

## 🛠️ Technologies utilisées

![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=for-the-badge&logo=node-red&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=for-the-badge&logo=eclipse-mosquitto&logoColor=white)
![Modbus](https://img.shields.io/badge/Modbus-010101?style=for-the-badge)

## 📸 Démonstration

### Dashboard principal
![Main Dashboard](assets/images/mes-main-dashboard.png)
z
### Flow Node-RED
![Node-RED Flow](assets/images/node-red-flow.png)

## 🏗️ Architecture du système

┌─────────────┐         ┌───────────────┐         ┌───────────────┐
│             │         │               │         │               │
│  Machines   │◀━━━━━━━▶│  Node-RED    ◀━━━━━━━▶│   InfluxDB    │
│ Industriels │         │  (Acquisition │         │  (Time-series │
│ (Modbus/    │         │   & Traitement│         │    Database)  │
│  MQTT)      │         │   des données)│         │               │
│             │         │               │         │               │
└─────────────┘         └───────────────┘         └───────────────┘

## 🚀 Fonctionnalités

- **Acquisition multi-protocole**: Support Modbus TCP/RTU, MQTT, OPC-UA
- **Stockage optimisé**: Base de données temporelle InfluxDB
- **Dashboards personnalisables**: Visualisation Grafana avancée
- **Calcul d'indicateurs**: OEE, MTBF, MTTR en temps réel
- **Traçabilité complète**: Historique des productions et événements

## 🔍 Défis techniques et solutions

### Gestion des données à grande échelle
- Compression et downsampling automatique
- Partitionnement chronologique des données
- Cache pour optimiser les requêtes fréquentes

### Interopérabilité
- Adaptateurs pour différents protocoles industriels
- Normalisation des données via pipeline ETL
- API RESTful standardisée

## 📊 Impact

- Amélioration du TRS/OEE de 15-30% en moyenne
- Réduction des temps d'arrêt non planifiés
- Visibilité en temps réel de la production


## 👤 Contact

Pour toute question ou suggestion, n'hésitez pas à me contacter:
- Email: [anas.zehraoui17@gmail.com](mailto:anas.zehraoui17@gmail.com)
- LinkedIn: [Zehraoui anas ](https://www.linkedin.com/in/votre-profil)
