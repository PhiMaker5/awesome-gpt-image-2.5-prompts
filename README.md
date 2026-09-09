<h1 align="center">🎨 Awesome GPT Image 2.5 Prompts</h1>

<p align="center">
  <strong>24 verbatim, source-linked prompts for GPT Image 2.5</strong>,<br>
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

<a id="what-is-this"></a>

## 🤔 What is this?

GPT Image 2.5 launched on September 8, 2026 ([announcement](https://openai.com/index/introducing-chatgpt-images-2-5/)). It renders sharper detail, edits a scoped region without touching the rest of the image, keeps subjects consistent across turns, and cuts latency roughly in half. The API ships two models: `gpt-image-2.5-flare` (fast, default) and `gpt-image-2.5-sunburst` (precision edits).

The model is days old, so this list is small on purpose. Every prompt is copied word-for-word from a named source, either OpenAI's official guide or a real launch-week post on X, and every result image is the actual render from that source. Nothing is paraphrased, regenerated, or "reverse-engineered." New entries land as launch-week prompts surface.

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
- [🐦 First Wave from X (5)](#first-wave-from-x)
- [🔬 Hands-On Write-ups (1)](#hands-on-write-ups)
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

Real prompts posted on X during the launch window (Sep 3-8, 2026), reproduced verbatim with each author's own result images hot-linked from the original post.

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

## 🤝 Contributing

Launch week is when the best prompts get written. If you find a real prompt with its source post and render, please open a PR: the full rules and the `data/prompts.json` schema are in [CONTRIBUTING.md](CONTRIBUTING.md). Links are re-verified before merge, and any original author can request removal via an issue.

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

<p align="center">⭐ Star to catch new prompts as the launch-week wave lands.</p>