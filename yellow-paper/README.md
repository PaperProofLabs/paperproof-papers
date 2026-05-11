# PaperProof Yellow Paper

This directory contains the LaTeX version of the formal PaperProof protocol
yellow paper.

## Purpose

The yellow paper should be the protocol specification. It should define the
core objects, state transitions, event model, validation rules, governance
logic, indexing rules, deployment manifest expectations, and SDK-facing
contracts with enough precision for developers, auditors, and indexer builders.

## Copyright and Use

The LaTeX yellow paper includes a dedicated copyright and use notice. In short,
it is published for review, citation, education, auditing, SDK development,
indexing, and integration with official PaperProof Protocol deployments. It does
not grant trademark rights, official deployment identity, permission to imply
endorsement, or a license to copy contract source code beyond the licenses that
apply to those separate materials.

## Target Audience

- Smart contract auditors.
- SDK maintainers.
- Indexer builders.
- Advanced frontend developers.
- Protocol contributors.
- Ecosystem reviewers who need implementation-level clarity.

## Files

- `paperproof-yellow-paper.tex` - main LaTeX source.

## Build

Compile with `pdflatex`:

```powershell
pdflatex -interaction=nonstopmode paperproof-yellow-paper.tex
pdflatex -interaction=nonstopmode paperproof-yellow-paper.tex
```

No BibTeX pass is currently required. Source-derived references are listed in
the final section.

## Structure

1. Notation and Terminology
2. Protocol Object Inventory
3. Deployment Manifest
4. Artifact Type Registry
5. Artifact Series and Version Records
6. Walrus Content References
7. Comment Tree and Likes Book
8. Governance Vault, Proposals, Voting, and Claims
9. Events and Canonical Indexing
10. Query and Watch Semantics
11. Transaction Builders and SDK Contracts
12. Validation Rules and Error Codes
13. Upgrade and Drift Handling
14. Security Boundaries
15. Appendix: Package IDs, Object IDs, and Event Type Constants

## Notes

This document should be stricter than the whitepaper. If an object structure or
event field is uncertain, verify it from Move source, deployment manifests,
tests, SDK code, or mainnet data before presenting it as normative.
