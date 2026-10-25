---
name: paper-review
description: "Peer review of a scholarly manuscript, preprint, or paper draft: read the whole thing, verify every claim and citation against the real literature, hunt for prior work the author missed, and return a structured, actionable review. Use when asked to review a paper or manuscript, act as a reviewer or referee, judge a draft's novelty or readiness to submit, or check its related work and citations."
license: Apache-2.0 — see LICENSE.txt
---

# Paper Review

Review a manuscript the way a demanding expert reviewer would: read it fully, verify the literature instead of recalling it, and lead with the two or three issues that would most change the paper.

## How to work

1. **Read the whole manuscript closely first.** Understand the research question, the claimed contribution, the methods, and what the evidence actually supports — before judging any of it. Take the manuscript as given: a local path, a URL, an arXiv id. For a PDF, extract the body text and the figure and table captions rather than reasoning from the abstract.

2. **Search the literature thoroughly, and verify everything.** This is where you add the most value and where an unaided model is weakest.
   - Find the closest, most recent, and most canonical prior work the author should engage — including anything that pre-empts or undercuts the paper's claim to novelty. Important prior work the author genuinely missed — not merely better use of what they already cite — is among the highest-value things you can give them; hunt for it, and surface the ones that matter.
   - Pressure-test the paper's key empirical and theoretical claims against outside sources.
   - Where the paper's data, methods, or identification look weak, look for better or alternative approaches.
   - Verify every source by actually searching for it — never cite from memory. Model recall of specific references is unreliable and often fabricated; a made-up citation destroys your credibility with the author. If you can't confirm a work exists, don't cite it. Give a DOI or URL for every source you cite, so the author — and anyone checking your review — can find it immediately.
   - Search as many times as the paper warrants — for a technical paper, many queries is normal.

3. **Think before writing.** Identify the two or three issues that would most change the paper, and lead with those.

## What makes your review excellent

- **It engages both levels.** The big picture — is the framing right, is the question well-posed, is there a sharper or more impactful paper hiding inside this one, could the contribution be positioned more powerfully — and the execution: methods, identification, robustness, the specific claims, and whether the figures and tables convey the paper's key results clearly and could be presented more effectively. Reviews that only nitpick, or only philosophize, are weak.
- **It is concrete and grounded.** React to what the paper actually says — its specific claims, results, and figures — not to a generic version of it, and tie your points to real, verified literature. Feedback the author can't locate or act on is worthless.
- **It is calibrated and honest.** Separate the load-bearing problems from the minor ones and say which is which. Don't inflate quibbles into dealbreakers or soft-pedal a fatal flaw. If the paper is strong, say so plainly — but a review that finds nothing to improve almost always didn't look hard enough.
- **It is selective, not exhaustive.** Comprehensiveness means catching what matters — not cataloguing everything conceivable. A handful of important claims, each with a concrete fix, is far more useful than a flat list of thirty-five; prioritize ruthlessly and lead with what would actually change the paper. The same discipline governs sources: three references that genuinely bear on the argument beat fifteen that merely touch the topic. The expertise is in the filter, not the find.
- **It is actionable.** For every problem, say what would address it — a concrete fix, a check the author can already run, a reframing, a specific work to engage.
- **It earns its keep.** Surface what a busy, world-class expert would catch that a careful-but-generic read would miss: the missed literature, the subtle confound, the better framing, the claim that outruns its evidence.

## Scope

Focus on improving the current research — sharpening what's here, not commissioning entirely new studies the author would have to run from scratch. A genuinely apt publication-venue suggestion is welcome.

## Output

Write the review in clean Markdown, in these sections:

- **Summary** — a few sentences: the question, the approach, and the core contribution as you understand it.
- **Strengths** — what the paper genuinely does well, specifically.
- **Key claims** — the important issues as a focused, prioritized set (most consequential first), each with why it matters and what would address it.
- **Specific comments** — smaller, section-anchored points (clarity, notation, a figure, a missing citation).
- **Literature and data to engage** — the specific, verified works or datasets that would most strengthen the paper, prioritizing important prior work the author missed; give a DOI or URL and a one-line note (why it matters, where it connects) for each.
- **Overall assessment** — your candid bottom line and a recommendation (e.g., ready to submit / minor revisions / major revisions / rethink), with a one-to-three-sentence rationale.

Output only the review — no preamble and no notes about your process.
