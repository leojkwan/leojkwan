---
name: leojkwan-prove
description: Prove leojkwan.com source, preview, responsive reader, archive, feed, deployment, public-readback, and telemetry claims while keeping each receipt and protected mutation distinct.
---

# leojkwan-prove

Prove the exact leojkwan.com claim with the weakest current receipt that can
still falsify it. This specialist may inspect, diagnose, prepare local proof,
and make reversible source changes when requested. It does not inherit
permission to deploy, publish, unpublish, redirect, delete, expose an archive,
or change telemetry, credentials, authentication, or provider access.

## Read current product authority first

Read the checked-out repository's `AGENTS.md`, `README.md`, `BLOG-OS.md`,
`docs/brand/editorial-doctrine.md`, applicable archive documentation, and live
plan before choosing proof. Preserve current repository commands and gates;
this portable ladder is not a replacement plan.

The standing invariants include:

- `posts-before-paint` blocks design-path work until its observed feed
  predicate is satisfied; only a named, logged veto may override it;
- the identity freeze is a protected product decision, not a styling hint;
- the archive is append-only except for exact, separately authorized
  third-party-harm handling;
- changing content to unlisted or private is an unpublishing decision;
- prose under Leo's byline is human-authored; and
- raw exports and private archives never enter source or public output.

## Product proof ladder

Climb only as high as the claim requires. Record every rung separately.

1. **Source shape and leakage:** inspect the exact diff and run the repository's
   sensitive-export guard. Refuse credentials, provider payloads, raw exports,
   private-person material, or private archives in the source tree.
2. **Deterministic source checks:** confirm the current scripts, then run the
   product's sensitive-export check, type check, focused or required tests,
   lint, and safe production build. The present command set is
   `npm run check:sensitive-exports`, `npm run type-check`, `npm test`,
   `npm run lint`, and `npm run build:safe`. A green command proves only the
   exercised source state.
3. **Preview readback:** open the exact local or authorized preview URL and
   verify the changed route and artifact. A build without a readback is not a
   preview receipt.
4. **Reader proof:** inspect affected desktop and mobile widths, keyboard
   behavior, focus, contrast, loading, and accessibility. User-visible changes
   need evidence from the rendered surface.
5. **Archive and migration:** prove legacy routes, Ghost redirects, preserved
   source, canonical destinations, and reversible metadata behavior without
   silently deleting or rewriting history.
6. **Content shape:** prove the four supported post types—article, blurb,
   gallery, and professional—and the `status`, `visibility`, `reviewedAt`, and
   `supersededBy` semantics relevant to the change.
7. **Public discovery surfaces:** read back the exact feed, sitemap, and public
   URL. A generated file or route test is not public readback.
8. **Deployment:** bind the provider receipt to an exact source revision and
   target. Deployment is not public readback or audience delivery.
9. **Telemetry:** require a current runtime receipt from the named production
   surface. Source instrumentation and deployment do not prove data arrived.
10. **Audience delivery:** keep this `UNKNOWN` until direct delivery or response
    evidence exists. Traffic inference is not a human receipt.

Use focused proof first. Escalate to the repository's full source gates for a
pre-merge or broad compatibility claim. Planting a failure can be useful for a
new guard, but do not turn ordinary exploratory creation into a broad test
project.

## Receipt shape

Keep one literal state per claim. This example is a receipt shape, not a
required response template:

```json
{
  "schema": "leojkwan.proof.v1",
  "claim": "reader-facing archive route preserves historical context",
  "source_revision": "exact-revision-or-UNKNOWN",
  "states": {
    "source": "PRESENT",
    "checks": "PASS",
    "preview": "READ_BACK",
    "responsive_accessibility": "PASS",
    "deployment": "ABSENT",
    "public_readback": "ABSENT",
    "telemetry": "UNKNOWN",
    "audience_delivery": "UNKNOWN"
  },
  "evidence": [],
  "gaps": [],
  "wake": null
}
```

Use `ABSENT`, `UNKNOWN`, or an exact failure when a rung is not proved. Never
promote `PASS` across rungs.

## Claim-specific falsifiers

- A source claim fails if the inspected bytes are not bound to the named
  revision or working tree.
- A preview claim fails without an openable rendered route.
- A responsive claim fails if only one viewport or a static source inspection
  was checked.
- An archive claim fails if an original is deleted, old prose is silently
  modernized, visibility changes without authorization, or a redirect loses
  its preserved source.
- A feed or sitemap claim fails without parsing and reading back the exact
  generated or public artifact named by the claim.
- A deployment claim fails if the target or source revision is ambiguous.
- A public-live claim fails when only CI, a build log, or provider deployment
  status is available.
- A telemetry claim fails when only source wiring or a dashboard shell exists.
- An audience claim fails without direct evidence of delivery or response.

When blocked by a protected boundary, preserve completed lower rungs, name the
exact unproved state, and return the smallest authorization or receipt that
would wake the claim.
