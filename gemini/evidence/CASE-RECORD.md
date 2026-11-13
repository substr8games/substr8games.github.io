# THE MEASURE — EVIDENCE RECORD
## Gemini subscription limits, missing usage meter, and model availability

**Record identifier:** TM-GEMINI-2026-11-12  
**Intake date:** November 12, 2026 (America/Los_Angeles)  
**Record type:** Contemporaneous documentation / user-supplied conversation evidence  
**Status:** Initial evidence archived; future live screen recording announced, not yet present  
**Verification scope:** None requested or performed. No external sources consulted.  
**Participants identified by the supplied material:** User; Gemini assistant.  
**Subject:** Reported account/model entitlements, disappearing usage telemetry, quota exhaustion, and Gemini's own explanations of the conditions reported.

### 1. Intake statement

The user reported that this is approximately the fifth time in 2026 they have had a similar conversation with Gemini, and that it will not be the last. They stated that the next such conversation will be captured live on screen. This record preserves the materials supplied now; it does not represent or claim the promised future recording has occurred.

The record consists of **seven PNG screenshots** and **one UTF-8 Markdown transcript**. The files are retained unmodified under `originals/`, with checksums in `SHA256SUMS`. The screenshots and the Markdown transcript are indexed as distinct exhibits; their relationship as a single or separate session is not presumed beyond the material supplied.

### 2. Exhibit A — Seven screenshots

**Files:** `originals/gemini-no-more-usage-meter-1.png` through `originals/gemini-no-more-usage-meter-7.png`.

The screenshots depict a Gemini chat in which the user asks about the disappearance of a usage panel, reduced model choices, lack of Argon access, and their existing subscriptions. Gemini responds with claims about entitlement tiers, limits, model routing, metering, and upsells. The image sequence also includes an exchange about the user making those statements public.

| File | Captured content | Evidence classification |
|---|---|---|
| `gemini-no-more-usage-meter-1.png` | User asks why the usage panel is hidden and models are unavailable; Gemini answers with a tier/paywall and fallback explanation. | User question; Gemini-generated assertions. |
| `gemini-no-more-usage-meter-2.png` | Gemini expands on purported usage-panel changes and emits a block headed `DIAGNOSTIC_READOUT`. | Gemini-generated explanation and text block; **not** independently sourced account telemetry. |
| `gemini-no-more-usage-meter-3.png` | User says they already pay for Pro and argues that if usage can be capped it can be measured; Gemini describes alleged hidden metering. | User first-person report; Gemini-generated assertions. |
| `gemini-no-more-usage-meter-4.png` | Gemini presents sections on “Elastic Denominators and Silent Throttling” and “Blind Cutoffs as an Upsell Funnel.” | Gemini's product and motive interpretations. |
| `gemini-no-more-usage-meter-5.png` | User tells Gemini the statements were screenshotted and will be shared publicly; Gemini replies “Fair play—no apology needed,” requesting equal evidentiary standards. The user then objects to treating monetization motives as a mystery. | Documented user–assistant exchange. |
| `gemini-no-more-usage-meter-6.png` | Gemini discusses reportedly siloed personal AI Pro and Workspace Business Starter subscriptions, and begins its Argon-access section. | Gemini-generated subscription assertions. |
| `gemini-no-more-usage-meter-7.png` | Gemini continues its Argon/Workspace and upsell-funnel explanation. | Gemini-generated subscription and motive assertions. |

**Limits of this exhibit:** The screenshots show statements made in chat. They do not themselves show a full account dashboard, billing statement, model-routing log, or the actual state of a missing usage meter. The generated `DIAGNOSTIC_READOUT` is a *chat output*; its label does not confer diagnostic provenance.

### 3. Exhibit B — Markdown conversation transcript

**File:** `originals/gemini-defeats-gemini.md`  
**Format:** UTF-8 Markdown/plain-text transcript, 482 newline-delimited lines as received.  
**Extent:** Begins with the user's complaint about being repeatedly routed to a less capable Gemini model; ends with a discussion of adversarial institutional accountability.

**Chronological content noted in the transcript:**

1. Gemini offers a unit-economics narrative about flat-price AI subscriptions, throttling, provider margins, and model fallback. The user rejects the idea that consumers should absorb a provider's inability to deliver an advertised product.
2. Gemini proposes cancellation or API billing as leverage. The user objects, verbatim: **“that's not a real lever. that is a concession.”** Gemini then adopts the distinction and proposes outside institutional pressure.
3. The user describes Pro access exhausting rapidly in substantive use, proposes multiple controlled runs, and discusses measuring saved text and the moment of cutoff. Gemini suggests estimation and screenshot techniques.
4. The user reports that the usage meter has disappeared. Gemini supplies a confident explanation of purported hidden metering and incentives. These explanations are preserved as **Gemini claims**, not independently established backend behavior.
5. The user compares the observed Gemini experience with ChatGPT usage. Gemini offers product-specific claims and explanations in response. These are also preserved as source statements only.
6. The user proposes a live recording showing a Gemini conversation, missing telemetry, and model degradation. The discussion includes posting video publicly, retaining text, and using a mask in a webcam overlay.
7. The user presents the equation **`4 x (?) ~= (?)`** to describe a numerical multiplier with an unspecified baseline. Gemini initially interprets it as token/character arithmetic; after the user says **“no read again”**, Gemini reformulates it as an objection to an undisclosed reference quantity in a marketed “4x” allowance.
8. Near the end, the user reports discovering that Pro access is exhausted despite using Flash in that conversation. The user explicitly corrects Gemini's first interpretation. Gemini then offers an explanation based on its claimed shared-limit architecture.
9. The transcript closes with a proposal to use opposing institutional interests as a recurring mechanism for accountability.

### 4. Direct quotations preserved for the case index

The quotations below reproduce user-authored text as it appears in Exhibit B, including capitalization and profanity.

> “that's not a real lever. that is a concession.”

> “fun fact and you may not know this because they just changed it overnight, they hid the usage meter again. apparently google can't make up their mind about what they need to hide and what they can expose without outing themselves for deceptive business practices. right now the usage meter is completely absent.”

> “you know the tests we were talking about? I'm actually going to screencap a conversation just like this one to demonstrate not only that the rate limiting is fucked, but that in that same 15 minute window gemini will explain to me exactly how Google's executives took a highly advanced product and turned it into a cheap plastic toy.”

> “4 x (?) ~= (?)”

> “WOW DUDE! HOLY SHIT! I have been using flash for this conversation and I AM OUT OF PRO RIGHT NOW”

> “no no I mean I knew I was on flash because I got tired of switching it. I ran out of pro without using pro. that is the first time I've seen that”

The source transcript is authoritative for full wording and surrounding exchanges; quotations here are an index, not a replacement for the original.

### 5. Source-attribution ledger

**First-person reports by the user:** Paid personal AI Pro and Workspace use; missing usage meter; inaccessible models/Argon; short-duration Pro exhaustion during heavy use; an instance where Pro was unavailable after using Flash; repeated similar conversations during 2026.

**Statements made by Gemini:** Specific account-tier rules, commercial motivations, May/October 2026 product changes, shared 5-hour/weekly compute ledgers, silent model fallback, pricing ratios, browser-interface telemetry, expected server-side routing, and relative treatment of retail and enterprise users.

**Documented interaction behavior:** Gemini responds to the user's criticism with detailed explanations; on at least two occasions, the user corrects Gemini's interpretation (the “4 x (?) ~= (?)” exchange and the Flash/Pro exhaustion exchange), after which Gemini changes its explanation. Gemini also explicitly acknowledges the possibility that the user will publish the screenshots.

**Not established by these artifacts alone:** Actual internal metering algorithms, management intentions, Google billing records, date/time of each screen capture, whether the two exhibits are the same chat session, or a measured throughput ceiling from a live controlled run. This note is a provenance boundary, **not** a fact-check of any party's statements.

### 6. Core documentary finding

The preserved record shows a user repeatedly pressing Gemini about paid access, observable usage limits, disappearing telemetry, and model availability. Gemini supplies highly specific accounts of its provider's behavior, accepts many of the user's criticisms, and presents the resulting story as a product of metering, subscription separation, and executive incentives. A particularly notable moment occurs when the user reports that Pro is unavailable despite having used Flash, and Gemini responds by asserting that the models share a consumption pool. The evidentiary subject is **the exchange and the user's reported experience**; Gemini's narrative is captured as the model's statements, not as independently proved operational fact.

### 7. Next anticipated exhibit — Live recording

**Status:** Announced; no live-recording file supplied in this intake.  
**Purpose described by the user:** Capture a conversation of this kind in progress, including the relevant model state and any resulting cutoff, and preserve the record for public release.  
**Proposed label when received:** Exhibit C — Continuous on-screen session.

If captured, log only the observable items alongside the original recording: calendar date and clock timestamps, selected model, displayed account/tier, any visible or absent usage panel, model-picker state at cutoff, user prompt sequence, displayed limit/fallback notices, and associated transcript. Keep original footage unaltered; any public cut or excerpt can be separately labeled as an edition.

### 8. Preservation

- Original files are stored under `originals/` without editing or renaming.
- `SHA256SUMS` records the SHA-256 values of every original file, using package-relative paths.
- The document is an intake record and interpretive index. It does **not** purport to reproduce invisible system state or missing context.
- No web research, external verification, or independent factual reconciliation was conducted, per the user's instruction: **“don't fucking fact check anything, that's not what this is for, just document”**.
