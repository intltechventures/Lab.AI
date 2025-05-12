
# AI Citations

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

- https://en.wikipedia.org/wiki/AI_alignment

- https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)

- https://en.wikipedia.org/wiki/Instrumental_convergence

- https://en.wikipedia.org/wiki/Principal%E2%80%93agent_problem


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


## Papers

- The Leaderboard Illusion
  + https://arxiv.org/abs/2504.20879


- Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference
  + https://arxiv.org/abs/2403.04132


- SWE-Lancer: Can Frontier LLMs Earn $1 Million from Real-World Freelance Software Engineering?
  + https://arxiv.org/abs/2502.12115
  + https://openai.com/index/swe-lancer/
  + https://github.com/openai/SWELancer-Benchmark


- SWE-bench
  + [SWE-bench: Can Language Models Resolve Real-World GitHub Issues? [2023, last revised 11 Nov 2024 (this version, v3)]](https://arxiv.org/abs/2310.06770)
  + https://www.swebench.com/



- LLMs are Bug Replicators: An Empirical Study on LLMs' Capability in Completing Bug-prone Code
  + https://arxiv.org/abs/2503.11082


- Medical Hallucination in Foundation Models and Their Impact on Healthcare
  + https://arxiv.org/abs/2503.05777


- ChatGPT is bullshit
  + https://link.springer.com/article/10.1007/s10676-024-09775-5


- Artificial Intelligence Is Stupid and Causal Reasoning Will Not Fix It
  + https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2020.513474/full
    * "As Judea Pearl sees it, the underlying reason for such mistakes is that '... all the impressive achievements of deep learning amount to just curve fitting.'"
    * "Gary Marcus and Ernest Davis in a recent piece for the New York Times: 'we need to stop building computer systems that merely get better and better at detecting statistical patterns in data sets—often using an approach known as ‘Deep Learning’—and start building computer systems that from the moment of their assembly innately grasp three basic concepts: time, space, and causality.`"
    * "In this paper, foregrounding what in 1949 Gilbert Ryle termed 'a category mistake', I will offer an alternative explanation for AI errors; it is not so much that AI machinery cannot 'grasp' causality, but that AI machinery (qua computation) cannot understand anything at all."
  + https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2020.513474/full


- ARC-AGI-2
  + https://arcprize.org/blog/announcing-arc-agi-2-and-arc-prize-2025
  + https://arcprize.org/competition
  + https://arcprize.org/leaderboard
  + [2025-03-25 LLMs Hit a New Low on ARC-AGI-2 Benchmark, Pure LLMs Score 0%](https://analyticsindiamag.com/ai-news-updates/llms-hit-a-new-low-on-arc-agi-2-benchmark-pure-llms-score-0/)
 

- National Aeronautics and Space Administration (NASA)
  + Examining Proposed Uses of LLMs to Produce or Assess Assurance Arguments (March 1, 2025)
    + https://ntrs.nasa.gov/citations/20250001849


- Hallucination is Inevitable: An Innate Limitation of Large Language Models
  + https://arxiv.org/abs/2401.11817


- LLMs Will Always Hallucinate, and We Need to Live With This
  + https://arxiv.org/abs/2409.05746


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

  
- When Large Language Models contradict humans? Large Language Models' Sycophantic Behaviour
  + https://www.semanticscholar.org/paper/When-Large-Language-Models-contradict-humans-Large-Ranaldi-Pucci/c6178035aab3bf6083e2523a51c6fae15c0b323f
  + Sycophancy in GPT-4o: What happened and what we’re doing about it
	* https://openai.com/index/sycophancy-in-gpt-4o/


- We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs
  + https://arxiv.org/abs/2406.10279


- When Large Language Models contradict humans? Large Language Models' Sycophantic Behaviour
  + https://www.semanticscholar.org/paper/When-Large-Language-Models-contradict-humans-Large-Ranaldi-Pucci/c6178035aab3bf6083e2523a51c6fae15c0b323f


- Self-Consuming Generative Models Go MAD
  + https://arxiv.org/abs/2307.01850


- The Curse of Recursion: Training on Generated Data Makes Models Forget
  + https://arxiv.org/abs/2305.17493


- TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks (December 2024)
  + https://arxiv.org/abs/2412.14161
  + https://the-agent-company.com/
  + Professors Staffed a Fake Company Entirely With AI Agents, and You'll Never Guess What Happened
    * https://futurism.com/professors-company-ai-agents
  + Carnegie Mellon staffed a fake company with AI agents. It was a total disaster.
	* https://tech.yahoo.com/ai/articles/next-assignment-babysitting-ai-081502817.html


- NoLiMa: Long-Context Evaluation Beyond Literal Matching
  + https://arxiv.org/abs/2502.05167
    * "We evaluate 12 popular LLMs that claim to support contexts of at least 128K tokens. While they perform well in short contexts (<1K), performance degrades significantly as context length increases. At 32K, for instance, 10 models drop below 50% of their strong short-length baselines. Even GPT-4o, one of the top-performing exceptions, experiences a reduction from an almost-perfect baseline of 99.3% to 69.7%."
  + https://huggingface.co/datasets/amodaresi/NoLiMa
  + https://www.reddit.com/r/LocalLLaMA/comments/1io3hn2/nolima_longcontext_evaluation_beyond_literal/


- GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models
  + https://arxiv.org/abs/2410.05229


- Towards Understanding Sycophancy in Language Models
  + https://arxiv.org/abs/2310.13548


- (Im)possibility of Automated Hallucination Detection in Large Language Models
  + https://www.arxiv.org/abs/2504.17004


- Cheating Automatic LLM Benchmarks: Null Models Achieve High Win Rates  
  + https://arxiv.org/abs/2410.07137


## Articles

- The Illusion of Understanding
  + https://www.linkedin.com/pulse/illusion-understanding-ivo-boniolo-7fbcf/


- The Nuremberg Defense of AI
  + https://copin43.hashnode.dev/the-nuremberg-defense-of-ai


- Novel Universal Bypass for All Major LLMs
  + The Policy Puppetry Prompt Injection Technique
  + https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/
  

- A Comprehensive Guide to LLM Temperature
  + https://medium.com/@kelseyywang/a-comprehensive-guide-to-llm-temperature-%EF%B8%8F-363a40bbc91f


- AI models routinely lie when honesty conflicts with their goals
  + https://www.theregister.com/2025/05/01/ai_models_lie_research/


- AI Hallucinations Create “Slopsquatting” Supply Chain Threat
  + https://www.infosecurity-magazine.com/news/ai-hallucinations-slopsquatting/


- OpenAI’s new reasoning AI models hallucinate more
  + https://techcrunch.com/2025/04/18/openais-new-reasoning-ai-models-hallucinate-more/


- OpenAI updated its safety framework—but no longer sees mass manipulation and disinformation as a critical risk
  + https://fortune.com/2025/04/16/openai-safety-framework-manipulation-deception-critical-risk/


- Cursor AI's Own Support Bot Hallucinated Its Usage Policy
  + https://www.theregister.com/2025/04/18/cursor_ai_support_bot_lies/


- A 2023 study from Stanford and the University of Toronto found that recursive training leads to "irreversible performance decay" over generations.
  + Shumailov et al. (2023) — "The Curse of Recursion: Training on Generated Data Creates Model Collapse" (Stanford, Toronto, Rice University)
  + https://arxiv.org/abs/2305.17493
  + https://www.linkedin.com/posts/alshalloway_are-we-teaching-the-internet-to-eat-itself-activity-7322050576710565888-Iu2S
  + https://clairva.ai/journal/guarding-future-ai-authenticated-knowledge
  + https://venturebeat.com/ai/generative-inbreeding-and-its-risk-to-human-culture/


- Generative AI doesn’t copy art, it ‘clones’ the artisans — cheaply
  + https://ea.rna.nl/2024/07/27/generative-ai-doesnt-copy-art-it-clones-the-artisans-cheaply/


- The Atlantic: The Unbelievable Scale of AI’s Pirated-Books Problem
  + https://www.theatlantic.com/technology/archive/2025/03/libgen-meta-openai/682093/


- Leading AI models accused of cheating benchmark tests, Able to regurgitate test sets verbatim
  + https://www.computing.co.uk/news/2025/ai/ai-models-cheating-benchmark-tests
  + https://www.thestack.technology/ai-benchmarking-scandal-were-top-models-caught-gaming-the-system/
  + https://gizmodo.com/meta-cheated-on-ai-benchmarks-and-its-a-glimpse-into-a-new-golden-age-2000586433
  + https://whoisnnamdi.substack.com/p/ai-benchmarking-broken



## Noteworthy LinkedIn Posts

- Stephen Wolfram:
  + Re: Hallucinations...
  + https://www.linkedin.com/posts/stephenwolfram_what-do-you-call-it-when-you-believe-something-activity-7324178239667539968-GjHi/
    * "It just happened to me 🤨. The paper-length math looked convincing (well, after I told the LLM to fix some mistakes) ... and the references (including to my own writings!) were so plausible I started to look them up. But oops 🫠"


- Andrew Nicholson:
  + Re: Hallucinations...
  + https://www.linkedin.com/feed/update/urn:li:activity:7323274966873931777/
    * "I asked ChatGPT to research 50 companies, and provide a summary for each of their recent achievements, citing sources."
    * "50 achievements came back, alongside links to source webpages."
    * "Each and every one returned a 404 page not found error. ChatGPT had made up ALL the links."


- Maria Sukhareva: “but what’s the use case for ‘r’s in strawberry”    
  + https://www.linkedin.com/posts/msukhareva_ai-tech-activity-7327292006987104257-5PdO



