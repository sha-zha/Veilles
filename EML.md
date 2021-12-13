# FORMAT EML 

## qu'est ce qu'est le format EML ? 

Le format EML est un format souvent utilisés pour les messages électroniques (email ) enregistrés par les programmes de messagerie, tel que la messagerie outlook. 
Ce type de fichier peut contenir du text brut ou des pièces jointes ( binaires ) envoyées par e-mail. Il faut faire attention car les fichiers EML sont susceptibles d'être infectés par des virus et/ou par d'autres logiciels malveillants.

Le format EML a été créé par Microsoft Corporation.

## struture du fichier

Un document .eml est généralement composé de deux parties: l'en-tête de fichier et le corps de fichier. L'en-tête comprend les adresses d'expéditeur et de recepient, le sujet et l'horodatage. Le message lui-même est stocké dans le corps de fichier. Typiquement, un fichier .eml stocke un seul message.

On peut ouvrir ses fichiers eml depuis des applications tels que  
* Mozilla Thunderbird
* Microsoft Outlook Express
* Outlook Express


## Technique 

## hedaer 

Exemple Header

From: John@bmw.eml.light.com

To: Andy@fileformat.com

Date: Thu, 8 Mar 2018 10:43:37 +0100

Subject: bmw eml light

## corps message possible

| Type       | 	Description    | Exemple |
| -----------|-----------------|---------|
|text| format lisible pour humain| 	text/plain, text/html, text/css, text/javascript|
|image| image |image/bmp, image/png, image/jpg, image/gif|
|audio|	audio |	audio/mdi, audio/wav|
|binaire |fichier pouvant être traduit en binaire souvent pièces jointes |	application/octet-stream, application/vnd.mspowerpoint, application/xhtml+xml, application/xml, application/pdf|

## Exemple dd'un fichier format EML

Suivre ce tuto pour voir à quoi ressemble un fichier eml depuis votre messagerie gmail

https://www.lifewire.com/save-an-email-as-an-eml-file-in-gmail-1171956

vous pouvez également sauvegarder ce fichier 

vous pouvez le lire en passant par un client de messagerie ou application dédiée.

## CORRUPTION FICHIER 

lien article : https://www.commentcamarche.net/contents/1230-le-ver-nimda


résumé risque possible :

*C'est quoi NIMDA ?*

un ver se propageant à l'aide du courrier électronique, mais il exploite également 4 autres modes de propagation :
* Le web
* Les répertoires partagés
* Les failles de serveur Microsoft IIS
* Les échanges de fichiers


*méchant hackers*

Si votre ordinateur a déjà corrompu en amont, le hacker pourra :

- écouter vos échanges 
- répondre à votre place 
- glisser des fichier .eml exécutable afin de mieux surveiller et prendre les informations souhaités.

## indices pour prévenir de la menace

1. rechercher l'existance de fichier .eml sur votre ordinateur si vous n'êtes pas la personne qui a faite cette action supprimmer le fichier
2. ne ouvrir les email suspects ( spams ) 
3. ne pas cliquer sur des pièces jointes suspectes notamment lorsqu'elles ont le nom de README.eml ou README.exe généralement le nom utilisé quand le fichier est corrompu.



sources informations : 
 
* https://www.vadesecure.com/fr/blog/les-hackers-contournent-les-couches-de-transport-pour-deposer-des-spams-via-imap/
* https://www.commentcamarche.net/contents/1230-le-ver-nimda
* https://www.reviversoft.com/fr/file-extensions/eml

* https://www.lifewire.com/save-an-email-as-an-eml-file-in-gmail-1171956
