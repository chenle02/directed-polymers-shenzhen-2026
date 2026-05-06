<div align="center">

# A Class of *d*-Dimensional Directed Polymers in a Gaussian Environment

### Workshop on PDEs and Stochastic PDEs in Material Science and Statistical Mechanics

**The Chinese University of Hong Kong, Shenzhen** &middot; May 4–8, 2026

[![View Slides](https://img.shields.io/badge/▶%20View%20Slides-chenle02.github.io%2Fdirected--polymers--shenzhen--2026-2EA44F?style=for-the-badge)](https://chenle02.github.io/directed-polymers-shenzhen-2026/)

[![Reveal.js](https://img.shields.io/badge/Reveal.js-5.0.5-9CC?style=flat-square)](https://revealjs.com)
[![MathJax](https://img.shields.io/badge/MathJax-3-005A9C?style=flat-square)](https://www.mathjax.org/)
[![Manim](https://img.shields.io/badge/Manim-Community-FF7A00?style=flat-square)](https://www.manim.community/)
[![arXiv](https://img.shields.io/badge/arXiv-2603.06574-b31b1b?style=flat-square)](https://arxiv.org/abs/2603.06574)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

</div>

---

## ▶ View the Slides

**Live deployment:** <https://chenle02.github.io/directed-polymers-shenzhen-2026/>

| Key | Action |
|-----|--------|
| `→` `Space` | Advance |
| `←` | Back |
| `Esc` / `O` | Overview (jump by clicking a tile) |
| `S` | Speaker view (clock, timer, next-slide preview) |
| `F` | Fullscreen |
| `?` (Shift+/) | Help dialog |

---

## 🎤 The Talk

A research-colloquium slide deck by **Le Chen** ([Auburn University](https://chenle02.github.io)), joint work with

| Co-author | Affiliation |
|-----------|-------------|
| **Cheng Ouyang** | University of Illinois at Chicago |
| **Samy Tindel** | Purdue University |
| **Panqiu Xia** | Cardiff University |

**Wednesday, May 6, 2026 &middot; 16:00–17:00 &middot; CUHK-Shenzhen, Conference Complex II 202 & 203**

---

## 📄 Preprint

> L. Chen, C. Ouyang, S. Tindel, P. Xia,
> *A class of d-dimensional directed polymers in a Gaussian environment.*
> [**arXiv:2603.06574**](https://arxiv.org/abs/2603.06574) (2026).

---

## 📖 About the Talk

The talk introduces a class of *d*-dimensional **continuous directed polymers**
in a general Gaussian environment — white in time, homogeneous in space —
covering both trace-class and non-trace-class regimes.

### Central results

1. **Singularity dichotomy.**
   The quenched polymer measure $\mathbb{P}^W_\beta$ is mutually singular with the Wiener measure $\mathbb{P}_0$ for almost every realization of the noise $W$ if and only if the spatial covariance is *not* trace-class, i.e. $\widehat{f}(\mathbb{R}^d) = \infty$. The criterion is **sharp** and holds for every $\beta > 0$.

2. **Diffusive CLT in $d \ge 3$ at high temperature.**
   Under Dalang's spectral integrability $\Upsilon(0) < \infty$ and weak disorder $\beta < \beta_0$, the rescaled polymer endpoint converges to a Gaussian limit.

3. **Local Brownian behavior.**
   Despite the global singularity, the polymer path agrees with a Brownian motion at every fixed scale — singularity emerges only in the limit.

### Manim animations

Three Manim-rendered scenes carry the main ideas:

- **Scene A** — Discrete → continuous polymer via Donsker refinement
- **Scene B** — Brownian motion vs. polymer path (locally identical, globally singular)
- **Scene C** — Martingale collapse on a dyadic skeleton

---

## 🏗️ Built With

- [**Reveal.js 5.0.5**](https://revealjs.com) — slide framework, `night` theme
- [**MathJax 3**](https://www.mathjax.org/) — TeX rendering (CDN)
- [**Manim Community**](https://www.manim.community/) — open-source mathematical animations
- [**edge-tts**](https://github.com/rany2/edge-tts) — narration

### Local preview

```bash
git clone https://github.com/chenle02/directed-polymers-shenzhen-2026.git
cd directed-polymers-shenzhen-2026
python3 -m http.server 8000
# Open http://localhost:8000 in your browser
```

---

## 🗂️ Repository Layout

```
.
├── index.html              ← The slide deck
├── mystyle_polymer.css     ← Custom styling (overrides night theme)
├── dist/                   ← Reveal.js core
├── plugin/                 ← Reveal.js plugins (notes, math, highlight)
├── assets/                 ← Images (Jupiter, team, Bessel, SPDE landscapes)
└── videos/                 ← Manim animations (scene_A–D.mp4)
```

---

## 🙏 Acknowledgments

This work is supported by:

- **U.S. National Science Foundation** &mdash; CAREER Award
  [No. 2443823](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2443823) (2025–2030)
- **Simons Foundation** &mdash; Travel Support for Mathematicians
  No. 959981 (2022–2027)

The mathematical animations were built with the
[**Manim Community**](https://www.manim.community/) open-source library —
warm thanks to the community of contributors who maintain it.

I am grateful to the **Workshop on PDEs and SPDEs in Material Science and Statistical Mechanics** organizers at CUHK-Shenzhen — *Yuan Chen*, *Cheuk Yin Lee*, and *Xuefeng Wang* — for the kind invitation, and to **Bella Lin** (SSE) for impeccable logistics support.

Special thanks to my coauthors **Cheng Ouyang**, **Samy Tindel**, and **Panqiu Xia** for the long collaboration that produced this work, and to the broader SPDE community whose ideas this talk builds upon.

---

<div align="center">

*Slides © 2026 Le Chen — released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).*
*Reveal.js, MathJax, Manim, and other third-party code retain their respective licenses.*

**谢谢 · Thank You**

</div>
