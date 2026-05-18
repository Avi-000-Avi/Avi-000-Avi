<div align="center">

```
█████╗ ██╗   ██╗██╗
██╔══██╗██║   ██║██║
███████║██║   ██║██║
██╔══██║╚██╗ ██╔╝██║
██║  ██║ ╚████╔╝ ██║
╚═╝  ╚═╝  ╚═══╝  ╚═╝
```

### `avinash toppo` — backend engineer who ships, breaks, fixes, and ships again

**🇮🇳 Bengaluru · Distributed systems by day · Agents & on-chain curiosity by night · Cinema in between**

[![Mail](https://img.shields.io/badge/email-let's_talk-e8ff5a?style=for-the-badge&logo=protonmail&logoColor=black)](mailto:toppo.avinash@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-connect-1f1f1f?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/toppo-avinash/)
[![X](https://img.shields.io/badge/@toppo__avinash-follow-0f0f0f?style=for-the-badge&logo=x&logoColor=white)](https://x.com/toppo__avinash)

</div>

---

## `whoami`

```bash
$ cat ~/.identity
─────────────────────────────────────────────────────
role          backend engineer · distributed systems
company       ADP — SecurTime (workforce scheduling)
prev          Settlin (seed-stage PropTech)
edu           B.Tech CS · IIIT Guwahati '21
yoe           4
stack         java · spring boot · kafka · redis · pg
focus         event-driven systems · agentic ai · web3
─────────────────────────────────────────────────────
```

I write the unglamorous backend code that quietly keeps things running at 3 AM — the kind that doesn't trend on Twitter but absolutely needs to be correct. **Exactly-once Kafka pipelines. CDC-driven cache invalidation. 23-service migrations with zero client regressions. Sub-100ms P95 at 300k+ daily ops.** That kind of thing.

Off the clock, I'm building agentic systems, deploying React Native apps, and shooting Wong Kar-wai-coded short films with AI tools because apparently one craft was never enough.

---

## `🪙 web3 — i want back in`

In **ETHOnline 2021**, I was on the team behind [**FIN — Financially Intelligent NFTs**](https://ethglobal.com/showcase/fin-financially-intelligent-nfts-xerrk) — NFT-wrapped ERC-20 positions where Chainlink Keepers triggered Uniswap swaps when price targets hit. The project picked up **four prizes**: Chainlink Pool, Skynet Pool, Moralis (2nd place), and a Uniswap Grants honorable mention.

I was a junior contributor on **frontend**, learning the basics as I went. The heavy lifting on smart contracts and architecture was done by teammates who knew the space far better than I did. I came away with a working mental model of how Solidity, oracles, and decentralized hosting fit together — and then I went deep on distributed systems for the next four years.

**I never went back. I should have. I'm fixing that now.**

The honest pitch:

- I have **4 years of production backend chops** (Kafka, Spring Boot, Redis, Postgres at real scale) that I didn't have in 2021
- I've shipped real distributed systems — event-driven architectures, idempotency, exactly-once semantics — concepts that translate directly to on-chain reasoning
- I'm an open-source-and-philosophy-first person, and the credible-neutrality, permissionless-composability ethos is what I actually want to build for
- I'm **re-learning the smart contract stack from scratch** (Foundry, viem, account abstraction, L2 mechanics) and looking for places to apply it

> **🤝 If you're building on-chain — DeFi, infra, tooling, agentic on-chain workflows — and you'd take a senior backend engineer who's web3-curious-but-relearning, I'm open. Open source contributions, learning-in-public projects, or part-time/freelance once I'm warmed back up. Talk to me.**

---

## `currently shipping`

<table>
<tr>
<td width="50%" valign="top">

### 🌊 **Pravah**
*household food intelligence — react native + supabase*

The one problem nobody in India has solved: **"what should we make for dinner with what's in the fridge, given the maid didn't show up?"** Constraint-first cooking, leftover rescue, zero-waste streaks. Heading to the Play Store.

`react-native` `expo` `supabase` `sentry` `zustand`

</td>
<td width="50%" valign="top">

### 🧠 **QuantMind**
*multi-agent algo trading platform — python + aws*

LLM agents that coordinate via SQS — signal generation, risk evaluation, execution — on AWS Lambda. Indian broker integrations (Upstox, Zerodha, Angel One). Built to ship to prod, not be a notebook.

`python` `lambda` `sqs` `langchain` `llms`

</td>
</tr>
</table>

---

## `the stack i ship with`

```yaml
core_backend:
  languages:   [java, python, typescript, sql]
  frameworks:  [spring boot, fastapi, express, expo]
  messaging:   [kafka, sqs, redis streams]
  data:        [postgresql, mongodb, elasticsearch, redis]
  cloud:       [aws (lambda, sqs, ec2, s3), supabase]
  observ:      [dynatrace, cloudwatch, sentry, posthog]

ai_layer:
  models:      [claude, gpt, gemini]
  workflows:   [claude code, cursor, codex, mcp]
  agents:      [langchain, custom orchestration]
  systems:     [.ai/ context layers, prompt contracts, rag]

web3_relearning:
  shipped_in_2021:  [react/web3 frontend on a chainlink+uniswap team]
  learning_now:     [foundry, viem, solidity, account abstraction]
  curious_about:    [intent-based defi, on-chain agents, l2s, mev]

infra_tooling:
  ci_cd:       [github actions, jenkins]
  testing:     [junit5, mockito, contract tests]
  patterns:    [outbox, saga, cqrs, circuit breaker, idempotency]
```

---

## `production war stories`

> *receipts, not vibes*

| at | what i actually shipped | the receipt |
|---|---|---|
| **ADP** | .NET monolith → 23 Spring Boot services, 50+ integrations | **zero client regression** |
| **ADP** | Redis distributed cache with CDC invalidation | **81% latency cut, 92% hit rate** |
| **ADP** | MTTR overhaul via Dynatrace + correlation IDs | **45min → 12min (-73%)** |
| **ADP** | Real-time scheduling at scale | **300k+ shifts/day · P95 <100ms** |
| **Settlin** | Incentive engine, exactly-once on Kafka | **99.9% accuracy under retries** |
| **Settlin** | MongoDB 2dsphere geospatial property search | **3.2s → 800ms** |
| **Settlin** | Webhook delivery pipeline + DLQ | **99.5% delivery, exponential backoff** |
| **ETHOnline '21** | Frontend contributor on a team that won 4 prizes | learned the stack, want back in |

---

## `currently obsessing over`

```diff
+ multi-agent systems · how to make non-determinism behave
+ ai-first development · the .ai/ context-layer pattern
+ india-first product design · pravah's "maid mode"
+ web3 — properly this time · foundry, l2s, on-chain agents
+ cinematic AI workflows · higgsfield, capcut, FCP
- pretending kubernetes yaml is a personality
- claiming credit for work other people did
```

---

## `🤝 i'm open for`

<table>
<tr>
<td width="33%" valign="top">

### **🌱 open source**
distributed systems, kafka patterns, agentic tooling.

i review PRs in good faith and write the kind of issues people actually want to pick up.

ship tests with the code, not "in a follow-up PR."

</td>
<td width="33%" valign="top">

### **🪙 web3 — relearning**
open to:
- low-stakes open-source contributions (frontend or backend infra around protocols)
- pair-coding / mentorship from people deeper in the space
- side projects that force me to write real solidity again
- part-time once i'm not green anymore

honesty over hype.

</td>
<td width="33%" valign="top">

### **💼 freelance**
- backend systems · event-driven architectures
- ai integration · agent design · rag pipelines
- react native MVPs (end-to-end)

~10–15hrs/week — small bets, high-trust work.

</td>
</tr>
</table>

**📬 reach me:** [toppo.avinash@gmail.com](mailto:toppo.avinash@gmail.com) · responses within 24h, in actual prose, not boilerplate.

---

## `the other side`

Because reducing humans to job titles is dimensionality reduction that loses signal:

- 📚 **763 books logged** — cinema theory to systems books to the occasional poetry that survives
- 🎬 **Cinephile** with a Wong Kar-wai / Tarkovsky aesthetic — building short films with Higgsfield, *"The Drowned Library"* in flight
- 🧘 **High-agency intentional living** — manifesto-writer, attention-fragment skeptic
- 🏋️ **Fitness & nutrition** — Bengaluru meal plans, deliberate physical practice
- 🧑‍🍳 **The Springz Nutrition orbit** — met the founders at the gym, pitch playbook still warm

---

<div align="center">

```
"the bar for 'good' just got higher.
lean into taste, judgment, and the unsexy infra problems."
```

*— me, to myself, at 1 AM, in a notion page i'll probably never reread*

⭐ **if any of my repos saved you an hour, star it — that's the actual currency here**

</div>
