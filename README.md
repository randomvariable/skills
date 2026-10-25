# skills

Agent skills ([`SKILL.md`](https://agentskills.io)) for scholarly and technical work.

## paper-review

Peer review of a manuscript, preprint, or paper draft. The skill makes the agent read the whole document first, verify every citation by actually searching for it, hunt for prior work the author missed, and return a fixed Markdown review structure — summary, strengths, prioritized key claims, section-anchored comments, literature and data to engage, and a recommendation with rationale.

Written for the failure modes of an unaided model review: fabricated references, padded lists of thirty-five nitpicks, and reflexive praise. The rules state which claims are load-bearing, and every source the review cites carries a DOI or URL.

```bash
npx skills add randomvariable/skills
```

Claude Code can also install it as a plugin:

```
/plugin marketplace add randomvariable/skills
```

Then ask for a review, handing over a path, a URL, or an arXiv id:

> Review this paper: https://arxiv.org/abs/2401.00001

Point it at a venue and a pre-submission critique comes back in the same shape:

> Act as a reviewer 2 for this draft before I submit it to OSDI.

## Layout

```
skills/paper-review/SKILL.md   # the skill
.claude-plugin/marketplace.json # Claude Code plugin marketplace entry
LICENSE.txt                     # Apache-2.0
```

Add a skill by dropping `skills/<name>/SKILL.md` in place: `name` and a trigger-rich `description` in the frontmatter, the procedure in the body. Nothing else registers it.

## Provenance

The `paper-review` review spec is adapted from a circulated reviewer prompt (<https://pastebin.com/raw/q6Qq05WC>), restructured as a skill: duplicated guardrails folded into single statements, and the review procedure given explicit completion criteria.

## License

Apache-2.0. See [LICENSE.txt](LICENSE.txt).
