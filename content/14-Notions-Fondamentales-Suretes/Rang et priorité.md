# Rang et priorité (Priority Ranking)

> **Concept**: The order in which secured creditors are paid from enforcement proceeds
> **Source**: Westendorf, T.1, §§200-230, Arts. 2092-2098 C.civ.
> **Critical for**: Intercreditor arrangements, syndicated lending, structured finance

---

## Definition

*Rang* (rank) determines the order of priority among creditors competing for the same assets or the same debtor's patrimony. Priority rules determine who gets paid first when assets are insufficient to satisfy all claims.

**Art. 2093 C.civ.**:
> "Les biens du débiteur sont le gage commun de ses créanciers."

*Translation*: The debtor's assets are the common pledge of his creditors.

**Art. 2094 C.civ.**:
> "[L]e prix s'en distribue entre eux par contribution, à moins qu'il n'y ait entre les créanciers des causes légitimes de préférence."

*Translation*: The price is distributed among them pro rata, unless there are legitimate causes of preference among the creditors.

---

## Priority Framework

### A. General Creditors (*Créanciers chirographaires*)

Unsecured creditors share *pari passu* (equally) in remaining assets after secured and privileged creditors are satisfied.

### B. Secured Creditors (*Créanciers garantis*)

| Security Type | Priority Basis | Registration |
|---------------|---------------|--------------|
| **Pledge (possessory)** | Date of dispossession | None required |
| **Financial collateral** | Date of constitution | None (Art. 5(5) Loi 2005) |
| **Hypothèque** | Date of registration | Required |
| **Nantissement fonds de commerce** | Date of registration | Required |
| **Réserve de propriété** | Ownership never transferred | N/A |
| **Fiducie/Cession** | Ownership transfer date | None |

### C. Privileged Creditors (*Créanciers privilégiés*)

Legal privileges rank according to statutory order (Arts. 2095-2098 C.civ.):
1. *Frais de justice* (enforcement costs)
2. *Créances salariales* (employee wages)
3. *Créances fiscales* (tax claims)
4. Specific privileges on movables/immovables

---

## Priority Rules by Security Type

### 1. Pledge (*Gage*)

**Rule**: First in time, first in right (*prior tempore, potior jure*)

**Date determination**:
- Civil pledge: Date of dispossession
- Financial collateral: Date agreement takes effect

**Trib. Luxembourg, 16 février 2011, n° 62/2011**:
> Priority of pledge over third parties established by effective dispossession or control.

### 2. Property-Based Securities

**Réserve de propriété**: Seller retains ownership → absolute priority over buyer's creditors for reserved goods.

**Cession à titre de garantie**: Assignee becomes owner → priority over assignor's creditors for assigned receivables.

**Fiducie-sûreté**: Assets in separate patrimony → protected from both parties' creditors.

### 3. Competing Securities

| Scenario | Priority Rule |
|----------|--------------|
| Multiple pledges | First dispossession prevails |
| Pledge vs. retention of title | ROT prevails (ownership never transferred) |
| Pledge vs. privilege | Depends on privilege rank |
| Assignment vs. assignment | First assignment in time |

---

## Financial Collateral Special Rules

**Loi 5 août 2005, Art. 5(5)**:

Financial collateral arrangements benefit from simplified priority rules:
- No registration required for opposability
- Constitution effective upon agreement
- Priority determined by date of constitution

**Art. 20 Loi 2005** (Insolvency protection):
> Financial collateral arrangements are NOT affected by insolvency proceedings opened after constitution.

---

## Intercreditor Agreements

### Purpose

When multiple creditors hold security over the same assets, intercreditor agreements modify statutory priority through:
- **Subordination** - junior creditor agrees to rank behind senior
- **Priority arrangements** - allocation of enforcement proceeds
- **Standstill provisions** - restrictions on enforcement rights

### Key Provisions

| Clause | Function |
|--------|----------|
| **Payment waterfall** | Order of distribution of proceeds |
| **Turnover** | Junior must pay over to senior any amounts received |
| **Enforcement standstill** | Junior cannot enforce until senior satisfied |
| **Release** | Senior can release security without junior consent |

### Luxembourg Recognition

Intercreditor agreements are **contractually binding** under Art. 1134 C.civ. but do NOT affect:
- Third parties not party to the agreement
- Statutory privileges
- Insolvency estate distribution rules (unless permitted by law)

---

## Insolvency Context

### Bankruptcy (*Faillite*)

**Art. 532 C.com.**: Opening of bankruptcy fixes creditor rights as of judgment date.

**Secured creditors** may:
- Exercise *droit de rétention* (retention right)
- Realize pledged assets with priority payment
- Assert ownership (ROT, fiduciary, assignment)

### Reorganization (*Gestion contrôlée*)

Secured creditors generally retain priority but may be subject to stay on enforcement.

---

## Banking Application

### Due Diligence

1. **Search existing encumbrances**:
   - Registre de commerce for nantissement sur fonds de commerce
   - No general pledge registry exists

2. **Verify no prior possession**:
   - For tangible assets, inspect location
   - For receivables, request confirmation from account bank

3. **Check contractual restrictions**:
   - Negative pledge clauses in existing facilities
   - Assignment restrictions in underlying contracts

### Documentation

**Priority confirmation clause** (typical):
> "The Borrower represents that no Security Interest exists over the Collateral other than as disclosed in Schedule [X] and permitted under this Agreement."

**Intercreditor structure** (syndicated loan):
```
Senior Secured Creditors
    ↓ (by intercreditor agreement)
Mezzanine Creditors
    ↓ (by subordination)
Subordinated Creditors
    ↓ (by statute)
Unsecured Creditors
```

---

## Common Law Comparison

| Feature | Luxembourg | English Law | UCC (USA) |
|---------|------------|-------------|-----------|
| Registration | Limited (immovables, fonds de commerce) | Companies House for company charges | UCC-1 filing |
| Priority basis | Possession/date | Registration | Filing date |
| Purchase money priority | ROT | PMSI possible | PMSI rules |
| Negative pledge | Contractual only | Contractual only | Contractual only |

---

## Cross-References

- [[Droit préférentiel]] — Right of preference
- [[13 - Contrat de garantie financière]] — Financial collateral priority rules
- [[19 - Réserve de propriété]] — Retention of title priority
- [[21 - Fiducie-sûreté]] — Fiduciary patrimony protection
- [[22 - Cession de créance à titre de garantie]] — Assignment priority
- [[Opposabilité aux tiers]] — Third-party effectiveness

---

#suretes #rang-priorite #intercreditor #droit-luxembourgeois #banking-law #insolvency
