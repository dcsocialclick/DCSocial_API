# How DCSocial Works

A simple guide to understanding trust-based credit.

---

## The Basic Concept

Imagine you and your friends create a private currency based on trust. Instead of needing a bank, you simply keep track of who owes whom.

**That's DCSocial—but scaled to millions of people with mathematical guarantees.**

---

## Step 1: Build Trust Relationships

You connect with people you trust. Each connection is a bilateral credit line.

```
You trust Alice with 500 DCP
Alice trusts you with 300 DCP
```

**What this means:**
- You're willing to lend Alice up to 500 DCP
- Alice is willing to lend you up to 300 DCP
- No money has moved yet—this is just capacity

---

## Step 2: Send Credit

You can send credit to anyone in the network, even if you don't know them directly.

```
You want to send 100 DCP to David
You don't have a direct connection to David
But you're connected through: You → Alice → Bob → David
```

**The system automatically:**
- Finds the best path(s) between you and David
- Routes the credit through intermediaries
- Records debt obligations at each hop
- Maintains zero-sum balance (total credit = total debt)

---

## Step 3: Strengthen Relationships

Your daily interactions automatically increase your credit capacity.

```
You like Alice's post → +1 point
You comment on Bob's article → +2 points
You share Charlie's content → +3 points
```

**Points accumulate and:**
- Increase the credit limit on your relationships
- Increase your borrowing capacity
- Decay if relationships become inactive (after 7 days)

**No credit applications. No institutional approval. Just organic growth.**

---

## Step 4: Automatic Optimization

The system continuously optimizes itself without you doing anything.

### Circular Debt Netting

If debts form cycles, they automatically cancel:

```
Before:
You owe Alice 100
Alice owes Bob 100
Bob owes you 100

After:
All debts eliminated
Capacity freed
Zero value transferred
```

### Warrant Mechanism

When you receive credit while you have debt, it creates locked backing:

```
You owe Charlie 200
Alice sends you 100

Result:
Your debt to Charlie reduces to 100
A warrant of 100 is created (locked, earns 5% interest)
Debt chain shortened
```

### Value Loop Rewards

When transactions form closed loops, all participants benefit:

```
You → Alice → Bob → You (closed loop)

Result:
All relationships in the loop are strengthened
Credit limits increase
Trust scores improve
```

---

## The Mathematics

### Zero-Sum Constraint

Every unit of credit corresponds to a debt obligation:

```
Σ(credit balances) = Σ(debt obligations)
```

**This means:**
- Money cannot be created without someone owing it
- Inflation is mathematically impossible
- Total money supply = total debt
- No central bank can print more money

### Aggregate Network Paths

Your capacity to send credit aggregates across all possible paths:

```
Path 1: You → Alice → David (capacity: 100)
Path 2: You → Bob → David (capacity: 150)
Path 3: You → Charlie → Eve → David (capacity: 50)

Total capacity: 300 DCP
```

**More connections = More liquidity**

---

## Community-Wide Visibility

Every participant's **total debt** is publicly visible (but individual transaction details can be private).

**Why?**
- Prevents over-leveraging
- Enables collective risk assessment
- Provides early warning of problems
- Eliminates information asymmetry

**Privacy through:**
- Pseudonymous identifiers (not real names)
- Aggregate totals public, details private
- Cryptographic proofs

---

## Governance

System parameters are decided by community consensus:

**What's governed:**
- Interest rates (warrant: 5%, direct debt: 8%)
- Capacity limits (max per edge: 2000 DCP)
- Decay rates (inactive edges: -1 point/day after 7 days)
- System rules and algorithms

**How it works:**
- One person, one vote (reputation-weighted)
- Transparent proposals
- Reversible decisions
- Democratic control

---

## Real-World Example

**Maria is a farmer in rural Philippines:**

1. **She joins DCSocial** through her cooperative's Discord server
2. **Her cooperative members trust her** with 500 DCP each (10 members = 5,000 DCP capacity)
3. **She needs 2,000 DCP** to buy seeds for planting season
4. **She borrows 2,000 DCP** from her network at 8% interest
5. **She buys seeds** from a supplier who accepts DCP
6. **She plants and harvests** her crops
7. **She sells her harvest** and receives DCP
8. **She repays her debt** plus interest
9. **Her trust relationships strengthen** because she honored her obligations
10. **Next season, her capacity increases** to 7,000 DCP

**No bank account. No credit score. No collateral. Just trust.**

---

## Key Differences from Traditional Banking

| Traditional Banking | DCSocial |
|-------------------|----------|
| Requires collateral | Requires trust |
| Centralized control | Distributed network |
| High fees (3-5%) | Zero fees |
| Slow (days) | Instant |
| Opaque algorithms | Transparent code |
| Excludes billions | Includes everyone |
| Inflation by policy | Inflation impossible |
| Corporate governance | Community consensus |

---

## Getting Started

### For Individuals

1. Visit https://dcsocial.click
2. Sign up (email or OAuth)
3. Connect with people you trust
4. Start transacting

### For Communities

1. Add Discord/Telegram bot to your server
2. Members link their DCSocial accounts
3. Build trust networks within your community
4. Enable peer-to-peer credit

### For Developers

1. Read the [BitCredit Whitepaper](./bitcredit-whitepaper.md)
2. Explore the API documentation
3. Build integrations
4. Contribute to the protocol

---

## Learn More

- **[BitCredit Whitepaper](./bitcredit-whitepaper.md)** - Complete technical specification
- **[Vision](./vision.md)** - The future we're building
- **[FAQ](./faq.md)** - Common questions answered
- **[Use Cases](./use-cases.md)** - Real-world applications

---

**Ready to get started?** [Sign up now](https://dcsocial.click/signup)
