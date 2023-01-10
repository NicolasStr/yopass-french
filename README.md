
# yopass - French language file

***Credits to [Anturix](https://github.com/Anturix) for example about translating Yopass***

---
## English
French language File for yopass by Johan Haals (jhaals/yopass)
[Yopass - Share Secrets Securely](https://github.com/jhaals/yopass)

### Installation

Copy the `website/public/locales/fr.json` file to the corresponding directory in your yopass installation.

yopass will automatically detect the new language and activate it if your Browser presents that language to yopass.

### Container

Check this repository out and build your own container with the german language file included to the original Yopass-Image from docker.io.

```
git clone https://github.com/NicolasStr/yopass-french.git
cd yopass-french
docker build -t anturix/yopassfr -f Dockerfile
```

---
## Français

Tranduction française pour Yopass par Johan Haals (Jhaals / Yopass)
[Yopass - Share Secrets Securely](https://github.com/jhaals/yopass)

### Installation

Copiez le fichier site `website/public/locales/fr.json` dans le répertoire correspondant dans votre installation Yopass.

Yopass détectera automatiquement la nouvelle langue et l'activera si votre navigateur présente cette langue à Yopass.

### Container

Clonez ce repository et créez votre propre conteneur avec le fichier de langue française inclus dans l'image d'origine Yopass.

```
git clone https://github.com/Anturix/yopass-german.git
cd yopass-german
docker build -t anturix/yopassde -f Dockerfile
```
