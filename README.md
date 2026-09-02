# web-olo

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
