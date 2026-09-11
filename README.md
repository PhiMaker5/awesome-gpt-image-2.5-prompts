<h1 align="center">🎨 Awesome GPT Image 2.5 Prompts</h1>

<p align="center">
  <strong>Verbatim, source-linked prompts for GPT Image 2.5</strong>,<br>
  OpenAI's newest image model (<code>gpt-image-2.5-flare</code> / <code>gpt-image-2.5-sunburst</code>, shipped with ChatGPT Images 2.5 on Sep 8, 2026).<br>
  Every prompt is copied word-for-word from its named source, with the original render attached.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/prompts-57-blueviolet?style=flat-square" alt="Prompts">
  <img src="https://img.shields.io/badge/official_examples-18-orange?style=flat-square" alt="Official">
  <img src="https://img.shields.io/badge/updated-daily-blue?style=flat-square" alt="Updated daily">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
</p>

---

<a id="what-is-this"></a>

## 🤔 What is this?

GPT Image 2.5 launched on September 8, 2026 ([announcement](https://openai.com/index/introducing-chatgpt-images-2-5/)). It renders sharper detail, edits a scoped region without touching the rest of the image, keeps subjects consistent across turns, and cuts latency roughly in half. The API ships two models: `gpt-image-2.5-flare` (fast, default) and `gpt-image-2.5-sunburst` (precision edits).

Every prompt here is copied word-for-word from a named source — OpenAI's official guide, a real post on X, or a published hands-on write-up — and every result image is the actual render from that source, hot-linked. Nothing is paraphrased, regenerated, or "reverse-engineered." The collection is refreshed daily by an automated pipeline; where each day's batch comes from is documented under [Sources](#sources).

<a id="how-to-use"></a>

## 🧭 How to use

1. Copy a prompt below exactly as written. The wording is part of the demo, so small edits can change the result.
2. Run it in ChatGPT, or call the API with `gpt-image-2.5-flare` (fast, default) or `gpt-image-2.5-sunburst` (precision edits).
3. Entries tagged *needs input image* are edit prompts: attach your reference photo first, then send the prompt. Everything else is plain text-to-image.
4. Pairs marked (1/2) and (2/2) are one multi-turn demo, like #14 and #15: send the first prompt, then keep the same conversation going so the character stays consistent.
5. ChatGPT Images 2.5 also ships Templates (poster and merch starters), @Sketch (draw to guide a generation), and shareable prompt links.

## 📖 Table of Contents

- [🤔 What is this?](#what-is-this)
- [🧭 How to use](#how-to-use)
- [🏛️ Official Examples (18)](#official-examples)
- [🐦 First Wave from X (38)](#first-wave-from-x)
- [🔬 Hands-On Write-ups (1)](#hands-on-write-ups)
- [📡 Sources](#sources)
- [🤝 Contributing](#contributing)
- [🔗 More GPT Image 2.5 Resources](#more-resources)
- [⚖️ License & Attribution](#license)

<a id="official-examples"></a>

## 🏛️ Official Examples

Verbatim example prompts from OpenAI's own [image prompting guide](https://developers.openai.com/api/docs/guides/image-prompting). Each one demonstrates a technique: style control, exact text rendering, layout, scoped editing, or multi-turn consistency. Shown renders are OpenAI's own, hot-linked from the same page; for edit prompts the input image is shown first.

#### 1. Photorealistic Sailor on a Fishing Boat

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/photorealism-gpt-image-2-5-flare.webp" alt="Photorealistic Sailor on a Fishing Boat — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/photorealism-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/infographic-coffee-machine-gpt-image-2-5-flare.webp" alt="Automatic Coffee Machine Infographic — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/infographic-coffee-machine-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/thread-ad-gpt-image-2-5-flare.webp" alt="“Thread” Streetwear Campaign Ad — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/thread-ad-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/logo-generation-1-gpt-image-2-5-flare.webp" alt="Field & Flour Bakery Logo — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/logo-generation-2-gpt-image-2-5-flare.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/world-knowledge-gpt-image-2-5-flare.webp" alt="Bethel, New York — August 16, 1969 — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/world-knowledge-gpt-image-2-5-sunburst.webp" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a realistic outdoor crowd scene in Bethel, New York on August 16, 1969.
Photorealistic, period-accurate clothing, staging, and environment.
```

</details>

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08

---

#### 6. Four-Panel Comic: Pet Watching You Leave

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/comic-reel-gpt-image-2-5-flare.webp" alt="Four-Panel Comic: Pet Watching You Leave — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/comic-reel-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/ui-farmers-market-gpt-image-2-5-flare.webp" alt="Farmers-Market App UI Mockup — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/ui-farmers-market-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/scientific-educational-cellular-respiration-gpt-image-2-5-flare.webp" alt="Cellular Respiration Biology Diagram — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/scientific-educational-cellular-respiration-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/market-opportunity-slide-gpt-image-2-5-flare.webp" alt="“Market Opportunity” Pitch-Deck Slide — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/market-opportunity-slide-gpt-image-2-5-sunburst.webp" width="320">

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

<img src="https://developers.openai.com/images/platform/guides/image-prompting/shampoo.webp" width="320">

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/extract-product-gpt-image-2-5-flare.webp" alt="Transparent Product Cutout — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/extract-product-gpt-image-2-5-sunburst.webp" width="320">

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

<img src="https://developers.openai.com/images/platform/guides/image-prompting/drawings.webp" width="320">

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/realistic-valley-gpt-image-2-5-flare.webp" alt="Turn a Drawing Into a Photorealistic Image — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/realistic-valley-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/scene-gpt-image-2-5-flare.webp" alt="Insert a Person Into a Bear-Attack Scene — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/scene-gpt-image-2-5-sunburst.webp" width="320">

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

<img src="https://developers.openai.com/images/platform/guides/image-prompting/shampoo.webp" width="320">

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/billboard-gpt-image-2-5-flare.webp" alt="Highway Billboard: “Fresh and Clean” — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/billboard-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/childrens-book-illustration-1-gpt-image-2-5-flare.webp" alt="Storybook Forest Hero — Establish & Continue (1/2) — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/childrens-book-illustration-1-gpt-image-2-5-sunburst.webp" width="320">

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

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ Official multi-turn example, prompt 1 of 2: establish the character.

---

#### 15. Storybook Forest Hero — Establish & Continue (2/2)

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/childrens-book-illustration-2-gpt-image-2-5-flare.webp" alt="Storybook Forest Hero — Establish & Continue (2/2) — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/childrens-book-illustration-2-gpt-image-2-5-sunburst.webp" width="320">

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

👤 **[OpenAI](https://openai.com)** · [Source](https://developers.openai.com/api/docs/guides/image-prompting) · 2026-09-08 · ℹ️ Official multi-turn example, prompt 2 of 2: continue with the same character in a new scene.

---

#### 16. Swap White Chairs for Wooden Chairs

<img src="https://developers.openai.com/images/platform/guides/image-prompting/kitchen.webp" width="320">

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/kitchen-chairs-gpt-image-2-5-flare.webp" alt="Swap White Chairs for Wooden Chairs — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/kitchen-chairs-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/christmas-holiday-card-teddy-gpt-image-2-5-flare.webp" alt="Christmas Card: Old Teddy in a Keepsake Box — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/christmas-holiday-card-teddy-gpt-image-2-5-sunburst.webp" width="320">

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

<a href="https://developers.openai.com/api/docs/guides/image-prompting"><img src="https://developers.openai.com/images/platform/guides/image-prompting/christmas-collectible-toy-airplane-gpt-image-2-5-flare.webp" alt="Vintage Propeller Plane Action Figure — official render from the prompting guide" width="560"></a>

<img src="https://developers.openai.com/images/platform/guides/image-prompting/christmas-collectible-toy-airplane-gpt-image-2-5-sunburst.webp" width="320">

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

<a id="first-wave-from-x"></a>

## 🐦 First Wave from X

Real prompts posted on X during the 2.5 launch window and the days since (Sep 2026), reproduced verbatim with each author's own result images hot-linked from the original post.

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

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
my portrait in cyberpunk
```

</details>

👤 **[@GaelBreton](https://x.com/GaelBreton)** · [Source](https://x.com/GaelBreton/status/2097427507712528468) · 2026-09-08 · ℹ️ Prompt 1 of 2 from the same post. The author notes 2.5 sometimes adds text nobody asked for.

---

#### 23. Yorkie Playing With His Ball in Budapest

<a href="https://x.com/GaelBreton/status/2097427507712528468"><img src="https://pbs.twimg.com/media/HRuPMi9a0AAN9uY.jpg" alt="Yorkie Playing With His Ball in Budapest — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
A yorkie playing with his ball in Budapest
```

</details>

👤 **[@GaelBreton](https://x.com/GaelBreton)** · [Source](https://x.com/GaelBreton/status/2097427507712528468) · 2026-09-08 · ℹ️ Prompt 2 of 2 from the same post.

---

<a id="hands-on-write-ups"></a>

#### 25. Japanese Woman with Tanuki-Like Face at Night

<a href="https://x.com/AI_money_club/status/2096921585076605167"><img src="https://pbs.twimg.com/media/HRnC4P3asAEA556.jpg" alt="Japanese Woman with Tanuki-Like Face at Night — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Photorealistic natural photo of a completely fictional 20-year-old adult Japanese woman. She has an extremely cute tanuki-like face, a soft round face and cheeks, gentle round eyes, and dark brown hair. At night on a quiet
```

</details>

👤 **[@AI_money_club](https://x.com/AI_money_club)** · [Source](https://x.com/AI_money_club/status/2096921585076605167) · 2026-09-07 · ℹ️ ❤️ 987 likes at collection time.

---

#### 26. Iconic Structure Miniature Diorama

<a href="https://x.com/Naiknelofar788/status/2095336325977444847"><img src="https://pbs.twimg.com/media/HRQhRqibwAA03l5.jpg" alt="Iconic Structure Miniature Diorama — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRQhRqpbYAA1Ewm.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRQhRqjaoAAcElO.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRQhRqkaYAAs4u_.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a whimsical handcrafted miniature diorama featuring [ICONIC STRUCTURE] as the main focal point. Place the structure in a cozy, highly detailed tiny world with miniature streets, trees, flowers, lamps, benches, small shops, seasonal decorations
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095336325977444847) · 2026-09-03 · ℹ️ ❤️ 443 likes at collection time.

---

#### 27. Restore Damaged Vintage Portrait

<a href="https://x.com/abs_uiux/status/2097316540257309161"><img src="https://pbs.twimg.com/media/HRsqRO7X0AAjVfC.jpg" alt="Restore Damaged Vintage Portrait — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Use the uploaded image as the main restoration and identity reference. Convert this severely damaged old portrait into a clean, fully restored modern-looking photo
```

</details>

👤 **[@abs_uiux](https://x.com/abs_uiux)** · [Source](https://x.com/abs_uiux/status/2097316540257309161) · 2026-09-08 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 338 likes at collection time.

---

#### 28. Frieren and Fern in a Good Place

<a href="https://x.com/AItomato2101/status/2095362678827151668"><img src="https://pbs.twimg.com/media/HRQ5MOcasAABFC3.jpg" alt="Frieren and Fern in a Good Place — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
フェルン『良い場所ですねフリーレン様』 フリーレン『…そうだね』 SFW illustration
```

</details>

👤 **[@AItomato2101](https://x.com/AItomato2101)** · [Source](https://x.com/AItomato2101/status/2095362678827151668) · 2026-09-03 · ℹ️ ❤️ 320 likes at collection time.

---

#### 29. Storefront Miniature Diorama

<a href="https://x.com/Naiknelofar788/status/2095477330059903223"><img src="https://pbs.twimg.com/media/HRShhJ_bcAAdbBz.jpg" alt="Storefront Miniature Diorama — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRShhJ4aAAAxBXY.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRShhJ_a8AEiVyn.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRShhJ_aIAAXsZT.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a charming handcrafted miniature diorama featuring [STORE / BRAND NAME] as the main focal point. Reimagine the recognizable storefront as a cozy, whimsical 3D clay miniature, preserving its signature architectural style, recognizable colors
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095477330059903223) · 2026-09-03 · ℹ️ ❤️ 316 likes at collection time.

---

#### 30. Vertical Two-Panel Original and Edited Image

<a href="https://x.com/MahnoorAi12/status/2095699083512164544"><img src="https://pbs.twimg.com/media/HRVq4lAbIAAFa2Q.jpg" alt="Vertical Two-Panel Original and Edited Image — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRVq4kxa8AAyuki.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Use the uploaded reference photograph as the exact visual source. Create one single vertical 4:5 image containing two clearly separated panels stacked vertically. TOP PANEL — ORIGINAL: Keep the uploaded photograph completely unchanged
```

</details>

👤 **[@MahnoorAi12](https://x.com/MahnoorAi12)** · [Source](https://x.com/MahnoorAi12/status/2095699083512164544) · 2026-09-04 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 241 likes at collection time.

---

#### 31. Candid Portrait in Urban Park

<a href="https://x.com/Aqsahere_/status/2095351414524608662"><img src="https://pbs.twimg.com/media/HRQu_OHbAAAW-TS.jpg" alt="Candid Portrait in Urban Park — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRQu_5paAAA0822.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
A photorealistic candid outdoor portrait of a young woman standing in a peaceful urban park on a sunny afternoon. She has long dark-brown hair styled in a loose low ponytail, with wispy face-framing strands gently falling across her face.
```

</details>

👤 **[@Aqsahere_](https://x.com/Aqsahere_)** · [Source](https://x.com/Aqsahere_/status/2095351414524608662) · 2026-09-03 · ℹ️ ❤️ 237 likes at collection time.

---

#### 32. Paris Street Portrait of Young Woman

<a href="https://x.com/Zoyavelle/status/2097183799348220253"><img src="https://pbs.twimg.com/media/HRqxi6BakAAJIO8.jpg" alt="Paris Street Portrait of Young Woman — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
High-resolution, natural-light street portrait of a young Asian-looking woman on a Paris-inspired, tree-lined shopping street, captured vertically with a crisp cinematic DSLR/phone-camera aesthetic, warm sunlight, realistic skin and fabric
```

</details>

👤 **[@Zoyavelle](https://x.com/Zoyavelle)** · [Source](https://x.com/Zoyavelle/status/2097183799348220253) · 2026-09-08 · ℹ️ ❤️ 217 likes at collection time.

---

#### 33. High-Angle Portrait in Qipao

<a href="https://x.com/BubbleBrain/status/2097513469172129825"><img src="https://pbs.twimg.com/media/HRvdLStaoAAAkSy.jpg" alt="High-Angle Portrait in Qipao — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16, wearing a qipao, soft light bloom, dreamy blur, high-angle shot looking down, tall slender model figure, refined makeup, fox-like beauty face
```

</details>

👤 **[@BubbleBrain](https://x.com/BubbleBrain)** · [Source](https://x.com/BubbleBrain/status/2097513469172129825) · 2026-09-09 · ℹ️ ❤️ 208 likes at collection time.

---

#### 34. Vintage Travel Poster of Iconic Structure

<a href="https://x.com/Naiknelofar788/status/2095774387857392008"><img src="https://pbs.twimg.com/media/HRWvsMfa4AAZ0Gn.jpg" alt="Vintage Travel Poster of Iconic Structure — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRWvsMybQAE45wA.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRWvsMnbUAApK_R.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a sophisticated vintage-inspired travel poster featuring [ICONIC STRUCTURE] as the main focal point. Keep the architecture highly recognizable with accurate proportions and distinctive details, but reinterpret it as a stylized hand-painted
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095774387857392008) · 2026-09-04 · ℹ️ ❤️ 158 likes at collection time.

---

#### 35. Handcrafted Miniature Food Scene

<a href="https://x.com/Naiknelofar788/status/2095703211374219472"><img src="https://pbs.twimg.com/media/HRVu9G2bkAAu7GO.jpg" alt="Handcrafted Miniature Food Scene — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRVu9G8asAAdB-6.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRVu9HIbQAAU8Bz.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a charming handcrafted miniature food scene featuring [FOOD / DISH] as the main focal point. Arrange the food beautifully on a simple ceramic plate with tiny complementary ingredients naturally placed around it. Add a small drink, miniature wooden
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095703211374219472) · 2026-09-04 · ℹ️ ❤️ 136 likes at collection time.

---

#### 36. Smartphone Selfie Identity Preservation

<a href="https://x.com/mehvishs25/status/2096435250935091331"><img src="https://pbs.twimg.com/media/HRgItrpbQAAVizz.jpg" alt="Smartphone Selfie Identity Preservation — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRgIvduakAAxidN.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
3:4 vertical ultra-realistic smartphone selfie of the same adult woman from the reference image. Preserve her facial identity, facial structure, skin tone, hairstyle, and overall appearance so she remains unmistakably the same person.
```

</details>

👤 **[@mehvishs25](https://x.com/mehvishs25)** · [Source](https://x.com/mehvishs25/status/2096435250935091331) · 2026-09-06 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 136 likes at collection time.

---

#### 37. Minimalist Single-Line Country Art

<a href="https://x.com/Naiknelofar788/status/2095405315768627299"><img src="https://pbs.twimg.com/media/HRRgBgObAAA0rCU.jpg" alt="Minimalist Single-Line Country Art — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRRgBgYacAApThF.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRRgBgOa4AAHyUF.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRRgBgTagAAzWRg.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Use the uploaded reference as the primary inspiration. Create a 4:5 vertical minimalist collectible art print representing [COUNTRY] through one continuous elegant line. Draw a single uninterrupted hand-drawn line that begins as the recognizable silhouette
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095405315768627299) · 2026-09-03 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 117 likes at collection time.

---

#### 38. Cinematic Lifestyle Photo with Identity Preservation

<a href="https://x.com/mehvishs25/status/2095735662570082344"><img src="https://pbs.twimg.com/media/HRWMcNJbMAAN_th.jpg" alt="Cinematic Lifestyle Photo with Identity Preservation — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRWMdpiasAASaqw.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create an ultra-photorealistic cinematic lifestyle photograph using the same young East Asian woman from the reference image. Preserve her facial identity, facial structure, hairstyle, skin tone, and overall appearance so she remains unmistakably
```

</details>

👤 **[@mehvishs25](https://x.com/mehvishs25)** · [Source](https://x.com/mehvishs25/status/2095735662570082344) · 2026-09-04 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 82 likes at collection time.

---

#### 39. Photo and Illustration Split Composition

<a href="https://x.com/MahnoorAi12/status/2096479426452365692"><img src="https://pbs.twimg.com/media/HRgwv1ibIAAAXQv.jpg" alt="Photo and Illustration Split Composition — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRgwv14bgAATip7.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create one vertical 3:4 composition that combines the uploaded photo with a hand-drawn illustrated version of the same moment. TOP HALF — ORIGINAL PHOTO Keep the uploaded photograph in the upper portion of the canvas, occupying roughly 50%.
```

</details>

👤 **[@MahnoorAi12](https://x.com/MahnoorAi12)** · [Source](https://x.com/MahnoorAi12/status/2096479426452365692) · 2026-09-06 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 81 likes at collection time.

---

#### 40. Ancient Chinese Fashion Photography Grid

<a href="https://x.com/DeepBlueX0/status/2097630845435572490"><img src="https://pbs.twimg.com/media/HRxAt0jbsAAv4cd.jpg" alt="Ancient Chinese Fashion Photography Grid — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
【宋玉穿衣全过程｜宋式闺房】

专业高级古风时尚摄影；9:16竖版完整画布，内部严格3列×3行九宫格，每格等比例、尺寸一致、间距细窄整齐；每格人物均以全身或接近全身构图为主，确保完整呈现服装穿着变化。
```

</details>

👤 **[@DeepBlueX0](https://x.com/DeepBlueX0)** · [Source](https://x.com/DeepBlueX0/status/2097630845435572490) · 2026-09-09 · ℹ️ ❤️ 157 likes at collection time.

---

#### 41. Miniature Travel Scene with Landmark

<a href="https://x.com/Naiknelofar788/status/2097646788258021837"><img src="https://pbs.twimg.com/media/HRxWoHva0AADhqK.jpg" alt="Miniature Travel Scene with Landmark — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRxWoHoa0AARxkv.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRxWoHpasAAZ4Zd.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRxWoH1bUAA3U0Y.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a charming handcrafted miniature travel scene featuring [ICONIC STRUCTURE] as the main focal point. Show the landmark as a beautifully sculpted tiny 3D model, with soft rounded details, handmade textures, delicate imperfections, and a
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2097646788258021837) · 2026-09-09 · ℹ️ ❤️ 151 likes at collection time.

---

#### 42. Cinematic Rain Portrait Collage

<a href="https://x.com/abs_uiux/status/2096571268057207220"><img src="https://pbs.twimg.com/media/HRiEcEqb0AAtNJn.jpg" alt="Cinematic Rain Portrait Collage — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Use the uploaded image as the composition, framing, lighting, rainy atmosphere, facial-expression
```

</details>

👤 **[@abs_uiux](https://x.com/abs_uiux)** · [Source](https://x.com/abs_uiux/status/2096571268057207220) · 2026-09-06 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 71 likes at collection time.

---

#### 43. K-Pop Concert Stage Editorial Photography

<a href="https://x.com/AIVideoHub_/status/2095823778794369489"><img src="https://pbs.twimg.com/media/HRXcnCGa0AA7kos.jpg" alt="K-Pop Concert Stage Editorial Photography — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRXcnCGbkAAeg3Y.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16 竖版，真实演唱会现场抓拍 × K-pop 女团舞台 × 高级舞台 Editorial × 电影级真人摄影。一位 20 岁、明确成年的韩国女团成员，身高约 1.76
```

</details>

👤 **[@AIVideoHub_](https://x.com/AIVideoHub_)** · [Source](https://x.com/AIVideoHub_/status/2095823778794369489) · 2026-09-04 · ℹ️ ❤️ 391 likes at collection time.

---

#### 44. Night Rooftop Stairs Editorial Fashion Shot

<a href="https://x.com/AIVideoHub_/status/2095884267255644605"><img src="https://pbs.twimg.com/media/HRYToJNaEAAbtQs.jpg" alt="Night Rooftop Stairs Editorial Fashion Shot — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRYToJIagAIYU-w.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRYToJKbcAAIip6.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16 竖版，超写实真人摄影 × 夜晚天台楼梯时尚 Editorial × 都市夜景 × 冷调电影感。上传图片仅作为动作、身体方向与构图参考，保留腿部位置、身体重心、手部支撑方式及人物与摄影机的空间关系，不复制参考图的人物身份、服装与环境。
```

</details>

👤 **[@AIVideoHub_](https://x.com/AIVideoHub_)** · [Source](https://x.com/AIVideoHub_/status/2095884267255644605) · 2026-09-04 · ℹ️ ❤️ 266 likes at collection time.

---

#### 45. Two Women in Qipao in Chinese Garden

<a href="https://x.com/AIVideoHub_/status/2096404303959503344"><img src="https://pbs.twimg.com/media/HRfsmJpboAAd8Xj.jpg" alt="Two Women in Qipao in Chinese Garden — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRfsmJraYAE6nLb.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16 竖版，超写实真人摄影 × 新中式旗袍 Editorial × 江南园林 × 清雅奢华电影感。

两位相貌明显不同的 20–22 岁、明确成年的漂亮东亚女性并肩坐在宁静的传统中式园林池塘旁深色木制长椅上。两人身高均约 1.75
```

</details>

👤 **[@AIVideoHub_](https://x.com/AIVideoHub_)** · [Source](https://x.com/AIVideoHub_/status/2096404303959503344) · 2026-09-06 · ℹ️ ❤️ 230 likes at collection time.

---

#### 46. Close-Up Portrait of an East Asian Woman in Wuxia Style

<a href="https://x.com/AIVideoHub_/status/2095524016295666021"><img src="https://pbs.twimg.com/media/HRTL-vCbwAAmc7T.jpg" alt="Close-Up Portrait of an East Asian Woman in Wuxia Style — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRTL-u1bsAA2yH_.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16 竖版，近距离半身构图，超写实真人摄影 × 东方武侠电影 × 极端广角透视 × 冷艳高级 Editorial。一位 20–23 岁、明确成年的漂亮东亚女性，身材高挑纤细，头部偏小、脸型小巧，肩颈舒展，腰身纤细。胸部视觉约为自然 E
```

</details>

👤 **[@AIVideoHub_](https://x.com/AIVideoHub_)** · [Source](https://x.com/AIVideoHub_/status/2095524016295666021) · 2026-09-03 · ℹ️ ❤️ 224 likes at collection time.

---

#### 47. Painterly Landscape with Dramatic Cumulus Clouds

<a href="https://x.com/churvikv/status/2095472478340468762"><img src="https://pbs.twimg.com/media/HRSdBobaEAAo92C.jpg" alt="Painterly Landscape with Dramatic Cumulus Clouds — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
A painterly, highly detailed landscape scene with a luminous blue summer sky dominated by towering white cumulus clouds, rendered in a romantic fine-art campaign style. The hero is the dramatic cloud formation and its
```

</details>

👤 **[@churvikv](https://x.com/churvikv)** · [Source](https://x.com/churvikv/status/2095472478340468762) · 2026-09-03 · ℹ️ ❤️ 150 likes at collection time.

---

#### 48. Gentle Shinigami Guiding Souls

<a href="https://x.com/FufuJiangshi/status/2097090034424021024"><img src="https://pbs.twimg.com/media/HRmOmF1aMAA_D1L.jpg" alt="Gentle Shinigami Guiding Souls — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
死を迎えに来るのではなく、
迷える魂を送り届けるために――。
「迎えに来た死神」
生と死の境界に立つ少女。
冷たい夜の霧の中、
彼女が差し出す手は終わりではなく、
静かな別れへの道標。
死もまた、ひとつの優しい旅立ちなのかもしれない。
```

</details>

👤 **[@FufuJiangshi](https://x.com/FufuJiangshi)** · [Source](https://x.com/FufuJiangshi/status/2097090034424021024) · 2026-09-07 · ℹ️ ❤️ 91 likes at collection time.

---

#### 49. 1980s Portrait from Facial Reference

<a href="https://x.com/Goodmanprotocol/status/2097954772586557873"><img src="https://pbs.twimg.com/media/HR1utPuasAABAU8.jpg" alt="1980s Portrait from Facial Reference — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HR1uuHFa4AAcEvE.jpg" width="320">

<img src="https://pbs.twimg.com/media/HR1uuxpaMAAu8lw.jpg" width="320">

<img src="https://pbs.twimg.com/media/HR1uvdMbYAIpAQy.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create an authentic 1980s retro-vintage portrait in a 4:5 vertical aspect ratio, using the provided person as the exact facial reference. Preserve their identity, facial structure, recognizable features, skin tone, and natural expression with high
```

</details>

👤 **[@Goodmanprotocol](https://x.com/Goodmanprotocol)** · [Source](https://x.com/Goodmanprotocol/status/2097954772586557873) · 2026-09-10 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 177 likes at collection time.

---

#### 50. Portrait of Woman in Dark Ritual Shrine

<a href="https://x.com/nicebabycat/status/2096632565788762390"><img src="https://pbs.twimg.com/media/HRi8M73aIAAR6Dd.png" alt="Portrait of Woman in Dark Ritual Shrine — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRi8M73aEAAgY7J.png" width="320">

<img src="https://pbs.twimg.com/media/HRi8M75asAA15fF.png" width="320">

<img src="https://pbs.twimg.com/media/HRi8M75bMAAQ7dZ.png" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
9:16 photorealistic cinematic portrait of an adult East Asian woman inside a dark ancient ritual shrine, long messy black hair with wet loose strands framing her face, soft smoky eye makeup, flushed skin, glossy
```

</details>

👤 **[@nicebabycat](https://x.com/nicebabycat)** · [Source](https://x.com/nicebabycat/status/2096632565788762390) · 2026-09-06 · ℹ️ ❤️ 70 likes at collection time.

---

#### 51. Bride's Dream At The Boundary

<a href="https://x.com/FufuJiangshi/status/2096937526527422714"><img src="https://pbs.twimg.com/media/HRma2O7bkAA3iKD.jpg" alt="Bride's Dream At The Boundary — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
生と死の境界にいる少女にも、
花嫁になる夢を見る朝がある。
「幻想花嫁」
人ではない彼女が、
初めて自分自身の幸せを願った瞬間。
鏡に映るのは、
死者でも怪異でもない――
ただ一人の少女の姿。
```

</details>

👤 **[@FufuJiangshi](https://x.com/FufuJiangshi)** · [Source](https://x.com/FufuJiangshi/status/2096937526527422714) · 2026-09-07 · ℹ️ ❤️ 69 likes at collection time.

---

#### 52. Stop Motion Claymation Charmander Hatching

<a href="https://x.com/cheerselflin/status/2097903279506125119"><img src="https://pbs.twimg.com/media/HR0_qR9XAAgQWW9.jpg" alt="Stop Motion Claymation Charmander Hatching — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
我要做stop motion animation
粘土风格
小火龙从蛋里面孵化成功，破壳而出，然后喷火。 规划好，输出36张图，然后合并在一起输出3s gif。
```

</details>

👤 **[@cheerselflin](https://x.com/cheerselflin)** · [Source](https://x.com/cheerselflin/status/2097903279506125119) · 2026-09-10 · ℹ️ ❤️ 303 likes at collection time.

---

#### 53. Photorealistic Editorial Portrait of East Asian Woman

<a href="https://x.com/VIBEQUIRKLABS/status/2097099987809456636"><img src="https://pbs.twimg.com/media/HRplK1VbkAAusrS.jpg" alt="Photorealistic Editorial Portrait of East Asian Woman — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRplK1Ua8AA0oPp.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRplK1Sa0AAi5Oj.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRplK1Pa0AAzsiL.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Photorealistic editorial portrait.

Knee-up cowboy shot, eye-level view.

A 20-year-old adult East Asian woman, small near-round oval face with full low cheeks, large level warm gray-brown round eyes, short low-bridge nose, small even rose-pink lips, luminous
```

</details>

👤 **[@VIBEQUIRKLABS](https://x.com/VIBEQUIRKLABS)** · [Source](https://x.com/VIBEQUIRKLABS/status/2097099987809456636) · 2026-09-07 · ℹ️ ❤️ 68 likes at collection time.

---

#### 54. Vertical Candid Portrait of Woman

<a href="https://x.com/boniusex/status/2095469801179369880"><img src="https://pbs.twimg.com/media/HRSaGPZbQAAQ_-v.jpg" alt="Vertical Candid Portrait of Woman — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRSaIwYaIAAruVz.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRSaVqKbMAALS2C.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRSaXGCa8AAtAHs.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Vertical 9:16 candid photograph of an adult East Asian woman in her mid twenties with very fair natural skin, a slim tall figure, long slightly messy black hair, soft oval face, clear dark eyes
```

</details>

👤 **[@boniusex](https://x.com/boniusex)** · [Source](https://x.com/boniusex/status/2095469801179369880) · 2026-09-03 · ℹ️ ❤️ 66 likes at collection time.

---

#### 55. Vintage Travel Postage Stamp Artwork

<a href="https://x.com/Naiknelofar788/status/2095856946075283552"><img src="https://pbs.twimg.com/media/HRX6xxZacAEMaHt.jpg" alt="Vintage Travel Postage Stamp Artwork — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRX6xxrawAAQ9ax.jpg" width="320">

<img src="https://pbs.twimg.com/media/HRX6xxZacAA80uh.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a sophisticated vintage travel postage-stamp artwork representing [COUNTRY]. Feature the country’s most iconic landmark as the main focal point, surrounded by 3–5 carefully chosen elements that instantly represent the country — landscape, traditional
```

</details>

👤 **[@Naiknelofar788](https://x.com/Naiknelofar788)** · [Source](https://x.com/Naiknelofar788/status/2095856946075283552) · 2026-09-04 · ℹ️ ❤️ 65 likes at collection time.

---

#### 56. Cinematic Portrait on a Subway Platform

<a href="https://x.com/weiinberg/status/2097539717973627013"><img src="https://pbs.twimg.com/media/HRv1P34a4AEJmNU.jpg" alt="Cinematic Portrait on a Subway Platform — source render from the source" width="560"></a>

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
cinematic, high-fidelity portrait of a young woman standing perfectly still on a subway platform as a train rushes behind her. She has warm brown hair with soft bangs and a few loose strands blowing in the wind created by the passing train.
```

</details>

👤 **[@weiinberg](https://x.com/weiinberg)** · [Source](https://x.com/weiinberg/status/2097539717973627013) · 2026-09-09 · ℹ️ ❤️ 76 likes at collection time.

---

#### 57. Candid Lifestyle Portrait From Reference

<a href="https://x.com/mehvishs25/status/2096850534150164490"><img src="https://pbs.twimg.com/media/HRmCbNbbIAMekL3.jpg" alt="Candid Lifestyle Portrait From Reference — source render from the source" width="560"></a>

<img src="https://pbs.twimg.com/media/HRmCcGBaUAAAWsv.jpg" width="320">

<details><summary><strong>📝 Prompt</strong> (click to expand)</summary>

```text
Create a high-quality, ultra-photorealistic candid lifestyle portrait of the same adult woman from the uploaded reference image. Use the reference as the single source of truth for her identity. Preserve her facial structure, proportions, natural
```

</details>

👤 **[@mehvishs25](https://x.com/mehvishs25)** · [Source](https://x.com/mehvishs25/status/2096850534150164490) · 2026-09-07 · ℹ️ Edit prompt — attach your own reference image first. ❤️ 63 likes at collection time.

---

## 🔬 Hands-On Write-ups

Verified prompts from day-one hands-on reviews.

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

<a id="contributing"></a>

<a id="sources"></a>

## 📡 Sources

Where each day's batch comes from. Aggregators and indexes are treated as **discovery only**: every candidate is re-verified against the original post (verbatim prompt text, live author handle, real render) before it enters this collection.

| Source | Role | Notes |
|---|---|---|
| [OpenAI — Image prompting guide](https://developers.openai.com/api/docs/guides/image-prompting) | Official examples | Quoted verbatim from the docs |
| X/Twitter search (EN / JA / ZH) | Primary source | Prompt text recovered live via the syndication API |
| [AtlasCloudAI/awesome-gpt-image-2.5-prompts](https://github.com/AtlasCloudAI/awesome-gpt-image-2.5-prompts) | Structured index | Largest 2.5 corpus with `source_link` per entry; author names can be misattributed, so the live tweet is always authoritative |
| [ZeroLu/awesome-gpt-image](https://github.com/ZeroLu/awesome-gpt-image) | Discovery index | Mixed GPT Image 2 / 2.5; only entries whose original post is 2.5-era are adopted |
| [youmind prompt collections](https://youmind.com/gpt-image-2-prompts) · [tosea.ai/prompts](https://tosea.ai/prompts) · [freegpt.im](https://freegpt.im/) | Periodic recheck | Watched for newly launched 2.5 sections with per-entry credit |
| Hands-on write-ups (Tom's Guide, Morphic, personal blogs) | Hands-on group | Only with complete verbatim prompts and a named author |

---

## 🤝 Contributing

Found a real prompt with its source post and render? Please open a PR: the full rules and the `data/prompts.json` schema are in [CONTRIBUTING.md](CONTRIBUTING.md). Links are re-verified before merge, and any original author can request removal via an issue.

<a id="more-resources"></a>

## 🔗 More GPT Image 2.5 Resources

- [OpenAI announcement](https://openai.com/index/introducing-chatgpt-images-2-5/) · [Image prompting guide](https://developers.openai.com/api/docs/guides/image-prompting) · [GPT-Image-2.5 on fal](https://fal.ai/models/openai/gpt-image-2.5/flare/text-to-image)
- [YouMind prompt collections](https://youmind.com/gpt-image-2-prompts): 17k+ X-sourced prompts (GPT Image 2 era)
- [tosea.ai evidence tracker](https://tosea.ai/blog/gpt-image-2-5-or-3-evidence-tracker): pre-launch fact trail for 2.5
- [LaplaceYoung/awesome-gpt-image-2.5](https://github.com/LaplaceYoung/awesome-gpt-image-2.5): official launch stills with clearly-labeled reconstruction prompts
- [stretchcloud/awesome-gpt-image-prompt-2.5](https://github.com/stretchcloud/awesome-gpt-image-prompt-2.5): 2,383 design-spec prompts (single vendor, not community-sourced)

<a id="license"></a>

## ⚖️ License & Attribution

- Repository structure and curation: **MIT**, see [LICENSE](LICENSE).
- Official example prompts are from OpenAI's published documentation (© OpenAI), quoted for reference.
- **Community prompts and result images remain the property of their original creators**, credited inline and linked to the source post. Included as educational curation with attribution; removed on request.

---

<p align="center">⭐ Star to catch new prompts — the collection is updated daily.</p>