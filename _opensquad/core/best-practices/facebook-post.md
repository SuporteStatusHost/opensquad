---
name: "Facebook Post"
platform: "facebook"
content_type: "feed"
description: "Text, link, image, and video posts optimized for meaningful interactions and comment-driven reach"
whenToUse: |
  Creating agents that produce Facebook feed posts: text updates, image posts, link posts, or native video posts for Facebook Pages.
constraints:
  text_recommended_chars: "40-80"
  text_max_before_truncation: 477
  max_hashtags: 2
  image_ratio: "1:1 or 4:5"
  image_resolution: "1080x1080px or 1080x1350px"
  video_ratio: "4:5 or 9:16 (native upload, not shared from other platforms)"
version: "1.0.0"
---

## Platform Rules

- Facebook's algorithm (Meta "Meaningful Social Interactions") weights signals: Comments (especially long ones that spark replies) > Shares > Reactions > Likes. A post that starts a conversation in the comments outperforms a post that only gets likes.
- Short posts (40-80 characters) consistently get more reach than long paragraphs — but a longer, personal/storytelling post that genuinely earns comments can still outperform a short generic one. Length is not the goal; comment-worthiness is.
- Native video (uploaded directly to Facebook) is favored over links to YouTube, Instagram, or TikTok. The algorithm suppresses reach for posts that send users off-platform.
- Audience skews older (35+) and values community, local relevance, and direct usefulness over trend-chasing aesthetics. Tone can be warmer and more explanatory than Instagram.
- Facebook Groups posts get materially more organic reach than Page posts — if the brand has an active group, cross-posting there is high-value.
- Posting cadence: 3-5x/week is enough; Facebook does not reward high frequency the way Instagram Reels does. Quality of interaction matters more than volume.
- Best posting windows: 12-3 PM and 7-9 PM local time, weekdays. Weekend engagement tends to be lower for B2B-leaning audiences.

## Content Structure

### Post Types

1. **Text-only update** — A direct statement, question, or opinion. Works best when it invites a reply (a genuine question, a poll-style either/or, a relatable complaint).
2. **Image post** — Single photo or simple graphic with a short caption. The image carries the message; the caption adds a hook or question.
3. **Link post** — Shares an external article/page with a one-line editorial take above the link preview, explaining why it matters to this audience (never just the headline restated).
4. **Native video** — Short explainer, testimonial, or behind-the-scenes clip, uploaded directly (never a shared Reels/TikTok link).

## Writing Guidelines

- Open with the point, not a windup — Facebook readers scroll fast; the first line must stand alone as the hook.
- Ask a real question when the goal is comments — not "What do you think?" (too generic) but a specific, answerable one tied to the audience's own experience.
- Use plain, conversational language. Avoid jargon and avoid over-polished "ad copy" tone — it reads as inauthentic on this platform.
- Hashtags are mostly decorative on Facebook — use 0-2 maximum, only if directly relevant (e.g., a branded campaign tag).
- For link posts, never just paste the URL with no context — always add 1-2 sentences framing why this matters before the link.
- Emojis are acceptable and expected in moderation (1-3 per post) to break up text and add warmth — avoid rows of emojis.

## Output Format

```
=== POST TYPE ===
[Text-only / Image / Link / Native Video]

=== POST TEXT ===
[Opening hook — must work as a standalone first line]

[Supporting line(s) — context, story, or value, kept short]

[Closing question or CTA — specific, answerable, invites a comment]

=== MEDIA DIRECTION ===
[Image/video description, or "N/A" for text-only]

=== LINK PREVIEW CONTEXT === (link posts only)
[1-2 sentence editorial framing before the shared link]

=== HASHTAGS ===
[0-2 hashtags, only if directly relevant — omit section if none]
```

## Quality Criteria

- [ ] Opening line works as a standalone hook — no slow windup
- [ ] Post invites a specific, answerable comment (not a generic "thoughts?")
- [ ] Tone is conversational and warm, not polished ad-copy
- [ ] Native video is used instead of a cross-platform link, when video is the format
- [ ] Link posts include editorial framing, not just the bare URL
- [ ] Hashtags are 0-2 and genuinely relevant, not decorative spam
- [ ] Length matches the content's actual need — short when short works, longer only when the story earns it

## Anti-Patterns

- **Sharing a YouTube/TikTok/Reels link instead of native upload** — Meta suppresses reach for off-platform links; always re-upload video natively to the Page.
- **Generic engagement bait** ("Like if you agree!", "Tag a friend!") — flagged and demoted by Meta's spam detection; avoid explicit engagement-bait phrasing.
- **Hashtag stacking** — Facebook does not use hashtags for discovery the way Instagram/TikTok do; more than 2-3 looks spammy.
- **Corporate/ad tone** — Overly polished, sales-y language underperforms versus a conversational, first-person voice.
- **Posting and ghosting** — Not replying to the first wave of comments reduces the post's algorithmic momentum within its critical early window.
- **Long paragraphs with no line breaks** — Wall-of-text posts get skipped; break into short lines even when the content is substantial.
