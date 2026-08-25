# Serein

> **Write quietly. Think deeply.**

**Serein** — 法语里「黄昏后的细雨」。不是暴雨，不是阵雨，只是润物细无声。

它描述的不是编辑器，而是你使用它时的心境：空气清冽，无人打扰，可以静静写点东西。

编辑器不该成为主角。它应当像黄昏的细雨一样安静存在——你只记得今天写得很顺，而不是「这个软件功能真多」。

![Version](https://img.shields.io/badge/0.7.5·Magic%20Bean-lightgrey)
![License](https://img.shields.io/badge/License-Proprietary-lightgrey)
[![Issues](https://img.shields.io/badge/GitHub-Issues-blue)](https://github.com/Jackstar1212/Serein/issues)

---

## This repository

This GitHub repository is the **public face for issues and selected documentation**.

- Repository: [github.com/Jackstar1212/Serein](https://github.com/Jackstar1212/Serein)
- Bug reports & ideas: [Issues](https://github.com/Jackstar1212/Serein/issues)

The Serein application is **proprietary**. Source code is not published here; development continues on a private forge.

Selected design docs may appear under `docs/` for transparency. They describe intent and philosophy — not a buildable tree.

## Positioning

Serein is a **Markdown-first modular document editor**.

Markdown is the default *serialization* — not the whole identity. At the center sits a unified **Document Model**: WYSIWYG, Source, Split, and Reading are four ways of looking at the same document. Change the glasses; the page remains one.

The kernel is designed to extend. The product is delivered as an **editor** — restrained, focused, local. Not a vault. Not a workspace. Not a platform. Not AI.

> *Kernel scalable. Product still an editor.*  
> Extensibility is not a license to pre-build sync, markets, or collaboration. Every abstraction still faces the [Manifesto](MANIFESTO.md) test.

## Philosophy

|          |                                                                 |
| -------- | --------------------------------------------------------------- |
| Content first | The document is the stage. UI is optional, dismissible, quiet. |
| Less is more  | Default: a blank page. Features must earn their place.         |
| Modular       | Core is the editor; capabilities are plugins. Remove any — it still writes. |
| Local-first   | No accounts. No telemetry. Your files never leave the machine. |
| Platform-native | Windows feels like Windows. macOS like macOS. Linux like Linux. |

We do not ship AI. We do not impose knowledge graphs, cloud sync, or welcome screens that delay the first keystroke. What you need, you choose. What you don't, never appears.

Full constitution: [MANIFESTO.md](MANIFESTO.md) · Vision: [docs/vision.md](docs/vision.md)

## Stack (at a glance)

| Layer    | Choice                                    |
| -------- | ----------------------------------------- |
| Desktop  | Tauri 2 + Rust                            |
| UI       | React 19 + TypeScript + Vite + Tailwind 4 |
| Editor   | ProseMirror + markdown-it                 |

Open-source components remain under their own licenses (MIT and others). Attribution lives in the app: **Help → About Serein → License**.

## Status

**0.7.5 · Magic Bean** — Phase 1 MVP delivered; Phase 2 underway.

Typora-style live syntax · four views · GFM & callouts · Mermaid / KaTeX / tables · export · multi-tab shell · themes · local drafts · privacy by default.

Windows is the primary surface today.

## Docs

|                   |                              |
| ----------------- | ---------------------------- |
| [MANIFESTO.md](MANIFESTO.md)     | Constitution              |
| [docs/vision.md](docs/vision.md) | Product vision            |
| [ISSUE_TEMPLATE.md](ISSUE_TEMPLATE.md) | How to file issues  |


## License

**Proprietary.** All rights reserved. Source is not published in this repository.

Third-party notices: in-app **Help → About Serein → License**.

---

*The editor fades away. Your thoughts remain.*
