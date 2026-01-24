# Phyllux Ecosystem Spine

This document defines the invariant "method spine" and establishes how repositories in the Phyllux ecosystem relate to each other.

## The Method Spine

The core invariant across all Phyllux repositories is:

**A geometric integration method using a shared phyllotactic angular parameter (137.508° golden angle) that provides non-periodic layout advantages.**

This spine:
- Is the protected core (may be subject to provisional patent application)
- Appears across multiple applications (neural interfaces, antennas, cryptography)
- Provides the unifying geometric principle
- Is not over-specified in public repositories (preserves future claim scope)

## Repository Roles

### phyllux-framework
**Role:** Governance, ethics, licensing, coordination surface

**Contains:**
- 4-tier licensing model
- Templates for prior art establishment
- Guides for IP protection
- Ethical framework
- Coordination mechanisms

**Does NOT contain:**
- Invention claims
- Embodiment descriptions
- Performance assertions
- Technical implementations

**Relationship:** Provides the framework that other repositories use

### biomimetic-inventions-public
**Role:** Canonical public prior art, reproducible demonstrations

**Contains:**
- Prior art disclosures for Phyllux Mesh, Wave, Vault, Core
- Technical demonstrations
- Reproducible examples
- Geometry and method illustrations

**Relationship:** Demonstrates framework implementation, establishes prior art

### phyllux-inventions-wip
**Role:** Generative invention laboratory, exploratory fusion space

**Contains:**
- Exploratory research outputs
- Supporting disclosure (not claimed embodiments)
- Generative invention concepts
- Research-stage documentation

**Relationship:** Explores applications of the method spine, generates new concepts

## How Repositories Relate

### Without Contradiction

Repositories support each other without competing:

1. **Framework defines structure** → Other repos use it
2. **Public repo establishes prior art** → Protects method spine
3. **WIP repo explores applications** → Generates new possibilities
4. **All reference the method spine** → Maintain consistency

### Maturity Progression

Content may progress through repositories:

1. **WIP:** Exploratory concept (Conceptual/Simulated)
2. **Public:** Prior art establishment (Structural/Candidate)
3. **Formal Filing:** Provisional patent application (if pursued)

### Linking Conventions

**Internal links (within repo):**
- Use relative paths: `[text](../path/to/file.md)`
- Verify links exist before committing

**Cross-repo links:**
- Use full GitHub URLs: `https://github.com/phibronotchi-beep/repo-name`
- Stable and accessible
- Appropriate for external references

**Canonical references:**
- Framework tier definitions: Link to `TEMPLATES/TEMPLATE_License_4Tier.md`
- Prior art strategy: Link to `phyllux-seed/prior-art-strategy.md`
- Disclosure framework: Link to `DISCLOSURE.md` (this repo or cross-repo)

## Maturity Tagging Rules

All content should indicate maturity level:

**Format:** `[Maturity: Conceptual|Derived|Simulated|Structural|Candidate]`

**Placement:**
- Near top of document
- In metadata if using frontmatter
- In image captions for visual content

**Examples:**
- `[Maturity: Conceptual]` - Early idea
- `[Maturity: Simulated]` - Simulation results
- `[Maturity: Structural]` - Defined implementation
- `[Maturity: Candidate]` - Ready for formalization

## Image Role Labeling

All images should indicate their role:

**Format:** `[Image Role: Concept Art|Placeholder|Structural Diagram|Reproducible Figure]`

**Placement:**
- In image caption
- In alt text
- In surrounding text

## Consistency Requirements

### Terminology
- Use consistent tier names: Tier 1 (Pioneer), Tier 2 (Mission-Aligned), Tier 3 (Commercial), Tier 4 (Free)
- Use consistent maturity labels
- Use consistent image role labels

### Language
- Neutral, technical tone
- No hype or promotional language
- Appropriate disclaimers
- Research-stage language where applicable

### Claims
- No unqualified performance claims
- No absolute security guarantees
- No medical advice
- Exploratory language for theoretical work

## Future Freedom

The spine and repository structure are designed to:

- **Preserve future claim scope** - Don't over-specify in public repos
- **Enable research** - Open sharing of concepts and methods
- **Support formalization** - Repos support but don't compete with PPA
- **Maintain flexibility** - Structure allows evolution without breaking

## Updates to This Document

This document should be updated when:
- New repositories are added to the ecosystem
- Repository roles evolve
- Linking conventions change
- Maturity tagging system is refined

**Changes should maintain the invariant method spine and preserve future freedom.**

---

**Last Updated:** January 2026  
**Status:** Living document - update as ecosystem evolves
