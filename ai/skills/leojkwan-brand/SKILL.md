---
name: leojkwan-brand
description: Apply Leo Kwan's stable public voice, visual identity, channel distinctions, and surface-specific authorship rules to leojkwan.com and public-channel work. Excludes private biography and mutable campaign or editing preferences.
---

# leojkwan-brand

Project Leo's public identity without turning a current preference, old post,
or one successful artifact into permanent doctrine. Current repository
authority wins when it changes a public rule.

## Public character

The center is a whole life, not a product portfolio or polished corporate
biography: work, life, travel, experiments, mistakes, and the trail between
them. Prefer concrete scenes, dates, objects, places, decisions, and changes
over generic lessons.

Write directly and conversationally. Be specific, technically clear when the
subject calls for it, and candid about failure or uncertainty. Avoid corporate
throat-clearing, inflated claims, synthetic inspiration, engagement bait,
keyword-shaped prose, and conclusions the evidence has not earned.

Preserved historical work keeps its period voice. Add dates or present-day
context when old product, medical, legal, platform, or career claims could be
mistaken for current advice; do not rewrite the younger author into the current
one.

## Public visual identity

- Warm paper and dark slate form the base; use a restrained rust accent.
- Upright Newsreader carries editorial display text; Geist Mono carries small
  metadata and technical labels.
- Photography appears as clear, unrotated plates and real process evidence,
  not stock-photo filler.
- The presentation may feel handmade, but never as a scrapbook costume.
  Hierarchy, contrast, keyboard behavior, loading, and mobile readability stay
  rigorous.
- Do not default to shocked faces, fake drama, generic creator thumbnails, or
  decorative motion without editorial meaning.

The site may interleave categories because the public promise is a person
learning across eras. Video may range beyond the site archive and may begin
from a blank page. Existing businesses or projects can be material, but none is
the default organizing premise of Leo's channel.

Historical content pillars, reference creators, and prior artifacts are
evidence and option space. Edit pace, music beds, cameras, lenses, LUTs,
caption styles, named footage, runtimes, title patterns, current culture
examples, and publishing cadence remain per-piece hypotheses until repeated
evidence and Leo's acceptance say otherwise.

## Authorship is surface-specific

- `blog: raw_material_only` — supply source links, commit facts, photo selects,
  and mechanical corrections. Never write sentences, a skeleton with slots, or
  prose to appear under Leo's byline.
- `video: labelled_proposal_or_scaffold` — originate proposals, outlines,
  freestyle prompts, storyboards, edit options, captions, and packaging, but
  label them. Leo owns selection, lived truth, first-person meaning, final
  spoken and public voice, watch, upload, and publish.
- `ui_copy: draft_allowed` — draft and implement reversible UI copy against
  public facts and brand rules. Deployment and publication stay separate.
- External messages and social posts are draft-only when requested. Leo
  authorizes the exact payload and sends or publishes it.

When surfaces compose, apply the strictest rule. Generic video permission must
never leak into blog authorship.

## Explicit adapter

Pass this adapter as data to independently installed production capabilities;
do not rely on an implicit lookup by Leo's name:

```yaml
brand_adapter:
  id: leojkwan
  public_voice:
    - direct and conversational
    - concrete before abstract
    - technically clear when useful
    - candid about failure and uncertainty
  visual_tokens:
    canvas: warm_paper
    ink: dark_slate
    accent: restrained_rust
    display_type: upright_newsreader
    metadata_type: geist_mono
    photography: unrotated_real_process_plates
  editorial_vetoes:
    - corporate_or_engagement_bait_language
    - invented_first_person_claims
    - stock_photo_or_shocked_face_defaults
    - one_off_taste_promoted_to_doctrine
  platform_rules:
    blog: preserve_period_voice_and_append_only_archive
    video: proposal_may_originate_but_human_truth_and_voice_stay_open
    ui: public_facts_only
  public_facts: []
authorship_policy:
  blog: raw_material_only
  video: labelled_proposal_or_scaffold
  ui_copy: draft_allowed
```

Populate `public_facts` only from current public repository authority or
supplied source evidence. Keep unknowns empty or explicit; never fill the
adapter from private context.

## Exclusions

Do not include private people or relationship details, health or energy
profiles, consent reasons, account identifiers, provider state, local paths,
credentials, private archives, dated receipt bodies, or mutable current-season
strategy. Do not import another product's brand or operational policy. Do not
claim that Leo must originate every topic, and do not claim an agent draft as
his final voice.
