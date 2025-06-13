
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


- https://www.wolfram.com/llm-benchmarking-project/


## Video Talks

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


## Papers

- The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity
  + https://machinelearning.apple.com/research/illusion-of-thinking


- AI as Agency without Intelligence: On Artificial Intelligence as a New Form of Artificial Agency and the Multiple Realisability of Agency Thesis
  + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5135645


- RealHarm: A Collection of Real-World Language Model Application Failures
  + https://arxiv.org/abs/2504.10277


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


- RealHarm: A Collection of Real-World Language Model Application Failures
  + https://arxiv.org/abs/2504.10277


- LLMs are Bug Replicators: An Empirical Study on LLMs' Capability in Completing Bug-prone Code
  + https://arxiv.org/abs/2503.11082


- Medical Hallucination in Foundation Models and Their Impact on Healthcare
  + https://arxiv.org/abs/2503.05777


- Global Health in the Age of AI: Charting a Course for Ethical Implementation and Societal Benefit
  + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5217060


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
  + aka "Slopsquatting"
  + AI-generated code could be a disaster for the software supply chain. Here’s why.
    * https://arstechnica.com/security/2025/04/ai-generated-code-could-be-a-disaster-for-the-software-supply-chain-heres-why/


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


- Sycophancy to subterfuge: Investigating reward-tampering in large language models. 
  + https://arxiv.org/abs/2406.10162
  + System Card: Claude Opus 4 & Claude Sonnet 4 (see pages 19-20, "re: Self-preservation attempts in extreme circumstances:")
    * https://www-cdn.anthropic.com/4263b940cabb546aa0e3283f35b686f4f3b2ff47.pdf


- (Im)possibility of Automated Hallucination Detection in Large Language Models
  + https://www.arxiv.org/abs/2504.17004


- LLMs Get Lost In Multi-Turn Conversation
  + https://arxiv.org/abs/2505.06120


- Cheating Automatic LLM Benchmarks: Null Models Achieve High Win Rates  
  + https://arxiv.org/abs/2410.07137


- Neural Thermodynamic Laws for Large Language Model Training
  + https://arxiv.org/abs/2505.10559


- Generalization bias in large language model summarization of scientific research
  + https://arxiv.org/abs/2504.00025
  + https://royalsocietypublishing.org/doi/10.1098/rsos.241776
  + https://doi.org/10.1098/rsos.241776


- Extracting memorized pieces of (copyrighted) books from open-weight language models
  + https://arxiv.org/abs/2505.12546
  + Meta's Llama 3.1 can recall 42 percent of the first Harry Potter book 
    * https://www.understandingai.org/p/metas-llama-31-can-recall-42-percent


### Cybersecurity Risks

- TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems
  + https://arxiv.org/abs/2506.04133


- https://cset.georgetown.edu/research-topic/cyberai/
  + "CSET’s CyberAI Project focuses on the intersection of AI/ML and cybersecurity, including analysis of AI/ML’s potential uses in cyber operations, the potential failure modes of AI/ML applications for cyber, how AI/ML may amplify future disinformation campaigns, and geostrategic competition centered around cyber and AI/ML."


- Adding Structure to AI Harm An Introduction to CSET's AI Harm Framework
  + Center for SECURITY and EMERGING TECHNOLOGY (CSET)
  + https://cset.georgetown.edu/
  + https://cset.georgetown.edu/wp-content/uploads/20230022-Adding-structure-to-AI-Harm-FINAL.pdf



### Anthropomorphizing Risks

- Stop Anthropomorphizing Intermediate Tokens as Reasoning/Thinking Traces!
  + https://arxiv.org/abs/2504.09762v2



### Agentic AI Risks

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



## Articles

- The Illusion of Understanding
  + https://www.linkedin.com/pulse/illusion-understanding-ivo-boniolo-7fbcf/


- The Nuremberg Defense of AI
  + https://copin43.hashnode.dev/the-nuremberg-defense-of-ai


### On the Erroneous Assumption that Programming is DEAD

- Why kids still need to learn to code in the age of AI 
  + https://www.raspberrypi.org/blog/why-kids-still-need-to-learn-to-code-in-the-age-of-ai/


### LLM Prompt Injection Risks

- Novel Universal Bypass for All Major LLMs
  + The Policy Puppetry Prompt Injection Technique
  + https://hiddenlayer.com/innovation-hub/novel-universal-bypass-for-all-major-llms/
  

### LLM Subterfuge Risks

- AI models routinely lie when honesty conflicts with their goals
  + https://www.theregister.com/2025/05/01/ai_models_lie_research/



### LLM Hallucination Risks
 
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


### LLM Safety Risks

- OpenAI updated its safety framework—but no longer sees mass manipulation and disinformation as a critical risk
  + https://fortune.com/2025/04/16/openai-safety-framework-manipulation-deception-critical-risk/



### Copyright Theft


- The Atlantic: The Unbelievable Scale of AI’s Pirated-Books Problem
  + https://www.theatlantic.com/technology/archive/2025/03/libgen-meta-openai/682093/


- Generative AI doesn’t copy art, it ‘clones’ the artisans — cheaply
  + https://ea.rna.nl/2024/07/27/generative-ai-doesnt-copy-art-it-clones-the-artisans-cheaply/


- Meta's Llama 3.1 can recall 42 percent of the first Harry Potter book 
  + https://www.understandingai.org/p/metas-llama-31-can-recall-42-percent


### LLM Cheating on Benchmarks Risks

- Leading AI models accused of cheating benchmark tests, Able to regurgitate test sets verbatim
  + https://www.computing.co.uk/news/2025/ai/ai-models-cheating-benchmark-tests
  + https://www.thestack.technology/ai-benchmarking-scandal-were-top-models-caught-gaming-the-system/
  + https://gizmodo.com/meta-cheated-on-ai-benchmarks-and-its-a-glimpse-into-a-new-golden-age-2000586433
  + https://whoisnnamdi.substack.com/p/ai-benchmarking-broken


### Legal and Ethical Risks

- David T. Laton, A Cautionary Tale of AI As A Research Tool for Lawyers, Prac. Law. 42, 43 (2024) (“ChatGPT currently lacks the ability to produce reliable and accurate results when given a legal query.”).
  + https://files.ali-cle.org/thumbs/datastorage/lacidoirep/articles/TPL2402_Laton_thumb.pdf

- Sarah Starnes, Artificial Intelligence and Ethical Considerations for the New Legal Learner: An Annotated BibliographyLearner: An Annotated Bibliography, Akron Law ReviewAkron Law Review, Volume 57, Issue 3, Symposium Issue, Article 4
  + https://ideaexchange.uakron.edu/cgi/viewcontent.cgi?article=2591&context=akronlawreview

- The Ethics of Artificial Intelligence in the Practice of Law, TENTH ANNUAL WESTERN DISTRICT OF VIRGINIA BANKRUPTCY CONFERENCE, ROANOKE, VIRGINIA, JUNE 14, 2024
  + https://www.vawb.uscourts.gov/sites/default/files/conf%20materials/2024/02%20-%20Ethics%20Panel%20-%20AI.pdf



### Model Collapse Risks

- AI Models Show Signs of Falling Apart as They Ingest More AI-Generated Data
  + https://futurism.com/ai-models-falling-apart


- Some signs of AI model collapse begin to reveal themselves
  + https://www.theregister.com/2025/05/27/opinion_column_ai_model_collapse/


- https://www.ibm.com/think/topics/model-collapse


### RAG Risks

- RAG LLMs are Not Safer: A Safety Analysis of Retrieval-Augmented Generation for Large Language Models
  + Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)
  + https://aclanthology.org/2025.naacl-long.281/



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



