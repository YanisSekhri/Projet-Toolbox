YS ToolBox

YS ToolBox est une collection d'outils de sécurité informatique accessibles via une interface graphique. Il suffit de lancer ystoolbox.py pour accéder à toutes les fonctionnalités sans avoir à exécuter les scripts individuellement.

Fonctionnalités
- Scanner Nmap : Scanne les ports d'une adresse IP ou d'un réseau en utilisant Nmap.
- Scanner de vulnérabilités : Scanne une adresse IP pour identifier les vulnérabilités en utilisant Nmap et le script vulners.
- Keylogger : Enregistre les frappes de touches.
- Attaque par force brute SSH : Tente de se connecter à un serveur SSH en utilisant une liste de noms d'utilisateur et de mots de passe.
- Détection de machines : Scanne une plage d'adresses IP pour identifier les périphériques connectés au réseau.


Installation
Pour exécuter ce projet, vous devez installer les bibliothèques Python suivantes :

- tkinter : Pour créer l'interface graphique (généralement inclus avec Python).
- pynput : Pour surveiller les frappes de touches.
- requests : Pour envoyer des requêtes HTTP.
- paramiko : Pour les connexions SSH.
- scapy : Pour envoyer des requêtes ARP.
- pillow : Pour certaines fonctionnalités graphiques avancées dans tkinter.
- nmap : Pour utiliser Nmap via Python.
- pandas : Pour la manipulation de données.
- beautifulsoup4 : Pour parser le HTML des pages web.
- keyboard : Pour écouter et enregistrer les événements du clavier.



Installation des dépendances

Vous pouvez installer toutes les dépendances en utilisant les commandes pip suivantes :

pip install pynput
pip install requests
pip install paramiko
pip install scapy
pip install pillow
pip install nmap
pip install pandas
pip install beautifulsoup4



Installation de Nmap

En plus des bibliothèques Python, vous devez également installer Nmap sur votre système. Vous pouvez télécharger et installer Nmap à partir du site officiel de Nmap.


Utilisation

Pour utiliser la toolbox, il suffit de lancer le script ystoolbox.py :
python ystoolbox.py

Cela ouvrira une interface graphique permettant d'accéder à toutes les fonctionnalités décrites ci-dessus.


Détails des fonctionnalités


Scanner Nmap : 
Scanne les ports d'une adresse IP ou d'un réseau. Vous pouvez configurer les options de scan comme le scan furtif (SYN), la détection de version, la détection du système d'exploitation et le scan agressif. Les résultats peuvent être exportés en format HTML.


Scanner de vulnérabilités: 
Scanne une adresse IP ou un nom DNS pour identifier les vulnérabilités en utilisant Nmap et le script vulners. Les résultats sont affichés dans l'interface et peuvent être exportés en format HTML avec des recommandations.


Keylogger
Enregistre les frappes de touches et les sauvegarde dans un fichier listkey.txt. Vous pouvez démarrer, arrêter et ouvrir le fichier de log à partir de l'interface graphique.


Attaque par force brute SSH : 
Utilise paramiko pour tenter de se connecter à un serveur SSH en utilisant une liste de noms d'utilisateur et de mots de passe. Les résultats de l'attaque sont affichés dans l'interface et un fichier de log est généré.


Détection de machines : 
Scanne une plage d'adresses IP pour identifier les périphériques connectés au réseau. Les résultats sont affichés dans l'interface et peuvent être exportés en format HTML.



Auteurs : 
Ce projet a été développé par Yanis Sekhri.



Ce README fournit une description complète du projet, des fonctionnalités disponibles, des étapes d'installation et des détails d'utilisation pour chaque outil inclus.

