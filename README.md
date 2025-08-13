# Al-Driven-Blockchain-Solutions-for-Next-Generation-loT-Applications
Solution IoT innovante intégrant TinyML, Ensemble Learning et Blockchain pour la détection de malwares. Entraînement distribué sur dispositifs simulés Raspberry Pi, communication MQTT sécurisée, et stockage immuable des performances via smart contract Ethereum.

Ce projet propose une architecture innovante combinant IoT, TinyML, Ensemble Learning et Blockchain pour la détection et la classification de malwares dans un environnement distribué et sécurisé.
L’objectif est de démontrer comment des dispositifs IoT à ressources limitées peuvent exécuter localement des modèles d’IA optimisés tout en garantissant la traçabilité et l’intégrité des résultats via la blockchain.

Fonctionnalités principales:

-Architecture distribuée Client-Serveur avec communication sécurisée via MQTT et SSH.

-Prétraitement et sélection de caractéristiques d’un dataset de détection de malwares (Kaggle) avec LASSO et standardisation.

-Implémentation d’un Ensemble Learning (Bagging) avec MLP pour améliorer la robustesse et la précision des prédictions.

-Conversion et optimisation des modèles en TensorFlow Lite Micro (quantification) pour exécution sur des dispositifs simulés Raspberry Pi via VirtualBox.

-Stockage immuable des résultats d’accuracy dans une blockchain privée Ethereum via un Smart Contract Solidity déployé avec Ganache et Hardhat.

Technologies clés:

-Langages : Python, Solidity, C++

-IA & ML : TensorFlow Lite Micro, scikit-learn

-IoT & Communication : MQTT (Paho-MQTT), SSH, SCP

-Blockchain : Ethereum (Ganache, Hardhat, Ethers.js)

-Environnements : Ubuntu Server/Desktop, VirtualBox

Architecture générale:

-Serveur central : prépare, divise et distribue les données vers les clients, puis agrège et envoie les résultats vers la blockchain.

-Clients IoT simulés : reçoivent un sous-ensemble de données, entraînent un modèle TinyML localement, et renvoient les performances au serveur.

-Blockchain : enregistre de manière sécurisée les résultats agrégés, garantissant transparence et intégrité.

Résultats:

-Précision de plus de 95% sur la détection de malwares après optimisation TinyML.

-Transmission et agrégation fiables dans un environnement distribué.

Stockage sécurisé et traçable des performances via blockchain.
