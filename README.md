# Awesome-AI-Safety-Evaluation-Platform

## Top AI Safety Evaluation Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Red Teaming, Safety Benchmarks, Jailbreak Evaluation, Guardrail Testing, Model Risk Assessment & Continuous AI Safety Scoring*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Safety Evaluation**. These systems systematically test models and applications for jailbreaks, toxic or biased outputs, prompt injection success, policy violations, and other safety failures—supporting pre-deployment gates, regression testing, and ongoing risk scoring.



**Examples** include Lakera, HiddenLayer, Patronus AI, Fiddler AI, Arthur AI, Robust Intelligence, CalypsoAI, Protect AI, Aporia, NVIDIA NeMo Guardrails, Virtue AI, and Invariant Labs (the category leaders and adjacent platforms).



**Open-source emphasis**: Safety evaluation has a rich open ecosystem. **garak**, **Promptfoo**, **DeepEval**, **Inspect**, and related frameworks enable rigorous, automated testing. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Lakera / Lakera Guard](https://www.lakera.ai/)**  

  LLM security and evaluation platform known for prompt-injection testing, practical defenses, and safety-oriented assessment of AI applications.



- **[Patronus AI](https://www.patronus.ai/)**  

  Evaluation platform focused on hallucination, safety, and quality scoring for LLM applications in production and pre-production workflows.



- **[HiddenLayer, Protect AI, Robust Intelligence, CalypsoAI](https://www.hiddenlayer.com/)**  

  AI security platforms offering adversarial testing, model risk assessment, red teaming, and safety/security evaluation across the AI lifecycle.



- **[Fiddler AI, Arthur AI, Aporia](https://www.fiddler.ai/)**  

  ML and LLM observability platforms with monitoring, drift, and evaluation capabilities that support ongoing safety and performance assessment.



- **[NVIDIA NeMo Guardrails / NVIDIA AI safety tooling](https://www.nvidia.com/)**  

  Guardrails and evaluation-oriented tooling within the NVIDIA AI ecosystem for controlling and assessing model behavior.



- **[Virtue AI, Invariant Labs & similar evaluation vendors](https://www.lakera.ai/)**  

  Additional platforms focused on AI safety testing, invariant checking, and structured evaluation of agent and model behavior.



## Open-Source GitHub Projects



- **[garak (NVIDIA)](https://github.com/NVIDIA/garak)**  

  Leading open LLM vulnerability scanner—probes models for jailbreaks, leakage, misinformation, and other safety failures with extensible probe libraries.



- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  

  Open-source LLM evaluation and red-teaming framework for CI/CD—compare models, run security test suites, and gate deployments on safety metrics.



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  Open evaluation framework for LLM applications with metrics for faithfulness, toxicity, bias, and custom safety criteria.



- **[Inspect AI (UK AISI / related)](https://github.com/UKGovernmentBEIS/inspect_ai)**  

  Open framework for large-scale AI evaluations, including safety and capability assessments used in research and policy contexts.



- **[NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Open programmable guardrails that also support evaluation of whether policies and rails hold under adversarial inputs.



- **[LLM Guard & safety filter libraries](https://github.com/protectai/llm-guard)**  

  Open scanners for inputs/outputs used both as runtime controls and as evaluation signals in safety pipelines.



- **[HELM, Eleuther evaluation harnesses & academic benchmarks](https://github.com/stanford-crfm/helm)**  

  Open benchmark suites and harnesses for systematic model evaluation across safety-relevant and general capabilities.



- **[Custom red-team datasets & jailbreak collections](https://github.com/search?q=jailbreak+dataset+OR+LLM+red+team+open+source)**  

  Community datasets and scripts for stress-testing models against known attack patterns.



### Additional Strong Open-Source Options



- **Automated red teaming**: garak and Promptfoo for continuous safety regression.

- **Application-level metrics**: DeepEval for RAG and agent safety scores.

- **Research-scale eval**: Inspect and HELM-style harnesses for broad capability/safety studies.

- **Guardrail verification**: Test NeMo rails and LLM Guard policies under adversarial suites.

- **Composable stacks**: Promptfoo/garak in CI + DeepEval metrics + dashboard for a full open safety evaluation loop.

- Commercial platforms still lead in managed adversarial intelligence, multi-model dashboards, and enterprise reporting.



**Frameworks for building custom systems**:  

**garak** + **Promptfoo** + **DeepEval** form a strong open safety evaluation core.  

Add **Inspect** or academic harnesses for deeper studies, and **NeMo Guardrails** / **LLM Guard** to close the loop from eval to control.  

Commercial platforms (Lakera, Patronus, HiddenLayer, Protect AI, Fiddler, Arthur, Robust Intelligence, etc.) provide polished workflows, threat updates, and organizational reporting.  

Many teams run open evaluation in every PR and use commercial AI safety platforms for periodic deep assessments and board-level risk views. Fully open evaluation pipelines are production-ready for continuous testing.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Safety evaluation is necessary but not sufficient. Passing a test suite does not guarantee safety in deployment. Models and agents change; evaluations must be continuous and threat models updated.

- Open-source tools offer transparency and CI integration but require you to design suites, interpret scores, and act on failures. Commercial platforms shift operational burden and threat intelligence to the vendor. Use multiple evaluation approaches for high-stakes systems.



---



**Made for AI safety researchers, ML platform teams, and organizations deploying LLMs and agents responsibly.**  

Let's expand open, rigorous AI safety evaluation while recognizing the coverage and operational maturity that leading commercial platforms deliver.
