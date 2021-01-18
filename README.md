Guide personnel d'introduction à la sécurité opérationnelle  
===================================================================

Ce guide à pour but de vous permettre d'apprendre les bases de la sécurité opérationnel pour votre usage personnel, afin de protéger votre identité, vos communications, vos fichier, l'accès à vos services, vôtre identité, la validité de vos documents publics ...

> Disclaimer : la sécurité absolue n'existe pas, ce guide utilise un niveau de sécurité que je considère suffisant pour mon usage personnel et peut ne pas s'adapter à vôtre cas d'usage (données d'entreprise, données médicales, etc ...).

## Sommaire

+ Les gestionnaires de mot de passe
+ L'authentification à 2 facteurs
+ Les clés cryptographiques
+ Les utilisations des clés cryptographiques
+ Les smartcard


# Les gestionnaires de mot de passe

Chaque jour nous utilisons une quantité astronomique de mot de passe pour accéder à différents service, critiques ou non: Banque, Assurance Maladie, Impôts, Facebook, Twitter, Amazon, etc...

Il est essentiel que ces mots de passe soit tous différents, car en cas de compromission d'un site, vots identifiants et mot de passe peut être divulgué sur internet, et si vous utilisez le même partout, alors tout vos services deviennent accessible à tous.

Pour tester si votre accès à été compromis lors d'une attaque, il existe un très bon site nommé [HaveIBeenPwned](https://haveibeenpwned.com/) qui recherche votre adresse mail parmi les identifiants piratés accessible sur internet.

Pour pallier à ce problème, il existe un type d'outil qui vous permet de stocker tout vos mot de passe, et de générer des mot de passe aléatoire pour accéder à vos service : les __gestionnaires de mot de passe__.

Une seule règle à observer pour l'utilisation de ces gestionnaires : retenir par coeur un mot de passe maître, qui doit être solide car il permet d'accéder à tous vos autres mot de passe.

Voici un comparatif non-exhaustif des gestionnaire de mot de passe disponibles.

Gardez à l'esprit en choisissant le vôtre qu'il doit être pratique pour votre utilisation, sinon vous ne l'utiliserez pas.

Voici les critère que j'ai choisi pour les différencier :

+ La disponibilité d'un service de synchronisation en ligne
+ La disponibilité du service sur plusieurs plateform (système d'exploitation/mobile/etc) 
+ Le logiciel est il open source ?
+ S'il y a un service en ligne, est-il audité ?
+ Le logiciel gère-t-il la double authentification ?
+ Partage de secret entre utilisateurs


| Logiciels          | Synchronisation | Clients                             | Opensource    | Audité           | 2FA   | Secret sharing   |
| ------------------ |:---------------:|:-----------------------------------:|:-------------:|:----------------:|:-----:|:----------------:|
| Keepass            | No              | Mac,Windows,Linux,IOS,Android,Web   | Yes           | ?                | ?     | No               |
| LastPass           | Yes             | IOS,Android,Web                     | No            | ?                | Yes   | Yes              |
| 1Password          | Yes             | Mac,Windows,Linux,IOS,Android,Web   | No            | ?                | Yes   | Yes              |
| DashLane           | Yes             | Mac,Windows,Linux,IOS,Android,Web   | No            | ?                | Yes   | Yes              |
| Buttercup          | No              | Mac,Windows,Linux,IOS,Android,Web   | Yes           | ?                | No    | No               |
| Bitwarden          | Yes             | Mac,Windows,Linux,IOS,Android,Web   | Yes           | Audit&BugBounty  | Yes   | Yes              |

TODO: https://github.com/drduh/YubiKey-Guide

