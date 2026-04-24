# pdf-forge
Marre de mettre tes documents sur des sites Internet et de dépendre de leur interface avec des pubs et des trucs qui aspirent tes données ? Petit personal software de bureautique pour fusionner les PDF.
```markdown
# PDF Forge

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Local%20Only-orange)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local-brightgreen)](https://github.com/Architecte1995/pdf-forge)

Outil de fusion PDF fonctionnant entièrement dans le navigateur. Aucun fichier n'est envoyé sur un serveur externe.

---

## Présentation

PDF Forge permet de fusionner plusieurs fichiers PDF en un seul document, directement sur votre appareil. Le traitement est local : vos documents ne quittent pas votre navigateur.

---

## Fonctionnalités

- Sélection multiple de fichiers PDF
- Glisser-déposer (drag & drop)
- Réorganisation de l'ordre des fichiers
- Affichage du nombre de pages par document
- Statistiques globales (fichiers, pages, taille)
- Suppression individuelle ou totale
- Interface adaptée aux smartphones
- Fonctionnement hors ligne après le premier chargement

---

## Utilisation

### GitHub Pages

Ouvrir l'URL publiée du dépôt.

### Fichier local

1. Télécharger `pdf-forge.html`
2. L'ouvrir dans un navigateur web
3. L'outil fonctionne sans connexion Internet

### Serveur local

```bash
git clone https://github.com/Architecte1995/pdf-forge.git
cd pdf-forge
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000/pdf-forge.html`.

---

## Technologies

- HTML5, CSS3, JavaScript vanilla
- [PDF-Lib](https://pdf-lib.js.org/) (v1.17.1, chargé via CDN) pour la manipulation PDF côté client

Aucune étape de compilation ou d'installation de dépendances n'est requise.

---

## Compatibilité

| Navigateur | Support |
|------------|---------|
| Chrome / Edge | ✅ |
| Firefox | ✅ |
| Safari (iOS) | ✅ |
| Chrome (Android) | ✅ |

Le traitement de fichiers volumineux peut prendre quelques secondes sur mobile.

---

## Licence

MIT License

Copyright (c) 2026 Architecte1995 & Kimi K 2.6 Thinking

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

---

## Crédits

- **Concept** : Architecte1995
- **Développement** : Kimi K 2.6 Thinking (Moonshot AI)
- **Moteur PDF** : [PDF-Lib](https://pdf-lib.js.org/) par Andrew Dillon
