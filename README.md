# Awesome AI Image Prompts

Original, reusable starter prompts for AI image creation, maintained by [Raphael AI](https://raphael.app).

**Status:** initial collection of **12 original prompt templates**. These examples have **not been model-tested**; no preview gallery or cross-model compatibility is claimed. Help us improve them with reproducible, rights-cleared examples.

[English](#use-a-prompt) · [中文说明](#中文说明) · [Machine-readable collection](prompts.json) · [Contributing](https://github.com/RaphaelAI-OpenLab/.github/blob/main/CONTRIBUTING.md)

## Use a prompt

1. Pick a creative goal below and replace every bracketed variable.
2. Choose an appropriate generation or editing tool; you can start at [raphael.app](https://raphael.app).
3. Generate a small set, inspect the result, and change one variable at a time.
4. If contributing a result, record the model/version, prompt, settings, generation date, and any reference requirements. Mark unknown settings explicitly.

## Prompts

| Prompt | Category |
| --- | --- |
| [Editorial portrait](#editorial-portrait) | portrait |
| [Studio product photograph](#product-studio) | product |
| [Botanical illustration](#botanical-illustration) | illustration |
| [Cozy interior concept](#cozy-interior) | interior |
| [Cinematic landscape](#cinematic-landscape) | environment |
| [Food editorial](#food-editorial) | food |
| [Isometric workspace](#isometric-workspace) | illustration |
| [Storybook scene](#storybook-scene) | illustration |
| [Abstract background](#abstract-background) | design |
| [Original character study](#character-sheet) | character |
| [Reference background edit](#reference-background-edit) | editing |
| [Minimal poster artwork](#minimal-poster-art) | design |

<a id="editorial-portrait"></a>

### Editorial portrait

```text
An editorial portrait of an adult [SUBJECT] wearing [WARDROBE], seated beside a large window in [SETTING]. Soft side lighting, natural skin texture, relaxed expression, [COLOR PALETTE], uncluttered background, medium close-up, no text or logos.
```

**Variables:** SUBJECT, WARDROBE, SETTING, COLOR PALETTE.

**Notes:** Use a fictional adult subject or a consenting subject. Avoid unnecessary beauty or identity assumptions.

**Validation:** untested starter template.

<a id="product-studio"></a>

### Studio product photograph

```text
A studio product photograph of [PRODUCT] on a [SURFACE] pedestal against a seamless [BACKGROUND COLOR] background. Soft key light from the upper left, subtle rim light, believable contact shadow, precise material detail, generous negative space on the right for later layout. No text, invented labels, or extra objects.
```

**Variables:** PRODUCT, SURFACE, BACKGROUND COLOR.

**Notes:** If exact packaging or branding matters, use an authorized reference and verify every detail.

**Validation:** untested starter template.

<a id="botanical-illustration"></a>

### Botanical illustration

```text
A botanical illustration of [PLANT], showing one complete flowering stem and a separate close study of a leaf. Fine ink outlines with translucent watercolor, warm ivory paper, restrained [PALETTE] colors, balanced scientific-illustration composition, no labels or lettering.
```

**Variables:** PLANT, PALETTE.

**Notes:** Illustrative output is not a verified botanical reference; check anatomy independently.

**Validation:** untested starter template.

<a id="cozy-interior"></a>

### Cozy interior concept

```text
A calm [ROOM TYPE] interior with [MATERIALS], one focal piece of furniture, and [ACCENT COLOR] textiles. Diffused morning daylight from a single large window, plausible scale, clear circulation space, lived-in but tidy, eye-level interior photograph, no people or text.
```

**Variables:** ROOM TYPE, MATERIALS, ACCENT COLOR.

**Notes:** Concept visualization only; dimensions and feasibility require separate review.

**Validation:** untested starter template.

<a id="cinematic-landscape"></a>

### Cinematic landscape

```text
A wide cinematic view of [LANDSCAPE] during [TIME OF DAY]. A small [FOREGROUND ELEMENT] creates scale, layered atmospheric depth, believable directional light, [PALETTE] color grade, detailed but restrained composition, no text or watermark.
```

**Variables:** LANDSCAPE, TIME OF DAY, FOREGROUND ELEMENT, PALETTE.

**Notes:** Avoid overloading the scene; change one visual variable at a time.

**Validation:** untested starter template.

<a id="food-editorial"></a>

### Food editorial

```text
An editorial food photograph of [DISH] on simple [TABLEWARE], placed on a [TABLE SURFACE] table. Natural window light, visible ingredients, appetizing but realistic texture, one folded linen napkin, carefully controlled styling, three-quarter camera angle, no hands or text.
```

**Variables:** DISH, TABLEWARE, TABLE SURFACE.

**Notes:** Verify ingredients and presentation when the image communicates a real product.

**Validation:** untested starter template.

<a id="isometric-workspace"></a>

### Isometric workspace

```text
An isometric illustration of a compact [WORKSPACE TYPE], with [THREE KEY OBJECTS], consistent geometry, soft ambient shadows, matte surfaces, [PALETTE] colors, isolated on a plain light background, clean readable silhouettes, no labels or text.
```

**Variables:** WORKSPACE TYPE, THREE KEY OBJECTS, PALETTE.

**Notes:** Count objects and check geometry before using the result in an explanatory diagram.

**Validation:** untested starter template.

<a id="storybook-scene"></a>

### Storybook scene

```text
A warm storybook illustration of [FICTIONAL CHARACTER] discovering [OBJECT] in [SETTING]. Gentle expressive gesture, hand-painted gouache texture, clear focal point, [PALETTE] colors, simple background shapes, narrative composition, no lettering.
```

**Variables:** FICTIONAL CHARACTER, OBJECT, SETTING, PALETTE.

**Notes:** Use original characters and a descriptive visual style rather than copying a living artist.

**Validation:** untested starter template.

<a id="abstract-background"></a>

### Abstract background

```text
An abstract background made of [SHAPES OR MATERIALS] flowing diagonally across the frame. [PALETTE] colors, subtle tactile texture, soft depth, low-detail negative space in the center for a separate text overlay, no lettering, symbols, or logos.
```

**Variables:** SHAPES OR MATERIALS, PALETTE.

**Notes:** Add final copy in a layout editor and check text contrast at the intended size.

**Validation:** untested starter template.

<a id="character-sheet"></a>

### Original character study

```text
A clean character study of an original adult [CHARACTER DESCRIPTION] wearing [OUTFIT], shown in a neutral standing pose against a plain [BACKGROUND] background. Distinctive [TWO IDENTITY ANCHORS], consistent proportions, even lighting, full body and feet visible, no labels or text.
```

**Variables:** CHARACTER DESCRIPTION, OUTFIT, BACKGROUND, TWO IDENTITY ANCHORS.

**Notes:** Start with one pose; multiple views may introduce identity drift.

**Validation:** untested starter template.

<a id="reference-background-edit"></a>

### Reference background edit

```text
Edit the provided authorized product reference. Preserve the exact product shape, color, material, proportions, and visible label. Replace only the background with [NEW SETTING]. Match lighting and perspective, keep realistic contact shadows, add no extra products or text.
```

**Variables:** NEW SETTING.

**Notes:** Requires an editing model and a reference image you have rights to use. Check that labels and geometry remain unchanged.

**Validation:** untested starter template.

<a id="minimal-poster-art"></a>

### Minimal poster artwork

```text
A minimal poster artwork featuring [MAIN MOTIF] as one bold visual form. [PALETTE] colors, refined paper grain, strong silhouette, asymmetrical balance, generous empty area in the upper third for typography added later. Artwork only, no letters or logos.
```

**Variables:** MAIN MOTIF, PALETTE.

**Notes:** This creates background artwork; set and proofread typography separately.

**Validation:** untested starter template.

## Contribute a tested example

Open a [resource submission](https://github.com/RaphaelAI-OpenLab/awesome-ai-image-prompts/issues/new/choose) or PR. Use [docs/SUBMISSION_FORMAT.md](docs/SUBMISSION_FORMAT.md). Include source and license information for every reference and preview. Keep unsuccessful results and limitations honest; do not report invented test counts.

## 中文说明

这是 Raphael AI OpenLab 的首批原创图像提示词模板。请将方括号内的变量替换成自己的创作内容，再根据具体模型逐步调整。当前 12 条模板均标记为**未实测**，没有附带生成结果，也不承诺适用于所有模型。

欢迎贡献带有模型版本、参数、效果预览及明确授权信息的可复现案例。需要参考图的编辑模板，请只上传自己有权使用的图片。

## License

Original prompt text and repository documentation: [MIT](LICENSE). Model services, third-party references, and generated outputs have separate terms; this license does not grant rights to those assets.
