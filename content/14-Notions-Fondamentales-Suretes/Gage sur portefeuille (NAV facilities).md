# Gage sur portefeuille (NAV Facilities)

> **Type**: Notion fondamentale — Fund Finance Security
> **Source**: Banking practice; Loi 5 août 2005; Fund Finance Laws and Regulations
> **Key Legislation**: Loi 5 août 2005 (CGF); L1915
> **Related**: [[Gage sur engagements investisseurs]], [[Financial collateral (loi 5 août 2005)]]

---

## Definition

**NAV facilities** (Net Asset Value facilities) are financings where lenders have recourse to the value of a fund's portfolio investments, with borrowing capacity calculated on the net asset value of eligible assets.

Unlike subscription line facilities (which look "upward" to investor commitments), NAV facilities are **"downward looking"** — security is based on portfolio assets rather than uncalled capital.

> NAV facilities have experienced significant growth in Luxembourg fund finance, particularly for mature funds with invested portfolios and limited remaining unfunded commitments.

---

## Comparison: NAV vs. Subscription Facilities

| Feature | Subscription Facility | NAV Facility |
|---------|----------------------|--------------|
| **Collateral base** | Uncalled investor commitments | Portfolio asset values |
| **"Direction"** | Upward (to investors) | Downward (to investments) |
| **Fund lifecycle** | Early stage (capital being called) | Mature stage (capital deployed) |
| **Borrowing base** | % of uncalled commitments | % of NAV of eligible assets |
| **Primary risk** | Investor default | Portfolio asset valuation |

---

## Security Package

### Core Collateral Elements

| Security | Description |
|----------|-------------|
| **Equity pledge** | Pledge over shares/interests in SPVs and portfolio companies |
| **Account pledge** | Pledge over accounts receiving portfolio distributions |
| **Receivables assignment** | Security over distribution claims from portfolio investments |
| **Share pledge (CGF)** | Financial collateral over shares in target entities |

### Typical Structure

```
Fund (Borrower)
    │
    ├── Pledge over SPV Equity
    │       │
    │       └── SPV holds Portfolio Assets
    │
    ├── Pledge over Distribution Accounts
    │
    └── Assignment of Receivables
            │
            └── Distribution claims from Portfolio
```

---

## Pledge Over SPV Equity

### Luxembourg Law Considerations

When portfolio assets are held through Luxembourg SPVs:

**For SA/SàRL SPVs:**
- Pledge governed by Loi 5 août 2005 (if "financial instruments")
- Register pledge in share register
- Notification to SPV recommended
- Control provisions for enforcement

**For SCS/SCSp SPVs:**
- Pledge of parts d'intérêts
- Gesamthand considerations for SCSp
- See [[Parts d'intérêts (Partnership Units)]]
- Notification to gérant required

### Perfection Requirements

| SPV Form | Perfection Method |
|----------|-------------------|
| **SA** | Entry in share register + pledge agreement |
| **SàRL** | Notification to company + pledge agreement |
| **SCS** | Notification to gérant + pledge agreement |
| **SCSp** | Notification to gérant; Gesamthand analysis |

---

## Pledge Over Distribution Accounts

### CGF Regime Application

Security over bank accounts holding portfolio distributions:

> "The security interest over bank accounts (held in Luxembourg) into which investors are required to fund their contributions may be created by way of a pledge in accordance with the Collateral Law."

**Requirements:**
- Written pledge agreement
- Account held with Luxembourg credit institution (typically)
- Control mechanisms for enforcement
- Consider cash sweep/waterfall provisions

### Practical Considerations

| Issue | Recommendation |
|-------|----------------|
| **Account location** | Luxembourg preferred for CGF protections |
| **Control** | Lender control provisions essential |
| **Perfection** | Account bank acknowledgment |
| **Commingling** | Separate accounts for pledged distributions |

---

## Assignment of Distribution Rights

### Receivables Security

Security over the fund's right to receive distributions from portfolio investments:

**Covered rights:**
- Dividend distributions
- Interest payments
- Proceeds from asset sales
- Liquidation distributions

### CGF Coverage

Under Loi 5 août 2005, receivables (*créances*) qualify as "avoirs" and can be pledged under the CGF regime:

- Written agreement required
- No notification to debtor required for validity (but recommended)
- Enforcement through appropriation or sale

---

## Borrowing Base Mechanics

### NAV Calculation

| Element | Treatment |
|---------|-----------|
| **Eligible assets** | Defined by facility agreement |
| **Valuation methodology** | Typically GP/AIFM valuation |
| **Advance rate** | % of eligible NAV (often 30-60%) |
| **Concentration limits** | Per asset, sector, geography |
| **Exclusions** | Distressed assets, litigation assets |

### Borrowing Base Certificate

Periodic (monthly/quarterly) certification of:
- NAV of eligible portfolio
- Compliance with concentration limits
- Available borrowing capacity
- No material adverse change in valuations

---

## Enforcement Considerations

### Portfolio Complexity

NAV facility enforcement involves selling or realizing portfolio assets:

| Challenge | Mitigation |
|-----------|------------|
| **Illiquidity** | Advance rates reflect illiquidity discount |
| **Control requirements** | Voting rights transfer on enforcement |
| **Regulatory approvals** | Due diligence on portfolio company restrictions |
| **Third party consents** | Review portfolio co-investment/JV docs |

### CGF Advantages

Under Loi 5 août 2005:
- **Appropriation** possible at contractual valuation
- **Accelerated sale** mechanisms
- **Insolvency protection** for financial collateral
- **No stay** applies to enforcement

---

## Fund Structure Considerations

### RAIF-Structured Funds

For RAIF borrowers:
- Excluded from Loi 7 août 2023 restructuring
- No reorganization stay risk
- Direct enforcement rights preserved
- See [[42 - RAIF — Overview]]

### SIF/SICAR Funds

Regulated vehicles may have:
- Borrowing restrictions in fund docs
- CSSF notification requirements
- Diversification requirements affecting concentration

### Unregulated Funds

Maximum flexibility for:
- Borrowing capacity
- Security arrangements
- Enforcement provisions

---

## Banking & Finance Application

### Due Diligence Checklist

**Fund Level:**
- [ ] Borrowing capacity in fund constitutional documents
- [ ] AIFM consent to facility
- [ ] Investor consent requirements (LPA review)
- [ ] Existing leverage restrictions

**Portfolio Level:**
- [ ] SPV jurisdiction analysis
- [ ] Share register access for perfection
- [ ] Distribution waterfall review
- [ ] Co-investor/JV consent requirements
- [ ] Change of control restrictions in portfolio docs

**Security:**
- [ ] CGF eligibility analysis
- [ ] Perfection requirements by jurisdiction
- [ ] Control provisions for enforcement
- [ ] Valuation methodology agreement

### Documentation Considerations

| Document | Key Provisions |
|----------|----------------|
| **Facility Agreement** | Borrowing base, eligible assets, concentration limits |
| **Security Agreement** | CGF-compliant pledge over shares/accounts |
| **Account Pledge** | Collection account mechanics |
| **Receivables Assignment** | Distribution rights coverage |
| **Intercreditor** | If hybrid with subscription facility |

---

## Hybrid Facilities

### Combination Structures

Many funds use **hybrid facilities** combining:
- Subscription line (early stage)
- NAV facility (mature stage)
- Single documentation with bifurcated security

### Intercreditor Considerations

| Issue | Treatment |
|-------|-----------|
| **Priority** | Typically pari passu or pro rata |
| **Enforcement** | Coordinated through intercreditor |
| **Proceeds allocation** | Waterfall provisions |
| **Release mechanics** | As commitments called / assets sold |

---

> **Common Law Comparison**
>
> **UK/Cayman**: Similar security structures but relying on common law pledge/charge regimes without Luxembourg's CGF statutory protections.
>
> **US**: UCC Article 9 security interests; different perfection requirements.
>
> **Key Luxembourg advantage**: CGF regime provides statutory enforcement rights and insolvency protections exceeding common law equivalents.

---

## Cross-References

### Fund Finance
- [[Gage sur engagements investisseurs]]
- [[Financial collateral (loi 5 août 2005)]]
- [[SCSp — Fund Structures (AIFM-SICAR-FIS)]]

### Related Securities
- [[11 - Gage civil (droit commun)]]
- [[12 - Gage sur créances]]
- [[Parts d'intérêts (Partnership Units)]]

### Fund Vehicles
- [[42 - RAIF — Overview]]
- [[43 - UCI — Overview]]

---

#luxembourg-law #droit-des-suretes #NAV-facility #fund-finance #portfolio-pledge #CGF #subscription-line
