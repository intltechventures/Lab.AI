
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



### Papers: Productivity Impact 

- Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity
  + https://arxiv.org/abs/2507.09089
    * "Before starting tasks, developers forecast that allowing AI will reduce completion time by 24%. After completing the study, developers estimate that allowing AI reduced completion time by 20%. Surprisingly, we find that allowing AI actually increases completion time by 19%--AI tooling slowed developers down. This slowdown also contradicts predictions from experts in economics (39% shorter) and ML (38% shorter)."



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



### Papers: Agentic AI Risks


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



### Papers: Training Risks 

- Surface Fairness, Deep Bias: A Comparative Study of Bias in Language Models
  + https://arxiv.org/abs/2506.10491
  + [ChatGPT advises women to ask for lower salaries, study finds](https://thenextweb.com/news/chatgpt-advises-women-to-ask-for-lower-salaries-finds-new-study)


- Neural Thermodynamic Laws for Large Language Model Training
  + https://arxiv.org/abs/2505.10559



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


### Articles: LLM Prompt Injection Risks

- Novel Universal Bypass for All Major LLMs
  + The Policy Puppetry Prompt Injection Technique
  + https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/
  


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
  + Columbia Engineering, Lecture Series in AI: "How Could Machines Reach Human-Level Intelligence?” 
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



### Noteworthy Social Media Posts

- Andrew Karpathy's original Vibe Coding post (February 2, 2025):
  + https://x.com/karpathy/status/1886192184808149383?lang=en
    * "There's a new kind of coding I call "vibe coding", where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard. I ask for the dumbest things like "decrease the padding on the sidebar by half" because I'm too lazy to find it. I "Accept All" always, I don't read the diffs anymore. When I get error messages I just copy paste them in with no comment, usually that fixes it. The code grows beyond my usual comprehension, I'd have to really read through it for a while. Sometimes the LLMs can't fix a bug so I just work around it or ask for random changes until it goes away. It's not too bad for throwaway weekend projects, but still quite amusing. I'm building a project or webapp, but it's not really coding - I just see stuff, say stuff, run stuff, and copy paste stuff, and it mostly works."

