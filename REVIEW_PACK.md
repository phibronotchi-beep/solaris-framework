# 🔍 PHYLLUX-FRAMEWORK REVIEW PACK

**Date:** January 2026  
**Repository:** phyllux-framework  
**Scope:** Comprehensive hardening and alignment audit

---

## A) REPOSITORY ROLE SUMMARY

**phyllux-framework** serves as the governance, ethics, licensing, and coordination surface for the Phyllux ecosystem. It defines the 4-tier licensing model, provides templates for prior art establishment, offers guides for IP protection, and establishes the ethical framework. This repository does NOT contain invention claims or embodiment descriptions—it is purely a framework and coordination mechanism. It references other repositories (biomimetic-inventions-public, phyllux-inventions-wip) as examples but maintains clear boundaries.

---

## B) FINDINGS

### 1) Secrets & Credentials Hygiene

**Status:** ✅ CLEAN

**Findings:**
- No API keys, tokens, or hardcoded credentials found
- No .env files present
- No .bat or .sh scripts with embedded secrets
- Scripts (invention-generator.js, path-explorer.py) contain only constants (golden angle, Fibonacci sequence)
- Email addresses present (phibronotchi@gmail.com) - appropriate for contact purposes
- No private key formats detected

**Risk Level:** LOW

**Action Required:** None

---

### 2) Dependency & Supply Chain

**Status:** ⚠️ MINIMAL DEPENDENCY MANAGEMENT

**Findings:**
- No requirements.txt or package.json found
- Scripts use standard library only (Python stdlib, Node.js built-ins)
- No external dependencies declared
- No lockfiles present
- No GitHub Actions workflows (no CI/CD automation)
- No Dependabot configuration

**Risk Level:** LOW (current scripts are dependency-free, but future additions may need management)

**Action Required:**
- Add .github/dependabot.yml for future dependency management
- Consider adding requirements.txt if Python dependencies are added
- Consider adding package.json if Node.js dependencies are added

---

### 3) Licensing Consistency

**Status:** ✅ CONSISTENT

**Findings:**
- Single LICENSE file present (CC BY-SA 4.0)
- License clearly states it applies to framework templates/docs only
- No conflicting license declarations found
- License headers not present in individual files (acceptable for documentation repo)
- Badge in README matches LICENSE file

**Risk Level:** LOW

**Action Required:**
- Consider adding license header comments to script files for clarity
- No changes required to LICENSE file

---

### 4) Disclosure & Claim Language

**Status:** ⚠️ SOME LANGUAGE NEEDS SOFTENING

**Findings:**
- "Quantum-resistant" language found in:
  - PHYLLUX_PROJECT.md (line 19): "Quantum-resistant encryption"
  - vault-branch-phi/index.md: References to quantum-resistant crypto
  - STATUS.md: "Quantum-resistant cryptography"
  - GITHUB_DESCRIPTIONS.md: Multiple references
- Performance language found:
  - "Proven technology" in FAQ.md (line 133)
  - "Performance benchmarks" in PHYLLUX_PROJECT.md (line 200)
  - ">20% performance gain" in tier documents (improvement sharing threshold)
- No medical/implant implication risks detected
- No company-specific targeting language found
- Appropriate disclaimers present ("research-stage", "simulations suggest")

**Risk Level:** MEDIUM (quantum-resistant claims need context; performance language is mostly appropriate)

**Action Required:**
- Soften "quantum-resistant" to "explores quantum resistance" or "aims for quantum resistance" in documentation (NOT in PPA text)
- Ensure DISCLOSURE.md clarifies status of claims
- Review performance language for appropriate hedging

---

### 5) Link Rot & Cross-Repo Navigation

**Status:** ✅ MOSTLY STABLE

**Findings:**
- Internal links: All relative paths appear valid
- External links to other repos use full GitHub URLs (stable)
- References to LEGAL/ and COMMUNITY/ directories in README.md - need verification these exist
- References to GUIDES/ directory in README.md - need verification
- No broken internal links detected in accessible files
- External links to creativecommons.org (stable)
- Links to GitHub repos (stable)

**Risk Level:** LOW (but some referenced directories may not exist)

**Action Required:**
- Verify existence of LEGAL/, COMMUNITY/, GUIDES/ directories
- If missing, either create placeholder structure or remove references
- Consider adding link validation to CI/CD

---

### 6) Repo Hygiene

**Status:** ✅ GOOD, WITH MINOR IMPROVEMENTS NEEDED

**Findings:**
- .gitignore present and comprehensive (excludes binaries, media, build artifacts)
- No large binaries detected in tracked files
- No duplicate files detected
- Naming conventions consistent (kebab-case for directories, PascalCase for some docs)
- Scripts are functional and well-documented
- Some temporary files present (STOP_GREEN_LIGHT.md, COMMIT_FIX_GUIDE.md, QUICK_COMMIT_FIX.md) - consider archiving or removing
- ALIGNMENT_NOTES.md present (useful, should keep)

**Risk Level:** LOW

**Action Required:**
- Consider removing or archiving temporary troubleshooting files
- Verify no large files slipped through .gitignore
- Consider adding .github/ directory structure for automation

---

### 7) CI/Automation Readiness

**Status:** ⚠️ NO AUTOMATION PRESENT

**Findings:**
- No .github/ directory exists
- No GitHub Actions workflows
- No pre-commit hooks
- No automated link checking
- No markdown linting
- Scripts exist but are not integrated into automation

**Risk Level:** LOW (framework repo doesn't require heavy automation, but basic checks would help)

**Action Required:**
- Add .github/workflows/ for basic validation
- Add markdown linting (warn, not fail)
- Add internal link checking (warn, not fail)
- Consider pre-commit hooks for basic checks

---

## C) RISKS

### LOW RISK
- Dependency management (scripts are currently dependency-free)
- Secrets/credentials (none found)
- Licensing (consistent)
- Link rot (mostly stable external links)
- Repo hygiene (good state)

### MEDIUM RISK
- **Claim language:** "Quantum-resistant" assertions need softening in docs
- **Missing directories:** README references LEGAL/, COMMUNITY/, GUIDES/ that may not exist
- **No automation:** Basic validation would improve maintainability

### HIGH RISK
- None identified

---

## D) PROPOSED CHANGES

### Files to ADD:

1. **SECURITY.md** (new)
   - Vulnerability reporting instructions
   - Contact information
   - No legal tone, no hype

2. **CONTRIBUTING.md** (new)
   - Minimal guidelines
   - Reference repo role and boundaries
   - Contribution process

3. **DISCLOSURE.md** (new, canonical)
   - Conceptual vs derived vs simulated vs structural vs candidate definitions
   - Image role labeling (placeholder/concept art/diagram)
   - Public disclosure intent (non-legal framing)
   - "Openly shared research concepts and methods" language
   - Explicit: no guarantees, no performance claims unless measured/cited

4. **PHYLUX_SPINE.md** (new, canonical)
   - Invariant "method spine"
   - Roles of each repo
   - How repos relate without contradicting
   - Maturity tagging rules
   - Linking conventions

5. **.github/dependabot.yml** (new)
   - Weekly schedule
   - Future-proofing for dependencies

6. **.github/workflows/lint.yml** (new)
   - Markdown linting (warn only)
   - Internal link checking (warn only)
   - Low-noise, non-blocking

### Files to MODIFY:

1. **README.md**
   - Add small links to SECURITY.md, CONTRIBUTING.md, DISCLOSURE.md, PHYLUX_SPINE.md near top
   - Verify/remove references to non-existent directories (LEGAL/, COMMUNITY/, GUIDES/)

2. **PHYLLUX_PROJECT.md**
   - Soften "quantum-resistant" to "explores quantum resistance" or "aims for quantum resistance" (if not in PPA text)

3. **vault-branch-phi/index.md**
   - Review and soften quantum-resistant language if present

4. **STATUS.md**
   - Review quantum-resistant language

5. **GITHUB_DESCRIPTIONS.md**
   - Review quantum-resistant language (if used for external promotion)

### Files to REMOVE/ARCHIVE (optional):

1. **STOP_GREEN_LIGHT.md** - Temporary troubleshooting guide
2. **COMMIT_FIX_GUIDE.md** - Temporary troubleshooting guide
3. **QUICK_COMMIT_FIX.md** - Temporary troubleshooting guide

**Note:** These can be kept if useful for future reference, but consider moving to .github/ or docs/archive/

---

## E) WHAT I WILL NOT CHANGE

### Safety Boundaries:

1. **NO deletion of repositories or directories**
2. **NO removal of prior art or legal documents**
3. **NO weakening of disclaimers**
4. **NO invention of results, benchmarks, or performance claims**
5. **NO replacement of existing content (only additive)**
6. **NO modification of LICENSE file**
7. **NO changes to PPA-related text (if any exists)**
8. **NO changes to core framework philosophy**
9. **NO modification of tier definitions (only add canonical references)**
10. **NO changes to cross-repo links (they are appropriate as external URLs)**

### Content Preservation:

- All existing documentation preserved
- All templates preserved
- All scripts preserved
- All cross-references preserved
- All philosophical content preserved
- All tier definitions preserved

---

## F) ADDITIONAL OBSERVATIONS

### Strengths:
- Clear repository role and boundaries
- Well-organized structure
- Comprehensive .gitignore
- Good cross-repo linking
- Appropriate license clarity
- No security issues

### Areas for Improvement:
- Add missing canonical documentation (DISCLOSURE.md, PHYLUX_SPINE.md)
- Add basic automation for maintainability
- Soften claim language where appropriate
- Verify referenced directory structure
- Consider archiving temporary files

### Ecosystem Alignment:
- References to biomimetic-inventions-public are appropriate
- References to phyllux-inventions-wip are appropriate
- Framework maintains clear boundaries (no invention claims)
- Licensing model is well-defined and consistent

---

**Next Steps:** Proceed to Phase 2 (Additive Safety Layer) after user review of this pack.

---

*This review pack is a living document. Update as findings are addressed.*
