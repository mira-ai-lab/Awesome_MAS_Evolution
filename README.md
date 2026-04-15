<div align="center">

<img src="figs/survey_logo.png" style="width: 70%;"/>

## Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution

[![Awesome](https://img.shields.io/badge/Awesome-0066CC?style=for-the-badge&logo=awesome-lists&logoColor=white)](https://github.com/sindresorhus/awesome) [![Survey](https://img.shields.io/badge/Paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_ARXIV_ID) [![Github](https://img.shields.io/badge/Companion--Repo-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PLACEHOLDER_ORG/PLACEHOLDER_REPO) [![HF Papers](https://img.shields.io/badge/HF--Paper-%23FFD14D?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/papers/PLACEHOLDER_HF_PAPER_ID) [![Twitter](https://img.shields.io/badge/Twitter-%23000000.svg?style=for-the-badge&logo=x&logoColor=white)](https://x.com/PLACEHOLDER/status/PLACEHOLDER_TWEET_ID)

</div>

> **Replace all `PLACEHOLDER_*` URLs** (survey PDF/arXiv, GitHub org/repo, Hugging Face Papers, X/Twitter, legacy links, and any `https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD` rows) before public release.  
> We welcome issues for missing or misclassified papers: `https://github.com/PLACEHOLDER_ORG/PLACEHOLDER_REPO/issues`.

## News

- **[PLACEHOLDER_DATE]** Survey manuscript sources are maintained under `latex/` (see `latex/bare_jrnl_new_sample4.tex` and `latex/reference.bib`).
- **[PLACEHOLDER_DATE]** Curated paper tables in this README are aligned with the four-part lifecycle: **Individual Intelligence → Multi-Agent Collaboration → Failure Attribution → Self-Evolution**.
- **[PLACEHOLDER_DATE]** `PLACEHOLDER_NEWS_ITEM` (e.g., arXiv release, project page, or dataset drop).

## Citation

If you find this survey useful, please cite (update venue fields after publication):

```bibtex
@article{qi2026beyond,
  title   = {Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution},
  author  = {Qi, Shihao and Ma, Jie and Xing, Rui and Guo, Wei and Huang, Xiao and Gao, Zhitao and Deng, Jianhao and Liu, Jun and Zhang, Lingling and Wei, Bifan and Wang, Pinghui and Wu, Yaqiang and Liu, Hui and Tao, Jing and Liu, Tongliang},
  journal = {PLACEHOLDER_VENUE},
  year    = {PLACEHOLDER_YEAR}
}
```

## Contents

- [Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution](#beyond-individual-intelligence-a-survey-of-multi-agent-collaboration-attribution-and-evolution)
- [News](#news)
- [Citation](#citation)
- [Contents](#contents)
- [Overview](#overview)
- [Paper List](#paper-list)
  - [Individual Intelligence: Core Capabilities and Boundary Analysis](#individual-intelligence-core-capabilities-and-boundary-analysis)
    - [Overview: From LLM to LLM-based Agent](#overview-from-llm-to-llm-based-agent)
    - [Reasoning: Input-Stage Enhancement](#reasoning-input-stage-enhancement)
    - [Reasoning: Reasoning-Process Enhancement](#reasoning-reasoning-process-enhancement)
    - [Reasoning: Output-Stage Regulation](#reasoning-output-stage-regulation)
    - [Memory: Formation](#memory-formation)
    - [Memory: Maintenance](#memory-maintenance)
    - [Memory: Retrieval and Utilization](#memory-retrieval-and-utilization)
    - [Planning: Decomposition-Based](#planning-decomposition-based)
    - [Planning: Search-Based](#planning-search-based)
    - [Tool Use: Capability Acquisition](#tool-use-capability-acquisition)
    - [Tool Use: Invocation](#tool-use-invocation)
    - [Tool Use: Generalization](#tool-use-generalization)
  - [Multi-Agent Collaboration](#multi-agent-collaboration)
    - [Role](#role)
    - [Communication](#communication)
    - [Orchestration](#orchestration)
    - [Interaction](#interaction)
    - [Evaluation](#evaluation)
    - [Discussion](#discussion)
  - [Multi-Agent System Failure Attribution](#multi-agent-system-failure-attribution)
    - [Formal Definition](#formal-definition)
    - [MAS Failure Category](#mas-failure-category)
    - [Failure Attribution Taxonomy](#failure-attribution-taxonomy)
    - [Failure Attribution Evaluation](#failure-attribution-evaluation)
    - [Challenges and Future Directions](#challenges-and-future-directions)
  - [Multi-Agent System Self-Evolution](#multi-agent-system-self-evolution)
    - [Motivation](#motivation)
    - [From Attribution to Evolution](#from-attribution-to-evolution)
    - [Formalizing Multi-Agent System Self-Evolution](#formalizing-multi-agent-system-self-evolution)
    - [MAS Self-Evolution Taxonomy](#mas-self-evolution-taxonomy)
    - [Agentic Self-Evolution](#agentic-self-evolution)
    - [Systemic Self-Evolution](#systemic-self-evolution)
    - [Meta Self-Evolution](#meta-self-evolution)
- [Acknowledgment](#acknowledgment)
- [Star History](#star-history)

## Overview

This companion repository supports the survey **Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution**, which studies the **full operational lifecycle** of LLM-based multi-agent systems (MAS): single-agent foundations, collaboration design, runtime failure attribution, and self-evolution that closes the loop from diagnosis to structural adaptation.

<p align="center">
   <img src="figs/teaser.png" alt="Survey overview figure (replace with lifecycle figure if needed)" style="width: 100%;">
</p>

We organize the literature around **four main pillars** (mirroring the manuscript):

1. **Individual intelligence:** Reasoning, memory, planning, and tool use as modular capabilities of a single LLM-based agent.
2. **Multi-agent collaboration:** Roles, communication modes/protocols, orchestration topology, and interaction policies.
3. **Failure attribution:** Formal definitions, failure taxonomies, attribution methods, and evaluation benchmarks.
4. **Self-evolution:** From postmortem signals to updates at agentic, systemic, and meta levels (prompts, memory, parameters, topology, team composition, and whole-system design).

> Replace `figs/teaser.png` with the official survey teaser when available.

## Paper List

Representative entries include **stable public links** (arXiv, official blogs, or GitHub) used in `latex/reference.bib`. Additional rows can be marked with **`https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD`** until curated. Tables follow the same column convention as the prior Awesome-style README: **Date | Nickname | Title | Paper | Github**.

---

### Individual Intelligence: Core Capabilities and Boundary Analysis

#### Overview: From LLM to LLM-based Agent

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-08 | `LLM-Agent-Survey` | A survey on large language model based autonomous agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://link.springer.com/article/10.1007/s11704-024-50795-9) | - |
| 2025-02 | `The-Rise-of-LLM-Agents` | The rise and potential of large language model based agents: A survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://doi.org/10.1007/s11432-024-4025-8) | - |
| 2023-05 | `ReAct` | ReAct: Synergizing reasoning and acting in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2210.03629) | - |
| 2023-12 | `Reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.11366) | [![GitHub Stars](https://img.shields.io/github/stars/noahshinn024/reflexion?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/noahshinn024/reflexion) |
| TBD | `PLACEHOLDER_ROW` | *Additional foundational agent papers from the survey taxonomy* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_ARXIV_TBD) | - |

#### Reasoning: Input-Stage Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2020-12 | `RAG` | Retrieval-augmented generation for knowledge-intensive NLP tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2005.11401) | - |
| 2024-03 | `Self-RAG` | Self-RAG: Learning to retrieve, generate, and critique through self-reflection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.11511) | [![GitHub Stars](https://img.shields.io/github/stars/AkariAsai/self-rag?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/AkariAsai/self-rag) |
| TBD | `PLACEHOLDER_ROW` | *More input-stage reasoning papers (e.g., KG/RAG variants in the survey)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Reasoning: Reasoning-Process Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2022-01 | `CoT` | Chain-of-thought prompting elicits reasoning in large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2201.11903) | - |
| 2025-01 | `DeepSeek-R1` | DeepSeek-R1: Incentivizing reasoning capability in LLMs via reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.12948) | [![GitHub Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-R1?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/deepseek-ai/DeepSeek-R1) |
| 2023-05 | `ToT` | Tree of Thoughts: Deliberate problem solving with large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.10601) | - |
| TBD | `PLACEHOLDER_ROW` | *Search, PRM, and RL-for-reasoning rows to mirror survey tables* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Reasoning: Output-Stage Regulation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-05 | `Self-Consistency` | Self-consistency improves chain of thought reasoning in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2203.11171) | - |
| 2023-10 | `FActScore` | FActScore: Fine-grained atomic evaluation of factual precision in long form text generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.14251) | - |
| TBD | `PLACEHOLDER_ROW` | *Hallucination mitigation / verification rows from the survey* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Formation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-04 | `Generative-Agents` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2304.03442) | [![GitHub Stars](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/joonspk-research/generative_agents) |
| 2024-10 | `MemGPT` | MemGPT: Towards LLMs as operating systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) | [![GitHub Stars](https://img.shields.io/github/stars/cpacker/MemGPT?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/cpacker/MemGPT) |
| TBD | `PLACEHOLDER_ROW` | *Abstractive distillation / typed routing (survey Section Memory Formation)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Maintenance

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Consolidation, forgetting, and lifecycle control (survey subsection)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Retrieval and Utilization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Retrieval policies and utilization at decision time* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Planning: Decomposition-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Task decomposition and hierarchical planning (survey subsection)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Planning: Search-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Search-space expansion / path verification at planning time* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Capability Acquisition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Learning to use APIs / toolkits (survey subsection)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Invocation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Schemas, function calling, and closed-loop tool loops* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Generalization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Generalization to unseen tools and environments* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent Collaboration

#### Role

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-05 | `CAMEL` | CAMEL: Communicative agents for mind exploration of LLM society | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.17760) | [![GitHub Stars](https://img.shields.io/github/stars/camel-ai/camel?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/camel-ai/camel) |
| 2024-05 | `ChatDev` | ChatDev: Communicative agents for software development | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2307.07924) | [![GitHub Stars](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/OpenBMB/ChatDev) |
| 2025-07 | `MAPoRL` | MAPoRL: Multi-agent post-co-training for collaborative LLMs with RL | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.18439) | [![GitHub Stars](https://img.shields.io/github/stars/chanwoo-park-official/MAPoRL?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/chanwoo-park-official/MAPoRL) |
| TBD | `PLACEHOLDER_ROW` | *Role allocation / heterogeneous teams (survey Role section)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Communication

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-11 | `MCP` | Introducing the Model Context Protocol (Anthropic) | [![Blog](https://img.shields.io/badge/Official-1F4E79?style=for-the-badge)](https://modelcontextprotocol.io) | [![GitHub Stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/modelcontextprotocol/servers) |
| 2025-04 | `A2A` | Agent2Agent (A2A) protocol (Google) | [![Blog](https://img.shields.io/badge/Official-1F4E79?style=for-the-badge)](https://google.github.io/A2A/) | [![GitHub Stars](https://img.shields.io/github/stars/google/A2A?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/google/A2A) |
| TBD | `PLACEHOLDER_ROW` | *Explicit vs implicit communication modes (survey Communication)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Orchestration

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-08 | `MetaGPT` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.00352) | [![GitHub Stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/geekan/MetaGPT) |
| 2024-02 | `GPTSwarm` | GPTSwarm: Language agents as optimizable graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.16823) | [![GitHub Stars](https://img.shields.io/github/stars/metauto-ai/gptswarm?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/metauto-ai/gptswarm) |
| TBD | `PLACEHOLDER_ROW` | *Topology search, pruning, decentralized routing (survey Orchestration)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Interaction

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-08 | `AutoGen` | AutoGen: Enabling next-gen LLM applications via multi-agent conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.08155) | [![GitHub Stars](https://img.shields.io/github/stars/microsoft/autogen?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/microsoft/autogen) |
| 2024-07 | `LLM-MAS-Survey-IJCAI` | Large language model based multi-agents: A survey of progress and challenges | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://www.ijcai.org/proceedings/2024/876) | - |
| TBD | `PLACEHOLDER_ROW` | *Interaction policies and debate / critique patterns* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Benchmarks and metrics for collaborative MAS (survey Evaluation)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Discussion

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Position papers and design trade-offs referenced in Discussion* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Failure Attribution

#### Formal Definition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Formalization of failures, responsibility, and observables* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### MAS Failure Category

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-03 | `MAST` | Why do multi-agent LLM systems fail? (MAST / MAST-Data) | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.13657) | [![GitHub Stars](https://img.shields.io/github/stars/multi-agent-systems-failure-taxonomy/MAST?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/multi-agent-systems-failure-taxonomy/MAST) |
| TBD | `PLACEHOLDER_ROW` | *Additional failure-mode taxonomies cited in the survey* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Failure Attribution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-04 | `Who-When` | Which agent causes task failures and when? On automated failure attribution of LLM multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.00212) | [![GitHub Stars](https://img.shields.io/github/stars/mingyin1/Agents_Failure_Attribution?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/mingyin1/Agents_Failure_Attribution) |
| 2025-05 | `TRAIL` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| TBD | `PLACEHOLDER_ROW` | *Attribution methods aligned with survey taxonomy* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Failure Attribution Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-09 | `AgentErrorBench` | Where LLM agents fail and how they can learn from failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025-09 | `Diagnosing-Agentic-Systems` | Diagnosing failure root causes in platform-orchestrated agentic systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| TBD | `PLACEHOLDER_ROW` | *Additional benchmarks / leaderboards* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Challenges and Future Directions

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2026-02 | `CHIEF` | From flat logs to causal graphs: hierarchical failure attribution for LLM-based MAS | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.23701) | - |
| TBD | `PLACEHOLDER_ROW` | *Open challenges summarized in the survey conclusion* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Self-Evolution

#### Motivation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-07 | `Self-Evolving-Agents-Survey` | A survey of self-evolving agents: What, when, how, and where to evolve | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.21046) | - |
| 2025-08 | `Self-Evolving-AI-Agents-Survey` | A comprehensive survey of self-evolving AI agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.07407) | - |
| TBD | `PLACEHOLDER_ROW` | *Motivation bridges from attribution to evolution* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### From Attribution to Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Works explicitly connecting diagnosis signals to system updates* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Formalizing Multi-Agent System Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *Formal models of evolutionary operators (survey subsection)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### MAS Self-Evolution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *High-level taxonomy overview (see subsections below)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Agentic Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-10 | `MorphAgent` | MorphAgent: Empowering agents through self-evolving profiles and decentralized collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.15048) | - |
| 2025-10 | `CoMAS` | CoMAS: Co-evolving multi-agent systems via interaction rewards | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08529) | - |
| 2025-10 | `Multi-Agent-Evolve` | Multi-agent evolve: LLM self-improve through co-evolution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.23595) | - |
| TBD | `PLACEHOLDER_ROW` | *Prompt / memory / parameter / tool evolution (survey Agentic level)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Systemic Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-02 | `GPTSwarm` | GPTSwarm: Language agents as optimizable graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.16823) | [![GitHub Stars](https://img.shields.io/github/stars/metauto-ai/gptswarm?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/metauto-ai/gptswarm) |
| TBD | `PLACEHOLDER_ROW` | *Topology, team composition, shared memory evolution* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Meta Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-05 | `MAS-ZERO` | MAS-zero: Designing multi-agent systems with zero supervision | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.14996) | - |
| 2025-03 | `MAS-GPT` | MAS-GPT: Training LLMs to build LLM-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.03686) | - |
| 2024-08 | `ADAS` | Automated design of agentic systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2408.08435) | [![GitHub Stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/ShengranHu/ADAS) |
| TBD | `PLACEHOLDER_ROW` | *Meta-search / architecture generators (survey Meta level)* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

## Acknowledgment

This README structure follows the **Awesome-style survey companion** format (logo, badges, news, citation, deep `Contents`, `Overview` figure, and wide markdown tables). Source manuscript and BibTeX live under `latex/`. Replace every **`PLACEHOLDER_*`** token with your public release URLs. Optional: link a legacy branch or archive with `PLACEHOLDER_LEGACY_TREE_URL` if older Awesome lists should remain discoverable.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=PLACEHOLDER_ORG/PLACEHOLDER_REPO&type=Date)](https://www.star-history.com/#PLACEHOLDER_ORG/PLACEHOLDER_REPO&Date)
