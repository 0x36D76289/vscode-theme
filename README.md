# Allay Theme for VS Code

[![Licence GitHub](https://img.shields.io/github/license/0x36D76289/vscode-theme?style=for-the-badge)](./LICENSE)

**Allay** est un thème moderne pour Visual Studio Code, conçu pour être à la fois esthétique et fonctionnel. Avec des accents vibrants de bleu et de violet, il offre un contraste parfait pour réduire la fatigue oculaire tout en rendant votre code éclatant.

Le thème est disponible en deux variantes soigneusement conçues pour s'adapter à votre environnement de travail, que vous préfériez les interfaces sombres ou claires.

---

## 🚀 Installation

Vous pouvez installer le thème de deux manières.

### Via l'interface graphique (GUI)

1.  Ouvrez **Visual Studio Code**.
2.  Allez dans le panneau **Extensions** en cliquant sur l'icône dans la barre d'activités ou en utilisant le raccourci `Ctrl+Shift+X`.
3.  Recherchez `Allay Theme`.
4.  Cliquez sur le bouton **Installer**.
5.  VS Code vous demandera de sélectionner l'un des thèmes Allay.

### Via la ligne de commande (CLI)

1.  Ouvrez votre terminal.
2.  Exécutez la commande suivante :

```bash
npm install -g vsce
vsce package
code --install-extension allay-theme-0.0.1.vsix
```

3.  Redémarrez VS Code si nécessaire.

---

## 🎨 Activation

Après l'installation, ou à tout moment pour changer de thème :

1.  Ouvrez la **Palette de Commandes** avec `Ctrl+Shift+P`.
2.  Tapez `Preferences: Color Theme` et appuyez sur Entrée.
3.  Dans la liste, choisissez `Allay Dark` ou `Allay Light`.

---

## 🔧 Paramètres Recommandés

Pour une expérience visuelle optimale, je vous recommande d'utiliser une police qui supporte les ligatures de code, comme **Fira Code** ou **JetBrains Mono**.

Voici un exemple de configuration à ajouter à votre fichier `settings.json` :

```json
{
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "workbench.colorTheme": "Allay Dark" // ou "Allay Light"
}
```

---

## 💬 Feedback & Contribution

Vous avez trouvé un bug ou une couleur qui ne s'affiche pas correctement ? Vous avez une suggestion d'amélioration ?

N'hésitez pas à **ouvrir une issue** sur le [dépôt GitHub](https://github.com/0x36D76289/vscode-theme/issues) !

## 📜 Licence

Ce thème est publié sous la [Licence MIT](./LICENSE).
