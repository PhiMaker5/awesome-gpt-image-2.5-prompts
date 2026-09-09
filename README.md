<h1 align="center">🎨 Awesome GPT Image 2.5 Prompts</h1>

<p align="center">
  <strong>24 verbatim, source-linked prompts for GPT Image 2.5</strong> —<br>
  OpenAI's newest image model (<code>gpt-image-2.5-flare</code> / <code>gpt-image-2.5-sunburst</code>, shipped with ChatGPT Images 2.5 on Sep 8, 2026).<br>
  Every prompt is copied word-for-word from its named source: OpenAI's official guide or real launch-week posts on X.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/prompts-24-blueviolet?style=flat-square" alt="Prompts">
  <img src="https://img.shields.io/badge/official_examples-18-orange?style=flat-square" alt="Official">
  <img src="https://img.shields.io/badge/launch_week-Sep_2026-blue?style=flat-square" alt="Launch week">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
</p>

---

## 🤔 What is this?

GPT Image 2.5 launched **September 8, 2026** ([announcement](https://openai.com/index/introducing-chatgpt-images-2-5/)), bringing sharper detail, precise scoped editing, multi-turn consistency, 50% lower latency, plus two API models: **Flare** (fast, default) and **Sunburst** (precision edits). This repo tracks the prompts that define how the model is actually used.

Because the model is days old, this collection is deliberately **small and 100% verifiable** instead of padded:

- ✅ Every prompt is **verbatim** — no paraphrasing, no "reverse-engineered" fakes, no AI-rewritten variants.
- ✅ Every entry links to a **named source**: OpenAI's official docs, the author's X post (fetched live), or a published hands-on write-up.
- ✅ Every result image is the **real render from that source**, hot-linked — never re-generated to fake a demo.
- 🌱 The collection grows as launch-week prompts surface. See [Contributing](#-contributing) to add yours.

## 🧭 How to use

1. Copy any prompt below. Official edit prompts marked *needs input image* expect you to attach a reference photo first; the rest are plain text-to-image.
2. Run it in ChatGPT, or against `gpt-image-2.5-flare` (fast) / `gpt-image-2.5-sunburst` (precision) in the API.
3. 2.5 also ships **Templates** (poster/merch starters), **@Sketch** (draw to guide generation), and **shareable prompts** — when someone shares an image on ChatGPT with its prompt, that link is a valid source to contribute here.

## 📖 Table of Contents

- [🏛️ Official Examples (18)](#️-official-examples)
- [🐦 First Wave from X (5)](#-first-wave-from-x-5)
- [🔬 Hands-On Write-ups (1)](#-hands-on-write-ups-1)
- [🤝 Contributing](#-contributing)
- [🔗 More GPT Image 2.5 Resources](#-more-gpt-image-25-resources)
- [⚖️ License & Attribution](#️-license--attribution)

<a id="official-examples"></a>

## 🏛️ Official Examples

Verbatim example prompts from OpenAI's own [GPT Image 2.5 prompting guide](https://developers.openai.com/api/docs/guides/image-prompting). Each one demonstrates a technique — style control, exact text rendering, layout, multi-turn consistency. Prompts tagged *needs input image* are edit prompts: attach a reference photo first.

#### 1. Photorealistic Sailor on a Fishing Boat

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a photorealistic candid photograph of an elderly sailor standing on a small fishing boat.
He has weathered skin with visible wrinkles, pores, and sun texture, and a few faded traditional sailor tattoos on his arms.
He is calmly adjusting a net while his dog sits nearby on the deck. Shot like a 35mm film photograph, medium close-up at eye level, using a 50mm lens.
Soft coastal daylight, shallow depth of field, subtle film grain, natural color balance.
The image should feel honest and unposed, with real skin texture, worn materials, and everyday detail. No glamorization, no heavy retouching.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 2. Automatic Coffee Machine Infographic

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a detailed Infographic of the functioning and flow of an automatic coffee machine like a Jura.
From bean basket, to grinding, to scale, water tank, boiler, etc.
I'd like to understand technically and visually the flow.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 3. “Thread” Streetwear Campaign Ad

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Give me a cool in culture ad / fashion shot for a brand called Thread.
It's a hip young street brand. The ad shows a group of friends hanging out together with the tagline "Yours to Create."
Make it feel like a polished campaign image for a youth streetwear audience: stylish, contemporary, energetic, and tasteful.
Use clean composition, strong color direction, natural poses, and premium fashion photography cues.
Render the tagline exactly once, clearly and legibly, integrated into the ad layout.
No extra text, no watermarks, no unrelated logos.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 4. Field & Flour Bakery Logo

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create an original, non-infringing logo for a company called Field & Flour, a local bakery.
The logo should feel warm, simple, and timeless. Use clean, vector-like shapes, a strong silhouette, and balanced negative space.
Favor simplicity over detail so it reads clearly at small and large sizes. Flat design, minimal strokes, no gradients unless essential.
Fully transparent background. Deliver a single centered logo with generous padding, clean alpha edges, and no solid backdrop, scenery, checkerboard, or watermark.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 5. Bethel, New York — August 16, 1969

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a realistic outdoor crowd scene in Bethel, New York on August 16, 1969.
Photorealistic, period-accurate clothing, staging, and environment.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 6. Four-Panel Comic: Pet Watching You Leave

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a short vertical comic-style reel with 4 panels.
Panel 1: The owner leaves through the front door. The pet is framed in the window behind them, small against the glass, eyes wide, paws pressed high, the house suddenly quiet.
Panel 2: The door clicks shut. Silence breaks. The pet slowly turns toward the empty house, posture shifting, eyes sharp with possibility.
Panel 3: The house transformed. The pet sprawls across the couch like it owns the place, crumbs nearby, sunlight cutting across the room like a spotlight.
Panel 4: The door opens. The pet is seated perfectly by the entrance, alert and composed, as if nothing happened.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 7. Farmers-Market App UI Mockup

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a realistic mobile app UI mockup for a local farmers market.
Show today’s market with a simple header, a short list of vendors with small photos and categories, a small “Today’s specials” section, and basic information for location and hours.
Design it to be practical, and easy to use. White background, subtle natural accent colors, clear typography, and minimal decoration.
It should look like a real, well-designed, beautiful app for a small local market.
Place the UI mockup in an iPhone frame.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 8. Cellular Respiration Biology Diagram

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a simple biology diagram titled "Cellular Respiration at a Glance" for high school students.

Show how glucose turns into energy inside a cell. Include glycolysis, the Krebs cycle, and the electron transport chain.
Use arrows to connect the steps, and label the main molecules: glucose, pyruvate, ATP, NADH, FADH2, CO2, O2, and H2O.
Make it look like a clean classroom handout or slide, with a white background, simple icons, clear labels, and easy-to-read text.

Avoid tiny text, extra decoration, or anything that makes the diagram hard to understand.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 9. “Market Opportunity” Pitch-Deck Slide

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create one pitch-deck slide titled **"Market Opportunity"** that feels like a real Series A fundraising slide from a YC-backed startup.

Use a clean white background, modern sans-serif typography like Inter, and a crisp, minimal layout. The slide should include:

* A TAM/SAM/SOM concentric-circle diagram in muted blues and grays
* Specific, believable market sizing numbers:

  * **TAM:** $42B
  * **SAM:** $8.7B
  * **SOM:** $340M
* A clean bar chart below showing market growth from **2021 to 2026**, with a subtle upward trend
* Small footnotes: **"AGI Research, 2024"** and **"Internal analysis"**
* A company logo placeholder in the bottom-right corner

The design should look like it belongs in a deck that actually raised money: highly readable text, clear data hierarchy, polished spacing, and professional startup-style visual language.

Avoid clip art, stock photography, gradients, shadows, decorative elements, or anything that feels generic or overdesigned.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 10. Transparent Product Cutout

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Extract the product from the input image and isolate it on a fully transparent background.
Output: centered product, crisp silhouette, no halos/fringing.
Preserve product geometry and label legibility exactly.
Add only light polishing. Do not add a solid backdrop, checkerboard, scenery, or shadow.
Do not restyle the product; remove the background and preserve clean alpha transparency.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ expects a product photo as input image

---

#### 11. Turn a Drawing Into a Photorealistic Image

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Turn this drawing into a photorealistic image.
Preserve the exact layout, proportions, and perspective.
Choose realistic materials and lighting consistent with the sketch intent.
Do not add new elements or text.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ expects a sketch/drawing as input image

---

#### 12. Insert a Person Into a Bear-Attack Scene

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Generate a highly realistic action scene where this person is running away from a large, realistic brown bear attacking a campsite. The image should look like a real photograph someone could have taken, not an overly enhanced or cinematic movie-poster image.
She is centered in the image but looking away from the camera, wearing outdoorsy camping attire, with dirt on her face and tears in her clothing. She is clearly afraid but focused on escaping, running away from the bear as it destroys the campsite behind her.
The campsite is in Yosemite National Park, with believable natural details. The time of day is dusk, with natural lighting and realistic colors. Everything should feel grounded, authentic, and unstyled, as if captured in a real moment. Avoid cinematic lighting, dramatic color grading, or stylized composition.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ expects a reference photo of a person as input

---

#### 13. Highway Billboard: “Fresh and Clean”

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a realistic billboard mockup of the shampoo on a highway scene during sunset.
Billboard text (EXACT, verbatim, no extra characters):
"Fresh and clean"
Typography: bold sans-serif, high contrast, centered, clean kerning.
Ensure text appears once and is perfectly legible.
No watermarks, no logos.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 14. Storybook Forest Hero — Establish & Continue (1/2)

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a children’s book illustration introducing a main character.

Character:
A young, storybook-style hero inspired by a little forest outlaw,
wearing a simple green hooded tunic, soft brown boots, and a small belt pouch.
The character has a kind expression, gentle eyes, and a brave but warm demeanor.
Carries a small wooden bow used only for helping, never harming.

Theme:
The character protects and rescues small forest animals like squirrels, birds, and rabbits.

Style:
Children’s book illustration, hand-painted watercolor look,
soft outlines, warm earthy colors, whimsical and friendly.
Proportions suitable for picture books (slightly oversized head, expressive face).

Constraints:
- Original character (no copyrighted characters)
- No text
- No watermarks
- Plain forest background to clearly showcase the character
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ Official multi-turn example, prompt 1 of 2 — establish the character.

---

#### 15. Storybook Forest Hero — Establish & Continue (2/2)

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Continue the children’s book story using the same character.

Scene:
The same young forest hero is gently helping a frightened squirrel
out of a fallen tree after a winter storm.
The character kneels beside the squirrel, offering reassurance.

Character Consistency:
- Same green hooded tunic
- Same facial features, proportions, and color palette
- Same gentle, heroic personality

Style:
Children’s book watercolor illustration,
soft lighting, snowy forest environment,
warm and comforting mood.

Constraints:
- Do not redesign the character
- No text
- No watermarks
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ Official multi-turn example, prompt 2 of 2 — continue with the same character in a new scene.

---

#### 16. Swap White Chairs for Wooden Chairs

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
In this room photo, replace ONLY the white chairs with chairs made of wood.
Preserve camera angle, room lighting, floor shadows, and surrounding objects.
Keep all other aspects of the image unchanged.
Photorealistic contact shadows and fabric texture.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ expects a room photo as input image

---

#### 17. Christmas Card: Old Teddy in a Keepsake Box

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a Christmas holiday card illustration.

Scene:
a cozy Christmas scene with an old teddy bear sitting inside a keepsake box, slightly worn fur, soft stitching repairs, placed near a window with falling snow outside. The scene suggests the child has grown up, but the memories remain.

Mood:
Warm, nostalgic, gentle, emotional.

Style:
Premium holiday card photography, soft cinematic lighting,
realistic textures, shallow depth of field,
tasteful bokeh lights, high print-quality composition.

Constraints:
- Original artwork only
- No trademarks
- No watermarks
- No logos

Include ONLY this card text (verbatim):
"Merry Christmas — some memories never fade."
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 18. Vintage Propeller Plane Action Figure

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a collectible action figure of a vintage-style toy propeller airplane with rounded wings, a front-mounted spinning propeller, slightly worn paint edges, classic childhood proportions, designed as a nostalgic holiday collectible, in blister packaging.

Concept:
A nostalgic holiday collectible inspired by the simple toy airplanes
children used to play with during winter holidays.
Evokes warmth, imagination, and childhood wonder.

Style:
Premium toy photography, realistic plastic and painted metal textures,
studio lighting, shallow depth of field,
sharp label printing, high-end retail presentation.

Constraints:
- Original design only
- No trademarks
- No watermarks
- No logos

Include ONLY this packaging text (verbatim):
"Christmas Memories Edition"
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

<a id="first-wave-from-x-5"></a>

## 🐦 First Wave from X

Real prompts posted on X/Twitter during the 2.5 launch window (Sep 3–8, 2026), reproduced verbatim with the author's own result images hot-linked from the original post.

#### 19. Einstein Handwriting Essay

<a href="https://x.com/chetaslua/status/2095556181012128005"><img src="https://pbs.twimg.com/media/HRToxf0acAEd4I_.jpg" alt="Einstein Handwriting Essay — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRTozFXbwAAMDqF.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
a photorealistic, taken by phone photo of a handwritten essay in pencil, albert einstein handwriting, on an 8.5x11 piece of lined paper, about the history of money in world. make sure there is variance in the writing in a very einstein way. give it a slight coffee stain on the top right corner
```

</details>

👤 **[@chetaslua](https://x.com/chetaslua)** · [Source](https://x.com/chetaslua/status/2095556181012128005) · 2026-09-03 · ℹ️ Tested against the pre-launch checkpoint; left image is AI, right is a real photo for comparison.

---

#### 20. Pseudo-Code “Documentary Montage” Poster

<a href="https://x.com/Gdgtify/status/2097438835328369117"><img src="https://pbs.twimg.com/media/HRuVflbaQAAgMES.jpg" alt="Pseudo-Code “Documentary Montage” Poster — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRuWgvwasAAWpvo.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRuXf88WIAAq7Z5.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRuZWJyXsAAU4qQ.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
2x2 grid, 16:9, pick Einstein, Pele and 2 other GOATs in their fields who passed away: class Documentary_Montage_Poster: def __init__(self, subject="[FIGURE]", era="[VIBE/ERA]"): self.medium = "Vintage silver gelatin photography, sepia tones, film grain" self.layout = "Overlapping cinematic collage, physical photo prints with white borders" def generate_legacy_assets(self): # AI INFERENCE: Deduce the life and times of the subject typography = f"Massive, bold, distressed sans-serif title spelling '{subject}' at the top." hero_portrait = f"A giant, intensely detailed, fading portrait of {subject} anchoring the left side of the poster." # The Mosaic of Memories inset_photos = f"AI_INFER(5 to 7 distinct, varying-sized rectangular photographs showing key moments, vehicles, or peers from the life of {subject})." ephemera = f"AI_INFER(Scrapbook elements like handwritten letters, chalkboards, or newspaper clippings related to {subject}) wedged between the photos." return [typography, hero_portrait, inset_photos, ephemera, self.medium] # EXECUTE: Render as a cohesive, masterpiece movie poster. The inset photos must physically overlap like a scrapbook.
```

</details>

👤 **[@Gdgtify](https://x.com/Gdgtify)** · [Source](https://x.com/Gdgtify/status/2097438835328369117) · 2026-09-08 · ℹ️ Four images = GPT Images 2.5 vs 2.0 vs Nano Banana Pro vs Grok on the same prompt.

---

#### 21. Red Dragon Curled Around a Castle Tower

<a href="https://x.com/RealAstropulse/status/2097424407320809563"><img src="https://pbs.twimg.com/media/HRuL4JpWkAAVpy5.jpg" alt="Red Dragon Curled Around a Castle Tower — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRuLBm6a8AAsECc.png" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
a red dragon curled around the tower of a castle on a hill
```

</details>

👤 **[@RealAstropulse](https://x.com/RealAstropulse)** · [Source](https://x.com/RealAstropulse/status/2097424407320809563) · 2026-09-08 · ℹ️ Posted as a GPT Image 2.5 vs Retro Diffusion comparison; close-ups in the thread.

---

#### 22. Cyberpunk Portrait (stray-text quirk test)

<a href="https://x.com/GaelBreton/status/2097427507712528468"><img src="https://pbs.twimg.com/media/HRuPMimW4AAw2GK.jpg" alt="Cyberpunk Portrait (stray-text quirk test) — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRuPMi9a0AAN9uY.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
my portrait in cyberpunk
```

</details>

👤 **[@GaelBreton](https://x.com/GaelBreton)** · [Source](https://x.com/GaelBreton/status/2097427507712528468) · 2026-09-08 · ℹ️ Prompt 1 of 2 from the same post — author notes 2.5 sometimes adds text nobody asked for.

---

#### 23. Yorkie Playing With His Ball in Budapest

<a href="https://x.com/GaelBreton/status/2097427507712528468"><img src="https://pbs.twimg.com/media/HRuPMimW4AAw2GK.jpg" alt="Yorkie Playing With His Ball in Budapest — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRuPMi9a0AAN9uY.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
A yorkie playing with his ball in Budapest
```

</details>

👤 **[@GaelBreton](https://x.com/GaelBreton)** · [Source](https://x.com/GaelBreton/status/2097427507712528468) · 2026-09-08 · ℹ️ Prompt 2 of 2 from the same post.

---

<a id="hands-on-write-ups-1"></a>

## 🔬 Hands-On Write-ups

Verified prompts from detailed first-day tests by independent practitioners.

#### 24. Add a Raccoon Scientist Studying the Chart

<a href="https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/"><img src="https://static.simonwillison.net/static/2026/openai-agent-usage.webp" alt="Add a Raccoon Scientist Studying the Chart — original render from the source" width="560"></a>

<img src="https://static.simonwillison.net/static/2026/racoon-chart.webp" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
add a raccoon scientist studying the chart thoughtfully
```

</details>

👤 **[Simon Willison](https://simonwillison.net/)** · [Source](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/) · 2026-09-08 · `gpt-image-2.5-sunburst` · ℹ️ First image is the input chart, second is the 2.5 result. Run via his openai_image.py CLI with -m gpt-image-2.5-sunburst.

---

## 🤝 Contributing

Launch week is when the best prompts get written — help capture them. Requirements:

1. **Verbatim prompt text** (any language) — no paraphrasing.
2. **Named original author** + link to the source post (X preferred; Reddit, blogs, shared ChatGPT prompt links all fine).
3. **At least one real render** from that source, hot-linked from the original URL.
4. Add it to `data/prompts.json` (schema documented in [CONTRIBUTING.md](CONTRIBUTING.md)) and mirror it in `README.md`.

Links are re-verified before merge; entries are removed on the original author's request.

## 🔗 More GPT Image 2.5 Resources

- [OpenAI announcement](https://openai.com/index/introducing-chatgpt-images-2-5/) · [Image prompting guide](https://developers.openai.com/api/docs/guides/image-prompting) · [GPT-Image-2.5 on fal](https://fal.ai/models/openai/gpt-image-2.5/flare/text-to-image)
- [YouMind prompt collections](https://youmind.com/gpt-image-2-prompts) — 17k+ X-sourced prompts (GPT Image 2 era)
- [tosea.ai evidence tracker](https://tosea.ai/blog/gpt-image-2-5-or-3-evidence-tracker) — pre-launch fact trail for 2.5
- [LaplaceYoung/awesome-gpt-image-2.5](https://github.com/LaplaceYoung/awesome-gpt-image-2.5) — official launch stills with clearly-labeled reconstruction prompts
- [stretchcloud/awesome-gpt-image-prompt-2.5](https://github.com/stretchcloud/awesome-gpt-image-prompt-2.5) — 2,383 design-spec prompts (single vendor, not community-sourced)

## ⚖️ License & Attribution

- Repository structure and curation: **MIT** — see [LICENSE](LICENSE).
- Official example prompts are from OpenAI's published documentation (© OpenAI), quoted for reference.
- **Community prompts and result images remain the property of their original creators**, credited inline and linked to the source post. Included as educational curation with attribution; removed on request.

---

<p align="center">⭐ Star to catch new prompts as the launch-week wave lands.</p>