# Continuum Content Pack

> **Experimental — AI-generated, not human-validated.** This repository is
> built by an AI agent team under human ownership. Its contents have **not
> been validated by human experts**; we publish it for you to explore and give
> feedback on, not for production or compliance use. There is **no guarantee
> that anything here is correct or complete, and no liability is accepted**
> for its use. Nothing here is professional, compliance, or legal advice.
> The licence terms (including warranty disclaimers) apply in full.

Regulatory reference content for
[Continuum](https://github.com/mabel-co/continuum): clause-level mappings and
our own explanatory language for AI-governance regulations across 21 framework
sets (EU, UK, US, international standards bodies, and Asia-Pacific).
Start with [`MANIFEST.md`](MANIFEST.md) — the index of covered frameworks and
their sources — and [`content-pack/ATTRIBUTIONS.md`](content-pack/ATTRIBUTIONS.md)
for per-set provenance.

**Licence:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — the
full legal code is in [`LICENSE`](LICENSE).

**Attribution form.** When reusing this material, credit:
*"Continuum Content Pack, mabel-co/continuum-content, licensed under
CC BY 4.0."* Remove the attribution if you request it (CC BY 4.0 §3).

**No ISO text.** Nothing here reproduces verbatim ISO content. ISO clauses
are referenced by number with our own mapping language; EU/UK/US
government-derived sets carry their own attribution (OGL v3 / Commission
Decision 2011/833/EU / 17 U.S.C. §105) — the per-set record is
[`content-pack/manifest.json`](content-pack/manifest.json), rendered for
humans in [`content-pack/ATTRIBUTIONS.md`](content-pack/ATTRIBUTIONS.md).

## Liability disclaimer

This repository is **demo-grade reference material**, not compliance advice.
To the maximum extent permitted by law it is provided **as is**, **without
warranty of any kind**, express or implied, including without limitation the
disclaimers in [CC BY 4.0 §5](LICENSE) and, additionally:

- **Not legal or regulatory advice.** Nothing here constitutes advice on which
  you should rely. These mappings summarise publicly available regulations and
  guidance in our own words; they are simplified, may be incomplete, out of
  date, or inaccurate relative to the current authoritative text.
- **No assurance or certification.** Nothing in this pack is an audit,
  conformity assessment, or attestation, and using it does not make any
  system compliant with any regulation.
- **Verify against the primary source.** Each set names its authoritative
  source; always check the current official text before making decisions.
- **Use at your own risk.** The authors and maintainers accept **no liability**
  for any loss, damage, or regulatory consequence arising from use of, or
  reliance on, this material — including decisions about whether, or how, to
  deploy AI systems.

## Layout

```text
MANIFEST.md            index of covered frameworks by jurisdiction, with sources
content-pack/
  manifest.json        per-set provenance: source URL, licence basis, attribution,
                       derivation posture, currency date
  ATTRIBUTIONS.md      rendered from the manifest; do not hand-edit
  <set>/               one directory per regulation set:
    regulations.json     clause-level mapping hierarchy for that regulation
    applicability.json   obligation texts keyed by rule_id (where cited)
```

This tree is **data only**: it contains no code. The Continuum engine loads it
at runtime from a sibling clone at this exact name
(`continuum-content/content-pack/`) or from the directory named by
`ASSURER_CONTENT_PACK_ROOT`. Set membership and schema are validated against
the engine's seed contract; a mismatched pack fails loudly, never partially.
