[🇫🇷 Lire ce README en français](./README.fr.md)

# yopass-french

> 🇫🇷 French-translated Docker image for [Yopass](https://github.com/jhaals/yopass) – Secure, ephemeral sharing of secrets.

---

## About

**yopass-french** is a community-maintained Docker image of [Yopass](https://github.com/jhaals/yopass) with a French language translation.  
Yopass is a tool for sharing secrets (like passwords or sensitive information) quickly and securely. Its main goal is to reduce the number of passwords circulating in emails, ticketing systems, and chat messages.

- Secrets are encrypted/decrypted locally in your browser.
- The decryption key is never sent to the server and is only shown once.
- Yopass returns a one-time URL with a configurable expiry date.

> For full details, features, and security information, please refer to the [original Yopass README](https://github.com/jhaals/yopass#readme).

---

## Usage

This image works exactly like the original, but with French language support.

- To use the French version, simply replace `jhaals/yopass` with `nicolasstr/yopass-french` in your Docker commands.

---

## Docker Images

Images are automatically built and pushed to [GitHub Packages](https://github.com/NicolasStr/yopass-french/pkgs/container/yopass-french) and will be available for use.

---

## Installation & Configuration

For installation and configuration instructions, please see the [original Yopass documentation](https://github.com/jhaals/yopass?tab=readme-ov-file#installation--configuration).

---

## Versioning

- This project tracks the same version as the original Yopass.
- If translation updates are made without an upstream Yopass update, a bump is added:  
  e.g., `1.1.1-2`, `1.1.1-3`, etc.

---

## Building the Image

Clone this repository and build the Docker image:

```sh
git clone https://github.com/NicolasStr/yopass-french.git
cd yopass-french
docker build -t nicolasstr/yopass-french .
```

---

## Contributing

All PRs are welcome! If you have improvements, fixes, or updated translations, feel free to open a pull request.

---

## Credits

- Original project: [Yopass by Johan Haals](https://github.com/jhaals/yopass)
- French translation: [NicolasStr](https://github.com/NicolasStr)  
  (with thanks to [Anturix](https://github.com/Anturix) for translation guidance)

---

## More Information

- For advanced configuration, deployment, and security notes, see the [original Yopass documentation](https://github.com/jhaals/yopass#readme).

---