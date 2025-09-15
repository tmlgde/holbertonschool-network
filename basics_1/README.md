# Projet Réseau - Partie 2

## 📚 Ressources
À lire ou regarder pour ce projet :
- [What is localhost](https://en.wikipedia.org/wiki/Localhost)  
- [What is 0.0.0.0](https://stackoverflow.com/questions/2730142/what-is-the-meaning-of-0-0-0-0)  
- [What is the hosts file](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)  
- [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)  

Commandes utiles (voir `man` ou `help`) :
- `ifconfig`  
- `telnet`  
- `nc`  
- `cut`  

---

## 🎯 Objectifs pédagogiques
À la fin de ce projet, vous devez être capable d’expliquer **sans l’aide de Google** :

### Général
- ✅ Ce qu’est **localhost** / `127.0.0.1`  
- ✅ Ce qu’est **0.0.0.0**  
- ✅ Ce qu’est le fichier **/etc/hosts** et à quoi il sert  
- ✅ Comment afficher les interfaces réseau actives de votre machine  

---

## ⚙️ Exigences
- Tous vos fichiers seront interprétés sur **Ubuntu 22.04 LTS**  
- Tous vos fichiers doivent se terminer par une **nouvelle ligne**  
- Un fichier **README.md** est obligatoire à la racine du projet  
- Tous vos scripts **Bash** doivent être **exécutables**  
- Vos scripts Bash doivent passer **Shellcheck** (version 0.7.0 via `apt-get`) sans aucune erreur  
- La première ligne de tous vos scripts doit être :
  ```bash
  #!/usr/bin/env bash
