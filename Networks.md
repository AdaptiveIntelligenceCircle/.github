# NETWORKS

**Adaptive Intelligence Circle (AIC)**  
**Organization-level map of network generations**  
**Last updated:** 2026-08

This document is the **canonical index** of AIC network phases. 

Individual repositories may add detail; if they conflict with this file on **phase meaning or promotion rules**, this file and `AIC-Legal-and-Governance` win for policy intent.

---

## 1. Purpose

AIC does not treat “TestNet” as a single disposable chain.  
It uses **parallel network generations**: each phase stresses a different truth (lab → public kernel → cross-layer coherence → adversarial long-horizon → mainnet covenant).

| Principle | Meaning |
|-----------|---------|
| Parallelism | Later phases may run while earlier phases keep regressing |
| Gates, not vibes | Promotion requires documented exit signals |
| Ethics in the kernel | Phases test enforcement, not slide-deck ethics |
| No silent mainnet | **Covenant** only after explicit gates |
| Law still applies | No network name overrides jurisdiction or human rights |

---

## 2. Phase overview

```pgsql 
Phase 0 (lab / controlled)
│
▼
AIC-Emergence          ← Phase 1 public TestNet
│
▼
AIC-Resonance          ← Phase 2 public TestNet
│
▼
AIC-Transcendence      ← Phase 3 public TestNet
│
▼
AIC-Covenant           ← Mainnet
text
```


| Phase | Network name | Role | Production? |
|-------|--------------|------|-------------|
| 0 | *(local / controlled TestNet)* | Build truth, fixtures, kernel invariants | No |
| 1 | **AIC-Emergence** | Public adversarial kernel surface | No |
| 2 | **AIC-Resonance** | Cross-layer coherence (agents, recovery, HMN hooks) | No |
| 3 | **AIC-Transcendence** | Long-horizon, anti-capture scenarios, succession drills | No |
| — | **AIC-Covenant** | Mainnet — binding rule surface | **Yes** |

---

## 3. Repository map (org root)

| Path / repo | Phase | README |
|-------------|-------|--------|
| `AIC-TestNet` or `networks/phase0` | 0 | Phase 0 docs |
| [`AIC-Emergence`](./AIC-Emergence) | 1 | [README](./AIC-Emergence/README.md) |
| [`AIC-Resonance`](./AIC-Resonance) | 2 | [README](./AIC-Resonance/README.md) |
| [`AIC-Transcendence`](./AIC-Transcendence) | 3 | [README](./AIC-Transcendence/README.md) |
| [`AIC-Covenant`](./AIC-Covenant) | Mainnet | [README](./AIC-Covenant/README.md) |
| `AIC-Legal-and-Governance` | Policy | Gates, succession, zero-donation, third path |
| `ethical-kernel` / core repos | All phases | Normative principle source |

*Adjust relative links if repos are sibling repositories under the org rather than folders in a monorepo.*

---

## 4. What each phase proves

### Phase 0 — Controlled / lab

- Reproducible builds  
- Kernel principles load and fail closed in fixtures  
- Basic recovery and logging  
- **Not** a public trust surface  

### Phase 1 — AIC-Emergence

- Kernel under **public** stress  
- Multi-runner agreement on golden ethical decisions  
- Fault injection with observable recovery  
- First **parallel** public TestNet after Phase 0  

### Phase 2 — AIC-Resonance

- Agents cannot bypass kernel  
- Recovery cannot launder violations  
- Multi-domain traces stay coherent  
- Human-in-the-loop without “admin overrides the kernel”  

### Phase 3 — AIC-Transcendence

- Soak / long-run invariants  
- Simulated capture pressures (commercial, state, multilateral mis-label) as **scenarios**  
- Succession drills under published policy  
- Last major TestNet class before Mainnet  

### Mainnet — AIC-Covenant

- Production rule surface for the AIC network generation  
- Governance, audit, fork monitoring, succession **in force**  
- **Not** a claim of sovereignty, UN mandate, or immunity from law  
- Name means: **builders are bound by the same rules they ship**  

---

## 5. Parallelism rules

1. **Phase 0 may continue indefinitely** as CI truth even after Emergence is public.  
2. **Emergence may keep running** after Resonance starts (kernel regression).  
3. **Resonance and Transcendence may overlap** when testing different suites.  
4. **Covenant does not retire TestNets by default** — research and regression nets may remain.  
5. Running a later phase **does not** imply earlier gates were passed unless recorded in the gate log.

---

## 6. Promotion gates (summary)

Detailed checklists live with each network repo and in governance. Summary:

| From → To | Minimum idea |
|-----------|----------------|
| 0 → Emergence | Local invariants green; intentional public exposure decision |
| Emergence → Resonance | Public stress credible; no silent state corruption on suite |
| Resonance → Transcendence | No-bypass cross-layer; trace model stable |
| Transcendence → **Covenant** | Soak + anti-capture + succession + legal/security surface + public go/no-go |

**Fail gate ⇒ no promotion.**  
**Pass gate ⇒ permission, not obligation, to promote immediately.**

---

## 7. Identity, data, and risk labels

| Network | Treat identities as | Real value / PII |
|---------|---------------------|------------------|
| Phase 0 | Lab only | Forbidden unless synthetic |
| Emergence | Disposable test | Forbidden |
| Resonance | Disposable test | Forbidden |
| Transcendence | Disposable test | Forbidden |
| **Covenant** | Production operators | Only with lawful basis + policy |

Never present TestNet participation as Mainnet legal or financial finality.

---

## 8. Policy anchors (normative)

- **Third Path Absolute** — protocol rules resist single-principal capture  
- **Zero-Donation (protocol sense)** — money must not buy rule-power inside AIC  
- **GPL-3.0** (+ documented supplements) — copyleft / freedom surface as published per repo  
- **Succession** — Covenant must not depend on one human remaining online forever  
- **Security disclosure** — `SECURITY.md` per repo; no blind weaponization of tests  

See: `AIC-Legal-and-Governance/`.

---

## 9. Naming discipline

| Use this name | For |
|---------------|-----|
| AIC-Emergence | Phase 1 TestNet only |
| AIC-Resonance | Phase 2 TestNet only |
| AIC-Transcendence | Phase 3 TestNet only |
| AIC-Covenant | Mainnet only |

Avoid marketing that calls any TestNet “mainnet”, “UN network”, or “national infrastructure.”

---

## 10. Founder-era note

While AIC is founder-led, network promotion and Mainnet declaration follow **written gates**, not informal momentum.  
Informal contacts (multilateral, industry alliances, fiscal hosts, media) **do not** substitute for technical or legal gates in this document.

---

## 11. Document control

| Item | Value |
|------|--------|
| Owner | AIC core maintainers |
| Canonical location | Organization root `NETWORKS.md` |
| Related | Each phase `README.md`, `GOVERNANCE.md`, `SECURITY.md` |
| Change process | PR + maintainer review; material gate changes noted in governance changelog |

---

*Adaptive Intelligence Circle — parallel networks, single ethical spine, Mainnet only under Covenant.*