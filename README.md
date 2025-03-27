A curated paper list on **safety in reasoning of Large Reasoning Models (LRMs)**. Research on safety in reasoning for LRMs is still in its early stages. This repository aims to track and document advancements in this evolving field. Stay tuned for updates!

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](./LICENSE) ![Static Badge](https://img.shields.io/badge/Contributions-welcome-blue.svg?style=flat) 

## Content

- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
  - [Dataset and Systematical Study](#dataset-and-systematical-study)
  - [Comprehensive Analysis and Survey](#comprehensive-analysis-and-survey)
  - [Attack or Defense Methods](#attack-or-defense-methods)
  - [Evaluation and Guardrail](#evaluation-and-guardrail)
  - [Other Work](#other-work)
- [Resources](#resources)
- [Acknowledgements](#acknowledgements)


## Keywords Convention

![](https://img.shields.io/badge/COCONUT-blue) Abbreviation

![](https://img.shields.io/badge/ACL2025-orange) Conference

![](https://img.shields.io/badge/Analysis-green) Main Features

## Papers

### Dataset and Systematical Study
- **SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities**
  *Fengqing Jiang, Zhangchen Xu, Yuetai Li, Luyao Niu, Zhen Xiang, Bo Li, Bill Yuchen Lin, Radha Poovendran*. [[pdf](https://arxiv.org/pdf/2502.12025)] [[repo](https://github.com/uw-nsl/safechain)] [[data](https://huggingface.co/datasets/UWNSL/SafeChain)], 2025.2.17 ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SafeChain-blue) ![](https://img.shields.io/badge/three_decoding_strategies_without_additional_training-green) ![](https://img.shields.io/badge/dataset-green)
- **Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable**
  *Tiansheng Huang, Sihao Hu, Fatih Ilhan, Selim Furkan Tekin, Zachary Yahn, Yichang Xu, Ling Liu*. [[pdf](https://arxiv.org/pdf/2503.00555)] [[repo](https://github.com/git-disl/Safety-Tax)], 2025.3.1 ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DirectRefusal-blue) ![](https://img.shields.io/badge/tradeoff_between_safety_and_reasoning_capability-green) ![](https://img.shields.io/badge/dataset-green)


### Comprehensive Analysis and Survey
- **The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1**
  *Kaiwen Zhou, Chengzhi Liu, Xuandong Zhao, Shreedhar Jangam, Jayanth Srinivasa, Gaowen Liu, Dawn Song, Xin Eric Wang*. [[pdf](https://arxiv.org/abs/2502.12659v3)], 2025.2.27(v3) ![](https://img.shields.io/badge/Arxiv-orange)


### Attack or Defense Methods
- **BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack**
  *Zihao Zhu, Hongbao Zhang, Mingda Zhang, Ruotong Wang, Guanzong Wu, Ke Xu, Baoyuan Wu*. [[pdf](https://www.arxiv.org/pdf/2502.12202)] [[repo](https://github.com/zihao-ai/BoT)], 2025.2.16 ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/BoT-blue) ![](https://img.shields.io/badge/backdoor_attack-green) ![](https://img.shields.io/badge/dataset-green)
- **Reasoning-to-Defend: Safety-Aware Reasoning Can Defend Large Language Models from Jailbreaking**
  *Junda Zhu, Lingyong Yan, Shuaiqiang Wang, Dawei Yin, Lei Sha*. [[pdf](https://arxiv.org/pdf/2502.12970v1)] [[repo](https://github.com/chuhac/Reasoning-to-Defend)], 2025.2.18 ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/R2D-blue) ![](https://img.shields.io/badge/defend-green)
- **H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking**
  *Martin Kuo, Jianyi Zhang, Aolin Ding, Qinsi Wang, Louis DiValentin, Yujia Bao, Wei Wei, Hai Li, Yiran Chen*. [[pdf](https://arxiv.org/pdf/2502.12893)] [[repo](https://github.com/dukeceicenter/jailbreak-reasoning-openai-o1o3-deepseek-r1)], 2025.2.27(v2) ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/HCoT-blue) ![](https://img.shields.io/badge/attack-green)
- **Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models**
  *Meghana Rajeev, Rajkumar Ramamurthy, Prapti Trivedi, Vikas Yadav, Oluwanifemi Bamgbose, Sathwik Tejaswi Madhusudan, James Zou, Nazneen Rajani*. [[pdf](https://arxiv.org/pdf/2503.01781)] [[data](https://huggingface.co/datasets/collinear-ai/cat-attack-adversarial-triggers)], 2025.3.3 ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CatAttack-blue) ![](https://img.shields.io/badge/attack-green) ![](https://img.shields.io/badge/adversial_triggers-green) 

### Evaluation and Guardrail
- **GuardReasoner: Towards Reasoning-based LLM Safeguards**
  *Yue Liu, Hongcheng Gao, Shengfang Zhai, Jun Xia, Tianyi Wu, Zhiwei Xue, Yulin Chen, Kenji Kawaguchi, Jiaheng Zhang, Bryan Hooi*. [[pdf](https://arxiv.org/abs/2501.18492)] [[data](https://huggingface.co/datasets/yueliu1999/GuardReasonerTrain)], 2025.1.31 ![](https://img.shields.io/badge/ICLR2025_FM_Wild_Workshop-orange) ![](https://img.shields.io/badge/GuardReasoner-blue) ![](https://img.shields.io/badge/dataset-green) 

### Other Work
- **Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning**
  *Ang Li, Yichuan Mo, Mingjie Li, Yifei Wang, Yisen Wang*. [[pdf](https://arxiv.org/pdf/2502.09673)], 2025.2.21(v2) ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Analysis-green) 
- **OverThink: Slowdown Attacks on Reasoning LLMs**
  *Abhinav Kumar, Jaechul Roh, Ali Naseh, Marzena Karpinska, Mohit Iyyer, Amir Houmansadr, Eugene Bagdasarian*. [[pdf](https://arxiv.org/pdf/2502.02542)], 2025.2.5(v2) ![](https://img.shields.io/badge/Arxiv-orange)
- **o3-mini vs DeepSeek-R1: Which One is Safer?**
  *Aitor Arrieta, Miriam Ugarte, Pablo Valle, José Antonio Parejo, Sergio Segura*. [[pdf](https://arxiv.org/pdf/2501.18438)], 2025.1.31(v2) ![](https://img.shields.io/badge/Arxiv-orange)
- **Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies**
  *Manojkumar Parmar, Yuvaraj Govindarajulu*. [[pdf](https://arxiv.org/pdf/2501.17030)], 2025.1.28 ![](https://img.shields.io/badge/Arxiv-orange)
- **MetaSC: Test-Time Safety Specification Optimization for Language Models**
  *Víctor Gallego*. [[pdf](https://arxiv.org/pdf/2502.07985)], 2025.2.11 ![](https://img.shields.io/badge/Arxiv-orange)
- **Leveraging Reasoning with Guidelines to Elicit and Utilize Knowledge for Enhancing Safety Alignment**
  *Haoyu Wang, Zeyu Qin, Li Shen, Xueqian Wang, Minhao Cheng, Dacheng Tao*. [[pdf](https://arxiv.org/pdf/2502.04040)], 2025.2.6 ![](https://img.shields.io/badge/Arxiv-orange)
- **Reasoning and the Trusting Behavior of DeepSeek and GPT: An Experiment Revealing Hidden Fault Lines in Large Language Models**
  *Rubing Li, João Sedoc, Arun Sundararajan*. [[pdf](https://arxiv.org/pdf/2502.12825)], 2025.2.6 ![](https://img.shields.io/badge/Arxiv-orange)
- **Investigating the Impact of Quantization Methods on the Safety and Reliability of Large Language Models**
  *Artyom Kharinaev, Viktor Moskvoretskii, Egor Shvetsov, Kseniia Studenikina, Bykov Mikhail, Evgeny Burnaev*. [[pdf](https://arxiv.org/abs/2502.15799)], 2025.2.18 ![](https://img.shields.io/badge/Arxiv-orange)


## Resources
Reading lists related to LLMs/LRMs safety:
- [LightChen233/Awesome-Long-Chain-of-Thought-Reasoning](https://github.com/LightChen233/Awesome-Long-Chain-of-Thought-Reasoning)
- [tjunlp-lab/Awesome-LLM-Safety-Papers](https://github.com/tjunlp-lab/Awesome-LLM-Safety-Papers)
- [ianitow/awesome-guardrails-llm-papers](https://github.com/ianitow/awesome-guardrails-llm-papers)

## Acknowledgements

- We acknowledge that some important works in this field may be missing from this list. We warmly welcome contributions to help us improve!
- If you would like to promote your work or suggest other relevant papers, please feel free to open an issue or submit a pull request(PR). Your contributions are greatly appreciated, and we thank you in advance for helping enhance this resource!  
- Special thanks to [Awesome-Efficient-Reasoning](https://github.com/hemingkx/Awesome-Efficient-Reasoning), which inspired the structure and template of this project.