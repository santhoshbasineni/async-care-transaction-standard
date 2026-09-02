# Toward a Transaction Standard for Asynchronous AI-Mediated Care Review

**A Proposed Framework**

Santhosh Basineni, Mounika Avirineni — Independent Researchers

## Status

This is a draft proposal, not a ratified standard. It is offered as a starting artifact for community and standards-body discussion, in the tradition of an early-stage FHIR Implementation Guide draft. It has not yet been through formal peer review or HL7 Work Group sponsorship.

## Summary

This paper proposes a transaction framework, modeled on the NCPDP Telecommunication Standard, for asynchronous, AI-mediated care review: a defined set of message types spanning intake, conservative emergency escalation, distributed asynchronous physician review, structured disposition, provider registration and credentialing, and payer-facing coverage, cost-estimation, and claims transactions. The framework is specified as a profile over existing HL7 FHIR resources rather than a competing data model, and its payer-facing timeframes are drawn directly from the CMS Interoperability and Prior Authorization Final Rule rather than proposing new obligations from first principles.

A complete technical specification (full data-element schemas, code tables, and a reference implementation) is scoped as separate, forthcoming work.

## Files

- `proposed-standard-async-care-transactions.pdf` — the paper (read this)
- `proposed-standard-async-care-transactions.docx` — source document
- `ieee-formatted-transactions.docx` — draft formatted for IEEE Transactions submission
- `ieee-formatted-magazine.docx` — draft formatted for IEEE Magazine submission

## Next Steps

- Preprint posting (arXiv, category cs.CY, cross-listed cs.AI)
- Engagement with the relevant HL7 community
- Formal technical specification and reference implementation (separate, forthcoming work)
