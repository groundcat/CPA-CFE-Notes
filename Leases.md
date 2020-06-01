# Leases - IFRS 16

## Identify a Lease

**4 criteria** - A contract contains a lease if

- **Specifically identified asset** 
  - Underlying asset is **identified** in contract
  - Underlying asset is **specified**, supplier has no substitution rights (not changeable)
- Customer obtain **substantially all economic benefits**
  - Lessee benefits from asset
- Customer **directs purpose** of asset
- **Right to control** of (operate) asset on economic benefits
  - Type of output produced
  - When output produced
  - Where output produced
  - Whether output produced

## Lessee Accounting

### Exemptions

- Exemption is optional

Recognize ROU asset & lease liability, **unless** either

- **Short-term** lease and **no purchase option**, or
  - Include periods of **extension options** that are **reasonably certain** to be exercised
- Asset **low value when new** (US$ 5,000 but judgement required)
  - On absolute (dollar amount) basis,  irrelevant to materiality
  - Look at each **individual** asset
  - May avoid recognizing lease by leasing multiple low value items

If meet exemptions above, 

- Option to elect recognize as lease **expense** each period

### Non-lease Components

Alternatives allowed:

- Choose to **separate**
  - Lower ROU asset & lease liability
  - Proportionally allocate based on relative **stand-alone prices (FMV)**
    - If not available, must be **estimated** by **observable** inputs
    - Not use inputs in lease contract b/c IFRS requires price allocated to be **fair**
- Choose **not to separate**
  - Higher ROU asset & lease liability
  - Treat entire contract as lease
- ASPE: "Executory costs"

### Term of Lease

- **Non-cancellable** period
- **+ Extension** period when **reasonably certain** to exercise
  - No need to be 100% certain
- **+ Rent-free** period
- Do **not** include if period **not enforceable** (either party can cancel without significant penalty)

### Beginning of Lease Term

**Commencement date**: Asset made available for use, <u>when</u>

- Lessee recognize & measure A/L
- Lessor recognize finance lease asset in B/S
- Recognize: Asset, Liability, Income, Expense

**Inception date**: earlier of (a) date of agreement and (b) date of commitment of parties, <u>when</u>

- Evaluate if there is a lease in contract
- Lessor: determine lease classification

### Initial Recognition

- Recognize ROU **when available to use** (commencement date)
- DR. ROU asset = PVMLP / CR. Lease liability = PVMLP

### Measurement of Lease Liability

**Lease liability** <u>includes</u>:

- **Fixed payments** (PMT)
- **<u>Certain</u> variable payments**
  - <u>Only</u> include those **in substance are fixed** payments (based on an index or rate)
  - Not include percentage based variable payments
- **Residual value guarantee & Termination penalties**
  - Include if **reasonably certain to pay** (judgement required) 
- **Exercise price of purchase options**
  - Include if **reasonably certain to pay** (judgement required) 

Factors to consider: Not likely to terminate lease if

- Significant leasehold improvements
- Importance of asset to lessee
- Costs of relocation, new set up costs

### Measurement of Right-of-Use (ROU) Asset

**ROU asset** includes:

- **Lease liability** (see above), adjusted for:
- **Payments at/before lease contract commencement**
  - Commissions, legal
- **Initial direct costs**
- **Moving & restoring** costs, **ARO**
- **Less: Lease incentives** received

(Must be **incremental** costs)

### Discount Rate

- **I/Y = implicit rate, if reasonably determinable**
  - **Implicit rate**: Rate that makes PV MLP + unguaranteed residual value = FV of asset
- **Otherwise, I/Y = incremental borrowing rate (IBR)**
  - **IBR**: Rate that lessee would have to borrow to purchase the asset under similar term and type of asset

### Subsequent Measurements of ROU Asset

#### Cost Model

**Initial ROU**, and then adjusted for:

- Less: **Accumulated depreciation** over time of
  - **Useful life**, if
    - <u>Ownership transferred</u> at end of lease, or
    - <u>Purchase option</u> reasonably certain to exercise
  - Otherwise, use **lease term**
- Less: **Accumulated impairment** on ROU asset
  - Example: contamination of asset
- Plus/Less: **Gains & losses** recognized if lease liability and ROU **revalued**
  - When variables change

#### Revaluation Model

Option to use revaluation model if

- Revaluation with sufficient regularity 
- FV model

#### ASPE vs. IFRS

For leases the depreciable cost is calculated differently under ASPE and IFRS.

- Under ASPE, the depreciable amount deducts the guaranteed residual value at all times as per the below slide. 
- However, per IFRS, the residual value is deducted ONLY when there is a purchase option which the lessee will exercise or if ownership is transferred to the lessee automatically at the end of the lease term.

### Subsequent Measurements of Lease Liability

**Initial lease liability**, and then adjusted for:

- **Interest expense**
  - Effective interest method
  - I/Y unchanged, unless
    - Lease term changed
    - Purchase option amount changed
- **Payments** made
  - Reduces liability
- **Re-measurement** if 
  - payment linked to index, or 
  - substantial modifications to lease

**ROU also adjusted** for items above

- **Interest and amortization expense** also adjusted based on new info

Entries:

```
DR. Interest expense / CR. Liability
DR. Lease liability / CR. Cash payment
DR. Amortization expense / CR. Accumulated amortization
```

### Lease Modification

Modification is a **separate** lease if

- Increase scope of lease, add right to use 1 or more underlying assets, <u>and</u>
- Consideration of lease increase for stand-alone price of increase scope of lease

If modification is a separate lease,

- Remeasure lease liability, using revised discount rate

## Lessor Accounting

Key differences:

- Initial cost of asset may often be less since lessor may buy in bulk

- Lessor may expect residual value and may be quite high

- Lessor can have tax shield early tax savings from CCA (*all leases are operating leases for tax)

### Classify a Lease

#### 1. Finance Lease

- **Transfer substantially all <u>risks & rewards</u> of asset**
- **Primary indicators:**
  - <u>Transfer</u> title at end
  - <u>BPO</u>
  - <u>Lease term</u> is "major" part of economic life
    - Vs. ASPE: 75%
  - <u>PV of lease payments</u> "substantially all" FV of asset
    - Vs. ASPE: 90%
  - Asset has <u>specialized nature</u> (only lessee can use without major modifications)
- **Other indicators:**
  - Lessor's loss on cancellation borne by lessee
  - Gains/losses of FV accrue to lessee
  - Bargain renewal (less than market value)

#### 2. Operating Lease

- **NOT** transfer substantially all risks & rewards of asset

### Lease of Land and Buildings

- Assessed **separately** as a finance / operating lease
- **Land** has indefinite life, so **operating lease**
  - But capital lease if PVMLP substantially all FV
- **Payments al located** between land & building
  - Based on **relative FV of leasehold interests** (not FV)
    - Consider ROI, recovery value
  - Finance lease if not able to allocate reliably
- **If land immaterial, treat as one lease**
  - Economic life of building = life of entire asset (building + land)

### Head Lease and Sublease

- Head lease and sublease are 2 separate contracts
- If head lease is short-term, then sublease should be an operating lease
  - Otherwise sublease is ROU asset arising from head lease

### Accounting for Finance Lease

#### Recognition

- **Finance income**, at constant rate on net investment
- **<u>Net</u> investment in lease** = <u>Discounted</u> (at implicit rate) <u>gross</u> investment in lease
  - **<u>Gross</u> investment in lease** = <u>sum</u> of
    - Lease payments received
    - Unguaranteed residual value accruing to lessor
  - **Payments included** in net investment in lease:
    - Fixed payments - Any lease incentive payable
    - Variable lease payments
    - Residual value guarantees to lessor
    - Exercise price of purchase option (if reasonably certain exercise)
    - Termination penalty payments

Two types of finance leases:

#### 1) Non-Manufacturers Lease

- Purchase an asset and immediately leased
- Profit from **lease interest**

#### 2) Manufacturers Lease

- Lease to lessee from **inventory**
- Cost incurred are **expensed**, not part of net investment of lease
- Recognize on <u>commencement</u> date:
  - **Revenue** = <u>Lower</u> of 
    - FV of asset
    - PV (discounted by market rate) of lease payments
  - **Cost of sales** = Cost of asset - PV of unguaranteed residual value
  - **Selling profit or loss** = Revenue - Cost of sales

### Accounting for Operating Lease

- Leased **asset** on B/S
  - Amortized
  - Initial direct costs added to asset CV
  - Other costs expensed
- Lease **revenue** recognized when payments due

### Sale and Leaseback

|                 | Sale of Asset                                                |
| --------------- | ------------------------------------------------------------ |
| Seller (Lessee) | - Derecognize asset<br />- Recognize ROU asset<br />- Recognize lease liability<br />- G/L on sale |
| Buyer (Lessor)  | - Recognize asset purchase<br />- Apply lessor accounting    |

|                 | Not Sale of Asset                                            |
| --------------- | ------------------------------------------------------------ |
| Seller (Lessee) | - Continue to recognize asset<br />- Recognize financial liability |
| Buyer (Lessor)  | - Do not recognize asset<br />- Recognize financial asset    |

Use IFRS 15 to assess if it is a sale



# Leases - ASPE S3065

## Lessee Accounting

### Identify a Lease

#### Capital Lease

Criteria: **Substantially all risks & rewards transferred**, otherwise operating lease

Meet **<u>one</u>** condition:

- **Transfer title** after lease
- **Bargain purchase option (BPO)**: will exercise
- **Lease term $\geq$ 75%** economic life, **<u>or</u>**
- **PV MLP  $\geq$ 90% FV** at lease inception

Recognition:

- Record **asset & liability** = PV of MLP, excluding executory costs
  - Never exceed asset FV
  - Contingent rentals expensed as incurred
  - Include any penalty lessee paid for failure to renew
- Record **amortization expense** for asset
- Record **interest expense** for liability

#### Operating Lease

- Record **lease expense** each period

### Land and Buildings

- **Land** has indefinite life so **operating lease**, <u>unless</u>
  - Title expected to **transfer or BPO**, which is **capital lease**
- **If capital lease**,
  - Lessee capitalize land **separately** from building
  - in proportion to **FV at lease inception**

### Initial Costs

- **Always expensed** by lessee
  - Delivery, construction expenses
- NOT capitalized to asset, unlike IFRS

### Uneven Payments

- Free rent, lump sum payments, etc.
- Amortized over initial lease term
  - Lease expense each year = Total payments / Total terms

### Term of Lease

Includes:

- **All terms before exercising BPO**, if **reasonably certain**
- **BPO renewal term**
- **Renewal terms at lessor's option**
  - Lessor wants the lessee to renew (lessor does not want it back)

### Minimum Lease Payments (MLP)

MLP =

- Include (+) **Guaranteed residual value**
  - Value guaranteed to lessor at end
- Include (+) **BPO price**
- Exclude (-) **Operating/executory costs** 
  - insurance, maintenance
- Exclude (-) **Contingent lease payment** (cannot estimate)
  - based on subsequent events ($ per km)

### Discount Rate

<u>Lower</u> of

- **Implicit rate**
- **IBR**

### Subsequent Measurements

Amortization over time of

- Lease term if no BPO or title transfer
- Economic life if BPO or title transfer

Depreciable amount = PV - guaranteed residual value

Entries (same as IFRS):

```
DR. Interest expense / CR. Liability
DR. Lease liability / CR. Cash payment
DR. Amortization expense / CR. Accumulated amortization
```

## Lessor Accounting

### Capital Lease

- **Step 1 - Meet at least 1 criteria for lessee**
  - **Transfer title** after lease
  - **Bargain purchase option (BPO)**: will exercise
  - **Lease term $\geq$ 75%** economic life, **<u>or</u>**
  - **PV MLP  $\geq$ 90% FV** at lease inception
- **Step 2 - Meet both 2 additional criteria:**
  - Credit risk of lessee must be normal, **<u>and</u>**
  - Un-reimbursable costs to be borne by lessor must be estimable

### Classification of Capital Lease

#### 1) Direct Financing Lease

- No profit component
- Lessor acts as intermediary between manufacturer and lessee
- **Finance income** = <u>difference</u> between
  - Total MLP, 
    - net of executory costs and related profit
    - plus unguaranteed residual value accrued to lessor
  - Cost (CV) of leased asset
- Initial costs expensed

#### 2) Sales Type Lease

- Have profit component

### Interest Rate Discounting

For both capital lease & finance lease:

- Implicit rate (if known)

### Sales and Leaseback

- **Deter gain**, taken into income <u>over lease term</u>
  - Not allowed to recognize an immediate gain

|                 | Sales and Leaseback                                          |
| --------------- | ------------------------------------------------------------ |
| Capital Lease   | P/L deferred, amortized in proportion to amortization of asset, <br />unless land is amortized over term |
| Operating Lease | P/L deferred, amortized over term on S-L basis               |

- At time of sales leaseback, if **FV < CV**, recognize **loss** immediately