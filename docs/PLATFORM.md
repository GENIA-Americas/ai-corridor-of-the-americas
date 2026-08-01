# The Platform: Glápagos AI DevOps

Glápagos is the technology backbone of the AI Corridor of the Americas. Where [MANIFESTO.md](MANIFESTO.md) makes the case for why regional AI infrastructure matters and [POLICY.md](POLICY.md) covers the legislative track, this document covers the actual platform: what it is, what it's built from, and where the code lives.

## What it is

Glápagos is described by its own team as an AI DevOps and data orchestration platform, purpose-built for organizations operating across North, Central, and South America. The stated positioning is a direct contrast with general-purpose global platforms like Azure AI or AWS SageMaker: instead of a one-size-fits-all deployment target, Glápagos is built around multi-jurisdiction compliance, cross-border data pipelines, and AI models tuned to regional industry contexts. It is currently deployed across 12+ regions in the hemisphere.

It's described as **modular and open-source** — meaning organizations integrate the pieces they need into existing systems rather than adopting a single monolithic platform.

## The three capability areas

Glápagos organizes its offering into three named areas:

**Predict.** Machine learning deployment — turning an organization's existing data into operational decisions, rather than a research exercise that never reaches production.

**Build.** Data pipeline engineering — the infrastructure work of getting data flowing reliably across systems, which is the unglamorous prerequisite for everything else on this list.

**Connect.** Cross-team and cross-region collaboration tooling — the layer that lets teams in different countries, working under different regulatory regimes, operate against the same underlying platform.

This maps directly to the three-pillar argument in the main [README](../README.md): Build is the data pillar, Predict is where that data becomes usable talent-facing tooling, and Connect is the coordination layer the AI Corridor itself depends on.

## Where the code lives

| Component | Repository | Language | License |
|---|---|---|---|
| Platform backend | [Glapagos-Backend](https://github.com/GENIA-Americas/Glapagos-Backend) | Python | MIT |
| Federated research layer | [multimodal-ai-americas](https://github.com/GENIA-Americas/multimodal-ai-americas) | — | Apache-2.0 |
| Applied deployment example | [ciudadania-backend](https://github.com/GENIA-Americas/ciudadania-backend) (CiudadanIA project) | — | AGPL-3.0 |

If you want to see the platform rather than read about it, the fastest path is to clone `Glapagos-Backend` and read its own README — that repository, not this one, is the source of truth for setup instructions, dependencies, and current architecture. This document gives you context; it deliberately doesn't duplicate technical documentation that belongs closer to the code.

## Rollout model

Per Glápagos's own materials, engagement starts with a pilot: identify one specific operational bottleneck, prove impact in a small deployment, then scale. That's consistent with the "execution over hype" posture referenced elsewhere in this repository — the platform is positioned as something you pilot against a real problem, not something you adopt wholesale on faith.

There is also a public early-stage prototype referred to as **GLAPP**, linked from Glápagos's own site. If you're evaluating the platform, ask the team directly for current access rather than relying on this document, prototypes move fast and this repo won't always be current on that front.

## What's accurate here vs. what to verify directly

This document reflects what Glápagos publishes about itself publicly. Two things worth confirming directly with the team before you rely on them for a technical decision:
- Current architecture details beyond what's in the `Glapagos-Backend` repository's own README
- Specific compliance certifications implied by "multi-jurisdiction compliance" — a public claim of compliance orientation is not the same as a specific, current certification, and we'd rather point you to ask than overstate it here.

Contact: [admin@genia.ai](mailto:admin@genia.ai)
