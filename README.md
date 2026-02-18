# Sebi de la Mata — Smart Contract Security Audits

> Independent smart contract security researcher. This repository is a curated portfolio of audit reports covering protocols built on EVM-compatible chains.

---

## About

I'm Sebi de la Mata, a smart contract security researcher focused on identifying vulnerabilities before they become exploits. My work spans protocol logic, economic attack vectors, access control flaws, and edge cases that automated tooling routinely misses.

I conduct audits using **Solidity** and **Foundry**, combining manual code review with proof-of-concept exploit development to ensure every finding is demonstrable, reproducible, and actionable.

I follow the **CodeHawks Impact × Likelihood** severity framework to rank findings — ensuring that every report communicates not just what is broken, but how urgently it needs to be addressed.

---

## Severity Classification

Findings in all reports are ranked using the **CodeHawks methodology**, which evaluates severity as a function of two independent dimensions:

| Dimension | Description |
|-----------|-------------|
| **Impact** | The potential harm to users, funds, or protocol integrity if the vulnerability is exploited |
| **Likelihood** | The probability that the vulnerability will be triggered under realistic conditions |

The intersection of these two dimensions determines the final severity label: **Critical**, **High**, **Medium**, **Low**, or **Informational**.

This framework avoids the common pitfall of conflating theoretical worst-case scenarios with practical risk — every rating reflects both what *can* happen and how *likely* it is to happen.

---

## Audit Reports

| # | Protocol | Type | Findings | Report |
|---|----------|------|----------|--------|
| 1 | PasswordStore | encryption service | 3 | [Link](https://github.com/sebidelamata/security-research-reports/blob/main/passwordstore-audit-2026-02-18.pdf) |

> Reports are added to this repository as they are completed and cleared for public disclosure.

---

## Methodology

Each audit follows a structured, multi-phase process:

**1. Scoping & Architecture Review**
Understanding the protocol's intended behaviour, trust assumptions, and attack surface before touching a single line of code.

**2. Manual Code Review**
Line-by-line analysis of all in-scope Solidity contracts, with particular attention to state transitions, access control, arithmetic, and external interactions.

**3. Exploit Development**
Every non-informational finding is accompanied by a Foundry proof-of-concept that demonstrates the vulnerability is real and exploitable under stated conditions.

**4. Reporting**
Findings are documented with full technical detail: root cause, attack scenario, impact assessment, and a concrete remediation recommendation. Reports are written to be actionable by developers, not just legible to auditors.

**5. Remediation Review** *(where applicable)*
Re-evaluation of the codebase after fixes are applied to confirm issues are resolved without introducing new vulnerabilities.

---

## Tooling

- **Foundry** — testing, fuzzing, and proof-of-concept development
- **Solidity** — primary language for all audited contracts
- **Static analysis** — supplementary tooling used to assist, never to replace, manual review

---

## Working Together

I'm currently available for freelance engagements and open to joining a team on a longer-term basis. What matters most to me isn't the size of the protocol or the prestige of the client, it's working alongside people who are genuinely curious, rigorous, and care about getting things right.

If that sounds like you or your team, I'd like to hear from you.

**Contact:** 
  - TG: [@sebidelamata](https://t.me/sebidelamata)
  - X: [@Sebi_de_la_Mata](https://x.com/Sebi_de_la_Mata)

---

## Disclaimer

All audits in this portfolio were conducted with the explicit permission of the respective protocol teams. The reports are shared for transparency and educational purposes. A completed audit does not constitute a guarantee of security — it represents the findings identified within the agreed scope and timeframe.

---

*Sebi de la Mata · Smart Contract Security*
