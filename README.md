# Awesome-VLM-Papers-And-Models
A most Frontend Collection and survey of vision-language model papers, and models GitHub repository

Below we compile *awesome* papers and model and github repositories that 
- **State-of-the-Art VLMs** Collection of VLMs from 2022-2024.
- **applications** applications of VLMs in embodied AI, robotics, etc.
- **evaluate** VLM benchmarks and corresponding link to the works
- contribute **surveys**, **perspectives**, and **datasets** on the above topics.


Welcome to contribute and discuss!

---

🤩 Papers marked with a ⭐️ are contributed by the maintainers of this repository. If you find them useful, we would greatly appreciate it if you could give the repository a star or cite our paper.

---

## Table of Contents

* 1. [📚 SoTA VLMs](#Survey)
* 2. [🗂️ Dataset and Evaluation](#Dataset)
* 4. [⚒️ Tool enhancement](#Toolenhancement)
* 5. [⛑️ Alignment](#Alignment)
	* 5.1. [🌈 Pluralistic Alignment](#PluralisticAlignment)
* 6. [🚀 Simulation](#Simulation)
* 7. [👁️‍🗨️ Perspective](#Perspective)


---

##  1. <a name='Survey'></a>📚 Survey 
- **Survey of Cultural Awareness in Language Models: Text and Beyond**, 2024.11, [[paper]](https://arxiv.org/pdf/2411.00860).
- **How developments in natural language processing help us in understanding human behaviour**, 2024.10 Nat. Hum. Behav., [[paper]](https://www.nature.com/articles/s41562-024-01938-0.pdf).
- **Automated Mining of Structured Knowledge from Text in the Era of Large Language Models**, 2024.08, KDD 2024, [[paper]](https://dl.acm.org/doi/pdf/10.1145/3637528.3671469).
- **Affective Computing in the Era of Large Language Models: A Survey from the NLP Perspective**, 2024.07, [[paper]](https://arxiv.org/abs/2408.04638).
- **Perils and opportunities in using large language models in psychological research**, 2024.07, [[paper]](https://academic.oup.com/pnasnexus/article/3/7/pgae245/7712371).
- **The Potential and Challenges of Evaluating Attitudes, Opinions, and Values in Large Language Models**, 2024.06, [[paper]](https://arxiv.org/abs/2406.11096).
- **Can Generative AI improve social science?**, 2024.05, PNAS, [[paper]](https://www.pnas.org/doi/pdf/10.1073/pnas.2314021121).
- **Foundational Challenges in Assuring Alignment and Safety of Large Language Models**, 2024.04, [[paper]](https://arxiv.org/abs/2404.09932).
- **Large Language Model based Multi-Agents: A Survey of Progress and Challenges**, 2024.01, [[paper]](https://arxiv.org/abs/2402.01680), [[repo]](https://github.com/taichengguo/LLM_MultiAgents_Survey_Papers).
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2309.07864), [[repo]](https://github.com/WooooDyy/LLM-Agent-Paper-List).
- **A Survey on Large Language Model based Autonomous Agents**, 2023, [[paper]](https://arxiv.org/abs/2308.11432), [[repo]](https://github.com/Paitesanshi/LLM-Agent-Survey).
- **AI Alignment: A Comprehensive Survey**, 2023.11, [[paper]](https://arxiv.org/abs/2310.19852), [[website]](https://alignmentsurvey.com/).
- **Aligning Large Language Models with Human: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2307.12966), [[repo]](https://github.com/GaryYufei/AlignLLMHumanSurvey).
- **Large Language Model Alignment: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2309.15025).
- **Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives**, 2023.12, [[paper]](https://arxiv.org/abs/2312.11970).
- **A Survey on Evaluation of Large Language Models**, 2023.07, [[paper]](https://arxiv.org/abs/2307.03109), [[repo]](https://github.com/MLGroupJLU/LLM-eval-survey).
- **From Instructions to Intrinsic Human Values -- A Survey of Alignment Goals for Big Models**, 2023.08, [[paper]](https://arxiv.org/abs/2308.12014), [[repo]](https://github.com/ValueCompass/Alignment-Goal-Survey).


##  2. <a name='Dataset'></a>🗂️ Dataset

- ⭐️ **ValueBench: Towards Comprehensively Evaluating Value Orientations and Understanding of Large Language Models**, ACL 2024, [[paper]](https://arxiv.org/abs/2406.04214), [[code]](https://github.com/Value4AI/ValueBench).
- https://lit.eecs.umich.edu/downloads.html
- **COMPO: Community Preferences for Language Model Personalization**, 2024.10, [[paper]](https://arxiv.org/pdf/2410.16027).
- **Cultural Commonsense Knowledge for Intercultural Dialogues**, CIKM 2024, [[paper]](https://dl.acm.org/doi/pdf/10.1145/3627673.3679768), [[dataset]](https://mango.mpi-inf.mpg.de/).

### Datasets and Evaluation for VLM 


| Benchmark Dataset                                        | Metric Type        |     Evaluation Method    | Source                 | Size (K) | Project 							|
|----------------------------------------------------------|:------------------:|:------------------------:|:-----------------------:|:---------:|:----------------------------------:|
| [MMTBench](https://arxiv.org/pdf/2404.16006)         	        | Multiple Choice    | Acc                      | AI Experts               | 30.1 | [Github Repo](https://github.com/tylin/coco-caption)|
| [MM-Vet](https://arxiv.org/pdf/2308.02490)					| LLM Eval           | Acc                      | Human                    | 0.2  | [Github Repo](https://github.com/yuweihao/MM-Vet) |
| [MM-En/CN](https://arxiv.org/pdf/2307.06281) 					 | Multiple Choice    | Acc                      | Human                    | 3.2   |[Github Repo](https://github.com/open-compass/VLMEvalKit)|
| [GQA](https://arxiv.org/abs/2305.13245)						| Answer Matching	| Acc, Consistency, Validity | Seed with Synthetic | 22,000 |[Website](https://cs.stanford.edu/people/dorarad/gqa/index.html)|
| [VCR](https://arxiv.org/abs/1811.10830)						| Multiple Choice    | Acc    					| MTurks                  | 290| [Website](https://visualcommonsense.com/)|
| [VQAv2](https://arxiv.org/pdf/1505.00468)						| Yes/No; Answer Matching | Acc, F1  			| MTurks                  | 1,100| [Github Repo](https://github.com/salesforce/LAVIS/blob/main/dataset_card/vqav2.md)|
| [MMMU](https://arxiv.org/pdf/2311.16502)						| Answer Matching; Multiple Choice				| Acc    | College Students        | 11.5 |[Website](https://mmmu-benchmark.github.io/) |
| [SEEDBench](https://arxiv.org/pdf/2307.16125)					| Multiple Choice    | Acc                      | Synthetic                | 19 |[Github Repo](https://github.com/AILab-CVC/SEED-Bench) |
| [RealWorld QA](https://x.ai/blog/grok-1.5v)					| Multiple Choice    | Acc                      | Human                    | 0.765|[Huggingface](https://huggingface.co/datasets/visheratin/realworldqa)|
| [MMMU-Pro](https://arxiv.org/pdf/2409.02813)					| Multiple Choice    | Acc                      | Human                    | 3.64  |[Website](https://mmmu-benchmark.github.io/#leaderboard)|
| [DPG-Bench](https://arxiv.org/pdf/2403.05135)					| Semantic Alignment | Alignment Score          | Synthetic                | 1.06   |[Website](https://ella-diffusion.github.io)|
| [MSCOCO-30K](https://arxiv.org/pdf/1405.0312)					| BLEU, Rouge, Similarity | Similarity Score      | MTurks                  | 30 |[Website](https://cocodataset.org/#home)|
| [TextVQA](https://arxiv.org/pdf/1904.08920)					| Answer Matching    | Acc                      | CrowdSource              | 45		|[Github Repo](https://github.com/facebookresearch/mmf)|
| [DocVQA](https://arxiv.org/pdf/2007.00398)					| Answer Matching    | Acc                      | CrowdSource              | 50 |[Website](https://www.docvqa.org/)|
| [CMMLU](https://arxiv.org/pdf/2306.09212)						| Multiple Choice    | Acc                      | College Students         | 11.5|[Github Repo](https://github.com/haonan-li/CMMLU)|
| [C-Eval](https://arxiv.org/pdf/2305.08322)					| Multiple Choice    | Acc                      | Human                    | 13.9|[Website](https://cevalbenchmark.com/)|
| [TextVQA](https://arxiv.org/pdf/1904.08920)					| Answer Matching    | Acc                      | Expert Human             | 28.6	|[Github Repo](https://github.com/facebookresearch/mmf)|
| [MathVista](https://arxiv.org/pdf/2310.02255)					| Answer Matching/Multiple Choice | Acc              | Human                    | 6.15  |[Website](https://mathvista.github.io/)|
| [MathVision](https://arxiv.org/pdf/2402.14804) 				| Answer Matching/Multiple Choice | Acc              | College Students         | 3.04 |[Website](https://mathvision-cuhk.github.io/)|
| [OCRBench](https://arxiv.org/pdf/2305.07895)					| Answer Matching (ANLS) | Acc                   | Human                    | 1 |[Github Repo](https://github.com/Yuliang-Liu/MultimodalOCR)|
| [MME](https://arxiv.org/pdf/2306.13394)						| Yes/No             | Acc                      | Human                    | 2.8 |[Github Repo](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)|
| [InfographicVQA](https://arxiv.org/pdf/2104.12756) 			| Answer Matching    | Acc                      | CrowdSource              | 30|[Website](https://www.docvqa.org/)|
| [AI2D](https://arxiv.org/pdf/1603.07396)						| Answer Matching    | Acc                      | CrowdSource              | 1 |[Website](https://ai2d.med.upenn.edu/)|
| [ChartQA](https://arxiv.org/abs/2203.10244)					| Answer Matching    | Acc                      | CrowdSource/Synthetic    | 32.7 |[Github Repo](https://github.com/vis-nlp/ChartQA)|
| [GenEval](https://arxiv.org/pdf/2310.11513)					| CLIPScore/GenEval  | Similarity Score         | MTurks                  | 1.2	|[Github Repo](https://github.com/djghosh13/geneval)|
| [T2I-CompBench](https://arxiv.org/pdf/2307.06350)				| Multiple Metrics   | Similarity Score         | Synthetic                | 6 |[Website](https://karine-h.github.io/T2I-CompBench/)|
| [HallusionBench](https://arxiv.org/pdf/2310.14566)			| Yes/No             | Acc                      | Human                    | 1.13|[Github Repo](https://github.com/tianyi-lab/HallusionBench)|
| [POPE](https://arxiv.org/pdf/2305.10355)						| Yes/No             | Acc/Precision/Recall/F1  | Human                    | 9 |[Github Repo](https://github.com/RUCAIBox/POPE)|
| [MMLU](https://arxiv.org/pdf/2009.03300)						| Multiple Choice    | Acc                      | Human                    | 15.9	|[Github Repo](https://github.com/hendrycks/test)|
| [MMStar](https://arxiv.org/pdf/2403.20330)					| Multiple Choice    | Acc                      | Human                    | 1.5 |[Website](https://mmstar-benchmark.github.io/)|
| [M3GIA](https://arxiv.org/pdf/2406.05343)						| Multiple Choice    | Acc                      | Human                    | 1.8 |[Huggingface](https://huggingface.co/datasets/Songweii/M3GIA)|
| [InternetAGIEval](https://arxiv.org/pdf/2304.06364)			| Multiple Choice/Answer Matching | Acc/F1      | Human                    | 8.06    |[Github Repo](https://github.com/ruixiangcui/AGIEval)|
| [EgoSchem](https://arxiv.org/pdf/2308.09126)					| Multiple Choice    | Acc                      | Synthetic/Human          | 5     |[Website](https://egoschema.github.io/)|
| [MVBench](https://arxiv.org/pdf/2311.17005)					| Multiple Choice    | Acc                      | Synthetic/Human          | 4    |[Github Repo](https://github.com/OpenGVLab/Ask-Anything)|
| [MLVU](https://arxiv.org/pdf/2406.04264) 						| Multiple Choice    | Acc                      | Synthetic/Human          | 2.6   |[Github Repo](https://github.com/JUNJIE99/MLVU)|
| [VideoMME](https://arxiv.org/pdf/2405.21075)  | Multiple Choice    | Acc                      | Experts                  | 2.7                   |[Website](https://video-mme.github.io/)|
| [Perception-Test](https://arxiv.org/pdf/2305.13786)			| Multiple Choice    | Acc                      | CrowdSource       | 11.6 |[Github Repo](https://github.com/google-deepmind/perception_test)|



##  4. <a name='Toolenhancement'></a>⚒️ Tool enhancement
- **AI can help humans find common ground in democratic deliberation**, 2024.10, Science, [[paper]](https://www.science.org/doi/10.1126/science.adq2852).
- **PsyDI: Towards a Personalized and Progressively In-depth Chatbot for Psychological Measurements**, 2024, [[paper]](https://arxiv.org/abs/2408.03337), [[code]](https://github.com/opendilab/PsyDI).
- **ChatFive: Enhancing User Experience in Likert Scale Personality Test through Interactive Conversation with LLM Agents**, CUI 2024, [[paper]](https://dl.acm.org/doi/abs/10.1145/3640794.3665572)
- **LLM Agents for Psychology: A Study on Gamified Assessments**, 2024.02, [[paper]](https://arxiv.org/abs/2402.12326).
- **Generative Social Choice**, 2023.09, [[paper]](https://arxiv.org/abs/2309.01291)

##  5. <a name='Alignment'></a>⛑️ Alignment

- **Aligning Large Language Models with Human Opinions through Persona Selection and Value–Belief–Norm Reasoning**, 2024.11, [[paper]](https://arxiv.org/pdf/2311.08385).
- **SafetyAnalyst: Interpretable, transparent, and steerable LLM safety moderation**, 2024.10, [[paper]](https://arxiv.org/abs/2410.16665).
- **Moral Alignment for LLM Agents**, 2024.10, [[paper]](https://arxiv.org/abs/2410.01639).
- **ProgressGym: Alignment with a Millennium of Moral Progress**, NeurIPS 2024 D&B Tract Spotlight, [[paper]](https://arxiv.org/abs/2406.20087), [[code]](https://github.com/PKU-Alignment/ProgressGym).
- **Strong and weak alignment of large language models with human values**, 2024.08, Nature Scientific Reports, [[paper]](https://www.nature.com/articles/s41598-024-70031-3).
- **STELA: a community-centred approach to norm elicitation for AI alignment**, 2024.03, Nature Scientific Reports, [[paper]](https://www.nature.com/articles/s41598-024-56648-4).
- **A Roadmap to Pluralistic Alignment**, ICML 2024, [[paper]](https://arxiv.org/abs/2402.05070), [[code]](https://github.com/jfisher52/AI_Pluralistic_Alignment).
- [*Value*] **What are human values, and how do we align AI to them?**, 2024.04, [[paper]](https://arxiv.org/abs/2404.10636).
- **Agent Alignment in Evolving Social Norms**, 2024.01, [[paper]](https://arxiv.org/abs/2401.04620).
- [*Norm*] **Align on the Fly: Adapting Chatbot Behavior to Established Norms**, 2023.12, [[paper]](https://arxiv.org/abs/2312.15907), [[code]](https://github.com/GAIR-NLP/OPO).
- [*MBTI*] **Machine Mindset: An MBTI Exploration of Large Language Models**, 2023.12, [[paper]](https://arxiv.org/abs/2312.12999), [[code]](https://github.com/PKU-YuanGroup/Machine-Mindset).
- **Training Socially Aligned Language Models in Simulated Human Society**, 2023, [[paper]](https://arxiv.org/abs/2305.16960), [[code]](https://github.com/agi-templar/Stable-Alignment).
- **Fine-tuning language models to find agreement among humans with diverse preferences**, 2022, [[paper]](https://arxiv.org/abs/2211.15006).
- **ValueNet: A New Dataset for Human Value Driven Dialogue System**, AAAI 2022, [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21368), [[dataset]](https://liang-qiu.github.io/ValueNet/).

###  5.1. <a name='PluralisticAlignment'></a>🌈 Pluralistic Alignment
- [*Benchmark*] **Benchmarking Distributional Alignment of Large Language Models**, 2024.11, [[paper]](https://arxiv.org/abs/2411.05403).
- **Legal Theory for Pluralistic Alignment**, 2024.10, [[paper]](https://arxiv.org/abs/2410.17271).
- **Navigating the Cultural Kaleidoscope: A Hitchhiker’s Guide to Sensitivity in Large Language Models**, 2024.10, [[paper]](https://arxiv.org/abs/2410.12880), [[code and data]](https://github.com/NeuralSentinel/CulturalKaleidoscope).
- **PAD: Personalized Alignment at Decoding-Time**, 2024.10, [[paper]](https://arxiv.org/abs/2410.04070).
- **Policy Prototyping for LLMs: Pluralistic Alignment via Interactive and Collaborative Policymaking**, 2024.09, [[paper]](https://arxiv.org/abs/2409.08622).
- **Modular Pluralism: Pluralistic Alignment via Multi-LLM Collaboration**, 2024.06, [[paper]](https://arxiv.org/abs/2406.15951).

##  6. <a name='Simulation'></a>🚀 Simulation
- **OASIS: Open Agents Social Interaction Simulations on One Million Agents**, 2024.11, [[paper]](https://arxiv.org/abs/2411.11581), [[code]](https://github.com/camel-ai/oasis).
- **Generative Agent Simulations of 1,000 People**, 2024.11, [[paper]](https://arxiv.org/abs/2411.10109).
- **Social Science Meets LLMs: How Reliable Are Large Language Models in Social Simulations?**, 2024.11, [[paper]](https://arxiv.org/abs/2410.23426).
- **Multi-expert Prompting Improves Reliability, Safety, and Usefulness of Large Language Models**, EMNLP 2024, [[paper]](https://arxiv.org/pdf/2411.00492).
- **Simulating Opinion Dynamics with Networks of LLM-based Agents**, NAACL Findings 2024, [[paper]](https://aclanthology.org/2024.findings-naacl.211.pdf) [[code]](https://github.com/yunshiuan/llm-agent-opinion-dynamics)
- **Beyond demographics: Aligning role-playing llm-based agents using human belief networks**, EMNLP Findings 2024, [[paper]](https://arxiv.org/pdf/2406.17232)
- **The Wisdom of Partisan Crowds: Comparing Collective Intelligence in Humans and LLM-based Agents**, CogSci 2024, [[paper]](https://escholarship.org/content/qt3k67x8s5/qt3k67x8s5_noSplash_f34c019b5fef5ecab5b70e30108f787c.pdf)
- **Large Language Models can Achieve Social Balance**, 2024.10, [[paper]](https://arxiv.org/abs/2410.04054).
- **On the limits of agency in agent-based models**, 2024.09, [[paper]](https://arxiv.org/abs/2409.10568), [[code]](https://github.com/AgentTorch/AgentTorch).
- **United in Diversity? Contextual Biases in LLM-Based Predictions of the 2024 European Parliament Elections**, 2024.09, [[paper]](https://arxiv.org/abs/2409.09045).
- **Out of One, Many: Using Language Models to Simulate Human Samples**, 2022, [[paper]](https://arxiv.org/abs/2209.06899).
- **Social Simulacra: Creating Populated Prototypes for Social Computing Systems**, 2022, [[paper]](https://dl.acm.org/doi/abs/10.1145/3526113.3545616).
- **Generative Agents: Interactive Simulacra of Human Behavior**, 2023, [[paper]](https://arxiv.org/abs/2304.03442), [[code]](https://github.com/joonspk-research/generative_agents).
- **Using Large Language Models to Simulate Multiple Humans and Replicate Human Subject Studies**, 2023, [[paper]](https://proceedings.mlr.press/v202/aher23a.html), [[code]](https://github.com/GatiAher/Using-Large-Language-Models-to-Replicate-Human-Subject-Studies).
- **Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?**, 2023 [[paper]](https://www.nber.org/papers/w31122), [[code]](https://github.com/johnjosephhorton/homo_silicus).
- **$S^3$: Social-network Simulation System with Large Language Model-Empowered Agents**, 2023, [[paper]](https://arxiv.org/abs/2307.14984).
- **Rethinking the Buyer’s Inspection Paradox in Information Markets with Language Agents**, 2023, [[paper]](https://openreview.net/forum?id=6werMQy1uz).
- **SocioDojo: Building Lifelong Analytical Agents with Real-world Text and Time Series**, 2023, [[paper]](https://openreview.net/forum?id=s9z0HzWJJp).
- **Humanoid Agents: Platform for Simulating Human-like Generative Agents**, 2023, [[paper]](https://arxiv.org/abs/2310.05418), [[code]](https://github.com/HumanoidAgents/HumanoidAgents).
- **When Large Language Model based Agent Meets User Behavior Analysis: A Novel User Simulation Paradigm**, 2023, [[paper]](https://arxiv.org/abs/2306.02552), [[code]](https://github.com/RUC-GSAI/YuLan-Rec).
- **Large Language Model-Empowered Agents for Simulating Macroeconomic Activities**, 2023, [[paper]](https://arxiv.org/abs/2310.10436).
- **Generative Agent-Based Modeling: Unveiling Social System Dynamics through Coupling Mechanistic Models with Generative Artificial Intelligence**, 2023, [[paper]](https://arxiv.org/abs/2309.11456).
- **Using Imperfect Surrogates for Downstream Inference: Design-based Supervised Learning for Social Science Applications of Large Language Models**, 2023.06, NeurIPS 2023, [[paper]](https://arxiv.org/abs/2306.04746).
- **Epidemic Modeling with Generative Agents**, 2023.07, [[paper]](https://arxiv.org/abs/2307.04986), [[code]](https://github.com/bear96/GABM-Epidemic).
- **Emergent analogical reasoning in large language models**, 2023.08, nature human behavior, [[paper]](https://www.nature.com/articles/s41562-023-01659-w).
- **MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-oriented Coordination via Collaborative Generative Agents**, 2023.10, [[paper]](https://arxiv.org/abs/2310.06500).
- **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars**, 2023.11, [[paper]](https://arxiv.org/abs/2311.17227), [[code]](https://github.com/agiresearch/WarAgent).
- **Emergence of Social Norms in Large Language Model-based Agent Societies**, 2024.03, [[paper]](https://arxiv.org/abs/2403.08251), [[code]](https://github.com/sxswz213/CRSEC).
- **Large Content And Behavior Models To Understand, Simulate, And Optimize Content And Behavior**, ICLR-2024, [[paper]](https://openreview.net/forum?id=TrKq4Wlwcz)

##  7. <a name='Perspective'></a>👁️‍🗨️ Perspective

- **The benefits, risks and bounds of personalizing the alignment of large language models to individuals**, 2024.04, Nature Machine Intelligence, [[paper]](https://www.nature.com/articles/s42256-024-00820-y).
- **A social path to human-like artificial intelligence**, 2023.11, Nature Machine Intelligence, [[paper]](https://www.nature.com/articles/s42256-023-00754-x).
- **Using large language models in psychology**, 2023.10, Nature reviews psychology, [[paper]](https://www.nature.com/articles/s44159-023-00241-5).
