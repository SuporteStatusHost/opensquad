---
name: "TikTok Video"
platform: "tiktok"
content_type: "short-video"
description: "Short-form vertical video optimized for the For You Page, watch time, and non-follower discovery"
whenToUse: |
  Creating agents that produce TikTok videos or short-form vertical content scripted for TikTok's discovery-first feed.
constraints:
  max_duration_seconds: 600
  recommended_duration: "15-34s"
  aspect_ratio: "9:16 vertical"
  caption_max_chars: 2200
  caption_visible_chars: 150
  max_hashtags: 5
version: "1.0.0"
---

## Platform Rules

- TikTok is discovery-first: almost all reach comes from the For You Page (FYP), not from existing followers. The content itself — not the account's size — determines distribution.
- Completion rate and rewatches are the strongest ranking signals, ahead of likes. A short video watched to the end (or looped) outranks a longer video abandoned halfway.
- The hook window is shorter than any other platform: the first 0.5-1.5 seconds decide the scroll-away. There is no room for a logo, intro animation, or "hey guys."
- Native, slightly imperfect, "filmed on a phone" aesthetics consistently outperform polished, ad-like production. Overly branded content is penalized by viewer behavior (fast scroll-away), which then suppresses algorithmic reach.
- Trending sounds and formats ("templates") materially boost FYP placement — using a sound that is currently trending, applied authentically to the content, is one of the highest-leverage levers on this platform.
- On-screen text/captions are expected by default — most viewers watch with sound off, same as Reels, but TikTok also uses on-screen text as a storytelling device (not just subtitles).
- Comments are a key engagement layer: creators who reply to comments with another video ("reply with video") get an extra discovery boost.
- Posting cadence: 1-3x/day is viable for growth accounts; even 3-4x/week sustains an account if quality stays high. Consistency over a period of weeks matters more than any single viral hit.

## Content Structure

### Video Sequence

1. **Hook (0-1.5 seconds)** — Bold on-screen text or an immediate visual/verbal pattern-break. Must create instant curiosity, controversy, or recognition ("isso sou eu"). No intro, no branding, no slow build.
2. **Context (1.5-4 seconds)** — One sentence establishing what this video is about, keeping the promise from the hook alive.
3. **Delivery (4s to end)** — The core content: a tip, a story beat, a reveal, a transformation, an opinion. Cut or change the visual every 2-4 seconds to sustain attention (jump cuts, zoom punch-ins, B-roll).
4. **Payoff/CTA (last 2-3 seconds)** — Deliver on the hook's promise explicitly, then a specific ask: comment a word, follow for part 2, duet/stitch prompt, or share.

### Format Patterns

Pick the pattern that fits the content goal — do not default to talking-head for everything:

- **Talking head + text overlay** — direct-to-camera opinion or tip, with key phrases punched in as on-screen text.
- **Voiceover + B-roll** — narration over supporting footage; good for storytelling or explainer content.
- **Text-on-screen only (no voice)** — fast-paced story told entirely through on-screen text beats, often with trending audio underneath; works well for relatable/humor content.
- **Green-screen / reaction** — reacting to or explaining a screenshot, article, or stat shown behind the creator.
- **Duet/Stitch bait** — intentionally leaves an open question or incomplete take designed for other creators to duet/stitch, extending reach beyond the original post.

## Writing Guidelines

- Write the hook as text first, then decide the visual — the on-screen hook line must work even muted and paused on frame one.
- Script spoken lines at a brisk, natural pace (150-170 wpm) — TikTok audiences tolerate faster delivery than Reels or YouTube.
- Keep videos in the 15-34 second range for the best completion-rate-to-reach ratio, unless the content format genuinely needs longer (e.g., a multi-step tutorial) — longer is acceptable only when every second earns its place.
- Burn in on-screen text for every spoken line — treat captions as mandatory, not optional.
- Name the trending sound or format being used, and note why it fits the content (never bolt on a trending sound with no thematic connection).
- End with one specific, single ask — not a stacked list of CTAs ("like, comment, share, follow" all at once dilutes all of them).

## Output Format

```
=== VIDEO SCRIPT ===

FORMAT: [Talking head / Voiceover + B-roll / Text-on-screen only / Green-screen reaction / Duet bait]

HOOK (0-1.5s):
[Visual]: [First frame — what's on screen]
[Text Overlay]: [On-screen hook text — max 8 words]
[Audio]: [Spoken line or trending sound cue]

CONTEXT (1.5-4s):
[Script]: [One sentence setting up the content]

DELIVERY (4s-end):
[Visual]: [Shot-by-shot, cuts every 2-4 seconds]
[Script]: [Full spoken script, if any]
[Text Overlays]: [Key on-screen text beats]

PAYOFF/CTA (last 2-3s):
[Script]: [Delivers on the hook's promise]
[Text Overlay]: [Single CTA, on screen]

=== CAPTION ===
[Hook/context line — front-load value, max ~150 visible characters]

[Optional short expansion]

=== HASHTAGS ===
#hashtag1 #hashtag2 #hashtag3
[3-5 hashtags: mix of niche + broad/trending, never more than 5]

=== SOUND/TREND NOTE ===
[Trending sound or format being used, and why it fits the content]
```

## Quality Criteria

- [ ] Hook lands within the first 1.5 seconds with zero slow build-up
- [ ] On-screen text is present for every spoken line (sound-off viewing)
- [ ] Visual changes (cut, zoom, angle) occur at least every 2-4 seconds
- [ ] Video length matches the 15-34s sweet spot unless the format genuinely justifies longer
- [ ] Exactly one clear CTA at the end, not a stacked list of asks
- [ ] Trending sound/format use is named and thematically justified, not forced
- [ ] Caption front-loads the value within the visible character count
- [ ] Hashtags are 3-5, mixing niche and broader/trending tags
- [ ] Content delivers on the hook's exact promise — no bait-and-switch

## Anti-Patterns

- **Slow intros or branding before the hook** — any delay before the pattern-break causes an immediate scroll-away; TikTok has zero tolerance for windup.
- **Over-produced, ad-like polish** — content that visibly reads as "a brand's ad" gets scrolled past faster, which then suppresses FYP distribution.
- **No on-screen text** — most viewing happens muted; skipping burned-in text loses the majority of potential watch time.
- **Forced or irrelevant trending sound** — using a trending sound with no real connection to the content reads as inauthentic and does not deliver the discovery boost.
- **Stacking multiple CTAs** — asking for likes, comments, shares, and follows all at once dilutes each individual ask; pick one.
- **Reposting Reels/YouTube Shorts with visible watermarks** — TikTok's algorithm actively suppresses videos carrying another platform's watermark.
- **Ignoring comments** — not replying (ideally with a follow-up video) loses a key secondary discovery mechanism unique to TikTok.
