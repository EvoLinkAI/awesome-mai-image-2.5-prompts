<div align="center">

<img src="images/logo.svg" alt="Awesome MAI-Image-2.5 Prompts logo" width="640">

# Awesome MAI-Image-2.5 Prompts

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai)
[![Website](https://img.shields.io/badge/Website-Live-orange)](https://evolink.ai)
[![Docs](https://img.shields.io/badge/Docs-Read-blue)](https://evolink.ai)
[![Model](https://img.shields.io/badge/Model-MAI--Image--2.5-purple)](https://evolink.ai)

[![🇺🇸 English](https://img.shields.io/badge/🇺🇸_English-Default_Source-111111)](README.md)
[![🇪🇸 Español](https://img.shields.io/badge/🇪🇸_Español-Ver-ffb703)](README_es.md)
[![🇵🇹 Português](https://img.shields.io/badge/🇵🇹_Português-Ver-2a9d8f)](README_pt.md)
[![🇯🇵 日本語](https://img.shields.io/badge/🇯🇵_日本語-表示-52b788)](README_ja.md)
[![🇰🇷 한국어](https://img.shields.io/badge/🇰🇷_한국어-보기-4ea8de)](README_ko.md)
[![🇩🇪 Deutsch](https://img.shields.io/badge/🇩🇪_Deutsch-Ansehen-f4a261)](README_de.md)
[![🇫🇷 Français](https://img.shields.io/badge/🇫🇷_Français-Voir-e76f51)](README_fr.md)
[![🇹🇷 Türkçe](https://img.shields.io/badge/🇹🇷_Türkçe-Görüntüle-d62828)](README_tr.md)
[![🇹🇼 繁體中文](https://img.shields.io/badge/🇹🇼_繁體中文-查看-8338ec)](README_zh-TW.md)
[![🇨🇳 简体中文](https://img.shields.io/badge/🇨🇳_简体中文-查看-ef476f)](README_zh-CN.md)
[![🇷🇺 Русский](https://img.shields.io/badge/🇷🇺_Русский-Смотреть-577590)](README_ru.md)

</div>

<div align="center">

<a href="https://x.com/arena/status/2061887242579382660"><img src="images/leaderboard/output.jpg" width="560" alt="Image Edit Arena leaderboard: MAI-Image-2.5 ranks #2 with a score of 1401"></a>

***MAI-Image-2.5 ranks #2 on the Image Edit Arena (score 1401) — ahead of every Nano Banana variant.*** (leaderboard by [@arena](https://x.com/arena))

</div>

## 🍌 Introduction

Welcome to the MAI-Image-2.5 prompt repository! 🤗

**We collect high-quality prompts and image examples for Microsoft's MAI-Image-2.5 and MAI-Image-2.5-Flash across portraits, illustration, posters, and image editing.**

MAI-Image-2.5 is Microsoft's first fully in-house image model, announced at Microsoft Build 2026 — trained from scratch with no distillation, ranking #2 on the Image Edit Arena and #3 on text-to-image. It is built for photorealistic lighting, precise identity- and text-preserving edits, and high quality per dollar.

Most cases in this repository are curated from X/Twitter, creator communities, and public demos. Original authors are credited on every case.

Try it on Evolink: [MAI-Image-2.5](https://evolink.ai)

If you find this useful, consider giving it a star. ⭐

> [!NOTE]
> This repository focuses on reusable prompt patterns and reference cases. Prompts marked as **reconstructed** are faithful rebuilds of a showcased result whose author did not publish the exact text — they are clearly flagged so you never mistake them for verbatim author wording.

<a href='https://evolink.ai'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>

## 📰 News

- **June 4, 2026:** First repository release — 13 curated MAI-Image-2.5 cases across Portrait, Poster, and Comparison categories.

## 📑 Menu

- [🍌 Introduction](#-introduction)
- [📰 News](#-news)
- [📑 Menu](#-menu)
- [📸 Portrait & Photography Cases](#-portrait--photography-cases)
  - [Case 1: Editorial Fashion Portrait, Golden Hour (by @atomtanstudio)](#case-1-editorial-fashion-portrait-golden-hour-by-atomtanstudio)
  - [Case 2: Fashion Sense Battle, Character Consistency (by @grmchn4ai)](#case-2-fashion-sense-battle-character-consistency-by-grmchn4ai)
  - [Case 3: 90s OVA Retro-Cel Anime Style (by @doerstokyo342)](#case-3-90s-ova-retro-cel-anime-style-by-doerstokyo342)
  - [Case 4: Photorealistic Iceberg & Breaching Whale (by @annjose)](#case-4-photorealistic-iceberg--breaching-whale-by-annjose)
  - [Case 5: Amateur iPhone Mirror Selfie (by @SqueakAlGaib)](#case-5-amateur-iphone-mirror-selfie-by-squeakalgaib)
- [🎨 Poster & Illustration Cases](#-poster--illustration-cases)
  - [Case 1: Sumi-e Ink Wash Illustration (by @mk0600937254693)](#case-1-sumi-e-ink-wash-illustration-by-mk0600937254693)
  - [Case 2: Anime Character Illustration (by @WaifuGacha)](#case-2-anime-character-illustration-by-waifugacha)
  - [Case 3: Pose Edit with Art-Style Preservation (by @genel_ai)](#case-3-pose-edit-with-art-style-preservation-by-genelai)
  - [Case 4: Romantic Sublime Cliff Scene (by @RockGrokAI)](#case-4-romantic-sublime-cliff-scene-by-rockgrokai)
- [🆚 Comparison & Community Examples](#-comparison--community-examples)
  - [Case 1: Object Removal Edit, Text & Car (by @WolfRiccardo)](#case-1-object-removal-edit-text--car-by-wolfriccardo)
  - [Case 2: MAI-Image-2.5 vs Nano Banana Pro (by @eyupyusufa)](#case-2-mai-image-25-vs-nano-banana-pro-by-eyupyusufa)
  - [Case 3: Text-to-Image vs Nano Banana 2 (by @mrc_748)](#case-3-text-to-image-vs-nano-banana-2-by-mrc_748)
  - [Case 4: Flash vs Standard (by @400_yen)](#case-4-flash-vs-standard-by-400_yen)
- [🙏 Acknowledge](#-acknowledge)

## 📸 Portrait & Photography Cases

### Case 1: [Editorial Fashion Portrait, Golden Hour](https://x.com/atomtanstudio/status/2061905270025150679) (by [@atomtanstudio](https://x.com/atomtanstudio))

| Output (left: MAI-Image-2.5, right: Nano Banana Pro) |
| :----: |
| <img src="images/portrait_case1/output.jpg" width="600" alt="Editorial fashion portrait generated by MAI-Image-2.5 compared with Nano Banana Pro"> |

**Prompt:**

```
{
  "meta": {
    "active_style_trigger": "Editorial Fashion Mode",
    "intent": "Forensic Replication v3.3.1 (Full Scan)",
    "priorities": ["Anatomical Magnitude Locking", "High-Contrast Backlighting", "Material Iridescence"]
  },
  "frame": {
    "aspect_ratio": "4:5",
    "composition": "Low-angle medium shot, upward-tilt perspective",
    "layout": "Subject centered, dominant verticality, lens flare bisecting the midground"
  },
  "subject": {
    "core_identity": {
      "demographics": "Caucasian female",
      "biological_age_estimate": "22-25",
      "body_composition": "Ectomorph (slender neck, narrow ribcage, lean limbs)"
    },
    "face_forensics": {
      "hair_complex": {
        "fiber_texture": "Straight to wavy, fine-strand high-fidelity fibers",
        "color_variation": "Deep espresso roots transitioning to amber-translucent edges under intense light"
      },
      "facial_topography": {
        "eyes_orbital": "Dark brown irises, almond-shaped, subtle cat-eye makeup",
        "mouth_and_lips": "Full, plush lips; soft matte-pink finish with defined cupid's bow",
        "skin_physics": "Luminous, structural-first lighting; minimal texture; editorial glow"
      }
    },
    "pose_mechanics": {
      "geometric_lock": "Slight shoulder rotation, chin elevated, gaze directed downward toward the lens",
      "expression": "Relaxed, parted lips"
    }
  },
  "wardrobe": {
    "items": [
      { "item": "Iridescent sequined/holographic crop top", "details": "Metallic mesh, thin straps, prismatic shifts (pink, gold, cyan)" }
    ]
  },
  "environment": { "location": "Outdoor urban/carnival setting", "context": "Golden hour, high-contrast backlighting" },
  "lighting": { "setup": "Natural backlighting (Golden Hour Sun)", "direction": "180-degree rear-angle", "quality": "Hard rim light with soft wrap-around fill via flare diffusion" },
  "camera": { "lens": "35mm wide-angle equivalent", "aperture": "f/1.8", "focus_plane": "Subject's facial features (eyes/lips)" },
  "style": { "aesthetic": "High-fashion editorial, cinematic sun-drenched photography", "color_grading": "Warm amber tones", "film_stock": "Modern digital sensor with intentional anamorphic-style flaring" }
}
```

> [!NOTE]
> The author's verbatim structured JSON prompt (lightly trimmed for length — full version in [`cases/portrait.md`](cases/portrait.md)). MAI-Image-2.5 accepts plain natural-language prompts too; the JSON form locks many attributes at once.

---

### Case 2: [Fashion Sense Battle, Character Consistency](https://x.com/grmchn4ai/status/2061924642571559406) (by [@grmchn4ai](https://x.com/grmchn4ai))

| Output |
| :----: |
| <img src="images/portrait_case2/output.jpg" width="600" alt="Grid of fashion looks keeping the same character identity, generated by MAI-Image-2.5"> |

**Prompt:**

```
A 5x3 grid lookbook of the SAME young woman styled in fifteen different complete outfits — streetwear, formal evening, casual denim, athleisure, vintage, avant-garde, business, bohemian, etc. Keep her face, hairstyle and body identity perfectly consistent across every cell. Full-body fashion photography, neutral studio backdrop, soft even lighting, sharp focus, magazine styling. Each look distinct in color palette, silhouette and accessories while the person stays recognizably the same.
```

> [!NOTE]
> **Reconstructed prompt.** The original tweet ran a third-party "fashion sense" comparison prompt and did not publish its exact text; this is a faithful reconstruction of the task.

---

### Case 3: [90s OVA Retro-Cel Anime Style](https://x.com/doerstokyo342/status/2062060899935100935) (by [@doerstokyo342](https://x.com/doerstokyo342))

| Output |
| :----: |
| <img src="images/portrait_case3/output.jpg" width="600" alt="Character rendered in 1990s OVA retro cel-shaded anime style by MAI-Image-2.5"> |

**Prompt:**

```
A character portrait in authentic late-1990s OVA anime style: hand-painted cel-shading, slightly grainy film texture, muted retro color palette, visible cel-paint banding, soft analog glow. Detailed but not hyper-clean — the imperfect, nostalgic look of vintage Japanese animation cels rather than modern high-resolution rendering. Dramatic anime lighting, expressive eyes, period-accurate character design.
```

> [!NOTE]
> **Reconstructed prompt** based on the author's description of testing "90s OVA retro-cel" styles. Adjust the decade/studio reference to shift the era.

---

### Case 4: [Photorealistic Iceberg & Breaching Whale](https://x.com/annjose/status/2062032759993057737) (by [@annjose](https://x.com/annjose))

| Step 1: Iceberg | Step 2: + Whale | Step 3: + Sunset |
| :-------------: | :-------------: | :--------------: |
| <img src="images/portrait_case4/output0.jpg" width="250" alt="Photorealistic iceberg in an ocean generated by MAI-Image-2.5"> | <img src="images/portrait_case4/output1.jpg" width="250" alt="Blue whale breaching near the iceberg added by MAI-Image-2.5"> | <img src="images/portrait_case4/output2.jpg" width="250" alt="Sunset on the horizon added to the iceberg and whale scene by MAI-Image-2.5"> |

**Prompt:**

```
1. create an image of an iceberg in a beautiful ocean with stunning photorealistic way
2. add a bluewhale jumping from the water near the iceberg
3. show the sun setting in the horizon
```

> [!NOTE]
> The author's verbatim prompts, applied as three sequential edits on the same image. Run them one after another to build the scene up step by step.

---

### Case 5: [Amateur iPhone Mirror Selfie](https://x.com/SqueakAlGaib/status/2062292091418628270) (by [@SqueakAlGaib](https://x.com/SqueakAlGaib))

| Output |
| :----: |
| <img src="images/portrait_case5/output.jpg" width="600" alt="Hyper-realistic amateur iPhone mirror selfie of a woman in an elevator, generated by MAI-Image-2.5"> |

**Prompt:**

```
Ultra-realistic amateur iPhone front-camera selfie inside a luxury hotel elevator. A stunning young blonde American woman in her mid-20s wearing a fashionable short designer cocktail dress stands casually inside the elevator before a night out. The image feels completely unplanned and spontaneous, not posed for social media. She is naturally beautiful with a charismatic smile, healthy skin texture, subtle makeup, and realistic imperfections. The elevator walls are mirrored on three sides, creating multiple reflections at different angles. The smartphone partially obscures part of her face. Some reflections are cropped by the edge of the frame. Bright ceiling LEDs create realistic glare streaks and reflections across the mirrors. Tiny fingerprints and smudges are visible on the mirror surface. Slight wide-angle front-camera distortion. Uneven framing. One shoulder partially cropped. Authentic smartphone HDR processing. Natural color science. No studio lighting. No influencer aesthetic. The image should feel like an accidental snapshot discovered in a camera roll. Shot on an iPhone front camera, extremely realistic optics, realistic skin pores, realistic fabric texture, subtle sensor noise, slight motion blur in one hand, genuine amateur photography, impossible to distinguish from a real smartphone photo.
```

> [!NOTE]
> The author's verbatim prompt, from a text-to-image test against Nano Banana 2, GPT-Image 2.0, and Grok Imagine. The "amateur / accidental snapshot" framing and explicit imperfections are what drive the realism.

## 🎨 Poster & Illustration Cases

### Case 1: [Sumi-e Ink Wash Illustration](https://x.com/mk0600937254693/status/2062147536606126244) (by [@mk0600937254693](https://x.com/mk0600937254693))

| Output |
| :----: |
| <img src="images/poster_case1/output.jpg" width="600" alt="Sumi-e ink wash style illustration generated by MAI-Image-2.5"> |

**Prompt:**

```
A traditional Japanese sumi-e ink-wash painting with a soft watercolor feel. Expressive black ink brushstrokes with controlled bleeding and gradient washes on textured washi paper, generous negative space, minimal restrained color accents. Calm, meditative composition in the style of classical East Asian ink art.
```

> [!NOTE]
> **Reconstructed prompt** based on the author's description (墨絵 / watercolor feel). Swap the subject to apply the ink-wash style to any motif.

---

### Case 2: [Anime Character Illustration](https://x.com/WaifuGacha/status/2062160277425283384) (by [@WaifuGacha](https://x.com/WaifuGacha))

| Output |
| :----: |
| <img src="images/poster_case2/output.jpg" width="600" alt="Anime character illustration generated by MAI-Image-2.5"> |

**Prompt:**

```
A high-quality anime illustration of an original character, clean lineart, vibrant cel-style coloring, detailed eyes and hair shading, dynamic composition, soft background bokeh. Modern Japanese illustration aesthetic with crisp linework and polished color grading.
```

> [!NOTE]
> **Reconstructed prompt.** The original post showcased output only without publishing the prompt text.

---

### Case 3: [Pose Edit with Art-Style Preservation](https://x.com/genel_ai/status/2062100730899763367) (by [@genel_ai](https://x.com/genel_ai))

| Output |
| :----: |
| <img src="images/poster_case3/output.jpg" width="600" alt="Illustration edited to change pose while keeping the original art style, by MAI-Image-2.5"> |

**Input:** Upload one illustration to edit.

**Prompt:**

```
Change only the character's pose to [new pose] while keeping the original artwork's line style, coloring, character identity, and overall aesthetic completely unchanged. Do not redraw the face or alter the art style — preserve the source illustration's look and only restage the body position.
```

> [!NOTE]
> **Reconstructed editing prompt.** Replace `[new pose]` with the target pose. Highlights MAI-Image-2.5's strength at illustration editing that preserves the source art style.

---

### Case 4: [Romantic Sublime Cliff Scene](https://x.com/RockGrokAI/status/2062188994805281183) (by [@RockGrokAI](https://x.com/RockGrokAI))

| Output |
| :----: |
| <img src="images/poster_case4/output.jpg" width="600" alt="19th-century Romantic painting of a woman on a stormy cliff edge, generated by MAI-Image-2.5"> |

**Prompt:**

```
Set in mid 19th-century, a solitary young woman standing on stormy cliff edge, waves crashing in sublime fury below turbulent sky. 19th-century Romantic sublime, dramatic blue, stormy gray, fiery orange, lush green, overwhelming nature. Raging turbulent storm lightning, heroic low-angle tempestuous windswept pan.
```

> [!NOTE]
> The author's verbatim prompt. Naming the period ("mid 19th-century") and art movement ("Romantic sublime") strongly anchors the painterly style.

## 🆚 Comparison & Community Examples

### Case 1: [Object Removal Edit, Text & Car](https://x.com/WolfRiccardo/status/2061902205779632501) (by [@WolfRiccardo](https://x.com/WolfRiccardo))

| Input | Output |
| :---: | :----: |
| <img src="images/comparison_case1/input.jpg" width="300" alt="Original Amalfi Coast travel poster with title text and a white car"> | <img src="images/comparison_case1/output.jpg" width="300" alt="Same poster with the title text and car removed by MAI-Image-2.5"> |

**Input:** Upload one photo to edit.

**Prompt:**

```
texts and car / remove
```

> [!NOTE]
> The author's verbatim prompt. MAI-Image-2.5 (High) handles terse removal instructions — name the elements to delete and it cleans the scene while preserving the background.

---

### Case 2: [MAI-Image-2.5 vs Nano Banana Pro](https://x.com/eyupyusufa/status/2061934129046843543) (by [@eyupyusufa](https://x.com/eyupyusufa))

| MAI-Image-2.5 | Nano Banana Pro |
| :-----------: | :-------------: |
| <img src="images/comparison_case2/output0.jpg" width="300" alt="MAI-Image-2.5 rendering a Turkish classroom scene with chalkboard text"> | <img src="images/comparison_case2/output1.jpg" width="300" alt="Nano Banana Pro rendering the same Turkish classroom scene with chalkboard text"> |

> [!NOTE]
> Community comparison example — same prompt run on both models, published without a reusable prompt. A text-rendering test (the Atatürk quote "Hayatta en hakiki mürşit ilimdir.") shown for reference on how MAI-Image-2.5 stacks up against Nano Banana Pro.

---

### Case 3: [Text-to-Image vs Nano Banana 2](https://x.com/mrc_748/status/2061992269750862314) (by [@mrc_748](https://x.com/mrc_748))

| MAI-Image-2.5 | Nano Banana 2 |
| :-----------: | :-----------: |
| <img src="images/comparison_case3/output0.jpg" width="300" alt="MAI-Image-2.5 photorealistic office selfie"> | <img src="images/comparison_case3/output1.jpg" width="300" alt="Nano Banana 2 rendering of the same office selfie prompt"> |

> [!NOTE]
> Community comparison example — same prompt on both models, published without a reusable prompt. The author ran a dozen text-to-image comparisons and reported MAI-Image-2.5 coming out on top each time.

---

### Case 4: [Flash vs Standard](https://x.com/400_yen/status/2061912907244241093) (by [@400_yen](https://x.com/400_yen))

| MAI-Image-2.5-Flash | MAI-Image-2.5 |
| :-----------------: | :-----------: |
| <img src="images/comparison_case4/output0.jpg" width="300" alt="MAI-Image-2.5-Flash photorealistic desert scorpion"> | <img src="images/comparison_case4/output1.jpg" width="300" alt="MAI-Image-2.5 standard photorealistic desert scorpion"> |

> [!NOTE]
> Community comparison example — the author compared the Flash and standard tiers on the same prompt without publishing it. Shown for reference on the quality difference between the two tiers.

## 🙏 Acknowledge

This repository was inspired by outstanding open prompt collections and community-shared examples.

Thanks to the creators and contributors who shared their MAI-Image-2.5 work publicly and made these case studies possible.

- [@atomtanstudio](https://x.com/atomtanstudio)
- [@grmchn4ai](https://x.com/grmchn4ai)
- [@doerstokyo342](https://x.com/doerstokyo342)
- [@annjose](https://x.com/annjose)
- [@SqueakAlGaib](https://x.com/SqueakAlGaib)
- [@mk0600937254693](https://x.com/mk0600937254693)
- [@WaifuGacha](https://x.com/WaifuGacha)
- [@genel_ai](https://x.com/genel_ai)
- [@RockGrokAI](https://x.com/RockGrokAI)
- [@WolfRiccardo](https://x.com/WolfRiccardo)
- [@eyupyusufa](https://x.com/eyupyusufa)
- [@mrc_748](https://x.com/mrc_748)
- [@400_yen](https://x.com/400_yen)
- [@arena](https://x.com/arena)

*We cannot guarantee that every case is attributed to the original creator. If anything needs to be corrected, please open an issue and we will update it.*

If you have more interesting MAI-Image-2.5 prompt cases to share, feel free to reach out and help us expand the Evolink prompt library.

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/awesome-mai-image-2.5-prompts&type=Date)](https://www.star-history.com/#EvoLinkAI/awesome-mai-image-2.5-prompts&Date)
