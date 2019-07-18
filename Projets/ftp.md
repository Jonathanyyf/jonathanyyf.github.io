FTP
=

FTP : File Transfert Protocol – RFC959

D’après le **RFC 959**, Bhushan Abbay a créé et défini le 1er standard du protocole FTP en 1971, sous RFC 114 en tant que MIT-Project MAC.
Permet l’échange de fichiers, entre un serveur FTP et un client FTP.
C’est un protocole au niveau application (7) dans le modèle OSI.
**Par défaut il utilise le port 20 et 21**.
La définition et son standard sont consultables: https://tools.ietf.org/html/rfc959
Il peut être utilisé à l’aide d’un logiciel ou par la ligne de commande.
Le protocole FTP est multi-plateforme : Linux, Windows, Mac…


Ses principales caractéristiques :

- **Lisible** depuis un navigateur web
- Changement de dossier racine
- **Gestion/Permissions** des utilisateurs
- **Permissions** des dossier/fichiers
- Utilisable en **ligne de commande**
- Upload automatique vers un dossier défini


Les logiciels FTP serveur les plus connus :

FileZilla (Windows)
Vsftpd (linux)
CoreFTP (Windows)


Les logiciels FTP client les plus connus :

- FileZilla (Multi-plateforme)
- CurlFtpFS(CLI linux)
- WinSCP (Windows)



Le protocole FTP est obsolete au niveau sécurité, toutes les données transitant par le protocole FTP ne sont pas sécurisées, chiffrés, laissant la possibilité aux données critiques d’être lus et volées.

Alternatives sécurisées :

- FTPS (File Transfert Protocol TLS) : Protocole FTP avec TLS
- SFTP (SSH File Transfert Protocol) : Utilise le protocole SSH
- SCP (Secure Copy Protocol) : Utilise le protocole SSH
