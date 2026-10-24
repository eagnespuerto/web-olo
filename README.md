# web-olo

[![license](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![made with](https://img.shields.io/badge/made%20with-HTML5-E34F26?logo=html5&logoColor=white)](https://github.com/eagnespuerto/web-olo)
[![website](https://img.shields.io/badge/website-live-brightgreen)](https://eagnespuerto.github.io/web-olo/)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-support%20me-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/eagnespuerto)
[![Linktree](https://img.shields.io/badge/Linktree-soitsagnes-43E55E?logo=linktree&logoColor=white)](https://linktr.ee/soitsagnes)

Approximating **olo** — the color reported by Berkeley researchers in April 2025 after stimulating only the M cones of the human retina — via standard CIE and sRGB matrix transformations.

**Live page:** https://eagnespuerto.github.io/web-olo/

## What it shows

- The LMS → XYZ → linear-sRGB matrix chain applied to a pure M-cone stimulus `[0, 1, 0]`.
- Why the result falls outside every real display gamut.
- Three sRGB approximations (naive clip, white-axis gamut map, Oklab max-chroma).
- The same color rendered into Display P3, Rec. 2020, Adobe RGB via CSS `color()`.
- Raw linear values in ACEScg and ProPhoto RGB, plus ICtCp and xvYCC notes.

Everything computes in-browser; the page is a single static `index.html`.

## License

MIT — see [LICENSE](LICENSE).
