<p align="center">
  <a href="https://zrzur.com"><img src="https://zrzur.com/brand/banner.png" alt="Zrzur" width="720"></a>
</p>

<h3 align="center">Where your people gather.</h3>

<p align="center">
  <a href="https://zrzur.com">Website</a> ·
  <a href="https://app.zrzur.com">Open the app</a> ·
  <a href="https://zrzur.com/download">Download</a> ·
  <a href="https://discover.zrzur.com">Discover servers</a> ·
  <a href="https://zrzur.com/blog">Blog</a>
</p>

## What Zrzur is

Zrzur (زرزور) is an open-source home for friends and communities. You make a server, invite your people, and talk: in text channels, on voice, or with your screen shared.

- **Servers** with text and voice channels, roles and permissions
- **Voice and screen sharing**, with keys that work while a game is in front
- **Files, link previews, reactions, replies** and a message history you can go back through
- **Discover**: public servers that anyone can find and join
- **Bots and apps** through an open API, with slash commands, buttons and forms
- **In the browser** and as an app for Windows, macOS and Linux

In Arabic, every screen reads from right to left, and English and German get the same care. The app follows your device's language.

<p dir="rtl" align="right">
زرزور مكان مفتوح المصدر للأصدقاء والمجتمعات: سيرفرات بقنوات نصية وصوتية، ومشاركة الشاشة، وأدوار وصلاحيات. في المتصفح وعلى ويندوز وماك ولينكس، وبلغات كثيرة.
</p>

## Why it is open

- **You can read every line.** The server, the apps and the website are public.
- **You can run your own.** [self-hosted](https://github.com/zrzur/self-hosted) holds what a server of your own needs.
- **You can build on it.** Bots and apps use the same API as our own app, through [sdk-js](https://github.com/zrzur/sdk-js).

## The repositories

| Repository | What it is | Built with |
| --- | --- | --- |
| [backend](https://github.com/zrzur/backend) | REST API, real-time events, files, media proxy | Rust |
| [web](https://github.com/zrzur/web) | The app in the browser, also a PWA | Solid.js, TypeScript |
| [desktop](https://github.com/zrzur/desktop) | The app for Windows, macOS and Linux | Electron |
| [sdk-js](https://github.com/zrzur/sdk-js) | Library for bots and apps | TypeScript |
| [self-hosted](https://github.com/zrzur/self-hosted) | Run your own server | Docker Compose |
| [website](https://github.com/zrzur/website) | The source of zrzur.com | Solid.js, Vite |
| [sanad](https://github.com/zrzur/sanad) | Example bot, built with the SDK | JavaScript |

Each has two branches: `main` is the released version, `beta` is what comes next.

## Who builds Zrzur

Zrzur is a volunteer, open-source project. I build it in my free time, alongside school, and I pay for the servers, hosting and services out of my own pocket, with no salary or guaranteed income.

So an update, a fix or a reply can sometimes take a while. That's not because Zrzur doesn't matter to me. My time and resources are limited.

Zrzur isn't a big company with a budget or a full-time team. It grows step by step, and I won't promise dates I can't keep.

Thank you to everyone who supports Zrzur by sharing it, suggesting ideas, reporting bugs or contributing code. It means a lot. ❤️ If you want to help with the running costs: [Support Zrzur on Ko-fi](https://ko-fi.com/zrzur).

## Take part

- **Found a bug?** Open an issue in the repository it belongs to.
- **Found a security problem?** Do not open an issue. Follow `SECURITY.md` in that repository.
- **Want to change something?** Read `CONTRIBUTING.md` in that repository first.
- **Anything else:** support@zrzur.com

## Where Zrzur comes from

Zrzur is built on **Stoat**, the open-source chat software that used to be called Revolt. We took these versions as our starting point and have developed them on our own since:

| Zrzur | Started from | Version |
| --- | --- | --- |
| backend | [stoatchat/stoatchat](https://github.com/stoatchat/stoatchat) | `v0.16.2` |
| web | [stoatchat/for-web](https://github.com/stoatchat/for-web) | `stoat-for-web-v0.16.3` |
| desktop | [stoatchat/for-desktop](https://github.com/stoatchat/for-desktop) | `v1.5.4` |
| self-hosted | [stoatchat/self-hosted](https://github.com/stoatchat/self-hosted) | |
| sdk-js | stoat.js, © Pawel Makles and contributors | |

The server and the apps are licensed under AGPL-3.0 or later, the library under MIT. Every repository keeps the original copyright notices in `NOTICE` and lists our changes in `MODIFICATIONS.md`.

Zrzur is an independent chat platform based on the open-source Stoat software (formerly Revolt), licensed under AGPL-3.0 or later. Zrzur is not affiliated with Stoat, stoat.chat or Revolt Platforms Ltd. Please do not report Zrzur issues to the Stoat team.
