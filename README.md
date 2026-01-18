# MDT Microsoft binaries mirror (Binaries 8456)

Ce dépôt GitHub a été créé pour pallier la suppression par Microsoft des liens de téléchargement directs pour certains composants essentiels de **Microsoft Deployment Toolkit (MDT)**, et plus spécifiquement pour la version **8456**.

## 📝 Description

Le fichier contenu dans ce dépôt est nécessaire pour l'installation ou la mise à jour de MDT. Suite au nettoyage des serveurs de téléchargement Microsoft, ce miroir permet aux administrateurs systèmes de continuer à déployer leurs images Windows sans interruption.

## 📦 Contenu du dépôt

* **MicrosoftDeploymentToolkit_x64.msi** (ou le nom exact de ton fichier) : L'installeur principal pour MDT 8456.

## 🚀 Installation rapide

1. **Téléchargement** : Cliquez sur le fichier dans la liste ci-dessus, puis sur le bouton **Download**.
2. **Installation** : Lancez le fichier `.msi` sur votre serveur de déploiement.
3. **Configuration** : Suivez les étapes habituelles de configuration de votre Deployment Share.

> [!IMPORTANT]
> Assurez-vous d'avoir installé au préalable les versions compatibles d'**ADK (Assessment and Deployment Kit)** et du **WinPE Add-on** correspondant à votre version de Windows (généralement Windows 10/11).

## ⚠️ Avertissement (Disclaimer)

Ce dépôt est un miroir de courtoisie. 
* Ce logiciel appartient à **Microsoft Corporation**.
* Il est recommandé de vérifier l'empreinte numérique (Hash) du fichier pour garantir son intégrité avant installation.
* L'utilisation de ce fichier reste sous votre entière responsabilité.

## 🛠️ Liens utiles

* [Documentation officielle Microsoft MDT](https://learn.microsoft.com/en-us/mem/configmgr/mdt/)
* [Notes de version (Release Notes)](https://learn.microsoft.com/en-us/mem/configmgr/mdt/release-notes)
