# README - Script de Vérification de la Connectivité Ping

## Description

Ce script PowerShell a pour but de vérifier la connectivité ping des adresses IP répertoriées dans un fichier `ip-list.txt`. Il enregistre les résultats du ping dans un fichier `resultat.txt`. Le script peut être utile pour vérifier la disponibilité d'hôtes réseau.

## Utilisation

### Prérequis

- Assurez-vous d'avoir PowerShell installé sur votre système.
- Créez un fichier `ip-list.txt` contenant la liste des adresses IP que vous souhaitez vérifier. Chaque adresse IP doit être sur une ligne distincte.

### Exécution du Script

1. Assurez-vous d'éditer le script pour définir les chemins appropriés des fichiers :
   - `$IPFile` : Le chemin du fichier `ip-list.txt` contenant les adresses IP à vérifier.
   - `$LogFile` : Le chemin du fichier dans lequel les résultats du ping seront enregistrés.

2. Exécutez le script en utilisant PowerShell. Par exemple :

   ```powershell
   .\votre_script.ps1
   ```

3. Le script parcourra la liste des adresses IP du fichier `ip-list.txt` et effectuera un ping sur chaque adresse IP.

4. Les résultats du ping seront enregistrés dans le fichier `resultat.txt`. Les adresses IP en ligne seront marquées comme "en ligne", et les adresses hors ligne seront marquées comme "hors ligne".

5. Vous pouvez vérifier les résultats en consultant le fichier `resultat.txt`.

## Configuration

Le script ne nécessite généralement aucune configuration complexe. Cependant, assurez-vous que les chemins des fichiers `$IPFile` et `$LogFile` sont correctement définis.

## Avertissement

Assurez-vous de respecter les lois et les politiques de sécurité en vigueur avant de scanner des adresses IP sans autorisation.

@Xavito
