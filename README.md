# Igor Pascal

Security researcher focused on **web & API access control** — IDOR/BOLA, RBAC, business logic.
I build tooling that automates the tedious parts of bug bounty while keeping the researcher in charge of every action.

> *Automating security research without replacing the researcher's judgment.*

---

## 🛠 What I'm building

### Hermes BugHunter Workspace (BHW)
A Python CLI for running bug bounty investigations end to end, integrated with an LLM agent.

The core rule: **the system can observe, reason and plan on its own, but every action boundary requires explicit human approval — enforced in code, not in the prompt.** Prompts are not a control surface; an unattended agent told "don't delete data" can still delete data to prove a bug.

- **Canonical investigation pipeline** — authorization → recon → surface → hypothesis → impact → mission → validation → evidence → finding → report, with lineage invariants across every stage
- **Hard gates** — missions need `--confirm --actor`; validation requests are approved individually by SHA; network and auto-execution flags default to off
- **Evaluation harness** — ground-truth fixtures, class-aware precision/recall and ranking regression, so prioritization changes are *measured* before they ship
- **Engineering** — CI on Python 3.11–3.13, ruff + mypy, 1000+ tests, ADRs for every policy decision, reproducible certified releases

`Status: private — public release planned`
<!-- When published: replace the line above with the repo link -->

---

## 🎯 Focus

- Business logic flaws
- REST & GraphQL API security
- Safety design for AI agents in offensive security

## 🧰 Toolbox

Burp Suite Pro · Python · ffuf · nuclei · httpx · katana · Docker · Linux

---

## 📫 Find me

- HackerOne — [igothpascal](https://hackerone.com/igothpascal)
<!-- Add: LinkedIn / email / blog -->

*All testing is performed within program scope and rules.*
