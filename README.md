#  SDICTF(SEMAINE DE L'INNOVATION) ESATIC 2026

Auteur : **5yn0r**  
Année : 2026  
Événement : CTF organisé par le **A2E à la SDI** de l'**ESATIC**

Ce dépôt contient les solutions détaillées de deux challenges du SDICTF 2026 :

- 📱 **Gestionnaire Pro** (Mobile / Reverse Engineering)
- 🌐 **La Porte Dérobée** (Web / SQLi)

---

##  1. Gestionnaire Pro – APK Analysis

| Catégorie      | Mobile / Reverse Engineering |
|----------------|------------------------------|
| Difficulté     | Medium                       |
| Auteur         | Raphael                      |
| Format         | APK                          |
| Flag           | `SDICTF{XXXXXXXXXXXXXXXXXX}` |

### 📌 Résumé

L’APK `gestionnaire.apk` contient un fichier de configuration sensible mal dissimulé dans les assets. Une simple extraction permet d’obtenir le flag.

### Conclusion

> Mauvaise pratique de build : inclusion d’un fichier de configuration interne dans l’APK publié.

---

##  2. La Porte Dérobée – Web SQLi

| Catégorie       | Web / SQLi                   |
|----------------|-------------------------------|
| Difficulté     | Medium                        |
| Auteur         | Raphael                       |
| Format         | Formulaire de connexion       |
| Flag           | `SDICTF{XXXXXXXXXXXXXXXXXXX}` |

### 📌 Résumé

Un formulaire de connexion vulnérable à une injection SQL UNION avec WAF. Contournement possible grâce aux commentaires `/*/`.

### Conclusion

> Contournement de WAF par commentaires SQL, UNION-based SQLi sur SQLite, injection d’un rôle administrateur.

---

## Licences

Ce travail est mis à disposition sous licence **MIT** pour le code et **CC BY-NC-SA 4.0** pour les write-ups.

- Vous êtes libre de partager et adapter ces write-ups à des fins non commerciales, avec mention de l’auteur.
- Le code d’exploitation éventuel peut être réutilisé librement dans un cadre légal.

### Auteur

**5yn0r** – [GitHub](https://github.com/5yn0r)

---

## ⭐ Remerciements

Merci au **A2E de l’ESATIC** et aux parrains **Raphael DAMO & Modeste AKAFFOU** - [GitHub](https://github.com/modesteakaffou) pour ces challenges instructifs.


