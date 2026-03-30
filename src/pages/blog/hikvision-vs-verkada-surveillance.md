---
layout: ../../layouts/BlogPostLayout.astro
title: "Hikvision vs. Verkada: Giants at Opposite Ends of the Surveillance Industry"
description: "One is the world's largest surveillance camera manufacturer, blacklisted by the US government. The other is Silicon Valley's fastest-growing security startup, now valued at $5.8 billion. Together, they reveal everything about where the surveillance industry is heading."
pubDate: 2026-03-23
slug: "hikvision-vs-verkada-surveillance"
tags: ["surveillance", "Hikvision", "Verkada", "security technology", "geopolitics", "AI"]
author: "GEN Engine Insights"
---

## Hikvision vs. Verkada: Giants at Opposite Ends of the Surveillance Industry

The world's surveillance camera market is splitting in two. On one side stands Hikvision, a Chinese manufacturer that dominates by volume and cost — and that the US government has effectively banned from federal procurement. On the other stands Verkada, a Silicon Valley startup valued at $5.8 billion that is winning precisely because American companies and government agencies cannot legally buy from Hikvision.

Together, these two companies are not competing for the same customers. They are dividing the global surveillance market along geopolitical lines. Understanding why they exist at "opposite ends" — and what that tells us about the future of technology, regulation, and global supply chains — is essential for anyone in enterprise IT, government procurement, security, or venture capital.

## The Scale Comparison: One Dominates Volume, One Dominates Margins

Hikvision is, by a wide margin, the world's largest surveillance camera manufacturer. As of 2024, the company commands approximately 37% of the global video surveillance market by units shipped — roughly 300 million cameras deployed worldwide. Its revenue in 2024 exceeded $12 billion, with net profit of $1.4 billion. The company manufactures everything from commodity fixed cameras at under $50 per unit to sophisticated AI-powered edge systems and integration platforms.

Verkada, by contrast, is exclusively focused on premium mid-to-enterprise deployments in North America, Western Europe, and a handful of other regulated markets. The company has installed cameras at roughly 150,000+ locations globally, with estimated annual recurring revenue (ARR) of $200–$300 million as of late 2024, based on public statements and investor disclosures. Its December 2024 capital raise valued the company at $5.8 billion — a remarkable valuation for a company with less than 1% of Hikvision's global market share, but entirely logical given the structural tailwind it enjoys from regulatory barriers to its competitors.

The scale gap is enormous. Yet Verkada is valued at a fraction of Hikvision's market capitalization ($5.8 billion vs. Hikvision's $30+ billion), despite having a revenue base that is perhaps 2% of Hikvision's size. The reason: margins, growth trajectory, and most importantly, regulatory moats. Verkada's software-centric model allows gross margins exceeding 70%; Hikvision's hardware-dominant model operates closer to 40%. Investors are paying for recurring revenue and exclusivity, not commodity volume.

## The Regulatory Divide: NDAA and the New Mercantilism

The story begins with geopolitics. In recent years, the US government has effectively restricted the purchase of video surveillance equipment from Chinese manufacturers, particularly Hikvision. The 2019 National Defense Authorization Act (NDAA) and subsequent updates made it illegal for federal agencies and their contractors to procure surveillance equipment from companies deemed security risks — a designation that has applied to Hikvision since 2021.

The impact is straightforward: every US federal agency, every military base, every Department of Homeland Security facility, and every contractor serving them is legally prohibited from buying Hikvision equipment. SLED (State, Local, Education) markets increasingly follow suit, with many state procurement rules barring Chinese surveillance vendors. And private enterprises that do business with the federal government — defense contractors, technology vendors, healthcare systems receiving federal funds — often adopt the same policies preemptively to maintain compliance and avoid reputational risk.

This is not a market competition. It is a regulatory moat. Verkada was not winning against Hikvision on price or features — it was winning because Hikvision was legally unavailable. When you remove 20% of a market (US federal + contractor ecosystem, plus allied governments), the incumbent vendor disappears, and new entrants with no Chinese ties automatically inherit a substantial market.

Hikvision's response has not been to compete in regulated Western markets — it has conceded them — but instead to double down in developing markets, where NDAA restrictions are meaningless and price is paramount. The company's growth in Southeast Asia, India, the Middle East, and Latin America has remained robust precisely because of this regulatory divide. Hikvision is the default choice for 95% of the world; Verkada is mandatory for 5% of the world where regulatory compliance is non-negotiable.

## The Business Model Divide: Hardware vs. Subscription

Beyond geopolitics, the more enduring distinction between these companies is their business model — and what it means for the long-term economics of their respective customers.

Hikvision's model is largely transactional. A customer buys cameras and NVR equipment, pays a relatively modest one-time software license (or none at all), and owns the infrastructure outright. Total cost of ownership over five years is typically low. The tradeoff is complexity: managing firmware updates, storage provisioning, and network configuration falls on the customer or their integrator.

Verkada's model is subscription-first. Verkada hardware runs $500–$3,000 or more per camera, plus mandatory annual licenses of $199–$1,799 per camera. For a mid-sized deployment of 50 cameras, the annual licensing cost alone can exceed $50,000 — a recurring expense that compounds over a multi-year contract. Verkada is criticized for lock-in and a closed platform that cannot use third-party VMS or AI overlays, with risks including account lockouts and data access restrictions.

The model, however, also delivers real value. Software updates are automatic and continuous. There is no NVR to maintain or replace. The management interface is genuinely excellent — something that cannot be said for most legacy VMS platforms, including Hikvision's own HikCentral. For IT teams without dedicated security operations staff, the reduced management burden is worth a significant premium.

## AI: On-Camera Edge vs. Cloud Intelligence

Both companies are betting heavily on artificial intelligence, but their approaches reflect their underlying architectures.

Hikvision processes AI at the edge — directly on the camera's onboard chip. This approach enables real-time analytics without cloud latency, works in bandwidth-constrained environments, and keeps raw video data on-premises. The company's DeepinMind NVRs and edge AI cameras can perform facial recognition, vehicle classification, crowd density estimation, and behavioral anomaly detection without sending footage to any external server. Hikvision invested RMB 11.864 billion in research and development in 2024, equivalent to 12.83% of its total revenue — a figure that underscores its commitment to maintaining technical leadership at the hardware layer.

Verkada processes AI in the cloud. Footage is analyzed after being uploaded, and increasingly, large language model capabilities are being integrated — allowing operators to search footage using natural language queries. The company will reportedly use its latest capital raise to develop new AI features, and its connection to Alphabet through the CapitalG investment creates at least the possibility of deeper integration with Google's AI infrastructure over time.

Neither approach is categorically superior. Edge AI wins on latency, privacy, and bandwidth. Cloud AI wins on capability, updateability, and the ability to run models too large for embedded chips. The right choice depends heavily on use case — a high-security facility with sensitive data concerns may strongly prefer edge processing; a retail chain managing 500 locations may find cloud AI analytics far more practical to deploy and manage.

## Who Should Buy Which

For most buyers, the choice between Hikvision and Verkada is not primarily a technology decision — it is a compliance, budget, and operational one.

**Hikvision makes sense for:**

- Private commercial businesses outside the government contracting ecosystem
- Buyers in emerging markets where NDAA restrictions do not apply
- Organizations with existing on-premises infrastructure and in-house IT capacity
- Large-scale deployments where per-camera cost differences of $200–$500 are material

**Verkada makes sense for:**

- US federal agencies, government contractors, and SLED organizations where NDAA compliance is mandatory
- Mid-market companies that want plug-and-play simplicity and are willing to pay for it
- Multi-site enterprises that benefit from centralized cloud management
- Organizations with limited in-house security operations capacity

### The Lock-In Warning Buyers Often Ignore

Verkada's hardware is proprietary. Cameras only work with Verkada's cloud platform. If you cancel your subscription or Verkada changes its pricing, your cameras become unusable — unlike open-platform hardware from Hikvision, Axis, or Hanwha.

Your footage lives on Verkada's servers. Data residency, portability, and access in the event of a contract dispute are governed by Verkada's terms of service, not your own IT policy.

Total cost of ownership diverges sharply at scale. A 100-camera Verkada deployment can cost $80,000–$150,000 per year in licensing alone. At that scale, open-platform alternatives with equivalent features may be significantly cheaper over a five-year horizon.

## The Bigger Picture: A Market Splitting in Two

The Hikvision-Verkada comparison is ultimately a proxy for a broader structural split in the global surveillance market. On one side: inexpensive, hardware-first, on-premises systems dominated by Chinese manufacturers, serving the majority of the world by volume. On the other: premium, cloud-first, subscription-based platforms from Western companies, commanding higher margins and serving regulated markets where Chinese vendors are legally excluded.

The video surveillance systems market is projected to expand from $64.79 billion in 2025 to $118.83 billion by 2031, registering a CAGR of 10.65%. Both sides of the market will grow. But they will grow in different directions, serve different customers, and operate under different regulatory regimes. The camera on a government building in Washington and the camera on a factory floor in Jakarta may look similar, but the infrastructure behind them — and the politics governing their procurement — could not be more different.

Investors have clearly taken note. Verkada's December 2024 valuation of $5.8 billion reflects not just its revenue growth, but the structural tailwind created by every new NDAA restriction, every government procurement mandate, and every enterprise IT team that decides it no longer wants to manage on-premises NVRs. Meanwhile, Hikvision's steady revenue growth in developing markets reflects the equally durable reality that price matters enormously in most of the world — and no Western startup is close to matching its cost structure.

The two companies are not converging. They are diverging — and in doing so, they are drawing the map of what the surveillance industry looks like in a fractured geopolitical world.

## Key Takeaways

**Scale vs. model:** Hikvision dominates by volume and price; Verkada dominates by software margin and compliance eligibility. They are targeting increasingly different customer pools.

**NDAA is a market-maker:** US and allied government bans on Hikvision equipment are a structural revenue tailwind for Verkada and other compliant vendors — a competitive advantage created by legislation, not innovation.

**Verkada's lock-in is real:** The cloud-native model offers genuine operational advantages, but proprietary hardware and mandatory subscriptions create long-term cost and data-control risks that buyers must price in.

**AI architectures diverge:** Edge AI (Hikvision) and cloud AI (Verkada) each have genuine advantages depending on use case — there is no universal winner, despite each company's marketing claims.

**The market is splitting geographically:** Hikvision is accelerating in developing markets; Verkada is consolidating in regulated Western ones. The global surveillance market is fracturing along geopolitical lines, and that fracture is becoming permanent.
























































