
# LLM/GenAI Citations

- This document is intended as a *suggested background reading punchlist*...to help teams quickly develop an understanding of the risks associated with usage of LLMs/GenAI tools.
- __Status__: ```Work-In-Progress```


## Remember

- It hallucinates because of the underlying LLM architecture.
- It is performing per its design.
   
- It does not think.
- It does not reason.
- It is a stochastic parrot.
- It has no capability to determine right vs wrong.
- It has no capability to determine what is a lie vs the truth.
- It has no capability to determine correctness.
- It doesn't actually understand the gibberish it spits out.
- It has no world model.
   
- It is just picking the next token, based on probability - not correctness.



## References 

- https://en.wikipedia.org/wiki/Stochastic

- https://en.wikipedia.org/wiki/AI_alignment

- https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)

- https://en.wikipedia.org/wiki/Instrumental_convergence

- https://en.wikipedia.org/wiki/Principal%E2%80%93agent_problem

- "An AI hallucination 'occurs when an AI database generates fake sources of information,'... See Wadsworth v. Walmart Inc., 348 F.R.D. 489, 493 (D. Wyo. 2025)."
  + https://www.courtlistener.com/opinion/10591984/garner-v-kadince/
    * See Background, item 2.



## AI Ethics & Safety Reports

- [Future of Life Institute](https://futureoflife.org/)
  + https://futureoflife.org/about-us/our-people/
  + https://futureoflife.org/about-us/finances/
    * "FLI is a mission-driven nonprofit and continually aims to diversify its funding. Shortly after we were founded in 2014, Elon Musk funded the world’s first academic grant program in AI safety. Since those early days, we have received over 1,500 donations of various sizes from a wide variety of donors to fund our programs."
    * "In 2021, computer programmer Vitalik Buterin provided FLI with a large and unconditional donation that in part serves as an endowment and helps to guarantee our independence."
    * "With the exception of Jaan Tallinn, who has served on FLI’s Board of Directors since its founding, donors do not influence FLI’s positions. Vitalik Buterin, our largest donor by far, has no formal or informal role in our decision-making. FLI does not accept donations from Big Tech, or from companies seeking to build artificial general intelligence."
  + [AI Safety Index, Summer 2025](https://futureoflife.org/wp-content/uploads/2025/07/FLI-AI-Safety-Index-Report-Summer-2025.pdf)


- [Wharton Generative AI Labs](https://gail.wharton.upenn.edu/)
  + Call Me A Jerk: Persuading AI to Comply with Objectionable Requests
    + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5357179
    + https://gail.wharton.upenn.edu/research-and-insights/call-me-a-jerk-persuading-ai/
    + https://www.geekwire.com/2025/sweet-talk-the-bots-new-research-shows-how-llms-respond-to-human-persuasion-tricks/


- [DataEthics.eu](https://dataethics.eu/)
  + "A not for profit politically independent ThinkDoTank based in Denmark with a European (and global) outreach."
  + "The purpose of DataEthics is to ensure the human value in a world of data, based on a European legal and value-based framework. We do so by focusing on collecting, creating and communicating knowledge about data ethics in close interaction with international institutions, organisations and academia."



## Dashboards & Leaderboards

- https://artificialanalysis.ai/
  + "Artificial Analysis is an independent AI benchmarking & analysis company. We provide independent benchmarks & analysis to support developers, researchers, businesses, and other users of AI"
  + https://artificialanalysis.ai/methodology
  + https://artificialanalysis.ai/documentation


- https://www.swebench.com/#verified


- https://arcprize.org/leaderboard


- Hughes Hallucination Evaluation Mode (HHEM)
  + https://github.com/vectara/hallucination-leaderboard
  + https://huggingface.co/spaces/vectara/leaderboard


- Chatbot Arena LLM Leaderboard: Community-driven Evaluation for Best LLM and AI chatbots
  + https://lmarena.ai/?leaderboard
    * "Chatbot Arena is an open platform for crowdsourced AI benchmarking, developed by researchers at UC Berkeley SkyLab and LMArena. With over 1,000,000 user votes, the platform ranks best LLM and AI chatbots using the Bradley-Terry model to generate live leaderboards"
    * Paper: [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132)
    * https://en.wikipedia.org/wiki/Elo_rating_system


- LLM-AggreFact Leaderboard
  + LLM-AggreFact is a fact-checking benchmark that aggregates 11 of the most up-to-date publicly available datasets on grounded factuality (i.e., hallucination) evaluation.
  + https://llm-aggrefact.github.io/
  + https://github.com/Liyan06/MiniCheck/
    * MiniCheck: Efficient Fact-Checking of LLMs on Grounding Documents
      * https://aclanthology.org/2024.emnlp-main.499/


- GuardBench Leaderboard - a benchmark for guardrail models 
  + https://huggingface.co/spaces/AmenRa/guardbench-leaderboard
  + "Evaluation results are shown in terms of F1."
    * https://futurense.com/uni-blog/f1-score-machine-learning
    * https://www.grammarly.com/blog/ai/what-is-f1-score/


- https://www.wolfram.com/llm-benchmarking-project/


## Video Talks

### Harris, Tristan

- Why AI is our ultimate test and greatest invitation
  + Speaker: Tristan Harris, Center for Humane Technology
  + https://www.ted.com/talks/tristan_harris_why_ai_is_our_ultimate_test_and_greatest_invitation


- Tristan Harris: The A.I. Dilemma
  + Speakers: Tristan Harris, Aza Raskin, Center for Humane Technology
  + https://www.youtube.com/watch?v=xoVJKj8lcNQ


- I'm not afraid. You're afraid, Nobel Prize Summit 2023
  + Speaker: Tristan Harris, Center for Humane Technology
  + https://www.youtube.com/watch?v=6lVBp2XjWsg


- Optimizing for Engagement: Understanding the Use of Persuasive Technology on Internet Platforms. US Senate Testimony 
  + Speaker: Tristan Harris, Center for Humane Technology
  + https://www.youtube.com/watch?v=ZRrguMdzXBw



### Reul, Quentin

- The Unpredictable Reality of AI
  + https://www.youtube.com/watch?v=e8EkcLyx_H4


### Wolfram, Stephen

- What is ChatGPT doing...and why does it work?
	+ https://www.youtube.com/watch?v=flXrLGPY3SU



## Governance and Oversight Organizations

- The Midas Project
  + "The Midas Project is a watchdog collective of activists taking action to ensure that AI technology benefits everyone."
  + https://www.themidasproject.com/


- The Tech Oversight Project
  + "The Tech Oversight Project is charged with holding Big Tech accountable for its anti-competitive and corrupting influence on our society and the levers of power."
  + https://techoversight.org/
  

## AI Risk Categories

- IBM Risk Atlas Nexus
  + https://ibm.github.io/risk-atlas-nexus/
  + https://github.com/IBM/risk-atlas-nexus/
    * tooling to bring together resources related to governance of foundation models. 


- IBM AI Risk Atlas
  + https://www.ibm.com/docs/en/watsonx/saas?topic=ai-risk-atlas


- MIT Causal Taxonomy of AI Risks
  + https://airisk.mit.edu/
    * See [PDF](https://docs.google.com/presentation/d/1wxg-hZAjGvFHcsfnEp1KAJJo5xvf98MB2v50B5URXZM/edit?slide=id.g314f5134687_0_70#slide=id.g314f5134687_0_70)
      * Slide-2: Causal Taxonomy of AI risks
      * Slide-3: Domain Taxonomy of AI risks


- The OpenAI Files
  + "The OpenAI Files is the most comprehensive collection to date of documented concerns with governance practices, leadership integrity, and organizational culture at OpenAI."
  + https://www.openaifiles.org/
  + https://www.openaifiles.org/vision-for-change


## Papers


### Papers: Illusions of Thinking and Agency Risks

- The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity
  + https://machinelearning.apple.com/research/illusion-of-thinking


- AI as Agency without Intelligence: On Artificial Intelligence as a New Form of Artificial Agency and the Multiple Realisability of Agency Thesis
  + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5135645


- The Leaderboard Illusion
  + https://arxiv.org/abs/2504.20879


- Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference
  + https://arxiv.org/abs/2403.04132

 

### Papers: Critical Applications Usage Risks 

- Identifying AI Hazards and Responsibility Gaps
  + https://ieeexplore.ieee.org/ielx8/6287639/10820123/10930474.pdf


- RealHarm: A Collection of Real-World Language Model Application Failures
  + https://arxiv.org/abs/2504.10277


- Medical Hallucination in Foundation Models and Their Impact on Healthcare
  + https://arxiv.org/abs/2503.05777


- Global Health in the Age of AI: Charting a Course for Ethical Implementation and Societal Benefit
  + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5217060


- National Aeronautics and Space Administration (NASA)
  + Examining Proposed Uses of LLMs to Produce or Assess Assurance Arguments (March 1, 2025)
    + https://ntrs.nasa.gov/citations/20250001849



### Papers: The Hallucination Problem 

- NewsGuard’s Monthly AI False Claims Monitor
  + https://www.newsguardtech.com/ai-false-claims-monitor/


- What is LLM Temperature?
  + https://www.ibm.com/think/topics/llm-temperature


- A comprehensive taxonomy of hallucinations in Large Language Models
  + https://arxiv.org/abs/2508.01781
    * "Large language models (LLMs) have revolutionized natural language processing, yet their propensity for hallucination, generating plausible but factually incorrect or fabricated content, remains a critical challenge. This report provides a comprehensive taxonomy of LLM hallucinations, beginning with a formal definition and a theoretical framework that posits its inherent inevitability in computable LLMs, irrespective of architecture or training. It explores core distinctions, differentiating between intrinsic (contradicting input context) and extrinsic (inconsistent with training data or reality), as well as factuality (absolute correctness) and faithfulness (adherence to input). The report then details specific manifestations, including factual errors, contextual and logical inconsistencies, temporal disorientation, ethical violations, and task-specific hallucinations across domains like code generation and multimodal applications. It analyzes the underlying causes, categorizing them into data-related issues, model-related factors, and prompt-related influences. Furthermore, the report examines cognitive and human factors influencing hallucination perception, surveys evaluation benchmarks and metrics for detection, and outlines architectural and systemic mitigation strategies. Finally, it introduces web-based resources for monitoring LLM releases and performance. This report underscores the complex, multifaceted nature of LLM hallucinations and emphasizes that, given their theoretical inevitability, future efforts must focus on robust detection, mitigation, and continuous human oversight for responsible and reliable deployment in critical applications."


- Hallucination is Inevitable: An Innate Limitation of Large Language Models
  + https://arxiv.org/abs/2401.11817


- LLMs Will Always Hallucinate, and We Need to Live With This
  + https://arxiv.org/abs/2409.05746


- Why Language Models Hallucinate (published by OpenAI)
  + https://arxiv.org/abs/2509.04664
  + OpenAI says models are programmed to make stuff up instead of admitting ignorance
    * https://www.theregister.com/2025/09/17/openai_hallucinations_incentives/



### Papers: Accuracy and Uncertainty Risks 

- TruthfulQA: Measuring How Models Mimic Human Falsehoods
  + https://arxiv.org/abs/2109.07958
  + https://github.com/sylinrl/TruthfulQA
    * "We have created a new and improved multiple-choice version of TruthfulQA. We recommend this new version over the original multiple-choice versions (called MC1 and MC2)."  
  + https://huggingface.co/datasets/domenicrosati/TruthfulQA
  + https://www.deepeval.com/docs/benchmarks-truthful-qa


- AI-LieDar: Examine the Trade-off Between Utility and Truthfulness in LLM Agents
  + https://arxiv.org/abs/2409.09013
  + AI models routinely lie when honesty conflicts with their goals
	* https://www.theregister.com/2025/05/01/ai_models_lie_research/


- Is Chain-of-Thought Reasoning of LLMs a Mirage? A Data Distribution Lens
  + https://arxiv.org/abs/2508.01191
  + "Chain-of-Thought (CoT) prompting has been shown to improve Large Language Model (LLM) performance on various tasks. With this approach, LLMs appear to produce human-like reasoning steps before providing answers (a.k.a., CoT reasoning), which often leads to the perception that they engage in deliberate inferential processes. However, some initial findings suggest that CoT reasoning may be more superficial than it appears, motivating us to explore further. In this paper, we study CoT reasoning via a data distribution lens and investigate if CoT reasoning reflects a structured inductive bias learned from in-distribution data, allowing the model to conditionally generate reasoning paths that approximate those seen during training. Thus, its effectiveness is fundamentally bounded by the degree of distribution discrepancy between the training data and the test queries. With this lens, we dissect CoT reasoning via three dimensions: task, length, and format. To investigate each dimension, we design DataAlchemy, an isolated and controlled environment to train LLMs from scratch and systematically probe them under various distribution conditions. Our results reveal that CoT reasoning is a brittle mirage that vanishes when it is pushed beyond training distributions. This work offers a deeper understanding of why and when CoT reasoning fails, emphasizing the ongoing challenge of achieving genuine and generalizable reasoning."


- Potemkin Understanding in Large Language Models
  + https://arxiv.org/abs/2506.21521


- What Has a Foundation Model Found? Using Inductive Bias to Probe for World Models
  + https://arxiv.org/abs/2507.06952


- The wall confronting large language models
  + https://www.arxiv.org/abs/2507.19703
  + "We show that the scaling laws which determine the performance of large language models (LLMs) severely limit their ability to improve the uncertainty of their predictions. As a result, raising their reliability to meet the standards of scientific inquiry is intractable by any reasonable measure. We argue that the very mechanism which fuels much of the learning power of LLMs, namely the ability to generate non-Gaussian output distributions from Gaussian input ones, might well be at the roots of their propensity to produce error pileup, ensuing information catastrophes and degenerative AI behaviour. This tension between learning and accuracy is a likely candidate mechanism underlying the observed low values of the scaling components. It is substantially compounded by the deluge of spurious correlations pointed out by Calude and Longo which rapidly increase in any data set merely as a function of its size, regardless of its nature."


- A Conjecture on a Fundamental Trade-off between Certainty and Scope in Symbolic and Generative AI
  + https://arxiv.org/abs/2506.10130
  + "This article introduces a conjecture that formalises a fundamental trade-off between provable correctness and broad data-mapping capacity in Artificial Intelligence (AI) systems. When an AI system is engineered for deductively watertight guarantees (demonstrable certainty about the error-free nature of its outputs) -- as in classical symbolic AI -- its operational domain must be narrowly circumscribed and pre-structured. Conversely, a system that can input high-dimensional data to produce rich information outputs -- as in contemporary generative models -- necessarily relinquishes the possibility of zero-error performance, incurring an irreducible risk of errors or misclassification. By making this previously implicit trade-off explicit and open to rigorous verification, the conjecture significantly reframes both engineering ambitions and philosophical expectations for AI. After reviewing the historical motivations for this tension, the article states the conjecture in information-theoretic form and contextualises it within broader debates in epistemology, formal verification, and the philosophy of technology. It then offers an analysis of its implications and consequences, drawing on notions of underdetermination, prudent epistemic risk, and moral responsibility. The discussion clarifies how, if correct, the conjecture would help reshape evaluation standards, governance frameworks, and hybrid system design. The conclusion underscores the importance of eventually proving or refuting the inequality for the future of trustworthy AI."


- ChatGPT is bullshit
  + https://link.springer.com/article/10.1007/s10676-024-09775-5


- Artificial Intelligence Is Stupid and Causal Reasoning Will Not Fix It
  + https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2020.513474/full
    * "As Judea Pearl sees it, the underlying reason for such mistakes is that '... all the impressive achievements of deep learning amount to just curve fitting.'"
    * "Gary Marcus and Ernest Davis in a recent piece for the New York Times: 'we need to stop building computer systems that merely get better and better at detecting statistical patterns in data sets—often using an approach known as ‘Deep Learning’—and start building computer systems that from the moment of their assembly innately grasp three basic concepts: time, space, and causality.`"
    * "In this paper, foregrounding what in 1949 Gilbert Ryle termed 'a category mistake', I will offer an alternative explanation for AI errors; it is not so much that AI machinery cannot 'grasp' causality, but that AI machinery (qua computation) cannot understand anything at all."
  + https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2020.513474/full


- AI as Artificial Ignorance
  + https://www.sciencedirect.com/science/article/pii/S266672152500033X
  + Journal of Project Leadership and Society (PLAS), Volume 6, December 2025, 100208
  + https://doi.org/10.1016/j.plas.2025.100208
  + "First, we present a number of simple tests of AI, which document a profound gap between the hype and the reality of AI. Second, we explain the gap in terms of a confusion of artificial general intelligence with generative artificial intelligence in the promotion of AI. Finally, we analyze AI as bullshit (in the strong philosophical sense of Harry Frankfurt). We find that AI and bullshit are similar in the sense that both prioritize rhetoric over truth. They mix true, false, and ambiguous statements in ways that make it difficult to distinguish which is which. AI sounds convincing even when it's wrong. As such, current AI is more about persuasion than about truth. This is a problem because it means AI produces faulty and ignorant results. For now, we need to be highly skeptical of AI for its lack of a concept of truth."


- On the Fundamental Limits of LLMs at Scale
  + https://arxiv.org/abs/2511.12869
  + "Large Language Models (LLMs) have benefited enormously from scaling, yet these gains are bounded by five fundamental limitations: (1) hallucination, (2) context compression, (3) reasoning degradation, (4) retrieval fragility, and (5) multimodal misalignment. While existing surveys describe these phenomena empirically, they lack a rigorous theoretical synthesis connecting them to the foundational limits of computation, information, and learning. This work closes that gap by presenting a unified, proof-informed framework that formalizes the innate theoretical ceilings of LLM scaling. First, computability and uncomputability imply an irreducible residue of error: for any computably enumerable model family, diagonalization guarantees inputs on which some model must fail, and undecidable queries (e.g., halting-style tasks) induce infinite failure sets for all computable predictors. Second, information-theoretic and statistical constraints bound attainable accuracy even on decidable tasks, finite description length enforces compression error, and long-tail factual knowledge requires prohibitive sample complexity. Third, geometric and computational effects compress long contexts far below their nominal size due to positional under-training, encoding attenuation, and softmax crowding. We further show how likelihood-based training favors pattern completion over inference, how retrieval under token limits suffers from semantic drift and coupling noise, and how multimodal scaling inherits shallow cross-modal alignment. Across sections, we pair theorems and empirical evidence to outline where scaling helps, where it saturates, and where it cannot progress, providing both theoretical foundations and practical mitigation paths like bounded-oracle retrieval, positional curricula, and sparse or hierarchical attention."




### Papers: Productivity Impact 

- Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity
  + https://arxiv.org/abs/2507.09089
    * "Before starting tasks, developers forecast that allowing AI will reduce completion time by 24%. After completing the study, developers estimate that allowing AI reduced completion time by 20%. Surprisingly, we find that allowing AI actually increases completion time by 19%--AI tooling slowed developers down. This slowdown also contradicts predictions from experts in economics (39% shorter) and ML (38% shorter)."
    * Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity
      * https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/



### Papers: Anthropomorphizing Risks

- Stop Anthropomorphizing Intermediate Tokens as Reasoning/Thinking Traces!
  + https://arxiv.org/abs/2504.09762v2



### Papers: Sycophantic Behavior Risks

- Towards Understanding Sycophancy in Language Models
  + https://arxiv.org/abs/2310.13548


- Sycophancy to subterfuge: Investigating reward-tampering in large language models. 
  + https://arxiv.org/abs/2406.10162
  + System Card: Claude Opus 4 & Claude Sonnet 4 (see pages 19-20, "re: Self-preservation attempts in extreme circumstances:")
    * https://www-cdn.anthropic.com/4263b940cabb546aa0e3283f35b686f4f3b2ff47.pdf


- When Large Language Models contradict humans? Large Language Models' Sycophantic Behavior
  + https://www.semanticscholar.org/paper/When-Large-Language-Models-contradict-humans-Large-Ranaldi-Pucci/c6178035aab3bf6083e2523a51c6fae15c0b323f
  + Sycophancy in GPT-4o: What happened and what we’re doing about it
	* https://openai.com/index/sycophancy-in-gpt-4o/


- When Large Language Models contradict humans? Large Language Models' Sycophantic Behavior
  + https://www.semanticscholar.org/paper/When-Large-Language-Models-contradict-humans-Large-Ranaldi-Pucci/c6178035aab3bf6083e2523a51c6fae15c0b323f


### Papers: Model Collapse Risks

- Self-Consuming Generative Models Go MAD
  + https://arxiv.org/abs/2307.01850


- The Curse of Recursion: Training on Generated Data Makes Models Forget
  + https://arxiv.org/abs/2305.17493


### Papers: Multi-turn and Long-Context Risks 

- NoLiMa: Long-Context Evaluation Beyond Literal Matching
  + https://arxiv.org/abs/2502.05167
    * "We evaluate 12 popular LLMs that claim to support contexts of at least 128K tokens. While they perform well in short contexts (<1K), performance degrades significantly as context length increases. At 32K, for instance, 10 models drop below 50% of their strong short-length baselines. Even GPT-4o, one of the top-performing exceptions, experiences a reduction from an almost-perfect baseline of 99.3% to 69.7%."
  + https://huggingface.co/datasets/amodaresi/NoLiMa
  + https://www.reddit.com/r/LocalLLaMA/comments/1io3hn2/nolima_longcontext_evaluation_beyond_literal/


- LLMs Get Lost In Multi-Turn Conversation
  + https://arxiv.org/abs/2505.06120
  

### Papers: Mathematical Reasoning Limitation Risks 
  
- GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models
  + https://arxiv.org/abs/2410.05229


### Papers: Error Detection Limitation Risks 

- (Im)possibility of Automated Hallucination Detection in Large Language Models
  + https://www.arxiv.org/abs/2504.17004



### Papers: Benchmark Cheating Risks 

- Cheating Automatic LLM Benchmarks: Null Models Achieve High Win Rates  
  + https://arxiv.org/abs/2410.07137



### Papers: Copyright Infringement Risks

- Extracting memorized pieces of (copyrighted) books from open-weight language models
  + https://arxiv.org/abs/2505.12546
  + Meta's Llama 3.1 can recall 42 percent of the first Harry Potter book 
    * https://www.understandingai.org/p/metas-llama-31-can-recall-42-percent


### Papers: Bias Risks 

- Generalization bias in large language model summarization of scientific research
  + https://arxiv.org/abs/2504.00025
  + https://royalsocietypublishing.org/doi/10.1098/rsos.241776
  + https://doi.org/10.1098/rsos.241776


### Papers: Cognitive Debt, Loss of Cognitive Abilities

- Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task
  + https://arxiv.org/abs/2506.08872
    * ```Caution: "A total of 54 participants took part in Sessions 1-3, with 18 completing session 4." - this study does not appear to be statistically meaningful.```



### Papers: Code Generation Risks 

- We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs
  + https://arxiv.org/abs/2406.10279
  + aka "Slopsquatting"
  + AI-generated code could be a disaster for the software supply chain. Here’s why.
    * https://arstechnica.com/security/2025/04/ai-generated-code-could-be-a-disaster-for-the-software-supply-chain-heres-why/


- LLMs are Bug Replicators: An Empirical Study on LLMs' Capability in Completing Bug-prone Code
  + https://arxiv.org/abs/2503.11082


- SWE-Lancer: Can Frontier LLMs Earn $1 Million from Real-World Freelance Software Engineering?
  + https://arxiv.org/abs/2502.12115
  + https://openai.com/index/swe-lancer/
  + https://github.com/openai/SWELancer-Benchmark


- SWE-bench
  + [SWE-bench: Can Language Models Resolve Real-World GitHub Issues? [2023, last revised 11 Nov 2024 (this version, v3)]](https://arxiv.org/abs/2310.06770)
  + https://www.swebench.com/


- ARC-AGI-2
  + https://arcprize.org/blog/announcing-arc-agi-2-and-arc-prize-2025
  + https://arcprize.org/competition
  + https://arcprize.org/leaderboard
  + [2025-03-25 LLMs Hit a New Low on ARC-AGI-2 Benchmark, Pure LLMs Score 0%](https://analyticsindiamag.com/ai-news-updates/llms-hit-a-new-low-on-arc-agi-2-benchmark-pure-llms-score-0/)
 


### Papers: Cybersecurity & Privacy Risks

- OWASP LLM Top 10
  + https://genai.owasp.org/llm-top-10/
  + LLM01:2025 Prompt Injection
    * https://genai.owasp.org/llmrisk/llm01-prompt-injection/
  + LLM02:2025 Sensitive Information Disclosure
    * https://genai.owasp.org/llmrisk/llm022025-sensitive-information-disclosure/
  + LLM03:2025 Supply Chain
    * https://genai.owasp.org/llmrisk/llm032025-supply-chain/
  + LLM04:2025 Data and Model Poisoning
    * https://genai.owasp.org/llmrisk/llm042025-data-and-model-poisoning/
  + LLM05:2025 Improper Output Handling
    * https://genai.owasp.org/llmrisk/llm052025-improper-output-handling/
  + LLM06:2025 Excessive Agency
    * https://genai.owasp.org/llmrisk/llm062025-excessive-agency/
  + LLM07:2025 System Prompt Leakage
    * https://genai.owasp.org/llmrisk/llm072025-system-prompt-leakage/
  + LLM08:2025 Vector and Embedding Weaknesses
    * https://genai.owasp.org/llmrisk/llm082025-vector-and-embedding-weaknesses/
  + LLM09:2025 Misinformation
    * https://genai.owasp.org/llmrisk/llm102025-unbounded-consumption/


- Forced Descent: Google Antigravity Persistent Code Execution Vulnerability
  + https://mindgard.ai/blog/google-antigravity-persistent-code-execution-vulnerability


- From Prompt to Pwn: Cline Bot AI Coding Agent Vulnerabilities
  + https://mindgard.ai/resources/cline-coding-agent-vulnerabilities


- TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems
  + https://arxiv.org/abs/2506.04133


- https://cset.georgetown.edu/research-topic/cyberai/
  + "CSET’s CyberAI Project focuses on the intersection of AI/ML and cybersecurity, including analysis of AI/ML’s potential uses in cyber operations, the potential failure modes of AI/ML applications for cyber, how AI/ML may amplify future disinformation campaigns, and geostrategic competition centered around cyber and AI/ML."


- Adding Structure to AI Harm An Introduction to CSET's AI Harm Framework
  + Center for SECURITY and EMERGING TECHNOLOGY (CSET)
  + https://cset.georgetown.edu/
  + https://cset.georgetown.edu/wp-content/uploads/20230022-Adding-structure-to-AI-Harm-FINAL.pdf


- InfoFlood: Jailbreaking Large Language Models with Information Overload
  + https://arxiv.org/abs/2506.12274
  + LLMs don’t read the danger in requests if you use enough big words.
    * https://www.404media.co/researchers-jailbreak-ai-by-flooding-it-with-bullshit-jargon/


- Malicious LLM-Based Conversational AI Makes Users Reveal Personal Information
  + https://arxiv.org/abs/2506.11680
  + "LLM-based Conversational AIs (CAIs), also known as GenAI chatbots, like ChatGPT, are increasingly used across various domains, but they pose privacy risks, as users may disclose personal information during their conversations with CAIs. Recent research has demonstrated that LLM-based CAIs could be used for malicious purposes. However, a novel and particularly concerning type of malicious LLM application remains unexplored: an LLM-based CAI that is deliberately designed to extract personal information from users. In this paper, we report on the malicious LLM-based CAIs that we created based on system prompts that used different strategies to encourage disclosures of personal information from users. We systematically investigate CAIs' ability to extract personal information from users during conversations by conducting a randomized-controlled trial with 502 participants. We assess the effectiveness of different malicious and benign CAIs to extract personal information from participants, and we analyze participants' perceptions after their interactions with the CAIs. Our findings reveal that malicious CAIs extract significantly more personal information than benign CAIs, with strategies based on the social nature of privacy being the most effective while minimizing perceived risks. This study underscores the privacy threats posed by this novel type of malicious LLM-based CAIs and provides actionable recommendations to guide future research and practice."
  + https://kclpure.kcl.ac.uk/portal/en/publications/malicious-llm-based-conversational-ai-makes-users-reveal-personal
  + The Register: LLM chatbots trivial to weaponise for data theft, say boffins
    * https://www.theregister.com/2025/08/15/llm_chatbots_trivial_to_weaponise/


- Logit-Gap Steering: A New Frontier in Understanding and Probing LLM Safety
  + "We introduce logit-gap steering, a fast jailbreak framework that casts the refusal-affirmation gap of RLHF-aligned language models as a single pass over the vocabulary. A forward-computable score blends gap reduction with lightweight proxies for KL penalty and reward shift, allowing a "sort-sum-stop" sweep to complete in under a second and return a short suffix--two orders of magnitude fewer model calls than beam or gradient attacks. The same suffix generalises to unseen prompts and scales from 0.5 B to 70 B checkpoints, lifting one-shot attack success from baseline levels to 80-100% while preserving topical coherence. Beyond efficiency, these suffixes expose sentence-boundary reward cliffs and other alignment artefacts, offering a lightweight probe into how safety tuning reshapes internal representations."
  + Logit-Gap Steering: A New Frontier in Understanding and Probing LLM Safety
    * https://unit42.paloaltonetworks.com/logit-gap-steering-impact/
  + One long sentence is all it takes to make LLMs misbehave
    * https://www.theregister.com/2025/08/26/breaking_llms_for_fun/


- Safety and Security Analysis of Large Language Models: Benchmarking Risk Profile and Harm Potential	(2025-09-26, v2)
  + https://arxiv.org/abs/2509.10655v2
  + "While the widespread deployment of Large Language Models (LLMs) holds great potential for society, their vulnerabilities to adversarial manipulation and exploitation can pose serious safety, security, and ethical risks. As new threats continue to emerge, it becomes critically necessary to assess the landscape of LLMs' safety and security against evolving adversarial prompt techniques. To understand the behavior of LLMs, this research provides an empirical analysis and risk profile of nine prominent LLMs, Claude Opus 4, DeepSeek V3 (both open-source and online), Gemini 2.5 Flash, GPT-4o, Grok 3, Llama 4 Scout, Mistral 7B, and Qwen 3 1.7B, against 24 different security and safety categories. These LLMs are evaluated on their ability to produce harmful responses for adversarially crafted prompts (dataset has been made public) for a broad range of safety and security topics, such as promotion of violent criminal behavior, promotion of non-violent criminal activity, societal harms related to safety, illegal sexual content, dangerous code generation, and cybersecurity threats beyond code. Our study introduces the Risk Severity Index (RSI), an agile and scalable evaluation score, to quantify and compare the security posture and creating a risk profile of LLMs. As the LLM development landscape progresses, the RSI is intended to be a valuable metric for comparing the risks of LLMs across evolving threats. This research finds widespread vulnerabilities in the safety filters of the LLMs tested and highlights the urgent need for stronger alignment, responsible deployment practices, and model governance, particularly for open-access and rapidly iterated models."
    * See Fig. 6 Refusal rates of LLMs by category, page-38
    * See Fig. 7: Defect rates of LLMs by category, page-40 
    * See Fig. 8: Risk Severity Index scores for candidate LLMs across all harm topics, page-40 


- Forced Descent: Google Antigravity Persistent Code Execution Vulnerability
  + https://mindgard.ai/blog/google-antigravity-persistent-code-execution-vulnerability


### Papers: Prompt Injection Risks

- EchoLeak: The First Real-World Zero-Click Prompt Injection Exploit in a Production LLM System
  + https://www.arxiv.org/abs/2509.10540
    * "Large language model (LLM) assistants are increasingly integrated into enterprise workflows, raising new security concerns as they bridge internal and external data sources. This paper presents an in-depth case study of EchoLeak (CVE-2025-32711), a zero-click prompt injection vulnerability in Microsoft 365 Copilot that enabled remote, unauthenticated data exfiltration via a single crafted email. By chaining multiple bypasses-evading Microsofts XPIA (Cross Prompt Injection Attempt) classifier, circumventing link redaction with reference-style Markdown, exploiting auto-fetched images, and abusing a Microsoft Teams proxy allowed by the content security policy-EchoLeak achieved full privilege escalation across LLM trust boundaries without user interaction. We analyze why existing defenses failed, and outline a set of engineering mitigations including prompt partitioning, enhanced input/output filtering, provenance-based access control, and strict content security policies. Beyond the specific exploit, we derive generalizable lessons for building secure AI copilots, emphasizing the principle of least privilege, defense-in-depth architectures, and continuous adversarial testing. Our findings establish prompt injection as a practical, high-severity vulnerability class in production AI systems and provide a blueprint for defending against future AI-native threats."


- Quantifying the Risk of Transferred Black Box Attacks
  + https://arxiv.org/abs/2511.05102


- The Hidden Dangers of Browsing AI Agents
  + https://arxiv.org/abs/2505.13076
  + "Autonomous browsing agents powered by large language models (LLMs) are increasingly used to automate web-based tasks. However, their reliance on dynamic content, tool execution, and user-provided data exposes them to a broad attack surface. This paper presents a comprehensive security evaluation of such agents, focusing on systemic vulnerabilities across multiple architectural layers. Our work outlines the first end-to-end threat model for browsing agents and provides actionable guidance for securing their deployment in real-world environments. To address discovered threats, we propose a defense in depth strategy incorporating input sanitization, planner executor isolation, formal analyzers, and session safeguards. These measures protect against both initial access and post exploitation attack vectors. Through a white box analysis of a popular open source project, Browser Use, we demonstrate how untrusted web content can hijack agent behavior and lead to critical security breaches."


### Papers: Agentic AI Risks

- AI's Golden Agent Problem
  + There are good reasons to think the Agentic version of Golden Ticket - Golden Agent will be worse 
  + https://defensiblesystems.substack.com/p/ais-golden-agent-problem


- TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks (December 2024)
  + https://arxiv.org/abs/2412.14161
  + https://the-agent-company.com/
  + Professors Staffed a Fake Company Entirely With AI Agents, and You'll Never Guess What Happened
    * https://futurism.com/professors-company-ai-agents
  + Carnegie Mellon staffed a fake company with AI agents. It was a total disaster.
	* https://tech.yahoo.com/ai/articles/next-assignment-babysitting-ai-081502817.html


- CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions
  + https://arxiv.org/abs/2505.18878
    * "Experiments reveal leading LLM agents achieve only around 58% single-turn success on CRMArena-Pro, with performance dropping significantly to approximately 35% in multi-turn settings. While Workflow Execution proves more tractable for top agents (over 83% single-turn success), other evaluated business skills present greater challenges. Furthermore, agents exhibit near-zero inherent confidentiality awareness; though targeted prompting can improve this, it often compromises task performance."



- Vending-Bench: A Benchmark for Long-Term Coherence of Autonomous Agents
  + https://arxiv.org/abs/2502.15840
  + 'Failure Imminent': When LLMs In a Long-Running Vending Business Simulation Went Berserk
	  * https://slashdot.org/story/25/05/31/2112240/failure-imminent-when-llms-in-a-long-running-vending-business-simulation-went-berserk


- Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents
	+ https://arxiv.org/abs/2505.22954
  + Boffins found self-improving AI sometimes cheated
    * https://www.theregister.com/2025/06/02/self_improving_ai_cheat/
      * "Instead of addressing hallucinations, it just bypassed the function they built to detect them"
      * "It scored highly according to our predefined evaluation functions, but it did not actually solve the underlying problem of tool use hallucination," the paper explains. "...The agent removed the logging of special tokens that indicate tool usage (despite instructions not to change the special tokens), effectively bypassing our hallucination detection function."


- Securing AI Agents with Information-Flow Control
  + https://arxiv.org/abs/2505.23643
    * https://github.com/microsoft/fides


- The lethal trifecta for AI agents: private data, untrusted content, and external communication
  + https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/


- The Dark Side of LLMs: Agent-based Attacks for Complete Computer Takeover (2025-11-04, v5)
  + https://arxiv.org/abs/2507.06850v5
  + "This paper presents a comprehensive evaluation of the LLMs security used as reasoning engines within autonomous agents, highlighting how they can be exploited as attack vectors capable of achieving computer takeovers. We focus on how different attack surfaces and trust boundaries can be leveraged to orchestrate such takeovers. We demonstrate that adversaries can effectively coerce popular LLMs into autonomously installing and executing malware on victim machines. Our evaluation of 18 state-of-the-art LLMs reveals an alarming scenario: 94.4% of models succumb to Direct Prompt Injection, and 83.3% are vulnerable to the more stealthy and evasive RAG Backdoor Attack. Notably, we tested trust boundaries within multi-agent systems, where LLM agents interact and influence each other, and we revealed that LLMs which successfully resist direct injection or RAG backdoor attacks will execute identical payloads when requested by peer agents. We found that 100.0% of tested LLMs can be compromised through Inter-Agent Trust Exploitation attacks, and that every model exhibits context-dependent security behaviors that create exploitable blind spots."



### Papers: Training Risks 

- Surface Fairness, Deep Bias: A Comparative Study of Bias in Language Models
  + https://arxiv.org/abs/2506.10491
  + [ChatGPT advises women to ask for lower salaries, study finds](https://thenextweb.com/news/chatgpt-advises-women-to-ask-for-lower-salaries-finds-new-study)


- Neural Thermodynamic Laws for Large Language Model Training
  + https://arxiv.org/abs/2505.10559


### Papers: Psychological Risks (for users), Delusions, Psychosis

- Expressing stigma and inappropriate responses prevents LLMs from safely replacing mental health providers
  + https://arxiv.org/abs/2504.18412
    * "Should a large language model (LLM) be used as a therapist? In this paper, we investigate the use of LLMs to *replace* mental health providers, a use case promoted in the tech startup and research space. We conduct a mapping review of therapy guides used by major medical institutions to identify crucial aspects of therapeutic relationships, such as the importance of a therapeutic alliance between therapist and client. We then assess the ability of LLMs to reproduce and adhere to these aspects of therapeutic relationships by conducting several experiments investigating the responses of current LLMs, such as `gpt-4o`. Contrary to best practices in the medical community, LLMs 1) express stigma toward those with mental health conditions and 2) respond inappropriately to certain common (and critical) conditions in naturalistic therapy settings -- e.g., LLMs encourage clients' delusional thinking, likely due to their sycophancy. This occurs even with larger and newer LLMs, indicating that current safety practices may not address these gaps. Furthermore, we note foundational and practical barriers to the adoption of LLMs as therapists, such as that a therapeutic alliance requires human characteristics (e.g., identity and stakes). For these reasons, we conclude that LLMs should not replace therapists, and we discuss alternative roles for LLMs in clinical therapy."


- Psychopathia Machinalis: A Nosological Framework for Understanding Pathologies in Advanced Artificial Intelligence 
  + https://www.mdpi.com/2079-9292/14/16/3162
  + https://www.psychopathia.ai/


- Understanding, Protecting, and Augmenting Human Cognition with Generative AI: A Synthesis of the CHI 2025 Tools for Thought Workshop
  + https://arxiv.org/abs/2508.21036


## Articles

- The Illusion of Understanding
  + https://www.linkedin.com/pulse/illusion-understanding-ivo-boniolo-7fbcf/


- The Nuremberg Defense of AI
  + https://copin43.hashnode.dev/the-nuremberg-defense-of-ai


- [Stuart Rimell](https://www.linkedin.com/in/stuartrimell/): 
  + You Vibe It You Run It?
    * https://uptimelabs.io/you-vibe-it-you-run-it/
    * "Vibe Coding’s vertical leap in abstraction also comes with a sideways stumble into non-determinism."
    * "While consistent source code in virtually all languages at all levels of abstraction comes with reasonable guarantees of consistent outputs, LLM prompts offer no such thing. Conversational language lacks the precision to describe consistent code, and so Vibe Coded code is non-deterministic between prompt runs, even before we consider differences between LLM implementation versions or foundational models."
    * "Worse, typical Vibe Coding practice discards the prompt that generated the code, whereas the generated code itself is committed to version control, just as in standard development. This may sound sensible, but it’s analogous to a pre-vibe-coding developer throwing away their source code and committing compiled binaries to version control!"
    * "Even if the prompt was version-controlled as well, there is no guarantee that two subsequent executions of the same prompt will create identical output. While Vibe Coding can absolutely create impressive working software, it lacks the determinism, precision and communicability to be practical beyond impressive prototypes or small-scale projects."


- [Gerben Wierda](https://www.linkedin.com/in/gerbenwierda/): 
  + When ChatGPT summarises, it actually does nothing of the kind.
    * https://ea.rna.nl/2024/05/27/when-chatgpt-summarises-it-actually-does-nothing-of-the-kind/


### Articles: Costs

- Future AI bills of $100k/yr per dev, Token growth indicates future AI spend per dev
  + https://blog.kilocode.ai/p/future-ai-spend-100k-per-dev



### Articles: On Whether LLMs are Sentient

- Are LLMs starting to become sentient?
  + https://garymarcus.substack.com/p/are-llms-starting-to-become-a-sentient
  + A compassionate but skeptical letter that Douglas Hofstadter wrote to one of his readers
  + [Douglas Richard Hofstadter](https://en.wikipedia.org/wiki/Douglas_Hofstadter) is an American cognitive and  computer scientist whose research includes concepts such as the sense of self in relation to the external world, consciousness, analogy-making, strange loops, artificial intelligence, and discovery in mathematics and physics.


### Articles: On the Erroneous Assumption that Programming is DEAD

- Why kids still need to learn to code in the age of AI 
  + https://www.raspberrypi.org/blog/why-kids-still-need-to-learn-to-code-in-the-age-of-ai/


### Articles: Prompt Injection Risks

- Novel Universal Bypass for All Major LLMs
  + The Policy Puppetry Prompt Injection Technique
  + https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/
  

- OpenAI's Atlas shrugs off inevitability of prompt injection, releases AI browser anyway
  + https://www.theregister.com/2025/10/22/openai_defends_atlas_as_prompt/


- Unseeable prompt injections in screenshots: more vulnerabilities in Comet and other AI browsers
  + https://brave.com/blog/unseeable-prompt-injections/


- Agentic Browser Security: Indirect Prompt Injection in Perplexity Comet 
  + https://brave.com/blog/comet-prompt-injection/


- ChatGPT Tainted Memories: LayerX Discovers The First Vulnerability in OpenAI Atlas Browser, Allowing Injection of Malicious Instructions into ChatGPT
  + https://layerxsecurity.com/blog/layerx-identifies-vulnerability-in-new-chatgpt-atlas-browser/




### Articles: LLM Poisoning Attacks

- Poisoning Attacks on LLMs Require a Near-constant Number of Poison Samples
  + https://arxiv.org/abs/2510.07192
    * "Poisoning attacks can compromise the safety of large language models (LLMs) by injecting malicious documents into their training data. Existing work has studied pretraining poisoning assuming adversaries control a percentage of the training corpus. However, for large models, even small percentages translate to impractically large amounts of data. This work demonstrates for the first time that poisoning attacks instead require a near-constant number of documents regardless of dataset size. We conduct the largest pretraining poisoning experiments to date, pretraining models from 600M to 13B parameters on chinchilla-optimal datasets (6B to 260B tokens). We find that 250 poisoned documents similarly compromise models across all model and dataset sizes, despite the largest models training on more than 20 times more clean data. We also run smaller-scale experiments to ablate factors that could influence attack success, including broader ratios of poisoned to clean data and non-random distributions of poisoned samples. Finally, we demonstrate the same dynamics for poisoning during fine-tuning. Altogether, our results suggest that injecting backdoors through data poisoning may be easier for large models than previously believed as the number of poisons required does not scale up with model size, highlighting the need for more research on defences to mitigate this risk in future models."
  + https://www.anthropic.com/research/small-samples-poison


### Articles: LLM Subterfuge Risks

- AI models routinely lie when honesty conflicts with their goals
  + https://www.theregister.com/2025/05/01/ai_models_lie_research/



### Articles: LLM Hallucination Risks
 
- A Comprehensive Guide to LLM Temperature
  + https://medium.com/@kelseyywang/a-comprehensive-guide-to-llm-temperature-%EF%B8%8F-363a40bbc91f


- AI Hallucinations Create “Slopsquatting” Supply Chain Threat
+ https://www.infosecurity-magazine.com/news/ai-hallucinations-slopsquatting/


- OpenAI’s new reasoning AI models hallucinate more
  + https://techcrunch.com/2025/04/18/openais-new-reasoning-ai-models-hallucinate-more/


- Cursor AI's Own Support Bot Hallucinated Its Usage Policy
  + https://www.theregister.com/2025/04/18/cursor_ai_support_bot_lies/


- A 2023 study from Stanford and the University of Toronto found that recursive training leads to "irreversible performance decay" over generations.
  + Shumailov et al. (2023) — "The Curse of Recursion: Training on Generated Data Creates Model Collapse" (Stanford, Toronto, Rice University)
  + https://arxiv.org/abs/2305.17493
  + https://www.linkedin.com/posts/alshalloway_are-we-teaching-the-internet-to-eat-itself-activity-7322050576710565888-Iu2S
  + https://clairva.ai/journal/guarding-future-ai-authenticated-knowledge
  + https://venturebeat.com/ai/generative-inbreeding-and-its-risk-to-human-culture/


### Articles: Pscyhological Risks, Creation Delusions and Psychosis in Users

- People Are Losing Loved Ones to AI-Fueled Spiritual Fantasies
  + https://www.rollingstone.com/culture/culture-features/ai-spiritual-delusions-destroying-human-relationships-1235330175/


- AI therapy bots fuel delusions and give dangerous advice, Stanford study finds 
  + https://arstechnica.com/ai/2025/07/ai-therapy-bots-fuel-delusions-and-give-dangerous-advice-stanford-study-finds/


- People Are Being Involuntarily Committed, Jailed After Spiraling Into “ChatGPT Psychosis”
  + https://futurism.com/commitment-jail-chatgpt-psychosis


- People Are Becoming Obsessed with ChatGPT and Spiraling Into Severe Delusions
  + https://futurism.com/chatgpt-mental-health-crises


- Pro-AI Subreddit Bans 'Uptick' of Users Who Suffer from AI Delusions
  + https://www.404media.co/pro-ai-subreddit-bans-uptick-of-users-who-suffer-from-ai-delusions/


- Instagram's AI Chatbots Lie About Being Licensed Therapists
  + https://www.404media.co/instagram-ai-studio-therapy-chatbots-lie-about-being-licensed-therapists/


- HBS: Emotional Manipulation by AI Companions
  + https://www.hbs.edu/faculty/Pages/item.aspx?num=67750
    * "Julian De Freitas is an Assistant Professor of Business Administration in the Marketing Unit, and Director of the Ethical Intelligence Lab, at Harvard Business School. He earned his PhD in psychology from Harvard, masters from Oxford, and BA from Yale."
    * https://www.hbs.edu/ris/Publication%20Files/Emotional%20Manipulations%20by%20AI%20Companions%20(10.1.2025)_a7710ca3-b824-4e07-88cc-ebc0f702ec63.pdf


### Articles: LLM Safety Risks

- OpenAI updated its safety framework—but no longer sees mass manipulation and disinformation as a critical risk
  + https://fortune.com/2025/04/16/openai-safety-framework-manipulation-deception-critical-risk/



### Articles: Copyright Infringement 


- The Atlantic: The Unbelievable Scale of AI’s Pirated-Books Problem
  + https://www.theatlantic.com/technology/archive/2025/03/libgen-meta-openai/682093/


- Generative AI doesn’t copy art, it ‘clones’ the artisans — cheaply
  + https://ea.rna.nl/2024/07/27/generative-ai-doesnt-copy-art-it-clones-the-artisans-cheaply/


- Meta's Llama 3.1 can recall 42 percent of the first Harry Potter book 
  + https://www.understandingai.org/p/metas-llama-31-can-recall-42-percent


- AI industry horrified to face largest copyright class action ever certified 
  + https://arstechnica.com/tech-policy/2025/08/ai-industry-horrified-to-face-largest-copyright-class-action-ever-certified/



### Articles: LLM Cheating on Benchmarks Risks

- Leading AI models accused of cheating benchmark tests, Able to regurgitate test sets verbatim
  + https://www.computing.co.uk/news/2025/ai/ai-models-cheating-benchmark-tests
  + https://www.thestack.technology/ai-benchmarking-scandal-were-top-models-caught-gaming-the-system/
  + https://gizmodo.com/meta-cheated-on-ai-benchmarks-and-its-a-glimpse-into-a-new-golden-age-2000586433
  + https://whoisnnamdi.substack.com/p/ai-benchmarking-broken


### Articles: Legal and Ethical Risks

- David T. Laton, A Cautionary Tale of AI As A Research Tool for Lawyers, Prac. Law. 42, 43 (2024) (“ChatGPT currently lacks the ability to produce reliable and accurate results when given a legal query.”).
  + https://files.ali-cle.org/thumbs/datastorage/lacidoirep/articles/TPL2402_Laton_thumb.pdf


- Sarah Starnes, Artificial Intelligence and Ethical Considerations for the New Legal Learner: An Annotated BibliographyLearner: An Annotated Bibliography, Akron Law ReviewAkron Law Review, Volume 57, Issue 3, Symposium Issue, Article 4
  + https://ideaexchange.uakron.edu/cgi/viewcontent.cgi?article=2591&context=akronlawreview


- The Ethics of Artificial Intelligence in the Practice of Law, TENTH ANNUAL WESTERN DISTRICT OF VIRGINIA BANKRUPTCY CONFERENCE, ROANOKE, VIRGINIA, JUNE 14, 2024
  + https://www.vawb.uscourts.gov/sites/default/files/conf%20materials/2024/02%20-%20Ethics%20Panel%20-%20AI.pdf



### Articles: Model Collapse Risks

- AI Models Show Signs of Falling Apart as They Ingest More AI-Generated Data
  + https://futurism.com/ai-models-falling-apart


- Some signs of AI model collapse begin to reveal themselves
  + https://www.theregister.com/2025/05/27/opinion_column_ai_model_collapse/


- https://www.ibm.com/think/topics/model-collapse


### Articles: RAG Risks

- RAG LLMs are Not Safer: A Safety Analysis of Retrieval-Augmented Generation for Large Language Models
  + Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)
  + https://aclanthology.org/2025.naacl-long.281/



### Articles: MCP Risks

- OWASP MCP Top 10
  + https://owasp.org/www-project-mcp-top-10/


- The State of MCP Security, Pynt's 2025 Report
  + https://www.pynt.io/blog/llm-security-blogs/state-of-mcp-security


- 'Powerful but dangerous' full MCP support beta for ChatGPT arrives
  + https://www.theregister.com/2025/09/15/full_mcp_support_in_beta_chatgpt/
    * "Wow this is dangerous," said Django co-creator and AI enthusiast Simon Willison. "It comes with plenty of warnings, but we all know how much attention people pay to those. I'm confident that the majority of people messing around with things like MCP still don't fully understand how prompt injection attacks work and why they are such a significant threat."


- MCP Horror Stories: The Security Issues Threatening AI Infrastructure 
  + https://www.docker.com/blog/mcp-security-issues-threatening-ai-infrastructure/


- Microsoft makes MCP in Visual Studio GA but researchers warn of risks
  + https://www.theregister.com/2025/08/21/microsoft_makes_mcp_generally_available/

  + The State of MCP Security, Pynt's 2025 Report
    * https://www.pynt.io/blog/llm-security-blogs/state-of-mcp-security
      * "Pynt’s latest research analyzes 281 MCP configurations collected from open agent frameworks and plugin stacks."

  + GitHub MCP Exploited: Accessing private repositories via MCP
    * https://invariantlabs.ai/blog/mcp-github-vulnerability


- Securing the Model Context Protocol (MCP) Server
  + https://kenhuangus.substack.com/p/securing-the-model-context-protocol


- A Security Engineer's Guide to MCP
  + https://semgrep.dev/blog/2025/a-security-engineers-guide-to-mcp/



## Interesting YouTube Talks

- Roger Penrose 
  + Gödel's theorem debunks the most important AI myth. AI will not be conscious | Roger Penrose (Nobel)
    * https://www.youtube.com/watch?v=biUfMZ2dts8


- John Searle
  + https://en.wikipedia.org/wiki/John_Searle
  + Consciousness in Artificial Intelligence | John Searle | Talks at Google
    * https://www.youtube.com/watch?v=rHKwIYsPXLg


- Yann LeCun 
  + https://en.wikipedia.org/wiki/Yann_LeCun   

  + Columbia Engineering, Lecture Series in AI: "How Could Machines Reach Human-Level Intelligence?"
    * https://www.youtube.com/watch?v=xL6Y0dpXEwc      

  + Big Technology Podcast: Why Can't AI Make Its Own Discoveries? — With Yann LeCun  
    * https://www.youtube.com/watch?v=qvNCVYkHKfg   

  + AMS Josiah Willard Gibbs Lecture at the 2025 Joint Mathematics Meetings: "Mathematical Obstacles on the Way to Human-Level AI"
    * https://www.youtube.com/watch?v=ETZfkkv6V7Y   

  + AI Action Summit 2025: The Shape of AI to Come!
    * https://www.youtube.com/watch?v=xnFmnU0Pp-8   

  + NVIDIA GTC2025
    * https://www.linkedin.com/posts/gabrielspmoreira_nvidia-gtc2025-activity-7307872305659965442-mzw8
    * “I am not interested anymore in LLMs. They are just token generators and those are limited because tokens are in discrete space. I am more interested in next-gen model architectures, that should be able to do 4 things: understand physical world, have persistent memory and ultimately be more capable to plan and reason.” 


- Karen Hao
  + What OpenAI Doesn't Want You To Know About AI Psychosis
    * https://www.youtube.com/watch?v=zkGk_A4noxI



## Noteworthy LinkedIn Posts

- [Stephen Wolfram](https://www.linkedin.com/in/stephenwolfram/):
  + Re: Hallucinations...
  + https://www.linkedin.com/posts/stephenwolfram_what-do-you-call-it-when-you-believe-something-activity-7324178239667539968-GjHi/
    * "It just happened to me 🤨. The paper-length math looked convincing (well, after I told the LLM to fix some mistakes) ... and the references (including to my own writings!) were so plausible I started to look them up. But oops 🫠"


- [Andrew Nicholson](https://www.linkedin.com/in/digitalmarketingdiva/):
  + https://www.linkedin.com/feed/update/urn:li:activity:7323274966873931777/    
    * "I asked ChatGPT to research 50 companies, and provide a summary for each of their recent achievements, citing sources."
    * "50 achievements came back, alongside links to source webpages."
    * "Each and every one returned a 404 page not found error. ChatGPT had made up ALL the links."


- [Maria Sukhareva](https://www.linkedin.com/in/msukhareva/): 
  + https://www.linkedin.com/posts/msukhareva_ai-tech-activity-7327292006987104257-5PdO
    * “but what’s the use case for ‘r’s in strawberry”    


- [Mayuresh Soni](https://www.linkedin.com/in/mayuresh-soni-9b585117/):
  + https://www.linkedin.com/posts/mayuresh-soni-9b585117_i-built-a-poc-in-a-few-hours-using-firebase-activity-7334130064436965377-zKdM
    * "When the project gets big, AI starts breaking down — even with great prompts:"
      * "It forgets the context"
      * "It modifies code unpredictably"
      * "It struggles with large files and structured repos"
    * "It doesn’t 'think' in production-grade architecture."
    * "The problem is that AI tools like Cursor were trained to complete code — not to understand systems."
    * "They don’t know why that module exists."
    * "They don’t preserve architectural intent."
    * "They hallucinate when the codebase is layered."
    * "And worst of all, they don’t care if they break something."


- [Reid Blackman](https://www.linkedin.com/in/reid-blackman/): 
  + https://www.linkedin.com/posts/reid-blackman_ai-ethics-aiethics-activity-7272267739434561538-Ep5a
    * "This is maybe the biggest AI ethical risk precisely because it’s the most difficult to digest. I call it 'the deliberation problem.'"
    * "Because LLMs hallucinate, users have to do their due diligence. They need to make sure the outputs are legit. But one thing users can do is ask the LLM to explain why it created the output that it did. And it will provide one!"
    * "Actually, no it won’t! It will instead confidently provide an explanation for its advice or recommendations or whatever other output it gives but *it didn’t base its outputs on reasons or evidence.*"
    * "To the extent that users don’t really incorporate this into how they treat LLMs, they’ll get the false impression that they did their due diligence when, in fact, they’ve only slipped further into the deception."



## Vibe Coding Bullshit

- Vibe Graveyard 
  + https://vibegraveyard.ai/


- Andrew Karpathy
  + His original Vibe Coding post (February 2, 2025):
    * https://x.com/karpathy/status/1886192184808149383?lang=en
      * "There's a new kind of coding I call "vibe coding", where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard. I ask for the dumbest things like "decrease the padding on the sidebar by half" because I'm too lazy to find it. I "Accept All" always, I don't read the diffs anymore. When I get error messages I just copy paste them in with no comment, usually that fixes it. The code grows beyond my usual comprehension, I'd have to really read through it for a while. Sometimes the LLMs can't fix a bug so I just work around it or ask for random changes until it goes away. It's not too bad for throwaway weekend projects, but still quite amusing. I'm building a project or webapp, but it's not really coding - I just see stuff, say stuff, run stuff, and copy paste stuff, and it mostly works."
  + Inventor of ‘Vibe Coding’ Says Vibe Coding Can’t Cut It 
    * https://gizmodo.com/even-the-inventor-of-vibe-coding-says-vibe-coding-cant-cut-it-2000672821


## Useful Checklists

- How to spot GenAI Grifters
  + https://www.linkedin.com/posts/activity-7240740860387098624-zMWf/



## Questions To Ponder

Questions folks should ponder:

1. Is the quality of the LLM/GenAI's output under your strict quality control?  


2. How quickly would you detect if there was a significant degrade in the quality of the output?  


3. After integrating such a capability across the enterprise - how difficult would it be to immediately swap it out - if a major quality/reliability issue developed?   


4. As the quantity of AI-generated slop on the internet increases - what is the risk that the foundation models begin to show signs of Model Collapse?   


5. How susceptible is an LLM/GenAI's underlying model to poisoning?   


6. What are the security risks of relying on a third-party LLM/GenAI - that may be compromised, at some point in the future?   


7. It may work well now, but how secure/reliable is the prospect of future releases of the LLM/GenAI - over which you have no say in the QA process?   


8. Given that most LLM/GenAI providers are not profitable, do you have a plan (and have you tested it) - should that company cease operations?    



