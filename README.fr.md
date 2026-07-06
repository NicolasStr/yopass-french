> [!WARNING]
> ## 🗄️ Ce projet est archivé
>
> La traduction française est désormais **intégrée directement dans Yopass**.
> Il n'y a plus aucune raison d'utiliser ce fork.
>
> 👉 **Utilisez plutôt [jhaals/yopass](https://github.com/jhaals/yopass).**
> Le français est disponible nativement via le sélecteur de langue intégré —
> aucune image personnalisée n'est nécessaire.
>
> Ce dépôt est conservé en lecture seule à titre de référence historique et
> ne recevra plus de mises à jour.

---

# yopass-french (français)

> 🇫🇷 Image Docker traduite en français de [Yopass](https://github.com/jhaals/yopass) – Partage sécurisé et éphémère de secrets.

---

## À propos

**yopass-french** est une image Docker communautaire de [Yopass](https://github.com/jhaals/yopass) avec une traduction française.
Yopass permet de partager des secrets (mots de passe ou informations sensibles) rapidement et en toute sécurité. Son objectif principal est de réduire le nombre de mots de passe circulant dans les emails, tickets et messages instantanés.

- Les secrets sont chiffrés/déchiffrés localement dans votre navigateur.
- La clé de déchiffrement n'est jamais envoyée au serveur et n'est affichée qu'une seule fois.
- Yopass retourne une URL à usage unique avec une date d'expiration configurable.

> Pour plus de détails, consultez le [README Yopass original](https://github.com/jhaals/yopass#readme).

---

## Utilisation

Cette image fonctionne exactement comme l'originale, mais avec le support du français.

- Pour utiliser la version française, remplacez simplement `jhaals/yopass` par `nicolasstr/yopass-french` dans vos commandes Docker.

---

## Images Docker

Les images sont automatiquement construites et publiées sur [GitHub Packages](https://github.com/NicolasStr/yopass-french/pkgs/container/yopass-french) et sont disponibles à l'utilisation.

---

## Installation & Configuration

Pour l'installation et la configuration, veuillez consulter la [documentation Yopass originale](https://github.com/jhaals/yopass?tab=readme-ov-file#installation--configuration).

---

## Versionnage

- Ce projet suit la même version que Yopass original.
- Si des mises à jour de traduction sont faites sans mise à jour de Yopass, un suffixe est ajouté :
  ex : `1.1.1-2`, `1.1.1-3`, etc.

---

## Construire l'image

Clonez ce dépôt et construisez l'image Docker :

```sh
git clone https://github.com/NicolasStr/yopass-french.git
cd yopass-french
docker build -t nicolasstr/yopass-french .
```

---

## Contribuer

Toutes les contributions sont les bienvenues ! Si vous avez des améliorations, corrections ou mises à jour de traduction, ouvrez une pull request.

---

## Crédits

- Projet original : [Yopass par Johan Haals](https://github.com/jhaals/yopass)
- Traduction française : [NicolasStr](https://github.com/NicolasStr)
  (merci à [Anturix](https://github.com/Anturix) pour l'aide à la traduction)

---

## Plus d'informations

- Pour la configuration avancée, le déploiement et la sécurité, consultez la [documentation Yopass originale](https://github.com/jhaals/yopass#readme).

---
