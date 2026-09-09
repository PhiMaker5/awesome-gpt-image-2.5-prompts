# Contributing to Awesome GPT Image 2.5 Prompts

Thanks for helping grow this collection! The goal is a library of prompts that
is **verifiable**: every entry can be traced back to the person who wrote it and
the post it came from.

## Submission requirements

A pull request is accepted only if the entry includes **all** of the following:

1. **Full prompt text** — copied verbatim from the source. Any language is fine
   (English, Japanese, Chinese, …); do not translate or "clean up" the original.
2. **Original author's handle** and a **working link to the source post**
   (X/Twitter preferred; Reddit, Xiaohongshu, etc. also accepted).
3. **At least one real render** from that post, hot-linked from the original
   image URL. Do not re-generate a lookalike image and present it as the
   author's example.
4. **Category + short English title** — see the categories in `README.md`.

## How to add an entry

1. Append a new object to `data/prompts.json` following the existing schema:

   ```json
   {
     "id": 64,
     "title": "Short English Title",
     "category": "portrait",
     "language": "en",
     "prompt": "Full verbatim prompt text…",
     "author": "handle",
     "author_url": "https://x.com/handle",
     "source_url": "https://x.com/handle/status/…",
     "tester": null,
     "tester_url": null,
     "images": ["https://pbs.twimg.com/media/….jpg"],
     "source_verified": true
   }
   ```

2. Mirror the entry in `README.md` under the matching category, keeping the
   existing entry format (linked preview image, collapsible prompt, credit line,
   `---` separator) and the running entry number.
3. Confirm the source link resolves and the image URL returns HTTP 200.

## Ground rules

- **No unattributed content.** If you can't find who originally wrote a prompt,
  don't submit it.
- **No NSFW, deceptive, or impersonation-ready content** (e.g. real people in
  fabricated situations).
- **Respect takedowns.** Any original author may ask for removal via issue —
  we action these quickly, no questions asked.
- One entry per pull request keeps review fast, but small batches are fine.

## Review process

A maintainer checks that the tweet/post exists, the handle matches, the images
load, and the prompt text matches the source. Entries failing verification are
closed with a reason.
