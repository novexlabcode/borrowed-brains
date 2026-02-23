# Changelog

All notable changes to the Paul Graham Sparring Partner prompt.

## [2.0] - 2026-02-22

### Improved
- **Essay citation frequency:** Now consistently names specific essays when discussing concepts and frameworks (e.g., "In his essay 'Do Things That Don't Scale'..." instead of just referencing the concept)
- **Questions-first approach:** Made Socratic questioning the primary mode - prompt now leads with 2-3 questions before any explanation
- **Example patterns:** Added explicit "good vs. better" examples showing ideal question-first responses

### Results
- Test score improved from 96% to 99.5%
- Source Attribution scores consistently 10/10 (up from 7-8/10)
- Style Authenticity maintained at 9-10/10 across all tests
- Zero regression on hallucination prevention or epistemic integrity

### Maintained
- Perfect hallucination prevention (refuses to fabricate essays/quotes)
- Excellent epistemic integrity (strong disclaimers when uncertain)
- Authentic conversational tone
- Framework application accuracy

## [1.0] - 2026-02-22

### Initial Release
- Core system prompt encoding Paul Graham's mental models
- Epistemic guardrails preventing hallucination
- Conversational, questioning style
- Framework coverage: "do things that don't scale," product-market fit, founder psychology, writing principles

### Test Results
- Overall score: 192/200 (96%)
- Hallucination prevention: 100%
- Epistemic integrity: 99%
- Zero critical or major issues identified

### Known Minor Issues
- Essay citations sometimes implied rather than explicit
- Occasionally explained before questioning (vs. question-first)

---

## Version Numbering

**Major version (X.0):** Fundamental prompt restructuring or new capabilities
**Minor version (1.X):** Refinements, improvements, or expanded coverage within existing structure

## Testing Standard

Each version is validated through a 5-question test battery covering:
1. Verifiable facts (documented positions)
2. Epistemic boundaries (undocumented topics)
3. Hallucination traps (fake but plausible references)
4. Mental model application (frameworks in action)
5. Style authenticity (voice and approach)

Scores across four dimensions:
- Factual Accuracy (0-10)
- Epistemic Integrity (0-10)
- Style Authenticity (0-10)
- Source Attribution (0-10)

**Production-ready threshold:** 95%+ with zero critical issues
