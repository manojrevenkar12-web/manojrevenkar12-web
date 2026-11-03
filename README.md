<!-- ═══════════════════════════════════════════════════════════════════════
     Manoj Kumar P · GitHub profile README
     ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:38BDF8&height=230&section=header&text=Manoj%20Kumar%20P&fontSize=60&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Senior%20AI%20Engineer%20%C2%B7%20Generative%20%26%20Agentic%20AI%20%C2%B7%20Banking%20%26%20Payments&descSize=19&descAlignY=58&descAlign=50" width="100%" alt="Manoj Kumar P — Senior AI Engineer" />

<a href="https://github.com/manojrevenkar12-web">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=820&lines=I+build+AI+systems+that+have+to+be+right+%E2%80%94+not+just+impressive.;Every+agent+ships+behind+a+release+gate+it+has+to+pass.;LangGraph+%C2%B7+RAG+%C2%B7+LLM+Evaluation+%C2%B7+Multi-Agent+Systems;14%2B+years+inside+global+banks+%E2%80%94+SWIFT%2C+ISO+20022%2C+KYC%2FAML;Berlin%2C+Germany+%C2%B7+open+to+roles+across+Germany" alt="Typing intro" />
</a>

<br/>

<a href="https://www.linkedin.com/in/manoj-kumar-prakash-52b7a01b6"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="https://aml-investigator.onrender.com"><img src="https://img.shields.io/badge/Live_Demo-AML_Investigator-46E3B7?style=for-the-badge&logo=render&logoColor=0F172A" alt="Live demo" /></a>&nbsp;
<a href="https://github.com/manojrevenkar12-web?tab=repositories"><img src="https://img.shields.io/badge/Repositories-97%2B-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8" alt="Repositories" /></a>

<br/><br/>

<img src="https://img.shields.io/badge/📍_Berlin,_Germany-1E293B?style=flat-square" />
<img src="https://img.shields.io/badge/🟢_Open_to-Senior_AI_%2F_GenAI_%2F_Agentic_AI_roles-1E293B?style=flat-square" />
<img src="https://img.shields.io/badge/🗣️_English_C2_·_German_B1-1E293B?style=flat-square" />
<img src="https://komarev.com/ghpvc/?username=manojrevenkar12-web&label=Profile+views&color=38BDF8&style=flat-square" alt="Profile views" />

</div>

<br/>

## 🧭 About me

<table>
<tr>
<td width="50%" valign="top">

### What I build
- **Agents that are governed, not just clever** — LangGraph state machines that *stop* for a human when unsure, hash-chained audit trails, four-eyes approvals.
- **Evaluation as infrastructure** — golden datasets, LLM-as-judge, measured noise floors, release gates in CI that refuse to ship a model that got worse.
- **Models that know when to abstain** — calibrated confidence and selective prediction for vision and language models, with the trade-off measured, not assumed.
- **RAG and document intelligence over regulated, messy data** — payment messages, compliance alerts, invoices, German tax notices.

</td>
<td width="50%" valign="top">

### Where I come from
- **14+ years inside global banks** — Wells Fargo, JPMorgan Chase, Standard Chartered, ANZ and National Bank of Canada (via CGI).
- **Payments is my home turf** — SWIFT MT/MX, ISO 20022, SEPA, KYC/AML, Oracle FLEXCUBE / OBPM. I know what a `pacs.008` has to look like before an agent touches it.
- **Led an 8-engineer GenAI & automation team** at Wells Fargo — roadmap, hiring, stakeholder scope; shipped RAG-based log analysis and LLM test-data generation for MT103 / MT202 / pacs.008.
- **Now in Berlin**, building in the open and available immediately.

</td>
</tr>
</table>

<br/>

## 🏆 Spotlight

<table>
<tr>
<td>

### 🕵️ [aml-investigator](https://github.com/manojrevenkar12-web/aml-investigator) — Autonomous KYC / AML investigator with a human in the loop

A multi-agent investigation engine **and the compliance console a human uses to supervise it**. Agents triage a transaction-monitoring alert, pull the second-degree transaction network, gather register and adverse-media evidence, assess it against money-laundering typologies and draft the suspicious-activity report — then the graph **stops** and waits for a compliance officer to approve it, return it with a note, or close the case.

Uncited claims are dropped before a reviewer ever sees them (and the risk score is reduced accordingly). Every step lands in a **hash-chained audit trail**. Every generated **goAML** document is XSD-validated. Self-approval is refused.

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI_+_SSE-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/React_+_TypeScript-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/NetworkX-2C6BAC?style=flat-square" /> <img src="https://img.shields.io/badge/goAML_XSD-0A66C2?style=flat-square" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/CI_evals-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

<table>
<tr>
<td width="46%" valign="top">

**The four cases it ships with**

| Alert | Scenario | Outcome |
|---|---|---|
| 0001 | 11 credits just under €10k into a funnel account, one outbound to Panama | investigate · structuring · 99.0 |
| 0002 | Circular flow between four related corporates | investigate · carousel · 69.0 |
| 0003 | Monthly salary mistagged as a business transfer | **auto-closed at triage**, no report |
| 0004 | 22-day-old company forwards 99 % of a €187k credit to the UAE | investigate · pass-through · 55.0 |

</td>
<td width="54%" valign="top">

**Quality gates — CI fails the build on any breach**

| Metric | Gate | Why it matters |
|---|---|---|
| `missed_escalation_rate` | = 0 | a true positive auto-closed is what gets a bank fined |
| `triage_accuracy` · `typology_recall` | = 1.00 | right disposition, right laundering pattern |
| `citation_coverage` | = 1.00 | every finding a reviewer sees is evidenced |
| `determinism` | = 1.00 | identical risk scores across repeated runs |
| `audit_integrity` | = 1.00 | the hash chain verifies |
| `report_schema_validity` | = 1.00 | every goAML document validates |
| `four_eyes_enforced` | = 1.00 | self-approval and unqualified approval refused |

</td>
</tr>
</table>

🌐 **[Live demo](https://aml-investigator.onrender.com)** <sub>(free tier — first load can take ~50 s)</sub> · 🔗 **[Repository](https://github.com/manojrevenkar12-web/aml-investigator)** · 📖 **[Design decisions worth defending in an interview](https://github.com/manojrevenkar12-web/aml-investigator#design-decisions-worth-defending-in-an-interview)**

</td>
</tr>
</table>

<br/>

## 🚀 Featured projects

<sub>Every one of these has a **Results** section measured on held-out data, a test suite, and a CI release gate. Numbers below are copied from the repos.</sub>

<table>
<tr>
<td width="50%" valign="top">

### 💶 [controllable-finance-agents](https://github.com/manojrevenkar12-web/controllable-finance-agents)
**Finance agents built into a ledger — the AI prepares, the accountant decides**

<a href="https://github.com/manojrevenkar12-web/controllable-finance-agents"><img src="https://raw.githubusercontent.com/manojrevenkar12-web/controllable-finance-agents/main/docs/img/inbox.png" width="100%" alt="Review console: bookings ready to approve in bulk, each with its reason" /></a>

Three agents for a German mid-sized company: **coding** (account, cost centre, tax key), **pre-payment checks** and the **month-end close** (deferrals & accruals). Every proposal carries its reasoning and evidence; uncertain cases go to a person; every decision lands in an append-only audit log.

**Measured on 663 documents:** 95.0 % booked exactly right · 62.9 % approved in bulk at 98.1 % exact · payment issues caught 97.8 % with no false alarms · deferrals 54/54. Three flawed candidate versions are **refused by the release gates**, and CI keeps them refused. Blind test sets were written by someone who never saw the code.

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/61_tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />

</td>
<td width="50%" valign="top">

### 📬 [tax-notice-desk](https://github.com/manojrevenkar12-web/tax-notice-desk)
**Document intelligence for German tax notices — deadlines you can't get wrong**

<a href="https://github.com/manojrevenkar12-web/tax-notice-desk"><img src="https://raw.githubusercontent.com/manojrevenkar12-web/tax-notice-desk/main/docs/img/inbox.png" width="100%" alt="Notice desk inbox" /></a>

Reads every notice a group of tax firms receives — electronic, scanned, or a town's own layout — matches it to firm and client, computes the **objection deadline** under the rules of that date, checks it against the filed return, recomputes trade tax and interest, and decides the action.

**Measured on 230 notices (59 % scans):** 0 deadlines later than the real one · 0 notices wrongly closed · 99.6 % deadlines exact · 97.0 % right action · 100 % of planted errors caught, no false alarms · $0.011 in model cost. The release gate **refused to ship the first run** over a sign error on refund interest — the fix is documented, not hidden.

<img src="https://img.shields.io/badge/RAG_over_tax_law-7C3AED?style=flat-square" /> <img src="https://img.shields.io/badge/Document_AI-0F172A?style=flat-square" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/48_tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤐 [llm-abstention-tuning](https://github.com/manojrevenkar12-web/llm-abstention-tuning)
**Post-training a small LLM to say "I don't know" instead of hallucinating**

<a href="https://github.com/manojrevenkar12-web/llm-abstention-tuning"><img src="https://raw.githubusercontent.com/manojrevenkar12-web/llm-abstention-tuning/main/results/qwen2.5-1.5b/risk_coverage.png" width="100%" alt="Risk–coverage curves: base vs SFT vs SFT+DPO" /></a>

`Qwen2.5-1.5B-Instruct`, LoRA **SFT + DPO** on 6,000 probed TriviaQA questions, evaluated in- and out-of-distribution against a prompt-only baseline and against simply thresholding the base model's confidence.

**Hallucination 66.8 % → 5.9 %** on TriviaQA, **86.4 % → 2.4 %** on PopQA; ECE 0.320 → 0.083; selective accuracy 74.3 % vs 70.0 % for the confidence-threshold baseline at matched coverage. The README also reports what failed: the model **over-abstains and 2 of 3 blocking gates fail** — stated up front, with the next run planned.

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/🤗_TRL_·_LoRA-FFD21E?style=flat-square" /> <img src="https://img.shields.io/badge/SFT_+_DPO-7C3AED?style=flat-square" /> <img src="https://img.shields.io/badge/CI-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🔍 [item-identifier](https://github.com/manojrevenkar12-web/item-identifier)
**Fine-grained visual identification that knows when it's unsure**

<a href="https://github.com/manojrevenkar12-web/item-identifier"><img src="https://raw.githubusercontent.com/manojrevenkar12-web/item-identifier/main/results/active_learning/al_curve.png" width="100%" alt="Active learning: uncertainty sampling vs random" /></a>

**DINOv2 ViT-S/14** features, temperature calibration and per-category abstention thresholds fitted on validation and **measured on 8,041 untouched test images** (Stanford Cars, 196 classes). Active-learning loop, FastAPI + ONNX Runtime serving with numerical-parity check, p95 latency gate.

**90.6 % top-1** · calibration error **0.230 → 0.021** (11× better, accuracy unchanged) · **80.6 % of photos auto-identified at 95.9 % precision**, the rest routed to human review · uncertainty sampling needs ~20 % fewer labels than random.

<img src="https://img.shields.io/badge/DINOv2-8E44AD?style=flat-square" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎯 [reward-uplift-lab](https://github.com/manojrevenkar12-web/reward-uplift-lab)
**Does the bonus work, does it pay for itself, and who should get it?**

<a href="https://github.com/manojrevenkar12-web/reward-uplift-lab"><img src="https://raw.githubusercontent.com/manojrevenkar12-web/reward-uplift-lab/main/reports/criteo/figures/criteo_qini.png" width="100%" alt="Qini curve on Criteo Uplift" /></a>

An experimentation and uplift-modelling study, run first on a simulator with known ground truth and then on the real **Criteo Uplift** dataset, with the whole thing repeated over ten draws of the data to check it's robust.

A €0.50 bonus lifts conversion **+2.40 pts** (true +2.28) but **doesn't pay for itself when given to everyone**; targeting the 48 % with positive expected profit earns **€41 more per 1,000 users**. **CUPED** cuts estimator variance 35 %. Peeking at daily p-values gives 31.6 % false positives; **always-valid (mSPRT) p-values** keep it at 1.2 %. A sample-ratio check catches an injected logging bug (p = 3.5×10⁻⁹).

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Causal_inference-F59E0B?style=flat-square" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/60_tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />

</td>
<td width="50%" valign="top">

### 📉 [model-regression-detector](https://github.com/manojrevenkar12-web/model-regression-detector)
**CI-gated LLM evaluation — regressions show up as numbers, not incidents**

A prompt edit that looks harmless can drop accuracy by 10–15 % and nobody notices until production. This pipeline scores an LLM classifier against a hand-labelled golden dataset on every PR, diffs it against the baseline, and **fails the merge** when quality drops.

What makes it credible: the **noise floor is measured first** (two identical back-to-back runs) so thresholds are set empirically, not guessed. Async eval engine, LLM-as-judge scoring, HTML diff reports, Slack alerts, SQLite history, Docker, GitHub Actions gate — and the most iterated history in the portfolio (16 commits, 58 tests).

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/LLM--as--Judge-10B981?style=flat-square" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/58_tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />

</td>
</tr>
</table>

<br/>

## 🧠 How I think about production AI

The same pattern runs through every repo above: **an agent is allowed to act only after a deterministic gate says it may — and the gate is measured before it's trusted.**

```mermaid
flowchart LR
    A[/"📨 SWIFT MT/MX · ISO 20022<br/>KYC / AML event · documents"/] --> B["⚡ FastAPI ingestion<br/>schema validation"]
    B --> C{"🧠 LangGraph<br/>multi-agent state machine"}
    C -->|triage · RAG · tools| D["🔎 Domain agents<br/>payments · compliance · finance · legal"]
    D --> E{"⚖️ Deterministic gate<br/>LLM-as-judge · calibration · regression check"}
    E -->|confident| F["✅ Automated output<br/>goAML report · booking · audit trail"]
    E -->|uncertain → abstain| G["🙋 Human-in-the-loop<br/>review console"]
    G --> H[("📚 Golden dataset<br/>grows with every review")]
    H -.->|CI eval on every PR| E

    classDef ingest fill:#0F172A,stroke:#38BDF8,color:#E2E8F0,stroke-width:1.5px
    classDef agent  fill:#1E293B,stroke:#38BDF8,color:#E2E8F0,stroke-width:1.5px
    classDef gate   fill:#172554,stroke:#60A5FA,color:#E2E8F0,stroke-width:2px
    classDef out    fill:#064E3B,stroke:#34D399,color:#ECFDF5,stroke-width:1.5px
    classDef human  fill:#422006,stroke:#FBBF24,color:#FEF3C7,stroke-width:1.5px
    class A,B,H ingest
    class C,D agent
    class E gate
    class F out
    class G human
```

<br/>

## 🗂️ More projects

<details open>
<summary><b>🏦 Payments, banking & compliance AI</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [swift-ai-engine](https://github.com/manojrevenkar12-web/swift-ai-engine) | SWIFT & ISO 20022 intelligence engine — message explainer, anomaly detector, MT → MX migrator, test-case generator | `Python` `LangChain` `Streamlit` |
| [identity-risk-graph](https://github.com/manojrevenkar12-web/identity-risk-graph) | Identity risk graph — scoring fraud and KYC risk across linked identities and accounts | `graph` `risk scoring` |
| [tm-model-lifecycle](https://github.com/manojrevenkar12-web/tm-model-lifecycle) | Transaction-monitoring (AML) model lifecycle — development, validation, monitoring | `Python` `scikit-learn` `model risk` |
| [governed-ai-gateway](https://github.com/manojrevenkar12-web/governed-ai-gateway) | Governed LLM gateway for regulated enterprises — policy, routing, audit | `FastAPI` `policy` |
| [payments-lakehouse-accelerator](https://github.com/manojrevenkar12-web/payments-lakehouse-accelerator) | Spark / Delta Lake accelerator for payments data on Databricks | `PySpark` `Delta` `Databricks` |
| [payment-ops-copilot](https://github.com/manojrevenkar12-web/payment-ops-copilot) | RAG copilot for payment operations on the MEAN stack | `LangChain` `ChromaDB` `Node` `Angular` |
| [payment-qa-dashboard](https://github.com/manojrevenkar12-web/payment-qa-dashboard) | Real-time payment telemetry & release observability dashboard | `JavaScript` `Playwright` |

</details>

<details>
<summary><b>🧪 LLM evaluation, agents research & reliability</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [agentic-engineering-harness](https://github.com/manojrevenkar12-web/agentic-engineering-harness) | How should a team work with coding agents? Real agents work a ticket backlog in parallel sandboxes; each change graded the way a maintainer would merge it | `Python` `agent eval` `59 tests` |
| [defense-rl-gym](https://github.com/manojrevenkar12-web/defense-rl-gym) | RL environments for defensive security (patching, incident response) — the reward is validated before anything trains on it | `RL` `71 tests` |
| [symbolic-trace-compiler](https://github.com/manojrevenkar12-web/symbolic-trace-compiler) | Source-to-source PyTorch trace compiler where tensor sizes are symbols; guards fuzzed against eager | `PyTorch` `compilers` `50 tests` |
| [cx-agent-context-lab](https://github.com/manojrevenkar12-web/cx-agent-context-lab) | Context-engineering & prompt-caching lab for contact-centre agents | `prompt caching` `eval` |
| [probabilistic-synthetics](https://github.com/manojrevenkar12-web/probabilistic-synthetics) | Synthetic monitoring & alerting for non-deterministic AI systems | `TypeScript` `monitoring` |
| [chat-exposure-guard](https://github.com/manojrevenkar12-web/chat-exposure-guard) | Application-security guard against data exposure in chat / LLM apps | `AppSec` `Python` |

</details>

<details>
<summary><b>⚙️ Agent platforms & AI infrastructure</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [model-router-platform](https://github.com/manojrevenkar12-web/model-router-platform) | One API in front of closed and open-weight models — cheapest model *proven* to meet the quality target, exact-once accounting, row-level tenant isolation | `FastAPI` `LiteLLM` `Postgres RLS` `Redis` |
| [power-desk-agent-platform](https://github.com/manojrevenkar12-web/power-desk-agent-platform) | Governed agent platform on AWS Bedrock / AgentCore for a power-trading desk | `Bedrock` `AgentCore` |
| [rechtsschutz-agent](https://github.com/manojrevenkar12-web/rechtsschutz-agent) | LangGraph intake agent for legal-protection insurance claims | `LangGraph` `German legal` |
| [legal-invoice-review-agents](https://github.com/manojrevenkar12-web/legal-invoice-review-agents) | Multi-agent review of law-firm invoices against billing guidelines | `agents` `document AI` |
| [data-grounding-platform](https://github.com/manojrevenkar12-web/data-grounding-platform) | Grounding platform for statistics — answers that cite the data they came from | `RAG` `platform` |
| [n8n-enterprise-connector-kit](https://github.com/manojrevenkar12-web/n8n-enterprise-connector-kit) | Enterprise connector kit for n8n workflows | `TypeScript` `n8n` |

</details>

<details>
<summary><b>👁️ Vision, speech, robotics & signals</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [care-stt](https://github.com/manojrevenkar12-web/care-stt) | German speech-to-text for care documentation | `speech ML` |
| [station-cycle-vision](https://github.com/manojrevenkar12-web/station-cycle-vision) | Assembly-station video → cycle-time analytics | `computer vision` `PyTorch` |
| [pod-pick-lab](https://github.com/manojrevenkar12-web/pod-pick-lab) | Robotic fabric-pod picking lab | `robotics` `perception` |
| [onboard-perception-ros2](https://github.com/manojrevenkar12-web/onboard-perception-ros2) | Embedded perception stack on ROS 2 / Jetson | `ROS 2` `Jetson` |
| [spectrum-ssl-edge](https://github.com/manojrevenkar12-web/spectrum-ssl-edge) | Self-supervised learning on RF spectrum data, edge-deployable | `signal ML` `SSL` |
| [bodensee-sar-autonomy](https://github.com/manojrevenkar12-web/bodensee-sar-autonomy) | Deep-RL planning for UAV search-and-rescue over Lake Constance | `RL` `simulation` |
| [uxv-ml-platform](https://github.com/manojrevenkar12-web/uxv-ml-platform) | ML platform for drone / UxV sensor data | `ML platform` `MLOps` |

</details>

<br/>

## 🛠️ Tech stack

<div align="center">

**Generative & Agentic AI**

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" /> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/Anthropic_Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" /> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/vLLM_·_LiteLLM-0F172A?style=for-the-badge" /> <img src="https://img.shields.io/badge/MCP-0F172A?style=for-the-badge" /> <img src="https://img.shields.io/badge/RAG_·_Qdrant_·_Milvus_·_Chroma-0F172A?style=for-the-badge" /> <img src="https://img.shields.io/badge/LLM--as--Judge_evals-0F172A?style=for-the-badge" />

**ML & Data**

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,anaconda&theme=dark" />
<br/>
<img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white" /> <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" /> <img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" />

**Backend, platform & delivery**

<img src="https://skillicons.dev/icons?i=fastapi,java,ts,react,nodejs,postgres,redis,sqlite,docker,kubernetes,aws,gcp,githubactions,terraform,grafana,linux&theme=dark" />

**Payments & regulatory domain**

<img src="https://img.shields.io/badge/SWIFT_MT_%2F_MX-E30613?style=for-the-badge" /> <img src="https://img.shields.io/badge/ISO_20022-003399?style=for-the-badge" /> <img src="https://img.shields.io/badge/SEPA-1E40AF?style=for-the-badge" /> <img src="https://img.shields.io/badge/KYC_%2F_AML_·_goAML-0A66C2?style=for-the-badge" /> <img src="https://img.shields.io/badge/Oracle_FLEXCUBE_·_OBPM-C74634?style=for-the-badge&logo=oracle&logoColor=white" /> <img src="https://img.shields.io/badge/EU_AI_Act_·_DORA_·_GDPR-334155?style=for-the-badge" />

</div>

<br/>

## 📊 GitHub activity

<div align="center">

<a href="https://github.com/manojrevenkar12-web">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=manojrevenkar12-web&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9&ring_color=38BDF8" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manojrevenkar12-web&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&hide=html,css,jupyter%20notebook" alt="Top languages" />
</a>

<br/><br/>

<a href="https://github.com/manojrevenkar12-web">
  <img src="https://streak-stats.demolab.com?user=manojrevenkar12-web&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" alt="GitHub streak" />
</a>

<br/><br/>

<a href="https://github.com/manojrevenkar12-web">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=manojrevenkar12-web&bg_color=0D1117&color=C9D1D9&line=38BDF8&point=FFFFFF&area=true&area_color=38BDF8&hide_border=true&title_color=38BDF8" width="100%" alt="Contribution graph" />
</a>

</div>

<br/>

## 📜 Certifications

<div align="center">

<img src="https://img.shields.io/badge/IIT_Guwahati-Professional_Certificate_in_Generative_AI_%26_ML-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A" /> &nbsp;
<img src="https://img.shields.io/badge/Microsoft-Azure_Fundamentals_(AZ--900)-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A" />

</div>

<br/>

## 🤝 Let's build something

<div align="center">

I'm based in **Berlin** and open to **Senior AI / Generative AI / Agentic AI Engineer** roles anywhere in Germany — especially where AI has to meet regulation, money or both.

<br/>

<a href="https://www.linkedin.com/in/manoj-kumar-prakash-52b7a01b6"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;
<a href="https://github.com/manojrevenkar12-web?tab=repositories"><img src="https://img.shields.io/badge/Browse_all_repositories-0F172A?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<sub>⭐ If one of these repos helps you, a star goes a long way.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:1E3A8A,100:0F172A&height=120&section=footer" width="100%" alt="" />

</div>
