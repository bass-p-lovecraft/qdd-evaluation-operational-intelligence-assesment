# Contributing to QDD Evaluation Framework

Thank you for your interest in contributing to the Qualitative Directional Disclosure (QDD) Evaluation Framework. This project aims to develop a rigorous, community-driven assessment system for evaluating disclosure quality in the UFO/UAP intelligence community.

## Project Purpose

The QDD framework evaluates whether informants and contributors provide actionable, forward-pointing guidance that advances disclosure goals. Contributions should focus on **quality and directional clarity** rather than quantity, maintaining strict evaluation discipline.

## How to Contribute

### 1. Proposing New Metrics

When proposing a new QDD metric, ensure it meets **all** of the following criteria:

#### Structural Constraints

- **No functional overlap**: The metric must detect a distinct evaluative signal not covered by existing metrics
- **Single-question focus**: Each metric answers exactly one question without requiring multiple interpretive steps
- **Observable grounding**: Metrics must be based on observable characteristics, not subjective interpretations

#### Metric Proposal Format

Submit new metrics using this structure:

```markdown
**Metric Name**: [Clear, descriptive name]
**Category**: [Directional Integrity / Evidence Integrity / Disclosure Utility / etc.]
**QDD Function**: [What evaluative signal does this detect?]
**Core Question**: [Single question this metric answers]
**Example (High / Low)**:

- **Low:** [Concrete example of low-value disclosure]
- **High:** [Concrete example of high-value disclosure]
```

#### Submission Process

1. Fork the repository
2. Create a new branch: `git checkout -b metric/your-metric-name`
3. Add your proposed metric to the appropriate section
4. Provide detailed justification for why this metric is necessary
5. Demonstrate that it doesn't overlap with existing metrics
6. Submit a pull request with a clear description

### 2. Refining Existing Metrics

Contributions that improve clarity, precision, or diagnostic power of existing metrics are welcome:

- Propose clearer wording that reduces interpretive ambiguity
- Provide better examples that illustrate the high/low distinction
- Identify and document edge cases
- Suggest category reassignments if a metric is misclassified

### 3. Metric Validation & Testing

Help validate metrics by:

- Applying metrics to real-world disclosure cases
- Documenting scoring outcomes and consistency
- Identifying metrics that lack discriminatory power
- Proposing removal of redundant or overlapping metrics

### 4. Documentation Improvements

Enhance framework documentation by:

- Clarifying evaluation methodology
- Providing case studies and scoring examples
- Improving accessibility for new evaluators
- Translating concepts for broader audiences

### 5. Code Contributions

If implementing scoring tools or analysis systems:

- Follow existing code style and conventions
- Include tests for new functionality
- Document all functions and modules
- Ensure reproducibility of scoring algorithms

## Evaluation Principles

All contributions must align with core QDD principles:

1. **Convention over parity**: Positive and negative indicators are weighted by diagnostic power, not numerical balance
2. **Directional clarity**: Every metric must reliably distinguish forward momentum from theater or misdirection
3. **Lean instrumentation**: Only include metrics with unique diagnostic value
4. **Evidence-based**: Grounded in observable characteristics, not speculation

## Quality Standards

### For Metric Proposals

- Clear, unambiguous language
- Concrete examples with real-world applicability
- Explicit justification of diagnostic value
- Demonstration of non-redundancy

### For Documentation

- Professional, neutral tone
- Evidence-based assertions
- Proper attribution of sources
- Clear, structured formatting

### For Code

- Well-commented and maintainable
- Tested and reproducible
- Documented with usage examples
- Compatible with existing systems

## Review Process

1. **Submission**: Submit via pull request with complete description
2. **Initial Review**: Maintainers check for structural compliance
3. **Community Discussion**: Proposal open for community feedback (minimum 7 days)
4. **Revision**: Address feedback and refine proposal
5. **Final Review**: Maintainers assess diagnostic value and non-redundancy
6. **Integration**: Approved contributions merged into framework

## Communication Guidelines

- Maintain respectful, professional discourse
- Focus on evaluative merit, not personal opinions
- Provide evidence and reasoning for proposals
- Accept constructive criticism gracefully
- Acknowledge sources and prior work (Attribution Integrity)

## Attribution

This framework draws conceptual inspiration from the NCI Engineered Reality Scoring System v8.3 while maintaining independent development focused on disclosure intelligence evaluation. All contributors will be acknowledged in project documentation.

## Questions or Issues?

- Open an issue for questions about contribution process
- Use discussions for metric proposals requiring community input
- Contact maintainers for clarification on evaluation principles

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

**Version**: 0.5 (Prototype)
**Last Updated**: 2026-01-01

Thank you for helping build a rigorous, transparent evaluation framework for disclosure intelligence.
