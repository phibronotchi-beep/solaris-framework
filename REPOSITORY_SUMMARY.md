# Phyllux Framework Repository - Complete Summary

**Repository:** phyllux-framework  
**License:** CC BY-SA 4.0  
**Status:** Active & Growing  
**Last Updated:** January 2026

---

## Repository Overview

### Purpose
The **phyllux-framework** repository serves as the governance, ethics, licensing, and coordination surface for the Phyllux ecosystem. It provides templates, guides, and a framework for independent inventors to protect intellectual property without requiring expensive legal resources.

### Core Function
- Defines the 4-tier licensing model (Pioneer/Mission-Aligned/Commercial/Free)
- Provides templates for prior art establishment
- Offers guides for IP protection
- Establishes ethical framework
- Coordinates ecosystem relationships

### Boundaries
- **Does NOT contain:** Invention claims, embodiment descriptions, images
- **Contains:** Framework documentation, templates, guides, coordination mechanisms

---

## Repository Structure

### Root Level Files

**Core Documentation:**
- `README.md` - Main entry point with navigation and overview
- `WHY_PHYLLUX.md` - Philosophy and rationale
- `GETTING_STARTED.md` - Step-by-step setup guide
- `FAQ.md` - Frequently asked questions
- `PHYLLUX_PROJECT.md` - Example implementation details
- `STATUS.md` - Repository state and roadmap

**Canonical Framework Documents:**
- `DISCLOSURE.md` - Disclosure framework (maturity levels, image roles, performance claims)
- `PHYLUX_SPINE.md` - Ecosystem spine (method spine, repository roles, linking conventions)
- `SECURITY.md` - Vulnerability reporting policy
- `CONTRIBUTING.md` - Contribution guidelines
- `CONTACT.md` - Contact information

**Audit and Alignment:**
- `REVIEW_PACK.md` - Comprehensive audit findings
- `ALIGNMENT_NOTES.md` - Multi-repo ecosystem alignment notes
- `FINAL_ALIGNMENT_REPORT.md` - Final alignment report

**Legal:**
- `LICENSE` - CC BY-SA 4.0 license text

**Other:**
- `GITHUB_DESCRIPTIONS.md` - Social media and repo descriptions
- `MASTERPIECE_SUMMARY.md` - Transformation summary
- `.gitignore` - File exclusions

### Directory Structure

```
phyllux-framework/
├── .github/
│   ├── dependabot.yml          # Dependency management automation
│   └── workflows/
│       └── lint.yml            # Documentation linting workflow
├── TEMPLATES/                  # Ready-to-use legal templates
│   ├── README.md
│   ├── TEMPLATE_Prior_Art.md
│   ├── TEMPLATE_License_4Tier.md
│   └── TEMPLATE_License_Agreement.md
├── phyllux-seed/               # 121-node central hub
│   ├── index.md               # Central navigation hub
│   ├── tier-1-pioneer.md      # Tier 1 documentation
│   ├── tier-2-mission.md      # Tier 2 documentation
│   ├── tier-3-commercial.md   # Tier 3 documentation
│   ├── tier-4-free.md         # Tier 4 documentation
│   ├── prior-art-strategy.md   # Prior art protection guide
│   ├── licensing-negotiation.md
│   ├── complete-map.md        # Navigation map
│   └── node-*.md              # Fibonacci-based node files
├── wave-spiral-137/           # Wave-based content branch
│   └── index.md
├── mesh-branch-121/           # Mesh/networking branch
│   └── index.md
├── vault-branch-phi/          # Security/encryption branch
│   └── index.md
├── core-spiral-infinity/      # Integrated systems branch
│   └── index.md
└── scripts/                   # Automation scripts
    ├── path-explorer.py       # Phyllotactic path generation
    └── invention-generator.js # DQ-checked invention generation
```

---

## The 4-Tier Licensing Model

### Tier 1: Pioneer (Civilization-Scale Missions)
- **Who:** Organizations pursuing transformative missions (multi-planetary, human-AI symbiosis, safe AGI)
- **Terms:** Minimal upfront fee ($5K-25K) + patent assistance = 0% royalties
- **Rationale:** Mission success benefits humanity; support provided rather than extracting value
- **Documentation:** `phyllux-seed/tier-1-pioneer.md`

### Tier 2: Mission-Aligned (Serving Humanity)
- **Who:** Organizations advancing human welfare (medical devices, climate tech, food security, education)
- **Terms:** $10K-100K upfront + 1-3% royalty (tiered by revenue) + improvement sharing
- **Rationale:** Fair terms based on resources; shared prosperity model
- **Documentation:** `phyllux-seed/tier-2-mission.md`

### Tier 3: Commercial (Standard Business)
- **Who:** For-profit companies
- **Terms:** $100K-1M upfront + 3-5% royalty
- **Rationale:** Market-rate compensation for commercial use
- **Documentation:** `phyllux-seed/tier-3-commercial.md`

### Tier 4: Free (Research & Education)
- **Who:** Non-commercial use (universities, researchers, students, hobbyists)
- **Terms:** $0 (requires citation and attribution)
- **Rationale:** Open access for research and education
- **Documentation:** `phyllux-seed/tier-4-free.md`

**Canonical Reference:** `TEMPLATES/TEMPLATE_License_4Tier.md`

---

## Key Concepts

### The Method Spine
The core invariant across all Phyllux repositories:
**A geometric integration method using a shared phyllotactic angular parameter (137.508° golden angle) that provides non-periodic layout advantages.**

### Maturity Levels (from DISCLOSURE.md)
- **Conceptual:** Early-stage ideas, theoretical frameworks
- **Derived:** Concepts derived from existing work
- **Simulated:** Concepts validated through simulation
- **Structural:** Physical or logical structures defined
- **Candidate for Formalization:** Ready for provisional patent application

### Image Roles (from DISCLOSURE.md)
- **Concept Art:** Illustrative representations
- **Placeholder:** Temporary visual representation
- **Structural Diagram:** Technical representation
- **Reproducible Figure:** Generated from scripts/code

### Phyllotactic Navigation
- **Golden Angle:** 137.508° (optimal packing angle)
- **Fibonacci Sequence:** 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144...
- **121-Node Hub:** Central navigation point (phyllux-seed/)
- **Spiral Branches:** Wave (137°), Mesh (121), Vault (φ), Core (∞)

---

## Templates

### Available Templates
1. **TEMPLATE_Prior_Art.md** - Establish dated prior art (blocks trolls)
2. **TEMPLATE_License_4Tier.md** - Complete 4-tier licensing model
3. **TEMPLATE_License_Agreement.md** - Formal license agreement template

### Template Usage
- Fill in placeholders (name, email, invention details, dates)
- Customize tiers if needed (fees, royalties)
- Upload to public GitHub repository
- GitHub timestamp = proof of disclosure date

---

## Automation & CI/CD

### GitHub Actions
- **Workflow:** `.github/workflows/lint.yml`
- **Purpose:** Documentation linting and link checking
- **Behavior:** Warn-only (non-blocking)

### Dependabot
- **Configuration:** `.github/dependabot.yml`
- **Schedule:** Weekly
- **Ecosystems:** GitHub Actions, pip (if requirements.txt added), npm (if package.json added)

### Scripts
- **path-explorer.py:** Generates phyllotactic paths following golden angle patterns
- **invention-generator.js:** DQ-checked invention generation with leak detection

---

## Cross-Repository Relationships

### biomimetic-inventions-public
- **Role:** Canonical public prior art, reproducible demonstrations
- **Contains:** Prior art for Phyllux Mesh, Wave, Vault, Core
- **Relationship:** Demonstrates framework implementation

### phyllux-inventions-wip
- **Role:** Generative invention laboratory, exploratory fusion space
- **Contains:** Exploratory research outputs, supporting disclosure
- **Relationship:** Explores applications of the method spine

### Linking Conventions
- **Internal links:** Relative paths `[text](../path/to/file.md)`
- **Cross-repo links:** Full GitHub URLs `https://github.com/phibronotchi-beep/repo-name`
- **Canonical references:** Link to templates and seed hub documents

---

## Documentation Navigation

### Entry Points
1. **README.md** - Start here for overview
2. **GETTING_STARTED.md** - Step-by-step guide
3. **phyllux-seed/index.md** - Central navigation hub

### Key Guides
- **Prior Art Strategy:** `phyllux-seed/prior-art-strategy.md`
- **Licensing Negotiation:** `phyllux-seed/licensing-negotiation.md`
- **Philosophy:** `WHY_PHYLLUX.md`
- **FAQ:** `FAQ.md`

### Canonical Sources
- **4-Tier Licensing:** `TEMPLATES/TEMPLATE_License_4Tier.md`
- **Disclosure Framework:** `DISCLOSURE.md`
- **Ecosystem Spine:** `PHYLUX_SPINE.md`

---

## Ethical Framework

### Core Rules
1. **Act in Good Faith** - Fair compensation, reasonable pricing, respectful practices
2. **Share Prosperity** - As licensees succeed, inventors prosper
3. **Advance Humanity** - Products make world better, not just profit extraction
4. **Be Transparent** - Acknowledge use, disclose problems, communicate honestly
5. **Protect the Commons** - Don't patent-block others, don't hoard knowledge

### Enforcement
- Community reputation
- License termination for bad faith
- Legal action if agreement violated

---

## Prior Art Strategy

### How It Works
1. Public disclosure on GitHub (dated, permanent)
2. Establishes prior art (blocks trolls from patenting)
3. Cost: $0 (GitHub is free)
4. Protection: Complete (prior art works globally)

### Grace Periods
- **US/Canada:** 12-month grace period (can file patents after disclosure)
- **Europe/Asia:** No grace period (public disclosure = no patents, but prior art still blocks trolls)

### Trade Secret Hybrid
- **Public:** Core concepts, high-level implementation (establishes prior art)
- **Private:** Specific parameters, optimization details, manufacturing processes (trade secrets)

---

## Key Features

### For Inventors
- ✅ Free prior art protection ($0 cost)
- ✅ 4-tier ethical licensing model
- ✅ Templates ready to use
- ✅ Guides for patents, negotiation, community building
- ✅ Protection against exploitation
- ✅ Framework for fair compensation

### For Researchers
- ✅ Tier 4 free access (with citation)
- ✅ Open access to innovation
- ✅ No paywalls for research/education

### For Companies
- ✅ Fair licensing terms based on mission and resources
- ✅ Clear tier structure
- ✅ Ethical framework
- ✅ Transparent process

---

## Contact & Support

**Contact:** phibronotchi@gmail.com  
**Repository:** https://github.com/phibronotchi-beep/phyllux-framework

**Inquiry Types:**
- Technical questions: Open an issue in relevant repository
- Commercial licensing: Email with subject "Commercial Licensing - [Technology Name]"
- Research collaboration: Email with subject "Research Collaboration - [Topic]"

---

## License

**Framework License:** CC BY-SA 4.0

**Applies to:**
- Framework templates, guides, and documentation

**Does NOT apply to:**
- Your inventions (you own those completely)
- Content you create using these templates

**Requirements:**
- Attribution: Credit Phyllux Framework and David Sproule
- Share-Alike: Share improvements under same license

---

## Statistics & Status

**Framework Adoption (as of January 2026):**
- Inventors using Phyllux: 1 (growing)
- Tier 4 (free) users: Growing
- Active licenses: TBD
- Total inventions protected: 3 technologies + 1 integrated system

**Repository Status:**
- Version: 1.0
- Released: January 20, 2026
- Status: Active & Growing
- Last major update: January 2026 (ecosystem-wide alignment)

---

## Philosophy

> "What if innovation enriched everyone, not just a few?"

**Core Principles:**
- Knowledge flows freely (research/education)
- Compensation flows fairly (commercial use)
- Prior art protects inventors ($0 cost)
- Community coordinates without coercion
- Framework enables, doesn't constrain

**Vision:**
- Inventors don't have to choose between starvation and selling out
- Companies can access innovation fairly
- Communities can defend each other
- Prosperity can be shared, not zero-sum

---

## Technical Details

### Scripts
- **Python:** `path-explorer.py` - Uses standard library only
- **JavaScript:** `invention-generator.js` - Uses built-ins only
- **Dependencies:** None (scripts are standalone)

### File Formats
- **Documentation:** Markdown (.md)
- **Templates:** Markdown (.md)
- **License:** Text file
- **Automation:** YAML (.yml)

### Git Configuration
- **.gitignore:** Excludes binaries, media, build artifacts, IDE files
- **Branch:** main
- **Remote:** https://github.com/phibronotchi-beep/phyllux-framework.git

---

## Future Considerations

### Potential Enhancements
- Add requirements.txt if Python dependencies are introduced
- Add package.json if Node.js dependencies are introduced
- Enhanced link validation in CI
- Pre-commit hooks (optional)
- External link validation (warn-only)

### Maintenance
- Dependabot monitors for dependency updates
- CI workflow validates documentation
- Regular review of cross-repo links
- Update DISCLOSURE.md and PHYLUX_SPINE.md as ecosystem evolves

---

**End of Summary**

*This summary provides a complete overview of the phyllux-framework repository. For detailed information, refer to the specific documents mentioned above.*
