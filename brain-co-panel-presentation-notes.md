# Brain Co. Panel Presentation — Speaker Notes
## Jaron Parnala | Product Manager Final Round

---

## SECTION 1: ABOUT ME (5-7 minutes)

---

### Slide 1: Who I Am (~2 min)

I'm Jaron Parnala — I've spent 11+ years building 0→1 B2B and enterprise products across AI, blockchain, and developer infrastructure. The pattern across my career: join early, build from nothing, scale it.

Pivotal shaped my product foundation — I worked with Fortune 500 clients on software transformation through Pivotal Labs and built enterprise platform-as-a-service products on Cloud Foundry. That's where I learned how to operate inside complex organizations and ship for enterprise customers.

At Bison Trails, I was employee #15. I created a role we called 'Protocol PM' — essentially a general manager for specific blockchain networks, owning product strategy, engineering coordination, GTM, and partnerships end-to-end. We grew that from pre-revenue through acquisition by Coinbase, where the products I owned contributed to $20M+ ARR at peak.

In early 2024, I went deep on AI — did an engineering bootcamp focused on LLMs, RAG, and agents, then led product at Distributional building an AI evaluation and testing platform for enterprises. Now I'm building AI-native applications with agentic workflows and conversational interfaces. I stay close to the technology — right now I'm configuring multi-agent systems on my own hardware to understand how these tools actually work in practice.

---

### Slide 2: Why Product Management (~1 min)

I found product management the hard way. Early in my career at a startup, I watched us build in a vacuum — making product decisions without talking to users. I self-started doing user research with our actual customers, and that experience fundamentally changed how I thought about building products. I realized the most valuable thing I could do wasn't marketing or biz dev — it was making sure we were solving the right problem before we built anything. That's what drew me to PM, and honestly, it's still the thing I care most about — making sure we're building for real user problems, not assumptions.

---

### Slide 3: Why Brain Co., Why Now (~3 min)

Three things drew me to Brain Co.

First — I have a strong point of view on why enterprise AI adoption is hard, and Brain Co. is the only company I've seen that's actually solving the right problem. At Distributional, the thesis was that there's an 'AI confidence gap' — that enterprises aren't adopting AI because these systems are probabilistic and non-deterministic, and large organizations are too risk-averse to put them into production. I spent almost a year living inside that thesis, and I came away believing it's wrong — or at least, it's not the real bottleneck anymore. The actual problem is that these organizations lack the AI expertise and the concrete use cases to move forward. They're not sitting around worried about hallucination rates. They're asking 'what would we even build, and who would build it for us?' That's exactly what Brain Co. is solving — embedding world-class AI talent with these institutions to actually build and ship the applications they need.

Second — the role itself. This PM role is structured as a mini-GM — end-to-end ownership of a product area, not just writing PRDs and handing them off. That's the model I built for myself at Bison Trails. I created a role we called Protocol PM, which was essentially a general manager for specific blockchain networks — I owned strategy, engineering coordination, GTM, partnerships, all of it. That's where I'm at my best, and it's exactly how this role is set up.

Third — the timing. AI applications for enterprises are at the same inflection point that blockchain infrastructure was in 2019 when I joined Bison Trails as employee #15. The technology is moving faster than institutions can absorb it, the companies that embed with customers now will own those relationships for years to come, and I'd rather be building at that frontier than watching it from the sidelines.

---

## SECTION 2: PRODUCT DEEP DIVE — FLOW PROTOCOL LAUNCH (28-30 minutes)

---

### Slide 4: Context (~1 min)

Let me show you what this kind of end-to-end ownership looks like in practice.

Bison Trails was a blockchain infrastructure company — think of us as a specialized cloud provider for blockchain networks. When a new network launched, someone had to run the infrastructure that secured it. That was us.

Flow was a major new blockchain built by the team behind NBA Top Shot and CryptoKitties. When it launched, every token holder on the network needed to stake — essentially locking up their tokens to help secure the network and earn rewards. The company that provided that infrastructure on day one would capture the majority of the market.

That's the opportunity I was tasked with owning.

**VISUAL**: Flow website screenshot with brand logos (Samsung, UFC, Warner Music) and/or NBA Top Shot screenshot to make Flow tangible.

---

### Slide 5: Problem Framing — Why This Mattered (~3-4 min)

So the challenge wasn't just 'launch staking for Flow.' The real problem was: how do you become the dominant infrastructure provider for a network that doesn't exist yet, where the technical specs are changing weekly, and you have 8-10 weeks to be ready?

Here's why day one mattered so much. Token holders who don't stake when a network launches rarely come back to it later. It's a technical process, and the longer someone waits, the less likely they are to prioritize it. And there's a compounding effect — providers who capture more stake early are seen as more trustworthy by new token holders, so early share begets more share. It's a network effect. If you're not there on day one with significant stake, you're not just behind — you're losing ground faster every day. Speed and velocity weren't nice-to-haves. They were the entire game.

The protocol teams knew this too. Their entire network security depended on having as many tokens staked as possible on day one. Weak staking participation meant weak security, and for a new network, that could be a death sentence.

Now — this was my fourth or fifth protocol launch. My first one, Celo, had been rough. I was new to the Protocol PM role, I didn't deeply understand how the ecosystem players fit together — who was responsible for what between custodians, token holders, and infrastructure providers like us. That left our GTM team undersupported and I had to learn the hard way. After that, I committed to building a repeatable playbook. Each launch I ran, I iterated on that system — tighter protocol team relationships, earlier custodian partnerships, cross-functional launch coordination. By the time Flow came around, the playbook was on its fourth or fifth version. Flow was the test of whether that system actually worked at scale.

---

### Slide 6: The Three Decisions That Mattered (~10-12 min)

**Decision 1: Go deep on the protocol before touching the product**

The first decision was about where I spent my time. Most PMs would start with a PRD or a feature spec. I started by embedding with the Flow protocol team. I set up weekly syncs with their team, created a dedicated Slack channel, and joined engineering calls between our tech lead and theirs to map out exactly how Flow's staking mechanism worked at the infrastructure level.

This wasn't just about learning the domain — it was strategic. By going deep on the protocol, I could translate that technical knowledge into real assets for the rest of the company. I worked with marketing to create content on how Flow staking worked. I built sales collateral that our GTM team could actually use in conversations with token holders. I became the bridge between protocol complexity and commercial readiness.

The lesson I took from my Celo experience was that a Protocol PM who doesn't deeply understand the domain can't support GTM, can't make good prioritization calls, and can't earn the trust of the protocol team. So I invested the time upfront — and it paid dividends across every other decision we made.

**Decision 2: Support all four node types when no one else would**

Flow had a unique architecture — four specialized node types, where most blockchains have one or two. Our engineering team pushed back on supporting all four. One node type in particular was expensive to run and we could only operate a single instance of it — not scalable compared to the others.

But our GTM and Protocol Ops research team had intel that no other infrastructure provider was planning to support all four. That was the data point that tipped the decision. I made the call to support all four, accepting the higher cost, because being the only provider that could run the full set of node types became our number one differentiator. We were able to market ourselves as the only infrastructure provider that supported all four node types — that became a core selling point for our entire GTM motion and signaled to the Flow protocol team and token holders that we were the most committed and capable partner in the ecosystem.

The trade-off was real — more engineering effort, higher operating costs, one node type that didn't scale well. But the competitive positioning was worth it, and it turned out to be one of the biggest factors in why we captured the share we did.

**Decision 3: Cut day-one reporting to protect the launch**

The third decision was about what NOT to build. We had customers asking about blockchain reporting — rewards tracking, operational data, billing workflows. It was a reasonable request. But when I validated the priority through direct customer conversations, the answer was clear: no one was going to choose or reject an infrastructure provider based on reporting on day one. They cared about security, uptime, and whether we'd be ready when the network launched.

So I made the call to deprioritize reporting entirely for launch and ship it as a fast follow. This freed up engineering bandwidth to focus on what actually mattered — core staking functionality and security. Reporting shipped a few weeks after launch and no customer complained about the delay.

This is a trade-off I think about a lot — the discipline of cutting scope not because something isn't valuable, but because it's not valuable *right now*. In a compressed timeline with a winner-take-most market, every engineering hour has to go toward what drives day-one readiness.

---

### Slide 7: Collaboration — The Launch Machine (~4-5 min)

I ran a weekly cross-functional launch meeting that brought together product, engineering, design, marketing, sales, protocol ops, and customer success. Each team owned their deliverables. I facilitated, tracked milestones across functions, provided product context, and made sure nothing was falling through the cracks.

One thing that came out of this process was a go/no-go launch checklist. Before Flow, we didn't have a systematic way to decide if we were actually ready to launch a protocol. I built one that every function had to sign off on before we went live. That checklist became something the company reused for every protocol launch after Flow.

The other critical piece was custodian partnerships. Custodians are the companies that hold tokens on behalf of end users. I learned from earlier launches that custodians are the bottleneck for day one readiness. If they can't integrate with your staking infrastructure in time, it doesn't matter how ready you are because the tokens can't move. So I started engaging custodians well before mainnet, worked to make the integration as smooth as possible, and stayed close with them through testing. Getting custodians ready early became one of the most important parts of the playbook.

---

### Slide 8: Artifacts (~3 min)

A few things I can point to from this launch:

The protocol launch playbook and go/no-go checklist I've already described. I don't have those to show you since they were internal, but they became standard operating procedure for every launch after Flow.

The KPI framework. We set network penetration as our north star, defined as the percentage of staked tokens running on Bison Trails infrastructure. We set the target at 33%, and that number was intentional. Proof of stake protocols require a 66% supermajority to validate blocks. We deliberately didn't want to exceed that threshold because if our infrastructure went down, we could block consensus for the entire network. That would have been catastrophic for our reputation and for the protocol. So the target wasn't just a business goal, it reflected our responsibility as an ecosystem partner.

The content and GTM assets I built from going deep on the protocol. That technical knowledge I developed by embedding with the Flow team turned into published content, sales collateral, and eventually this Coinbase delegation guide that's still live today.

And the launch itself generated press coverage across CoinDesk, Yahoo Finance, and industry outlets.

**VISUALS**:
- KPI framework diagram (33% target with 66% supermajority threshold)
- Press coverage cluster: CoinDesk, Yahoo Finance, FFNews headlines/logos
- Coinbase Flow Delegation Guide screenshot
- Flow website / NBA Top Shot screenshots (if not used on Slide 4)

**REFERENCE LINKS**:
- https://www.coinbase.com/developer-platform/discover/protocol-guides/guide-to-flow
- https://www.coindesk.com/tech/2020/08/11/bison-trails-now-supports-flow-blockchain-from-cryptokitties-maker-dapper-labs
- https://finance.yahoo.com/news/bison-trails-now-supports-flow-130000360.html
- https://ffnews.com/newsarticle/bison-trails-integrates-dapper-labs-flow-blockchain-onto-platform-2/

---

### Slide 9: Results (~2-3 min)

Here's how it played out:

We launched day one on Flow mainnet as one of the first infrastructure providers ready.

Within six months, we captured roughly 40% of all staked Flow tokens. That exceeded our 33% target and made Flow our highest network penetration of any protocol on the platform.

We maintained 99.99% uptime from launch, which directly translated to rewards performance for our customers.

The launch contributed over $2 million in ARR for the business.

We got press coverage across CoinDesk, Yahoo Finance, and industry publications.

And more broadly, the Flow launch and the protocol launches that preceded it were a meaningful part of the story that led to our acquisition by Coinbase.

But I think the result I'm most proud of isn't a number. It's that the playbook I built across these launches became the system the company used for every protocol after Flow. Each launch got more efficient, more coordinated, and more successful because the process compounded.

**VISUAL**: Clean metric cards:
- **Day 1 ready** at mainnet launch
- **~40%** network penetration in 6 months
- **99.99%** uptime since launch
- **$2M+** ARR contribution
- **#1** highest penetration protocol on the platform
- **Acquired** by Coinbase (NASDAQ: COIN)

---

### Slide 10: Reflection — What I Learned, What I'd Do Differently (~3 min)

This is an interesting question because the success of the Flow launch was directly informed by asking ourselves 'what would we do differently' after every previous launch. I ran cross-functional retros after each protocol launch, and the strategies that made Flow successful — early custodian partnerships, deep protocol team embedding, the go/no-go checklist — all came from mistakes we made on earlier launches and iterated on. So in a real sense, this launch was the answer to that question asked four or five times over.

But if I'm being specific about Flow itself — I would have pushed harder on producing content with other ecosystem players earlier in the process. Flow had real virality through applications like NBA Top Shot, and I think leaning into that with co-branded content and more visible participation in the ecosystem would have further cemented our position as the top provider in the eyes of token holders. We did some of this, but not as aggressively or as early as we could have.

---

## SECTION 3: CLOSING

---

### Slide 11: Connection to Brain Co. (~1 min)

I want to close by connecting this back to why I'm here.

The Flow launch was about building infrastructure for a platform where the technology was evolving in real time, the ecosystem partners were critical to success, and being embedded with the protocol team early was the difference between winning and losing the market. Speed mattered, but building the right system mattered more.

That's the same challenge Brain Co. is solving. The AI landscape is moving faster than institutions can absorb it. The companies that embed with these organizations now, build real applications that ship to production, and earn those relationships through delivery — those are the companies that will define this space.

That's the kind of work I want to do, and that's what I'm here to talk about. I'd love to take your questions.

---

## TIMING GUIDE

| Slide | Section | Target | Hard Stop |
|---|---|---|---|
| 1 | Who I Am | ~2 min | 3 min |
| 2 | Why PM | ~1 min | 1.5 min |
| 3 | Why Brain Co., Why Now | ~3 min | 4 min |
| 4 | Context | ~1 min | 1.5 min |
| 5 | Problem Framing | ~3-4 min | 5 min |
| 6 | Three Decisions | ~10-12 min | 14 min |
| 7 | Collaboration | ~4-5 min | 6 min |
| 8 | Artifacts | ~3 min | 4 min |
| 9 | Results | ~2-3 min | 3 min |
| 10 | Reflection | ~3 min | 4 min |
| 11 | Closing | ~1 min | 1.5 min |
| **Total content** | | **~33-40 min** | |
| **Q&A woven throughout** | | **~15 min** | |

---

## VISUAL ASSETS TO INCLUDE

- Career timeline (Slide 1)
- Flow website screenshot with brand logos — Samsung, UFC, Warner Music (Slide 4 or 8)
- NBA Top Shot screenshot (Slide 4 or 8)
- KPI framework diagram — 33% target / 66% supermajority (Slide 8)
- Press coverage cluster — CoinDesk, Yahoo Finance, FFNews (Slide 8 or 9)
- Coinbase Flow Delegation Guide screenshot (Slide 8)
- Results metric cards (Slide 9)
