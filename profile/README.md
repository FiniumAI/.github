# Finium

### Built for consequential work.

We are the applied-AI lab behind [Finium Legal](https://finiumlegal.com), building a common foundation for complex operational work: **specialized intelligence, operational context and controlled execution**.

[Explore the lab](https://finium.tech) · [Explore Finium Legal](https://finiumlegal.com) · [Research](https://finium.tech/research)

## The work

- **Specialized intelligence.** Task-specific models, evaluation, calibration and abstention. Use a model where it earns its place; use a rule where it does not.
- **Operational context.** Source-linked records, typed relationships and versioned knowledge that connect an organization's data to its decisions.
- **Controlled execution.** Permissions, human review and bounded actions, with a record that can be inspected and challenged.

The shared foundation and model programmes are in development. Research directions are not claims of production availability.

## First application: Finium Legal

**From incident to legal response.**

Finium Legal brings monitoring, evidence collection, investigation and legal work into one workspace:

**Monitor & Collect → Investigate & Prepare → Review & Draft**

Online incidents, recurring brand and IP infringements, disputes and document-heavy investigations are different starting points. The work stays linked to its sources; legal judgment and consequential action stay with human counsel.

[See the workflows](https://finiumlegal.com)

## Open tooling you can run today

### [evidence-verify](https://github.com/FiniumAI/evidence-verify)

Check a Finium-format evidence pack offline, without a Finium account or service. Python standard library only. Apache-2.0.

The verifier re-hashes listed files, checks the aggregate root hash and flags missing, changed or unlisted files. It also inspects optional RFC 3161 timestamp tokens, within the verification limits documented in the repository.

**Integrity, not truth.** A consistent pack does not establish that its content is authentic or true, that a timestamp is legally qualified, or that the evidence is admissible.

```bash
git clone https://github.com/FiniumAI/evidence-verify.git
cd evidence-verify
python3 examples/make_demo_pack.py --zip
python3 -m evidence_verify examples/demo-pack.zip --json
```

[Pack format](https://github.com/FiniumAI/evidence-verify/blob/main/PACK-FORMAT.md) · [Verification limits](https://github.com/FiniumAI/evidence-verify#security-notes--what-this-proves-and-what-it-does-not-prove) · [Report a security issue](https://github.com/FiniumAI/evidence-verify/blob/main/SECURITY.md)

## Work with us

Interested in model evaluation, provenance or the control of agents that act? [Get in touch](mailto:contact@finium.tech).

This organization holds our published tools and documentation. It is not the full Finium platform, a public model release or a collection of deployed cross-sector applications.
