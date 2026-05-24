# SplitFlux Project Page

Project page for **SplitFlux: Learning to Decouple Content and Style from a Single Image** (CVPR 2026).

- Paper: https://arxiv.org/abs/2511.15258
- Code: https://github.com/yangyt46/SplitFlux

Template adapted from [CoTyle](https://kwai-kolors.github.io/CoTyle/) / [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).

## Layout

```
index.html
static/
  css/   bulma + carousel + slider + fontawesome + academicons + index.css
  js/    jquery + bulma carousel/slider + fontawesome + index/main.js
  images/  teaser.jpg, arxiv.png,
           fig1_flux_analysis.png, fig2_method.png, fig3_block_lora.png,
           fig4_disentangle_compare.png, fig5_recontext_compare.png,
           fig6_merger_compare.png, fig7_ablation_rca.png, fig8_ablation_vgra.png
```

## Preview locally

```bash
cd /Users/shuaige/code/splitflux_website
python3 -m http.server 8766
# open http://localhost:8766
```

## Deploy to GitHub Pages (recommended: dedicated org)

Same recipe as LangSplat / ReferSplat — create a free GitHub org named `SplitFlux` (or similar) and a repo named `splitflux.github.io` inside it:

```bash
git init
git add .
git commit -m "Initial SplitFlux project page"
git branch -M main
git remote add origin git@github.com:SplitFlux/splitflux.github.io.git
git push -u origin main
```

Site will be live at `https://splitflux.github.io/` within ~2 minutes.

Alternatively, push to a `gh-pages` branch of `yangyt46/SplitFlux` to get
`https://yangyt46.github.io/SplitFlux/`.
