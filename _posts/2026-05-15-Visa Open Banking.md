## Visa's Open Banking Journey
### A tale of failed acquisition, pivot, exit, and a two-tier strategy across the Atlantic

### Executive Summary
For decades, Visa has been the giant of payments. Its card network and trust layer have generated billions in free cash while keeping new entrants at abyss. But starting with the 2015 EU Open Banking regulation, that dominance came under serious threat. Plaid emerged, Visa tried to buy it for $5.3 billion, the deal failed in court, and Visa was forced to rethink its strategy. It built a two-tier playbook: own the trust layer in Europe through Tink and Visa A2A, and own the rails in the US through Visa Direct. Now, stable coins and agentic AI is disrupting the payment ecosystem and for Visa, it is both a threat to its existing model and an opportunity to replace its commoditizing products.

### Introduction

Say you are a $400 billion giant, owner of the largest payment network in the world, generating billions of dollars in free cash flow annually. Organic growth is healthy, the growth runway is long, and new entrants have failed to threaten your duopoly with Mastercard. Then, in 2015, a regulation in Europe, Payment Service Directive 2 (PSD 2), forced the banks to open up their silos, and suddenly tiny startups that were struggling for a lifeline find regulatory tailwinds to disrupt the business you spent decades building.

This article traces how the EU's open banking regulation opened the gates for fintech companies like Plaid to access siloed banking infrastructure in the EU and the US, enabling them to innovate on how payments work and threaten Visa's growth journey.

### Visa's Model

Visa owns proprietary payment infrastructure that lets it settle transactions over its network. It works with banking partners worldwide to issue cards that facilitate these transactions and takes a cut every time a cardholder makes a payment. Visa owns the bank connectivity and facilitates transactions, while ensuring compliance, fraud prevention, and dispute resolution through its trust layer, in exchange for the fees it charges. Visa, along with players like Mastercard, dominates the domain, and banks, the holders of capital, have been content in their silos, earning a slice of fee every time a transaction happens.

### Open Banking and the Threat

In 2015, EU regulators concluded that siloed banking systems were limiting competition and innovation in payments. To lower these walls, the European Parliament adopted the revised Payment Services Directive (PSD2) that allowed licensed third-party providers to programmatically access bank-held customer data such as account information and to initiate payments directly from customer accounts (with consent). PSD2 came into force in January 2016 and applied from January 2018. The result: young startups like Tink, Plaid, and others began building infrastructure that could directly access bank accounts to deliver financial services outside the established incumbents' dominance.

### Plaid: The Acquisition, the Lawsuit, and the Pivot

Plaid was founded in 2012 by two ex-Bain consultants, Zach Perret and William Hockey, to bring third-party technology to financial services. The early journey was tough as banks could not be compelled to open their systems, but PSD2 validated the model in Europe and helped Plaid secure the capital it needed to grow. Over the next five years, Plaid built infrastructure in the US, UK, and EU to facilitate financial services outside the older siloed ecosystems.

In 2019, Plaid announced plans to launch its own bank-account-based payment infrastructure, and Visa took notice. For Visa, this was a direct threat to its US debit cash cow. In January 2020, Visa offered $5.3 billion to buy Plaid (Exhibit 2). The motive: own the competition before it threatens your dominance, or as Visa's CEO Al Kelly put it in internal documents later disclosed in court, an *"insurance policy"* against a *"threat to our important US debit business."*

But the acquisition did not sit well with the US Department of Justice, which feared it would eliminate a nascent competitive threat and concentrate online debit power further. The DOJ filed suit in November 2020. By January 12, 2021, Visa walked away from the deal. For Plaid, this was a shot in the arm as venture capital saw an opportunity to back a company that could disrupt the payments market, and in April 2021 Plaid raised $425 million at a $13.4 billion valuation, more than 2.5x what Visa had offered to pay.

For Visa, it was a blow to its strategy. But large incumbents rarely cede ground without a counter-move. In June 2021, Visa acquired Tink, a Stockholm-based open banking platform, for €1.8 billion (~$2.15 billion), because the regulatory environment was favorable. When asked why Visa didn't simply build open banking capabilities itself, the answer was straightforward: building this infrastructure would take 5 to 7 years, and given the pace of innovation, buying it offered a better ROI.

### New Products and Services in UK and Europe

Visa recognized that open-banking-enabled account-to-account payments were no longer hypothetical, and that its card network could not stay isolated from this shift. So it used Tink's technology to develop Visa A2A, its own account-to-account payments product, launched in the UK in 2025. Visa already owned decades of expertise in fraud prevention, dispute resolution, and consumer protections from its card business. This was the time to leverage that expertise to enter the direct payment space (Exhibit 3). Tink provided the access layer to connect directly with banks. Together, Visa built a system that delivers identity verification, authentication, transaction routing, and dispute resolution on top of bank rails.

The underlying settlement happens on Pay.UK's Faster Payment System, the UK's government-supported instant payment rail. Visa's contribution is the *scheme layer* (Exhibit 3): the rulebook, the liability framework, and the consumer-protection guarantees that allow merchants and consumers to treat pay-by-bank with the same trust as a card payment. Critically, Visa A2A is designed as an *open* scheme, in which Plaid, Tink, TrueLayer, and other open banking providers can all participate as payment initiators. This means Visa earns scheme fees from every Visa A2A transaction regardless of which open banking provider routes it. Even when Plaid initiates the transaction, Visa is in the middle, earning from its proprietary trust layer.

### The US Story: Exit Instead of Expansion

Across the Atlantic, the US market evolved very differently. The Consumer Financial Protection Bureau (CFPB) finalized the equivalent open banking rule, Section 1033 under Dodd-Frank, in October 2024, and US banks immediately pushed to charge fees for the API access they would now be required to provide. The fintech firms that had banked on EU-style free access to US banking infrastructure suddenly faced an uncertain unit economics outlook, and capital began rotating away from fintech toward the new world favourite: AI.

In August 2025, Visa shut down its US open banking operations, a complete reversal from its initial strategy to become a player, as competition was high and the ecosystem was unsupportive (Exhibit 1). Industry analysts attributed the exit to three factors: the US market was already locked up by established players (Plaid, Mastercard's Finicity, MX, Akoya); the CFPB 1033 environment created fee uncertainty that made the unit economics unattractive; and building from scratch against an entrenched Plaid was no longer viable without an acquisition path.

In place of an open banking play, Visa has leaned on Visa Direct, its push-payments product launched in 2017 that uses Visa's own card rails to deliver near-real-time payouts. In April 2025, Visa Direct began transferring funds within one minute or less, putting it in direct speed competition with the bank-rail real-time systems and FedNow. Visa Direct processed over 9.5 billion transactions in FY2024, making it one of the most-used real-time payment solutions in the US, roughly 25x the combined volume of FedNow and the RTP network (Exhibit 4).

While bank-rail real-time systems such as The Clearing House's RTP (launched 2017) and the Federal Reserve's FedNow (launched July 2023) exist for open banking companies like Plaid to use, they cannot match Visa Direct's reach. The result: Visa is winning real-time payments in the US through its own proprietary card network, without needing an open banking play at all.

### The Two-Tier Strategy

In the EU, Visa continues to leverage open banking through its subsidiary Tink, innovating new payment services and capturing scheme fees on every account-to-account transaction. In the US, having exited open banking, Visa is monetizing real-time payments through its proprietary card rails (Visa Direct), supplemented by ancillary products like Visa A2A Protect (a fraud product for A2A payments running on *other* people's rails).

The picture that emerges is a deliberate two-tier strategy: own the *scheme/trust* layer where open banking is regulatorily mandated and competitive (Europe), and own the *rail* itself where it isn't (the US). It is a sophisticated bet on the reality that value in payments increasingly migrates toward the layer where consumer trust is established, and that Visa, more than any other player, has decades of brand equity in being that trust layer (Exhibit 5).

### Agentic AI: Threat or Opportunity

The conversation around AI agent-led payments is getting serious. Every ecosystem player, including banks, payment incumbents, AI giants, high-growth fintechs, and regulators, has dropped its hat in the ring, and the change is accelerating. Fintechs and AI companies are pushing hard for agent-led commerce. Banks are worried because they own the direct consumer relationship and will be most liable when something goes wrong. Visa's biggest fear is becoming invisible as agents shift volume to alternate payment rails, hitting the company's cash cow. With stablecoins rising after the GENIUS Act 2025, the current payment architecture is starting to lose its inevitability, and fintech players are investing heavily to build trust-layer capabilities of their own.

This leaves Visa in a daunting spot. Its card-network cash cow is under long-term threat, the valuable trust layer is productizing, and agents could make the Visa brand invisible at checkout. So Visa is investing heavily in its own AI efforts to make sure the threat it once faced through open banking cannot be repeated through agentic AI. Its multi-tier strategy (Exhibit 6) does two things at once: build the technical foundation for secure agentic commerce through authentication, tokenization, and AI-led risk signals, while actively partnering with AI platforms and infrastructure players to become part of the stack itself, avoiding the mistake it made with open banking.

### Final Insights

For Visa, the journey ahead is surely more challenging than the past. Over decades, it has built a network of relationships and a payment technology ecosystem that have served it well, but the future is uncertain and leads to the following conclusions:

1. **Visa Payment Network**: While the network is safe in the short term due to its scale and security, the changing technology and regulatory landscape, including direct payments and stablecoins, poses real threats, and Visa needs to become part of the process.
2. **Expansion through Partnerships**: Visa will continue to work with banks and issuing partners to scale up its network and add more customers. Visa needs to accelerate and innovate to prevent consumers and merchants from switching to other methods.
3. **Trust Layer (Fraud Prevention, Liability Management)**: The trust layer is an important resource for Visa and it has used it well. However, the challenge is that the technology itself is productizing, and Visa needs continuous investments (both organic and inorganic, such as the Featurespace acquisition) to maintain an edge.
4. **Open Banking and Payment Technology**: Open banking is turning into Open Finance and will eventually become a commodity play rather than a product play. For Visa, it is important to invest heavily in Tink to dominate UK and EU markets, while strategically investing in US open banking players to leverage its position once the regulatory concerns are resolved.
5. **Agentic AI**: This is possibly the biggest opportunity for Visa. With all of its current products under threat, Visa must invest heavily into agentic AI capabilities to avoid a repetition of the Plaid acquisition failure. Visa's primary focus should be to lead the play rather than follow others.

### Conclusion

The rise of open banking, stablecoins, and agentic AI clearly shows that the whole payment system is under disruption. While in the last few years Visa has taken multiple steps to consolidate its leadership position by investing in technology and scale, its current cash-generating sources are under serious long-term threat. While the regulatory challenges remain, Visa needs to continuously invest in its technology and scale to maintain its leadership position.


# APPENDIX

## Exhibit 1: Porter's Five Forces Analysis — Open Banking

### Summary Matrix

| Force | Intensity |
|---|:---:|
| Threat of New Entrants | **Moderate** |
| Bargaining Power of Suppliers (Banks) | **Low** |
| Bargaining Power of Buyers (Fintechs) | **Low** |
| Threat of Substitutes | **Low** |
| Rivalry Among Existing Competitors | **High** |

### Detailed Assessment

| Force | Intensity | Rationale |
|---|:---:|---|
| **Threat of New Entrants** | Moderate | Technology is widely available and European regulation actively supports entry, enabling the creation of 400+ open banking platforms. However, building a secure, feature-complete platform and integrating with the banking ecosystem requires substantial time. |
| **Bargaining Power of Suppliers (Banks)** | Low | Banks supply the underlying account access but lack the technical capacity to build a multi-bank open banking connectivity layer themselves. They are mandated to provide access, not to compete on it. |
| **Bargaining Power of Buyers (Fintechs)** | Low | Third-party fintechs in payments, insurance, and lending depend on open banking APIs to reach banking infrastructure. Building their own connectivity layer is not a feasible investment for them. |
| **Threat of Substitutes** | Low | The available substitutes are weak: manual file downloads and uploads (poor customer experience), or banks signing one-to-one contracts with every fintech (operationally infeasible at scale). |
| **Rivalry Among Existing Competitors** | High | Many peer firms offer overlapping open banking services and continue to layer additional capabilities on top, intensifying the race for differentiation. Rivalry has also moved to the M&A level, with Visa acquiring Tink and Mastercard acquiring Finicity. |

### Conclusion

> Open banking is structurally attractive: low supplier power, low buyer power, and weak substitutes create a favourable foundation. However, moderate entry threat and high rivalry mean profitability depends on **scale, regulatory positioning, and the ability to layer differentiated capabilities** (trust, fraud, dispute resolution) on top of commoditized connectivity.


## Exhibit 2: Build, Borrow, or Buy Analysis

**Acquirer:** Visa | **Target:** Plaid | **Time:** 2020

With Open Banking established in Europe and under US discussion, Visa needs this technology to reduce the threat of non-card payment rails and participate in fintech innovation.

### Step 1: Capability Gap

Visa needs a full open banking suite to programmatically access thousands of US and European banks within 18 to 24 months. Bank relationships exist via the card network, but the developer capacity to build it does not.

### Step 2: Strategic Importance

Visa's revenue is card-payment fees. A cheaper alternative outside its ecosystem erodes that base. Controlling open banking technology is strategically essential.

### Step 3: Four-Question Decision Tree

| # | Question | Verdict | Rationale (≤25 words) |
|:---:|---|:---:|---|
| 1 | **Internal resources adequate?** | **No, Reject Build** | Bank access, regulators, and developers exist, but Visa cannot ship a competitive system in 18 to 24 months. |
| 2 | **Contract or license available?** | **No, Reject License** | Visa would inherit the provider's roadmap and lose control. Licensing also doesn't stop Plaid from launching its own rails. |
| 3 | **Alliance or partnership viable?** | **No, Reject Alliance** | Interests are opposed: Visa wants to block Plaid's rail ambitions; Plaid wants to substitute Visa's network. |
| 4 | **Acquisition integration feasible?** | **Yes, Pursue Buy** | Visa is ~100x Plaid's size. Plaid's API-first architecture enables fast integration and a platform for Visa's own A2A network. |

### Step 4: Quantify Each Viable Path

| Path | Cost | Time | Probability of Success |
|---|---|---|---|
| **Build** | $500M to $1B | 3 to 5 years | Low: network effects favor incumbents |
| **Borrow** | $200M to $250M | 12 to 18 months | Low: Plaid likely launches A2A within 3 years |
| **Buy** | $4.4B to $4.8B (30% growth + 20% premium on Dec 2018 $2.65B valuation) | 9 to 15 months to close | Highest: absorbable against $72.5B in total assets, $35B book value (FY2018) |

*Note: Visa's actual offer was $5.3B. The model was directionally correct but conservative.*

### Step 5: Premortem Stress Test

> *"It is 2023 and the Plaid acquisition failed. Why?"*

| Failure Scenario | Probability |
|---|:---:|
| Regulators block the deal over competition concerns | **High** |
| Cultural mismatch drives Plaid talent attrition | **Medium** |
| Plaid features misalign with Visa's roadmap | **Low** |
| Open banking commoditizes; Visa fails to build A2A despite acquisition | **Low** |
| Balance sheet impact constrains other ventures | **Low** |

*The high-probability regulatory risk materialized: DOJ sued November 2020; deal abandoned January 2021.*

### Step 6: Decision and Exit Criteria

**Decision:** Pursue acquisition.

| Trigger | Exit Action |
|---|---|
| No regulatory approval within 9 to 15 months | Pivot to a different open banking target within regulatory limits |
| Significant Plaid talent attrition | Operate Plaid independently to preserve technology and culture |
| Plaid fails to deliver A2A rails post-acquisition | Build A2A internally or acquire a second target |
| External shocks impair the balance sheet | Divest Plaid to a competitor (very low probability) |

### Conclusion

> **Buy is the correct path.** Build is too slow, License surrenders control, Alliance fails on misaligned interests. Acquisition delivers integration speed, strategic control, and a platform for Visa's own A2A network at an absorbable cost. Regulatory risk is the only material failure mode, and the exit criteria address it.

## Exhibit 3: Visa A2A / Visa Trust Layer — VRIO Analysis

**Description:** Visa A2A is a set of rules, guidelines, and API standards that facilitate secure transactions across banks, ensuring consistent experience and compliance. Visa A2A does not facilitate payment itself but acts as a centralized framework for dispute resolution, liability management, and fraud monitoring.

### VRIO Decision Matrix

| Valuable? | Rare? | Inimitable? | Organized? | Competitive Implication |
|:---:|:---:|:---:|:---:|---|
| **Yes** | **Weakly Yes** | **Yes** | **Yes** | **Sustained Competitive Advantage** |

### Reasoning Per Dimension

| Dimension | Verdict | Rationale (≤25 words) |
|---|:---:|---|
| **Valuable** | Yes | Built over decades on billions of transactions. Layers over any payment rail, allowing Visa to charge fees for security and compliance services. |
| **Rare** | Weakly Yes | Technology evolves fast and startups offer similar algorithms, but achieving real-time scale tested across billions of transactions and regulator acceptance remains rare. |
| **Inimitable** | Yes | Mastercard built a comparable system, but many others burnt billions trying to build and achieve scale. Technology plus global banking-partner integration makes imitation costly. |
| **Non-Substitutable** | Weakly Yes | Several firms offer protection software, but regulatory acceptance and scale with banks across the world make this system difficult to substitute. |
| **Organized** | Yes | Visa built its trust layer over decades to secure its card network. When A2A emerged, Visa extended this capability through Visa A2A and monetized it. |

> While the Visa trust layer is not entirely unique, it is difficult to imitate, not only in terms of technology but in terms of scale, and Visa is organizationally structured to extract value from this resource.

## Exhibit 4: Transaction Volume in US

![Visa Payment Share](/assets/images/1_Visa_Open_Banking/Payment_share.png)


## Exhibit 5: Wardley Map — Payment Transaction System

**User Need:** A consumer paying a merchant for goods, securely and reliably, with recourse if something goes wrong.

### Wardley Map

![Wardley Map](/assets/images/1_Visa_Open_Banking/Payments_Wardley_Map.png)

### Component Placement Matrix

| Component | Evolution Stage | Strategic Note (≤25 words) |
|---|:---:|---|
| **Checkout Window** | Commodity | Standardized off-the-shelf (Stripe, Shopify). Differentiation minimal; pricing transparent. |
| **Payment Method** (BNPL, Card, Wallet, A2A) | Product → Commodity | Multiple competing options. BNPL still productizing; cards near-commodity. |
| **Open Banking** (Authentication, Aggregation) | Product | Standardized aggregators (Plaid, Tink). Drifting toward commodity as JPMorgan-style fee deals signal commoditization. |
| **Trust Layer** (Fraud & Risk) | Custom → Product | Standard fraud commoditizing; scheme-grade (Visa, Mastercard) still custom. Productization underway via Visa A2A and MC A2A Protect. |
| **Dispute Resolution & Liability** | Product | Productized rulebooks owned by schemes (Visa VCR, Mastercard, Visa A2A, UK PSR). Drifts toward commodity when regulator-mandated. |
| **Card Network / A2A Scheme** | Product | Multiple competing networks (Visa, Mastercard, Amex). High margin but standardized and transparent. |
| **Payment Rails** (ACH, RTP, FedNow) | Commodity / Utility | Government or consortium-operated plumbing. No firm builds new ones. |
| **Settlement Rails** | Commodity / Utility | Standardized infrastructure. Consumed as utility, priced per transaction. |
| **Core Banking APIs (Europe)** | Product | Standardized under PSD2 since 2018. Interoperable across thousands of banks. |
| **Core Banking APIs (USA)** | Custom → Product | Bilateral deals dominate. FDX standards emerging but not enforced. Section 1033 still contested. |
| **Core Banking Systems** | Commodity (legacy) | Mainframes are utilities; modern cores (Mambu, Thought Machine) still productizing. |
| **Stablecoin Payments** | Custom | USDC and USDT exist but payment use cases remain nascent. Not yet a product market. |
| **Agentic AI for Payment Authorization** | Genesis | Exploratory. CFPB still debating whether AI agents qualify as "representatives" under Section 1033. |
| **Agentic AI for Dispute Management** | Genesis → Custom | Early experiments at Stripe, Plaid, Anthropic. No standardized offering yet. |

### Strategic Implications

| Insight | Implication (≤25 words) |
|---|---|
| **Value migrating up** | Connectivity layer commoditizing. Trust, identity, and AI-mediated reasoning are where margin sits next. |
| **Value migrating down** | Settlement rails are utilities. Strategic control passes to scheme operators and regulators above them. |
| **Squeezed middle** | Open banking aggregators face inevitable margin pressure. Must move up (Plaid Signal/Identity) or accept commoditization. |
| **Where to build** | Agentic AI for authorization and dispute is Genesis. New defensible positions get created here. |
| **Where to buy** | Anything in Commodity. Outsource payment rails, settlement, cloud, processing. |
| **Where incumbents are positioning** | Visa A2A and MC A2A Protect productizing the Trust Layer for A2A; the next 5 to 10 years of margin. |

### Verdict

> The strategic frontier is **Genesis (agentic AI)** and the **productizing Trust Layer for A2A**. The commodity layer is a buy decision; the rail layer is a regulator decision; the middle layer is contested.

## Exhibit 6: Visa's Agentic AI Initiative — Visa Intelligent Commerce (VIC)

Launched April 30, 2025 at Visa's Global Product Drop, Visa Intelligent Commerce (VIC) is Visa's official umbrella initiative for agentic AI commerce, positioned as **"the trust layer for the agent economy."**

### Table 1: The Five Modules Within VIC

| Module | Function (≤25 words) |
|---|---|
| **Authentication** | Confirms the AI agent is authorized to act for a specific consumer, extending Visa's identity verification capabilities into AI commerce. |
| **Tokenization** | Replaces 16-digit card numbers with network tokens that work anywhere Visa is accepted, shielding raw card data from agents. |
| **Payment Instructions** | Lets consumers preset dollar limits, merchant categories, and real-time approval prompts. Guardrails enforced directly inside VisaNet. |
| **Personalization** | With consumer consent, shares basic spending patterns so agents can rank offers by airline preference, price comfort zone, or dining habits. |
| **Signals** | Streams real-time transaction signals back to Visa to trigger risk controls and aid dispute resolution for agent-initiated purchases. |

### Table 2: Extension Programs and Partnerships Built on VIC

| Program | Launch | Function (≤25 words) |
|---|---|---|
| **Trusted Agent Protocol (TAP)** | Oct 2025 | Open framework on GitHub helping merchants distinguish legitimate AI agents from malicious bots. Built on HTTP Message Signature and WebAuthn standards. |
| **Visa Agentic Ready** | 2025 (UK/EU); Apr 2026 (APAC/LatAm) | Structured program for issuing banks and payment partners to test agent-initiated payments. Live with 85+ partners across APAC and LatAm. |
| **Intelligent Commerce Connect** | Apr 2026 | Protocol-agnostic on-ramp accepting agent payments via TAP, MPP, ACP, and UCP. Positions Visa as neutral infrastructure regardless of protocol winner. |
| **Visa-AWS AgentCore Partnership** | Dec 2025 | VIC available through AWS Marketplace. Pre-built agent blueprints in Amazon Bedrock AgentCore for retail, travel, financial, and post-purchase workflows. |

### Pilot Programs and Traction

By Dec 2025, VIC had attracted 100+ ecosystem partners with 30+ actively building in the VIC sandbox, alongside hundreds of completed agent-initiated transactions. Visa is actively working with AI platform partners such as OpenAI, Anthropic, Microsoft, Stripe, and Samsung to embed its presence deep into the agentic AI commerce layer.


# AI Disclosure

While the basic draft was written by me, I have leveraged AI substantially to research the topic, summarize source pages and documents, implement frameworks, and give a professional look while retaining my original tone of writing. While a lot of factual information from sources listed below has been referred to during research, at no point has any information been copied from a published source.