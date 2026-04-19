# Security Policy

## About Gamma Seeds

The `gamma-seeds` GitHub organisation is operated by **Gamma Seeds Pte Ltd**
(Singapore; incorporation in progress as of 2026-04), a research and
licensing company developing the Synapticode product family including the
Tern ternary compression toolchain and the Gamma local-intelligence platform.

Several repositories in this organisation contain patent-adjacent material,
evaluation artefacts delivered under commercial agreements (e.g. KAIST
evidence packages), and pre-publication research code. We take the security
and integrity of these repositories seriously and welcome good-faith reports
from security researchers.

## Scope

This policy applies to all repositories owned by the `gamma-seeds`
organisation, public and private. The two publicly-visible repositories at
the time of publication are:

- `gamma-seeds/tern-core` — the public ecosystem seed for the Tern
  compression toolchain
- `gamma-seeds/tern-sdk` — the public developer SDK built on Tern

Private repositories under `gamma-seeds` are in scope for this policy even
though their source is not publicly accessible: if you have obtained
information through authorised access (e.g. as a licensee, evaluation
partner, or contracted collaborator) and believe you have identified a
security issue, please report it via the channel below.

## Reporting a Vulnerability

**Email: security@synapticode.ai**

Please include, to the extent you can:

- The repository and version (or commit SHA) affected
- A clear description of the issue and its security impact
- Steps to reproduce, ideally a minimal proof-of-concept
- Your name (or pseudonym) and preferred contact method for follow-up
- Whether you have disclosed this to any other parties

Do **not** open a public GitHub issue or pull request for a security
matter. Public disclosure before coordination prevents us from protecting
users during the remediation window.

PGP: not currently offered. If you require end-to-end encryption for a
report, contact the address above and we will arrange a channel.

## Our Commitment to Reporters

- **Acknowledgement**: within 72 hours of receipt.
- **Initial assessment**: within 14 calendar days, including whether we
  accept the finding, whether a fix is planned, and a target remediation
  window.
- **Coordinated disclosure**: we prefer to agree a public-disclosure date
  with you once a fix is ready. If agreement is not possible, we commit to
  disclosing no later than 90 days from the initial report in line with
  accepted industry practice.
- **Credit**: with your permission, we will credit you in the fix commit,
  release notes, and/or a security advisory. You may remain anonymous or
  pseudonymous if you prefer.

## Safe Harbor for Good-Faith Research

We support good-faith security research and will not pursue legal action
against researchers who:

- Make a reasonable, good-faith effort to avoid privacy violations,
  destruction of data, interruption of services, or degradation of systems;
- Report findings promptly and privately to the address above;
- Do not access, modify, or retain data beyond what is necessary to
  demonstrate the issue;
- Do not disclose the vulnerability publicly before coordinated disclosure
  (or 90 days, whichever is sooner);
- Comply with applicable laws.

Good-faith research conducted under these conditions is authorised and we
will work with you, not against you.

## Out of Scope

The following are not covered by this policy:

- Forks, mirrors, or third-party distributions of our repositories
- The `synapticode-ai` personal GitHub account (legacy; no repositories
  remain there after the 2026-04 migration to `gamma-seeds`)
- Denial-of-service findings against rate-limited public endpoints
- Social-engineering attacks against Gamma Seeds personnel
- Physical-security findings
- Findings in upstream dependencies — please report these to the upstream
  maintainers; if you believe our use of an upstream creates a novel
  security issue, that specific issue is in scope

## Legal

This policy is offered in the spirit of cooperation with the security
research community. It does not waive Gamma Seeds Pte Ltd's intellectual
property rights, nor does it grant any licence to the code or data in
these repositories beyond what is already granted in each repository's
LICENSE file. Good-faith researchers acting within the scope of this
policy will not be subject to legal action from Gamma Seeds Pte Ltd for
that research activity.

---

**Last updated:** 2026-04-19
**Next review:** 2026-10-19
