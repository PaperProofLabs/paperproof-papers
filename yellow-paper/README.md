# PaperProof Yellow Paper

This directory is for the formal PaperProof yellow paper.

## Purpose

The yellow paper should be the protocol specification. It should define the
core objects, state transitions, event model, validation rules, governance
logic, indexing rules, deployment manifest expectations, and SDK-facing
contracts with enough precision for developers, auditors, and indexer builders.

## Target Audience

- Smart contract auditors.
- SDK maintainers.
- Indexer builders.
- Advanced frontend developers.
- Protocol contributors.
- Ecosystem reviewers who need implementation-level clarity.

## Suggested Files

- `paperproof-yellow-paper.tex`
- `refs.bib`
- `figures/`
- `appendices/`

## Suggested Structure

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
