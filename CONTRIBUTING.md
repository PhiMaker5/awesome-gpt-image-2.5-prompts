# Contributing to Awesome GPT Image 2.5 Prompts

Thanks for helping capture the GPT Image 2.5 prompt corpus! This repo only
accepts entries that can be **traced back to a named source** — that is what
makes it useful as the model's prompt library grows.

## What we accept

| Group | Source type | Example |
|---|---|---|
| `official` | OpenAI docs / official accounts | The [image prompting guide](https://developers.openai.com/api/docs/guides/image-prompting) examples |
| `x` | X/Twitter posts (launch window onward) | A creator posting a prompt + their real render |
| `hands-on` | Published first-party write-ups | Blog posts with exact prompts and results |

## Submission requirements

A pull request is accepted only if the entry includes **all** of the following:

1. **Full prompt text**, copied verbatim from the source. Any language is fine
   (English, Japanese, Chinese, …); never translate or "clean up" the original.
2. **Named original author** and a **working link to the source post** —
   an X/Twitter status is ideal; Reddit posts, blogs, and shared ChatGPT
   prompt links also work. No anonymous screenshots.
3. **At least one real render** from that source, hot-linked from the original
   image URL (e.g. `pbs.twimg.com/media/...`). Do **not** re-generate a
   lookalike and present it as the source's example. If the post contains
   several prompts, include only the render(s) your entry's prompt actually
   produced, one entry per prompt.
4. **Title (short English), group, and category** — see `data/prompts.json`.

## How to add an entry

Append a new object to `data/prompts.json` following this schema:

```json
{
  "id": 25,
  "title": "Short English Title",
  "group": "x",
  "category": "Free-form short tag, e.g. Quirk tests",
  "language": "en",
  "prompt": "Full verbatim prompt text…",
  "author": "@handle or OpenAI or Author Name",
  "author_url": "https://x.com/handle",
  "source_url": "https://x.com/handle/status/…",
  "source_type": "x-post",
  "published_at": "2026-09-09",
  "images": ["https://pbs.twimg.com/media/….jpg"],
  "model_note": null,
  "notes": "optional context (input image needed, comparison set, …)",
  "source_verified": true
}
```

Then mirror the entry in `README.md` under the matching group, keeping the
existing entry format (linked preview image, collapsible prompt, credit line,
`---` separator) and the running entry number.

## Ground rules

- **No unattributed content.** If you can't find who originally wrote a prompt,
  don't submit it.
- **No reverse-engineered or "reconstructed" prompts** presented as community
  prompts.
- **No NSFW, deceptive, or impersonation-ready content** (e.g. real people in
  fabricated situations).
- **Respect takedowns.** Any original author may request removal via an issue —
  actioned quickly, no questions asked.

## Review

Maintainers review every pull request. Submissions missing any requirement
above are closed with a reason.
