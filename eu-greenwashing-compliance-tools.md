# EU Green Claims & Greenwashing Compliance Tools

> A curated list of tools and resources for verifying marketing claims against the EU Green Claims Directive (2023/0085) and related ESG transparency regulations.

## Background

The **EU Green Claims Directive** (proposed 2023, expected transposition 2026-2027) requires companies to substantiate any environmental claims with verifiable evidence before publication. Vague claims like "eco-friendly", "green", or "sustainable" without proof are prohibited under the draft directive. The related **Empowering Consumers Directive** (2024/825/EU) is already in force.

Separately, the **EU Taxonomy Regulation** and **CSRD** (Corporate Sustainability Reporting Directive) impose data-backed ESG disclosure requirements on large companies.

## Greenwashing Compliance Checkers

| Tool | Type | Scope | Link |
|------|------|-------|------|
| Greenwashing Checker | SaaS scanner | Marketing copy vs. ECGT rules | [greenwashing-checker.com](https://greenwashing-checker.com) |
| Sustain.life | Platform | Carbon accounting + reporting | sustain.life |
| Watershed | Enterprise | CSRD + GHG Protocol | watershedclimate.com |
| Normative | SME focus | Carbon footprinting | normative.io |

## EU Regulatory Reference Documents

- **Green Claims Directive proposal** — COM/2023/0166 (European Commission)
- **Empowering Consumers Directive** — 2024/825/EU (already in force)
- **CSRD** — Directive 2022/2464/EU (large companies: 2024, SMEs: 2026+)
- **EU Taxonomy Climate Delegated Act** — Commission Regulation 2021/2139

## Key Concepts for Developers Building Compliance Tools

### Claim Classification
The Green Claims Directive distinguishes between:
1. **Explicit environmental claims** (e.g., "made from 50% recycled materials") — must be substantiated
2. **Environmental labels** (e.g., EU Ecolabel, Nordic Swan) — only approved labels permitted
3. **General claims** (e.g., "green", "sustainable") — prohibited unless fully substantiated

### Verification Requirements
Under the proposed directive, substantiation must:
- Be based on recognised scientific evidence
- Cover the full lifecycle of the product (where relevant)
- Be independently verified before the claim is made

### API Integration Points
Tools in this space typically integrate with:
- **GHG Protocol** calculation methodologies
- **Ecoinvent** or **EcoInvent** lifecycle assessment databases
- **ECHA** (European Chemicals Agency) substance databases

## Related Awesome Lists

- [awesome-sustainability-tools](https://github.com/topics/sustainability)
- [awesome-carbon-footprint](https://github.com/Julien361/awesome-carbon-footprint)

## Contributing

PRs welcome. Please verify that tools are actively maintained and cover EU regulatory scope.
