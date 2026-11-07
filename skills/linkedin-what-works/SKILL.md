---
name: "linkedin-what-works"
description: "Decide which LinkedIn hooks, formats and carousel designs to use for Aashif's profile and the ScaleDev page, and diagnose low reach, from his own Buffer numbers first and 2026 research second."
---

# LinkedIn: what works and what doesn't

Use this when planning angles, picking a hook or format, or running the fortnightly review. Two accounts, always judged separately: Aashif's profile (@aashifbuilds) and the ScaleDev company page. Research notes with sources: /mnt/project-files/notes/linkedin-research-2026-10.md (13 Oct 2026, with 31 Oct and 7 Nov 2026 additions at the end).

## 1. His own numbers come first

Read these before proposing anything:
- /mnt/project-files/linkedin-content/hook-scoreboard.md (median impressions and engagement rate per hook type and format, per account)
- the newest file in /mnt/project-files/linkedin-content/reviews/
- /mnt/project-files/linkedin-content/metrics.md

Once a hook type or format has 3 or more posts on an account, his median beats any industry figure below. With 1 or 2 posts, call it an early signal, not a winner. Never estimate a number that Buffer or Aashif did not give.

## 2. 2026 baseline (until his data says otherwise)

Likely to work:
- Story, scene, timestamp or number openers, first line under 40 characters.
- First-person "what I did or saw", with one detail only Aashif could know.
- Images (about +31% vs text in his follower band) and carousels. The carousel lead over photos shrank from +21% to +9% in March 2026 (MagicPost, 687k posts), so a strong single image is as good as a carousel.
- Lived experience plus one concrete detail: about +15%, against about -23% for posts with neither (MagicPost, Jul 2026).
- Native vertical video under about 90 seconds. Re-cut the co-founder's best Instagram reels for LinkedIn with a rewritten caption.
- 1,300 to 2,500 characters on text posts.
- Ending on a specific, easy question from experience, or on nothing.

Likely to fail:
- Question openers (worst hook type in both large datasets).
- "Comment KEYWORD" CTAs (about -47% to -52% since late July 2026) and any other request to comment (about -19%).
- "What do you think?", "Agree?" (about -7% engagement).
- Posts that read as AI (about -24%): run linkedin-humanizer and its checker.
- Links anywhere: preview card about -19%, URL typed in the text about -21%, "link in the comments" about -16% (MagicPost, since May 2026). Polls (about -22% vs photos). More than 2 hashtags (hashtags show no measurable effect either way).
- Engagement pods: more views in the first hour, about -6% final reach.
- Text-only is the weakest format in his band, so text posts need the strongest hooks.

Hook types to tag every post with: story-scene, timestamp, number, statement, list ("3 places..."), build-log, question (avoid).

## 3. Carousels (Aashif's rules, 14 Oct 2026)

- 4 to 6 pages only. Research favoured 11+ pages; he chose 4 to 6, so measure them against his own average instead of arguing.
- Same palette and layout system, but never the same design twice in a row across both accounts.
- Designs in /mnt/project-files/brand/templates/: A carousel.html (numbered), B carousel-timeline.html, C carousel-checklist.html, D carousel-split.html, E carousel-numbers.html.
- Check /mnt/project-files/linkedin-content/carousel-log.md for the last design used, pick a different one, and add a row after it is approved.
- ScaleDev page carousels use the handle "ScaleDev" and the footer "ScaleDev · AI systems for UAE service businesses".
- Render: cd /mnt/project-files/brand && node render.mjs templates/FILE.html OUTDIR (PNG per page plus a PDF).

## 4. Cadence

- Profile: 4 posts a week, Monday to Thursday, 08:15 GST.
- ScaleDev page: 2 posts a week, Monday text and Wednesday carousel, 12:40 GST.
- Plan detail: /mnt/project-files/linkedin-content/post-plan.md.

## 5. Fortnightly review

1. Pull sent posts for the last 14 days from Buffer (list_posts with metrics) for both channels. If Buffer is unavailable, say so and stop.
2. Engagement rate = (reactions + comments + reposts) / impressions.
3. Group by hook type, pillar, format, carousel design and length band, per account.
4. Write reviews/YYYY-MM-DD.md and update hook-scoreboard.md.
5. Shift the next 2 weeks' angles in post-plan.md toward the winners and away from the losers. Keep the pillars.
6. Show Aashif the changes. Nothing is written, queued or published until he approves it.

## 6. When reach is low (7 Nov 2026)

Most profile posts have landed between 30 and 340 impressions at about 2,150 followers. Work through these before blaming hooks:
1. Judge at 72 hours. A median post has 8% of its final views at 1 hour, 23% at 4 hours and 72% at 3 days; posting hour moves final reach by 2% at most (MagicPost).
2. Audience fit. LinkedIn matches posts to readers by topic and profile signals (LinkedIn, Mar 2026). His followers are 38% Colombo and 2% Dubai, so UAE clinic posts meet an audience that doesn't care yet. Keep the approved mix (broad Monday story, student-founder Wednesday) for reach, and let the invite plan build UAE connections so ICP posts have someone to land on.
3. Lived detail. Every auto-queued post still needs one real detail from his week. If a draft has none, ask for one in the morning to-do; if none comes, use a tracked number, never an invented one.
4. His own comments. 10 thoughtful comments a day on UAE founders' and mid-size creators' posts is the biggest free lever, and the weekly counts show 0 confirmed. It goes first in his daily list.
5. Profile match. Headline, About and Featured should name the same topics the posts cover (UAE service businesses, AI receptionists, WhatsApp, CRM).
6. Format. Native vertical video every other week; images and short carousels the rest.
7. Company page. Pages reach only a small slice of their followers (about 2%, Socialinsider via ZoomSphere). Keep it at 1 post a week; growth comes from his profile.

Replying within the first hour showed no measurable effect on reach (MagicPost), so reply the same day for the relationship, not the algorithm.

## Never

- Invent clients, results, metrics or prospect details. Zeros stay zeros.
- Automate comments, likes, invites or DMs.
- Post to the IframesLK channel.
- Use em dashes or en dashes in any copy.