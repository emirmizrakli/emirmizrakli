<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E1065,100:0EA5E9&height=180&section=header&text=Emir%20M%C4%B1zrakl%C4%B1&fontSize=44&fontColor=ffffff&animation=fadeIn&desc=AI-assisted%20full-stack%20%26%20game%20developer&descAlignY=72" width="100%" alt="Emir Mızraklı" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=900&color=38BDF8&width=640&lines=Builds+from+scratch%2C+ships+to+production;TypeScript+%C2%B7+React+%C2%B7+React+Native+%C2%B7+Unity%2FC%23;Trains+its+own+language+model+in+the+browser" alt="what I do" />

**Two commercial games shipped on Steam · a language model written and trained from scratch · production web apps for real clients.**

[Portfolio](https://emirmizrakli.com.tr) · [LinkedIn](https://www.linkedin.com/in/emirmizrakli) · [Steam: Velron Games](https://store.steampowered.com/app/4913770/) · [emirmizrakli@gmail.com](mailto:emirmizrakli2525@gmail.com)

</div>

---

### What I do

I build software end to end and ship it — games people can buy, web apps clients actually use, and machine learning rebuilt from the math up when I want to prove I understand it.

- **Games** — Unity/C#. Two commercial titles released on Steam in 2026 under my own label, **Velron Games**, covering idle progression, deck-building, roguelike naval combat and shop-management sims.
- **Web & mobile** — Next.js, React, React Native (Expo), TypeScript, Node, Tailwind, Supabase. Client work in production plus my own products.
- **Machine learning from scratch** — no `pip install` in sight: I write the autodiff engine, the attention layers, the optimizer and the training loop myself, then check every gradient against numerical differentiation.

---

## Featured work

### 🧠 emergence — watch a language model train in your browser

A transformer, a reverse-mode autodiff engine and a training loop — **written from scratch, zero runtime dependencies** — that train live in the browser tab you open. The loss curve, the attention heads, the embedding space, the gradient norms and the text it writes are all recomputed from the weights as they change. Not a recording. Not a pre-rendered chart.

[![Live demo](https://img.shields.io/badge/live_demo-emirmizrakli.github.io-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emirmizrakli.github.io/emergence/)
[![Source](https://img.shields.io/badge/source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emirmizrakli/emergence)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/emirmizrakli/emergence)
[![Dependencies](https://img.shields.io/badge/runtime_dependencies-0-22C55E?style=for-the-badge)](https://github.com/emirmizrakli/emergence/blob/main/package.json)
[![Tests](https://img.shields.io/badge/tests-35%2F35-22C55E?style=for-the-badge)](https://github.com/emirmizrakli/emergence)

- **Two independent gradient engines.** Hand-written backward passes are fast but can be quietly wrong — so a tape-based autodiff engine doubles as an oracle, and both are checked against central finite differences. A wrong transpose cannot survive the test suite.
- **A model ladder, because the failure is the point.** bigram → fixed-window MLP → transformer, same trainer, same corpus, same budget: measured held-out perplexity **24.7 → 12.4 → 11.0**, with the transformer being *smaller* than the MLP it beats (106k vs 152k parameters).
- **Real numbers, not promises.** ~4,200 lines of source, 693 lines of tests, a 207,296-parameter checkpoint shipped with the demo (4 layers, 48-character context, held-out perplexity **10.1**), training at ~1,100 tokens/second on one CPU core in a Web Worker.
- **Bilingual docs** — [English](https://github.com/emirmizrakli/emergence/blob/main/README.md) · [Türkçe](https://github.com/emirmizrakli/emergence/blob/main/README.tr.md) — and the demo page itself switches between Turkish and English.

<sub>`TypeScript` · `Web Worker` · `Canvas` · `autodiff` · `transformer` · `no dependencies` · `Node 23+ native TS`</sub>

### 🎮 Velron Games — two titles on Steam

| game | released | what it is |
| --- | --- | --- |
| [**Corsair Fleet: Tides of Plunder**](https://store.steampowered.com/app/4913770/) | Sep 14, 2026 | idle progression + crew deck-building + roguelike naval combat — start with one ship, plunder the seven seas |
| [**Sole Mates: Tidy Up the Shoe Store**](https://store.steampowered.com/app/5174490/) | Oct 2026 | a shop-management sim: match two thousand scattered sneakers by model and size, fill the shelves, keep the customers happy |

Designed, coded, published and supported solo — developer *and* publisher of both.

### 🌐 Web & client work

- **[Şanlı Oto Kurtarma](https://github.com/emirmizrakli/sanli-oto-kurtarma)** — a Next.js 15 local-SEO site built for an İstanbul tow-truck company: real client, real business, structured data, service pages and a technical SEO audit.
- **[emirmizrakli.com.tr](https://emirmizrakli.com.tr)** — my portfolio, built and shipped.

---

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### Türkçe

Merhaba 👋 İstanbul'da yaşıyorum; oyun ve yazılım geliştiriyorum. Steam'de **Velron Games** etiketiyle yayınlanmış iki ticari oyunum, gerçek müşteriler için yaptığım web işleri ve sıfırdan yazdığım bir dil modeli (bkz. **emergence**) var.

Hazır kütüphaneleri kullanmakla kalmayıp işin matematiğini de kurabiliyorum: attention, geri yayılım, Adam — hepsi elle yazılmış ve sayısal türevle test edilmiş. Bu depoda gördüğünüz her şey benim tarafımdan, sıfırdan yazıldı.

Projenin Türkçe dokümantasyonu: **[README.tr.md](https://github.com/emirmizrakli/emergence/blob/main/README.tr.md)**

---

<div align="center">

<a href="https://emirmizrakli.github.io/emergence/"><img src="https://img.shields.io/badge/watch_it_train-▶-0EA5E9?style=for-the-badge" alt="watch it train" /></a>

<sub>Open to junior/entry-level software, AI and game development roles — remote or İstanbul.</sub>

</div>
