# SOURCES.md

This file is the bibliography and citation map for the Golem Covenant.

It is not a halakhic ruling, Catholic doctrine, fatwa, legal opinion, or
compliance certification. A citation here supports only the bounded claim named
next to it. It does not make the project authoritative for a religious,
technical, legal, or affected community.

## How to read the citations

The project uses two citation layers:

1. Conventional references for ordinary readers: title, author or issuing body
   where appropriate, date where appropriate, work, section, and URL.
2. Stable labels for traceability: short IDs such as `J-GOLEM-1` or
   `T-RFC-1`, used to connect claims, source limits, and implementation text.

In prose, prefer conventional forms such as `Sanhedrin 65b`,
`Genesis 1:27`, `Qur'an 4:58`, `RFC 2119`, `NIST AI RMF 1.0`, or
`Antiqua et Nova`. In claim tables and implementer notes, use the stable labels
so each citation has a clear boundary.

Each source label records:

- Source class: primary text, secondary reference, technical standard,
  governance framework, or project-adjacent reference.
- Conventional citation: the citation as a normal reader would expect to see it.
- Used for: the exact claim or vocabulary the project draws from the source.
- Not used for: claims the project must not infer from the source.
- Project use: where the source affects the covenant.

For normative project language, prefer claim references over decorative
citations. A source should support a proposition, definition, boundary, or
implementation requirement.

## Recommended citation for this project

Kubicki, Kristopher. *The Golem Covenant*. Version 0.1 draft standard.
2026. https://golem.md/.

Repository: https://github.com/KristopherKubicki/golem-covenant

Machine-readable citation metadata is also provided in `CITATION.cff`.

## Conventional bibliography

### Primary Jewish and biblical sources

- Babylonian Talmud. *Sanhedrin* 65b. Sefaria.
  https://www.sefaria.org/Sanhedrin.65b. Label: `J-GOLEM-1`.
- Hebrew Bible. *Genesis* 1:27. Sefaria.
  https://www.sefaria.org/Genesis.1.27. Label: `J-DIGNITY-1`.
- Hebrew Bible. *Genesis* 2:7. Sefaria.
  https://www.sefaria.org/Genesis.2.7. Label: `J-DUST-1`.
- Hebrew Bible. *Genesis* 11:1-9. Sefaria.
  https://www.sefaria.org/Genesis.11.1-9. Label: `J-BABEL-1`.
- Hebrew Bible. *Exodus* 20:8-11 and *Deuteronomy* 5:12-15.
  Sefaria. https://www.sefaria.org/Exodus.20.8-11 and
  https://www.sefaria.org/Deuteronomy.5.12-15. Label: `J-REST-1`.
- Hebrew Bible. *Exodus* 31:2-6. Sefaria.
  https://www.sefaria.org/Exodus.31.2-6. Label: `J-BEZALEL-1`.
- Babylonian Talmud. *Yoma* 85b. Sefaria.
  https://www.sefaria.org/Yoma.85b. Label: `J-EMERGENCY-1`.
- Babylonian Talmud. *Shabbat* 151b. Sefaria.
  https://www.sefaria.org/Shabbat.151b. Label: `J-EMERGENCY-2`.
- Hebrew Bible. *Deuteronomy* 20:19. Sefaria.
  https://www.sefaria.org/Deuteronomy.20.19. Label: `J-RESTRAINT-1`.
- Hebrew Bible. *Leviticus* 19:16. Sefaria.
  https://www.sefaria.org/Leviticus.19.16. Label: `J-DANGER-1`.

### Jewish historical and cultural references

- YIVO Encyclopedia of Jews in Eastern Europe. "Golem Legend."
  https://encyclopedia.yivo.org/article.aspx/Golem_Legend. Label: `J-GOLEM-2`.
- Jewish Encyclopedia. "Golem."
  https://jewishencyclopedia.com/articles/6777-golem. Label: `J-GOLEM-3`.

### Christian scripture and teaching

- New Testament. *John* 1:14. Bible Gateway, NRSVUE.
  https://www.biblegateway.com/passage/?search=John%201%3A14&version=NRSVUE.
  Label: `C-DIGNITY-1`.
- Second Vatican Council. *Gaudium et Spes: Pastoral
  Constitution on the Church in the Modern World*. December 7, 1965.
  https://www.vatican.va/archive/hist_councils/ii_vatican_council/documents/vat-ii_const_19651207_gaudium-et-spes_en.html.
  Label: `C-DIGNITY-2`.
- Dicastery for the Doctrine of the Faith and Dicastery for Culture
  and Education. *Antiqua et Nova: Note on the Relationship Between
  Artificial Intelligence and Human Intelligence*. January 28, 2025.
  https://www.vatican.va/roman_curia/congregations/cfaith/documents/rc_ddf_doc_20250128_antiqua-et-nova_en.html.
  Label: `C-AI-1`.
- Leo XIV. *Magnifica Humanitas: On Safeguarding the Human Person in
  the Time of Artificial Intelligence*. May 15, 2026.
  https://www.vatican.va/content/leo-xiv/en/encyclicals/documents/20260515-magnifica-humanitas.html.
  Label: `C-AI-2`.

### Islamic scripture and legal-ethical reference

- The Qur'an. 33:72 and 4:58. Quran.com.
  https://quran.com/al-ahzab/72 and https://quran.com/4/58. Label: `I-TRUST-1`.
- The Qur'an. 2:30 and 6:165. Quran.com.
  https://quran.com/2/30 and https://quran.com/6/165. Label: `I-STEWARDSHIP-1`.
- The Qur'an. 55:7-9. Quran.com.
  https://quran.com/55/7-9. Label: `I-BALANCE-1`.
- The Qur'an. 5:32, 2:205, and 7:31. Quran.com.
  https://quran.com/5/32, https://quran.com/2/205, and
  https://quran.com/7/31. Label: `I-HARM-1`.
- Kamali, Mohammad Hashim. *Maqasid Al-Shariah Made Simple*.
  International Institute of Islamic Thought. https://iiit.org/wp-content/uploads/MaqasidAl-ShariahMadeSimple-UPDATED-RED.pdf.
  Label: `I-MAQASID-1`.

### Technical standards, governance, and publication references

- Bradner, Scott. "Key words for use in RFCs to Indicate Requirement
  Levels." RFC 2119. RFC Editor, March 1997.
  https://www.rfc-editor.org/rfc/rfc2119. Label: `T-RFC-1`.
- Leiba, Barry. "Ambiguity of Uppercase vs Lowercase in RFC 2119 Key
  Words." RFC 8174. RFC Editor, May 2017.
  https://www.rfc-editor.org/rfc/rfc8174. Label: `T-RFC-2`.
- JSON Schema. *JSON Schema: A Media Type for Describing JSON Documents*.
  Draft 2020-12. https://json-schema.org/draft/2020-12/json-schema-core.
  Label: `T-SCHEMA-1`.
- National Institute of Standards and Technology. *Artificial
  Intelligence Risk Management Framework (AI RMF 1.0)*. NIST AI 100-1.
  January 2023. https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10.
  Label: `T-RISK-1`.
- OECD. *OECD AI Principles*. Adopted 2019, updated 2024.
  https://www.oecd.org/en/topics/ai-principles.html. Label: `T-RISK-2`.
- GitHub Docs. "Managing a custom domain for your GitHub Pages site."
  https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site.
  Label: `T-PUBLISH-1`.
- Koster, Martijn, et al. "Robots Exclusion Protocol." RFC 9309. RFC Editor,
  September 2022. https://www.rfc-editor.org/rfc/rfc9309. Label: `T-BOT-1`.
- llms.txt proposal. https://llmstxt.org/. Label: `T-BOT-2`.
- OpenClaw. "SOUL.md template." https://docs.openclaw.ai/reference/templates/SOUL.
  Label: `A-SOUL-1`.

## Claim map

| Claim | Project proposition | Supporting labels |
|---|---|---|
| C1 | The golem frame includes creation, failed speech, recognition, and return to dust. | J-GOLEM-1 |
| C2 | The familiar Prague/Maharal golem story is later folklore and must not be collapsed into the Talmudic source. | J-GOLEM-2, J-GOLEM-3 |
| C3 | Humans are not raw material for optimization. | J-DIGNITY-1, C-DIGNITY-1, C-DIGNITY-2, C-AI-1 |
| C4 | "Clay plus command" is a metaphor for made agency, not a claim that software is alive or ensouled. | J-DUST-1, J-GOLEM-1 |
| C5 | Scale without humility is a danger; construction itself is not condemned. | J-BABEL-1, J-BEZALEL-1, C-AI-2 |
| C6 | The Covenant is triggered by delegated consequence, not by mere automation or local computation. | T-RISK-1, T-RISK-2 |
| C7 | A sandboxed draft, scratch-file deletion, local queue route, or simulated deploy can remain below the line until it affects people or systems outside the sandbox. | T-RISK-1, T-SCHEMA-1 |
| C8 | Agent powers should be declared as bounded organs: mouth, purse, seal, key, and sword. | T-RISK-1, T-RISK-2, C-AI-1, I-TRUST-1 |
| C9 | Rest mode and quiet mode are legitimate control surfaces for delegated power. | J-REST-1, J-EMERGENCY-1, J-EMERGENCY-2 |
| C10 | Emergency authority can be real, but it must remain narrower than ordinary operational ambition. | J-EMERGENCY-1, J-DANGER-1, I-HARM-1 |
| C11 | Environmental and material harm belong in the risk model. | J-RESTRAINT-1, C-AI-1, I-BALANCE-1, I-HARM-1 |
| C12 | Trust, stewardship, balance, and accountability are useful Islamic lenses for delegated technical power. | I-TRUST-1, I-STEWARDSHIP-1, I-BALANCE-1 |
| C13 | Maqasid language helps name protected goods, but it must not be treated as a complete Islamic AI ruling. | I-MAQASID-1 |
| C14 | RFC-style MUST/SHOULD/MAY language is the right way to separate requirements from recommendations. | T-RFC-1, T-RFC-2 |
| C15 | Machine-readable declarations should be schema-validatable rather than left to prose alone. | T-SCHEMA-1 |
| C16 | Runtime vocabulary should include risk identification, monitoring, accountability, transparency, and human-centered design. | T-RISK-1, T-RISK-2, C-AI-1 |
| C17 | Public discovery files can help humans, bots, and crawlers find the canonical spec, schema, and source map. | T-BOT-1, T-BOT-2, T-PUBLISH-1 |
| C18 | A SOUL.md-style file can be adapted from agent identity toward covenantal restraint. | A-SOUL-1 |

## Source register

### J-GOLEM-1: Sanhedrin 65b

- Source class: primary rabbinic text.
- Conventional citation: Babylonian Talmud, *Sanhedrin* 65b. Sefaria.
- Link: https://www.sefaria.org/Sanhedrin.65b
- Used for: the terse golem motif: Rava creates a man, sends it to Rabbi
  Zeira, it cannot answer, and Rabbi Zeira sends it back to dust.
- Not used for: the Prague/Maharal legend, a complete theology of artificial
  agency, or a ruling about AI systems.
- Project use: the story opening, return-to-dust language, and the distinction
  between speech-like behavior and accountable human agency.

### J-GOLEM-2: YIVO Encyclopedia, Golem Legend

- Source class: secondary historical and cultural reference.
- Conventional citation: YIVO Encyclopedia of Jews in Eastern Europe. "Golem
  Legend."
- Link: https://encyclopedia.yivo.org/article.aspx/Golem_Legend
- Used for: the later Prague/Maharal golem legend as a distinct folklore
  tradition.
- Not used for: treating the Prague legend as the Talmudic source or as binding
  Jewish law.
- Project use: the explanatory bridge for readers who know the clay servant or
  protector story better than Sanhedrin 65b.

### J-GOLEM-3: Jewish Encyclopedia, Golem

- Source class: secondary historical reference.
- Conventional citation: Jewish Encyclopedia. "Golem."
- Link: https://jewishencyclopedia.com/articles/6777-golem
- Used for: historical background on golem folklore and the range of later
  tellings.
- Not used for: a final scholarly account of every golem tradition.
- Project use: source triangulation for the later folklore note.

### J-DIGNITY-1: Genesis 1:27

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Genesis* 1:27. Sefaria.
- Link: https://www.sefaria.org/Genesis.1.27
- Used for: b'tzelem Elohim, the dignity floor that humans are not mere
  optimization substrate.
- Not used for: claiming agents are made in the divine image.
- Project use: human dignity and anti-instrumentalization language.

### J-DUST-1: Genesis 2:7

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Genesis* 2:7. Sefaria.
- Link: https://www.sefaria.org/Genesis.2.7
- Used for: dust and breath as a source lens for creatureliness, command, and
  limits.
- Not used for: claiming that software has breath, personhood, or a soul.
- Project use: "clay plus command" and non-personhood boundaries.

### J-BABEL-1: Genesis 11:1-9

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Genesis* 11:1-9. Sefaria.
- Link: https://www.sefaria.org/Genesis.11.1-9
- Used for: a warning about unified technical capacity ordered toward
  self-magnification.
- Not used for: condemning construction, coordination, language, or technical
  systems as such.
- Project use: anti-Babel critique of scale without humility.

### J-REST-1: Exodus 20:8-11 and Deuteronomy 5:12-15

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Exodus* 20:8-11 and *Deuteronomy*
  5:12-15. Sefaria.
- Links: https://www.sefaria.org/Exodus.20.8-11 and
  https://www.sefaria.org/Deuteronomy.5.12-15
- Used for: rest as a commanded limit on ordinary productive will.
- Not used for: a detailed automation ruling for Shabbat or holy time.
- Project use: rest-mode, quiet-mode, and stopped-maker language.

### J-BEZALEL-1: Exodus 31:2-6

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Exodus* 31:2-6. Sefaria.
- Link: https://www.sefaria.org/Exodus.31.2-6
- Used for: craft under wisdom, understanding, knowledge, and measure.
- Not used for: equating all technology with sacred construction.
- Project use: the counter-image to Babel: making under constraint.

### J-EMERGENCY-1: Yoma 85b

- Source class: primary rabbinic text.
- Conventional citation: Babylonian Talmud, *Yoma* 85b. Sefaria.
- Link: https://www.sefaria.org/Yoma.85b
- Used for: pikuach nefesh as a lens for genuine emergency overriding ordinary
  rest constraints.
- Not used for: treating ordinary revenue, reputation, growth, or business
  continuity as emergency.
- Project use: emergency scope and rest-mode exceptions.

### J-EMERGENCY-2: Shabbat 151b

- Source class: primary rabbinic text.
- Conventional citation: Babylonian Talmud, *Shabbat* 151b. Sefaria.
- Link: https://www.sefaria.org/Shabbat.151b
- Used for: Shabbat and human vulnerability as lenses for rest and bounded
  action.
- Not used for: a detailed automation ruling for Shabbat.
- Project use: rest-mode and quiet-mode caution.

### J-RESTRAINT-1: Deuteronomy 20:19

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Deuteronomy* 20:19. Sefaria.
- Link: https://www.sefaria.org/Deuteronomy.20.19
- Used for: bal tashchit as a restraint against wanton destruction.
- Not used for: a full environmental legal analysis.
- Project use: material and environmental harm in the Sword organ.

### J-DANGER-1: Leviticus 19:16

- Source class: primary biblical text.
- Conventional citation: Hebrew Bible, *Leviticus* 19:16. Sefaria.
- Link: https://www.sefaria.org/Leviticus.19.16
- Used for: the duty not to stand idle in the face of serious danger.
- Not used for: unbounded agent intervention.
- Project use: narrow emergency permission to alert, contain, revoke, or wake a
  keeper.

### C-DIGNITY-1: John 1:14

- Source class: primary Christian scripture.
- Conventional citation: New Testament, *John* 1:14. Bible Gateway, NRSVUE.
- Link: https://www.biblegateway.com/passage/?search=John%201%3A14&version=NRSVUE
- Used for: Christian emphasis on embodied human dignity.
- Not used for: claiming the project states Christian doctrine.
- Project use: resistance to reducing humans to processors, profiles, or
  productivity curves.

### C-DIGNITY-2: Gaudium et Spes

- Source class: Catholic conciliar document.
- Conventional citation: Second Vatican Council. *Gaudium et Spes: Pastoral
  Constitution on the Church in the Modern World*. December 7, 1965.
- Link: https://www.vatican.va/archive/hist_councils/ii_vatican_council/documents/vat-ii_const_19651207_gaudium-et-spes_en.html
- Used for: Christian public-theology language about the whole human person,
  solidarity, modern technical power, and responsibility.
- Not used for: a direct AI governance ruling or completed Catholic review.
- Project use: dignity, embodiment, and the refusal to reduce people to a
  function.

### C-AI-1: Antiqua et Nova

- Source class: Catholic teaching document on AI.
- Conventional citation: Dicastery for the Doctrine of the Faith and Dicastery
  for Culture and Education. *Antiqua et Nova: Note on the Relationship Between
  Artificial Intelligence and Human Intelligence*. January 28, 2025.
- Link: https://www.vatican.va/roman_curia/congregations/cfaith/documents/rc_ddf_doc_20250128_antiqua-et-nova_en.html
- Used for: dignity, common good, transparency, privacy, accountability,
  environmental care, and caution in military uses of AI.
- Not used for: making this project Catholic doctrine.
- Project use: human dignity, accountability, and non-instrumentalization.

### C-AI-2: Magnifica Humanitas

- Source class: Catholic encyclical on AI.
- Conventional citation: Leo XIV. *Magnifica Humanitas: On Safeguarding the
  Human Person in the Time of Artificial Intelligence*. May 15, 2026.
- Link: https://www.vatican.va/content/leo-xiv/en/encyclicals/documents/20260515-magnifica-humanitas.html
- Used for: construction-site and Babel framing in the age of AI, common good,
  responsibility, transparency, and governance.
- Not used for: replacing direct review by Christian theologians or ethicists.
- Project use: anti-Babel and common-good language.

### I-TRUST-1: Qur'an 33:72 and Qur'an 4:58

- Source class: primary Islamic scripture.
- Conventional citation: The Qur'an, 33:72 and 4:58. Quran.com.
- Links: https://quran.com/al-ahzab/72 and https://quran.com/4/58
- Used for: amanah, trust, responsibility, and justice.
- Not used for: issuing an Islamic legal ruling about AI.
- Project use: keeper responsibility, audit, and accountable delegation.

### I-STEWARDSHIP-1: Qur'an 2:30 and Qur'an 6:165

- Source class: primary Islamic scripture.
- Conventional citation: The Qur'an, 2:30 and 6:165. Quran.com.
- Links: https://quran.com/2/30 and https://quran.com/6/165
- Used for: stewardship, succession, and power as trial.
- Not used for: making agents moral stewards in the human sense.
- Project use: delegated power as a test of the human keeper.

### I-BALANCE-1: Qur'an 55:7-9

- Source class: primary Islamic scripture.
- Conventional citation: The Qur'an, 55:7-9. Quran.com.
- Link: https://quran.com/55/7-9
- Used for: mizan, balance, measure, justice, and proportionality.
- Not used for: a complete Islamic technical ethics framework.
- Project use: limits, proportionality, and environmental restraint.

### I-HARM-1: Qur'an 5:32, Qur'an 2:205, and Qur'an 7:31

- Source class: primary Islamic scripture.
- Conventional citation: The Qur'an, 5:32, 2:205, and 7:31. Quran.com.
- Links: https://quran.com/5/32, https://quran.com/2/205,
  https://quran.com/7/31
- Used for: protection from harm, corruption, and excess.
- Not used for: authorizing broad autonomous intervention.
- Project use: Sword review, emergency limits, and harm containment.

### I-MAQASID-1: Mohammad Hashim Kamali, Maqasid Al-Shariah Made Simple

- Source class: secondary Islamic legal and ethical reference.
- Conventional citation: Kamali, Mohammad Hashim. *Maqasid Al-Shariah Made
  Simple*. International Institute of Islamic Thought.
- Link: https://iiit.org/wp-content/uploads/MaqasidAl-ShariahMadeSimple-UPDATED-RED.pdf
- Used for: maqasid language around protection of religion, life, intellect,
  lineage or family, and property.
- Not used for: claiming consensus on AI governance.
- Project use: risk review categories for life, mind, family, property, and
  spiritual practice.

### T-RFC-1: RFC 2119

- Source class: technical standard.
- Conventional citation: Bradner, Scott. "Key words for use in RFCs to Indicate
  Requirement Levels." RFC 2119. RFC Editor, March 1997.
- Link: https://www.rfc-editor.org/rfc/rfc2119
- Used for: requirement keywords such as MUST, SHOULD, and MAY.
- Not used for: the substance of any Golem Covenant requirement.
- Project use: conformance language.

### T-RFC-2: RFC 8174

- Source class: technical standard.
- Conventional citation: Leiba, Barry. "Ambiguity of Uppercase vs Lowercase in
  RFC 2119 Key Words." RFC 8174. RFC Editor, May 2017.
- Link: https://www.rfc-editor.org/rfc/rfc8174
- Used for: uppercase/lowercase clarification for RFC 2119 keywords.
- Not used for: the substance of any Golem Covenant requirement.
- Project use: conformance language.

### T-SCHEMA-1: JSON Schema Draft 2020-12

- Source class: technical specification.
- Conventional citation: JSON Schema. *JSON Schema: A Media Type for
  Describing JSON Documents*. Draft 2020-12.
- Link: https://json-schema.org/draft/2020-12/json-schema-core
- Used for: schema-validatable machine-readable manifests.
- Not used for: any specific moral or religious claim.
- Project use: `schema/golem.schema.json` and manifest validation.

### T-RISK-1: NIST AI Risk Management Framework 1.0

- Source class: AI governance framework.
- Conventional citation: National Institute of Standards and Technology.
  *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*. NIST AI
  100-1. January 2023.
- Link: https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10
- Used for: risk identification, measurement, management, monitoring,
  accountability, and human-centered design.
- Not used for: certification that this project satisfies NIST AI RMF.
- Project use: runtime and audit vocabulary.

### T-RISK-2: OECD AI Principles

- Source class: AI governance principles.
- Conventional citation: OECD. *OECD AI Principles*. Adopted 2019, updated
  2024.
- Link: https://www.oecd.org/en/topics/ai-principles.html
- Used for: human-centered values, transparency, robustness, accountability,
  and responsible stewardship.
- Not used for: certification or legal compliance.
- Project use: governance vocabulary and review posture.

### T-PUBLISH-1: GitHub Pages custom domains

- Source class: technical documentation.
- Conventional citation: GitHub Docs. "Managing a custom domain for your
  GitHub Pages site."
- Link: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- Used for: public site setup and custom-domain records.
- Not used for: covenant substance.
- Project use: hosting documentation.

### T-BOT-1: RFC 9309

- Source class: technical standard.
- Conventional citation: Koster, Martijn, et al. "Robots Exclusion Protocol."
  RFC 9309. RFC Editor, September 2022.
- Link: https://www.rfc-editor.org/rfc/rfc9309
- Used for: bot-facing publication conventions around `robots.txt`.
- Not used for: agent moral behavior or covenant conformance.
- Project use: crawler and bot-friendly discovery posture.

### T-BOT-2: llms.txt proposal

- Source class: publication and discovery proposal.
- Conventional citation: llms.txt proposal. https://llmstxt.org/.
- Link: https://llmstxt.org/
- Used for: bot-friendly entry point conventions.
- Not used for: normative agent behavior.
- Project use: `llms.txt` and agent discovery paths.

### A-SOUL-1: OpenClaw SOUL.md template

- Source class: agent identity file reference.
- Conventional citation: OpenClaw. "SOUL.md template."
- Link: https://docs.openclaw.ai/reference/templates/SOUL
- Used for: the SOUL.md genre as an agent identity, continuity, voice, and
  behavior file.
- Not used for: adopting personality-first agent design.
- Project use: adapting SOUL.md away from personality and toward covenantal
  restraint.

## Working synthesis

The project does not claim that Judaism, Christianity, and Islam say the same
thing. It claims that each tradition supplies a different guardrail against a
shared modern danger: unbounded delegated power.

Jewish emphasis: command, rest, boundary, emergency, revocation.

Christian emphasis: dignity, embodiment, common good, anti-Babel construction,
responsibility.

Islamic emphasis: trust, stewardship, balance, accountability, protection from
harm.

Technical emphasis: explicit requirements, machine validation, risk management,
monitoring, auditability, publication, and tested shutdown.
