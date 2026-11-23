# Content MANIFEST

Every regulation set shipped in this pack, grouped by jurisdiction. Each
entry links the set directory and its authoritative source. Per-set
licence basis and attribution: [`content-pack/ATTRIBUTIONS.md`](content-pack/ATTRIBUTIONS.md);
machine-readable provenance: [`content-pack/manifest.json`](content-pack/manifest.json).

Two files per set (where present):

- `regulations.json` — the clause-level mapping hierarchy
  (Regulation → Title → Section → Requirement → Control).
- `applicability.json` — obligation texts keyed by `rule_id`, cited by the
  AI Builder rule set in the [code repository](https://github.com/mabel-co/continuum).

## European Union

| Framework | Set | Source |
|---|---|---|
| [EU AI Act](content-pack/eu-ai-act/) | `eu-ai-act` | https://eur-lex.europa.eu/eli/reg/2024/1689/oj |
| [EU DORA](content-pack/eu-dora/) | `eu-dora` | https://eur-lex.europa.eu/eli/reg/2022/2554/oj |
| [EU GDPR](content-pack/eu-gdpr/) | `eu-gdpr` | https://eur-lex.europa.eu/eli/reg/2016/679/oj |
| [EU NIS2 Directive](content-pack/eu-nis2/) | `eu-nis2` | https://eur-lex.europa.eu/eli/dir/2022/2555/oj |
| [EBA AI/ML Guidelines](content-pack/eba-ai-guidelines/) | `eba-ai-guidelines` | https://www.eba.europa.eu/regulation-and-policy/internal-governance |
## United Kingdom

| Framework | Set | Source |
|---|---|---|
| [FCA Guidance on AI/ML](content-pack/uk-fca/) | `uk-fca` | https://www.fca.org.uk/publication/policy/fp-24-04.pdf |
| [PRA Model Risk Management — SS1/23](content-pack/pra-ai-guidance/) | `pra-ai-guidance` | https://www.bankofengland.co.uk/prudential-regulation/publication/2023/may/model-risk-management-principles-for-banks-ss |
| [UK AI White Paper — 5 Principles](content-pack/uk-ai-principles/) | `uk-ai-principles` | https://www.gov.uk/government/publications/ai-future-finding-the-right-time-to-act |
| [ICO AI & Data Protection Guidance](content-pack/ico-guidance/) | `ico-guidance` | https://www.informationstandardscentre.org/standards/10004092/ |
| [ICAEW — AI Standards and Guidance](content-pack/icaew-ai-standards/) | `icaew-ai-standards` | https://www.icaew.com/technical/technology/artificial-intelligence/managing-risks/ai-governance-10-essential-questions-for-responsible-adoption |
## United States

| Framework | Set | Source |
|---|---|---|
| [SR 26-2](content-pack/us-sr/) | `us-sr` | https://www.federalreserve.gov/supervisionreg/srletters/SR2602.htm |
| [FTC — AI Consumer Protection](content-pack/ftc-ai-consumer-protection/) | `ftc-ai-consumer-protection` | https://www.govinfo.gov/content/pkg/FR-2026-07-07/pdf/2026-13628.pdf |
| [NIST AI RMF 1.0](content-pack/nist-ai-rmf/) | `nist-ai-rmf` | https://www.nist.gov/itl/ai-risk-management-framework |
## International standards bodies

| Framework | Set | Source |
|---|---|---|
| [ISO 42001](content-pack/iso-42001/) | `iso-42001` | https://www.iso.org/standard/81594.html |
| [ISO/IEC 23894](content-pack/iso-23894/) | `iso-23894` | https://www.iso.org/standard/84936.html |
| [ISO/IEC 24027](content-pack/iso-24027/) | `iso-24027` | https://www.iso.org/standard/79827.html |
| [BCBS Model Risk / AI-ML Guidance](content-pack/bcbs-model-risk/) | `bcbs-model-risk` | https://www.bis.org/bcbs |
| [IOSCO AI Guidance](content-pack/iosco-ai-guidance/) | `iosco-ai-guidance` | https://www.iosco.org |
## Asia-Pacific

| Framework | Set | Source |
|---|---|---|
| [Singapore MGF for Agentic AI](content-pack/sg-mgf-agentic/) | `sg-mgf-agentic` | https://www.imda.gov.sg/-/media/imda/files/about/emerging-tech-and-research/artificial-intelligence/mgf-for-agentic-ai.pdf |
| [China Generative AI Measures](content-pack/china-genai/) | `china-genai` | https://www.cac.gov.cn/2023-07/13/c_1690898327029107.htm |
| [Japan AI Appropriateness Guideline](content-pack/japan-ai-gov/) | `japan-ai-gov` | https://www8.cao.go.jp/cstp/ai/ai_guideline/ai_gl_2025.pdf |

**Zero-ISO rule.** The three ISO sets carry clause numbers and our own
language only — no verbatim ISO text appears anywhere in this pack.

_Index generated for the 21 sets in the manifest._
