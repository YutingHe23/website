# Yuting He — personal homepage

This is an independent static homepage for [YutingHe23/website](https://github.com/YutingHe23/website), kept outside the paper-sync repository.

Open `index.html` directly or serve the directory with:

```bash
python3 -m http.server 8000
```

The page uses `index.html`, `style.css`, and self-hosted images in `assets/`. No build step is required. Keep the assets directory alongside the HTML when deploying.

The publication order is ScenePress, AniGen, HoloMobile, DeepFeature, Myo-Trainer, Learning Critically, and Class-Wise Adaptive Self Distillation (FedCAD). Update the publication entries in `index.html` to change their text or links.

Publication media comes from the authors' research materials: ScenePress and AniGen animations from [Yi-Hua Huang's homepage](https://yihua7.github.io/website/), author-provided HoloMobile and Myo-Trainer demos, the [DeepFeature overview figure](https://arxiv.org/html/2512.08379v3/overview.png), the [original Learning Critically figure](https://yutinghe20.github.io/YutingHe/images/papers/fedssd_framework.png), and the [original FedCAD figure](https://yutinghe20.github.io/YutingHe/images/papers/fedcad_framework.png). Animations have static alternatives for visitors who prefer reduced motion.

The desktop layout follows the reference template's column proportions, typography, and spacing. Each paper has one preview on the left, with its title and all metadata on the right; narrow screens retain this arrangement with smaller previews. The portrait is reused from [Yuting He's original homepage](https://yutinghe20.github.io/YutingHe/).

To publish with GitHub Pages, select **Settings → Pages → Deploy from a branch**, then choose **main** and **/ (root)**. The expected site URL is `https://yutinghe23.github.io/website/` after Pages is enabled.
