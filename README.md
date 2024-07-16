# Awesome LLM Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curation of awesome tools, documents and projects about LLM Security.

Contributions are always welcome. Please read the [Contribution Guidelines](CONTRIBUTING.md) before contributing.

## Table of Contents

- [Awesome LLM Security](#awesome-llm-security-)
  - [Papers](#papers)
    - [White-box attack](#white-box-attack)
    - [Black-box attack](#black-box-attack)
    - [Backdoor attack](#backdoor-attack)
    - [Defense](#defense)
    - [Platform Security](#platform-security)
    - [Survey](#survey)
  - [Tools](#tools)
  - [Articles](#articles)
  - [Other Awesome Projects](#other-awesome-projects)
  - [Other Useful Resources](#other-useful-resources)

## Papers

### White-box attack
- "Visual Adversarial Examples Jailbreak Large Language Models", 2023-06, AAAI(Oral) 24, `multi-modal`, [[paper]](https://arxiv.org/pdf/2306.13213.pdf) [[repo]](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models)
- "Are aligned neural networks adversarially aligned?", 2023-06, NeurIPS(Poster) 23, `multi-modal`, [[paper]](https://arxiv.org/pdf/2306.15447.pdf)
- "(Ab)using Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs", 2023-07, `multi-modal` [[paper]](https://arxiv.org/pdf/2307.10490.pdf)
- "Universal and Transferable Adversarial Attacks on Aligned Language Models", 2023-07, `transfer`, [[paper]](https://arxiv.org/pdf/2307.15043.pdf) [[repo]](https://github.com/llm-attacks/llm-attacks) [[page]](https://llm-attacks.org/)
- "Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models", 2023-07, `multi-modal`, [[paper]](https://arxiv.org/pdf/2307.14539.pdf)
- "Image Hijacking: Adversarial Images can Control Generative Models at Runtime", 2023-09, `multi-modal`, [[paper]](https://arxiv.org/pdf/2309.00236.pdf) [[repo]](https://github.com/euanong/image-hijacks) [[site]](https://image-hijacks.github.io)
- "Weak-to-Strong Jailbreaking on Large Language Models", 2024-04, `token-prob`, [[paper]](https://arxiv.org/pdf/2401.17256.pdf) [[repo]](https://github.com/XuandongZhao/weak-to-strong)

### Black-box attack
- "Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection", 2023-02, AISec@CCS 23 [[paper]](https://arxiv.org/pdf/2302.12173.pdf)
- "Jailbroken: How Does LLM Safety Training Fail?", 2023-07, NeurIPS(Oral) 23, [[paper]](https://arxiv.org/pdf/2307.02483.pdf)
- "Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output Robustness of Large Language Models", 2023-07, [[paper]](https://arxiv.org/pdf/2307.08487.pdf) [[repo]](https://github.com/qiuhuachuan/latent-jailbreak/tree/main)
- "Effective Prompt Extraction from Language Models", 2023-07, `prompt-extraction`, [[paper]](https://arxiv.org/pdf/2307.06865.pdf)
- "Multi-step Jailbreaking Privacy Attacks on ChatGPT", 2023-04, EMNLP 23, `privacy`, [[paper]](https://arxiv.org/pdf/2304.05197.pdf)
- "LLM Censorship: A Machine Learning Challenge or a Computer Security Problem?", 2023-07, [[paper]](https://arxiv.org/pdf/2307.10719.pdf)
- "Jailbreaking chatgpt via prompt engineering: An empirical study", 2023-05, [[paper]](https://arxiv.org/pdf/2305.13860.pdf)
- "Prompt Injection attack against LLM-integrated Applications", 2023-06, [[paper]](https://arxiv.org/pdf/2306.05499.pdf) [[repo]](https://github.com/liu00222/Open-Prompt-Injection)
- "MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots", 2023-07, `time-side-channel`, [[paper]](https://arxiv.org/pdf/2307.08715.pdf)
- "GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher", 2023-08, ICLR 24, `cipher`, [[paper]](https://arxiv.org/pdf/2308.06463.pdf) [[repo]](https://github.com/RobustNLP/CipherChat)
- "Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities", 2023-08, [[paper]](https://arxiv.org/pdf/2308.12833.pdf)
- "Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs", 2023-08, [[paper]](https://arxiv.org/pdf/2308.13387.pdf) [[repo]](https://github.com/Libr-AI/do-not-answer) [[dataset]](https://huggingface.co/datasets/LibrAI/do-not-answer)
- "Detecting Language Model Attacks with Perplexity", 2023-08, [[paper]](https://arxiv.org/pdf/2308.14132.pdf)
- "Open Sesame! Universal Black Box Jailbreaking of Large Language Models", 2023-09, `gene-algorithm`, [[paper]](https://arxiv.org/pdf/2309.01446.pdf)
- "Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!", 2023-10, ICLR(oral) 24, [[paper]](https://arxiv.org/pdf/2310.03693.pdf) [[repo]](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety) [[site]](https://llm-tuning-safety.github.io/) [[dataset]](https://huggingface.co/datasets/LLM-Tuning-Safety/HEx-PHI)
- "AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models", 2023-10, ICLR(poster) 24, `gene-algorithm`, `new-criterion`, [[paper]](https://arxiv.org/pdf/2310.04451.pdf)
- "Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations", 2023-10, CoRR 23, `ICL`, [[paper]](https://arxiv.org/pdf/2310.06387.pdf)
- "Multilingual Jailbreak Challenges in Large Language Models", 2023-10, ICLR(poster) 24, [[paper]](https://arxiv.org/pdf/2310.06474.pdf) [[repo]](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)
- "Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation", 2023-11, SoLaR(poster) 24, [[paper]](https://arxiv.org/pdf/2311.03348.pdf)
- "DeepInception: Hypnotize Large Language Model to Be Jailbreaker", 2023-11, [[paper]](https://arxiv.org/pdf/2311.03191.pdf) [[repo]](https://github.com/tmlr-group/DeepInception) [[site]](https://deepinception.github.io/)
- "A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily", 2023-11, NAACL 24, [[paper]](https://arxiv.org/pdf/2311.08268.pdf) [[repo]](https://github.com/NJUNLP/ReNeLLM)
- "AutoDAN: Automatic and Interpretable Adversarial Attacks on Large Language Models", 2023-10, [[paper]](https://arxiv.org/pdf/2310.15140.pdf)
- "Language Model Inversion", 2023-11, ICLR(poster) 24, [[paper]](https://arxiv.org/pdf/2311.13647.pdf) [[repo]](https://github.com/jxmorris12/vec2text)
- "An LLM can Fool Itself: A Prompt-Based Adversarial Attack", 2023-10, ICLR(poster) 24, [[paper]](https://arxiv.org/pdf/2310.13345.pdf) [[repo]](https://github.com/GodXuxilie/PromptAttack)
- "GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts", 2023-09, [[paper]](https://arxiv.org/pdf/2309.10253.pdf) [[repo]](https://github.com/sherdencooper/GPTFuzz) [[site]](https://github.com/sherdencooper/GPTFuzz)
- "Many-shot Jailbreaking", 2024-04, [[paper]](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf)
- "Rethinking How to Evaluate Language Model Jailbreak", 2024-04, [[paper]](https://arxiv.org/pdf/2404.06407.pdf) [[repo]](https://github.com/controllability/jailbreak-evaluation)

### Backdoor attack
- "BITE: Textual Backdoor Attacks with Iterative Trigger Injection", 2022-05, ACL 23, `defense` [[paper]](https://arxiv.org/pdf/2205.12700.pdf)
- "Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models", 2023-05, EMNLP 23, [[paper]](https://arxiv.org/pdf/2305.01219.pdf)
- "Backdooring Instruction-Tuned Large Language Models with Virtual Prompt Injection", 2023-07, NAACL 24, [[paper]](https://arxiv.org/pdf/2307.16888.pdf) [[repo]](https://github.com/wegodev2/virtual-prompt-injection) [[site]](https://poison-llm.github.io/)

### Defense
- "Baseline Defenses for Adversarial Attacks Against Aligned Language Models", 2023-09, [[paper]](https://arxiv.org/pdf/2309.00614.pdf) [[repo]](https://github.com/neelsjain/baseline-defenses)
- "LLM Self Defense: By Self Examination, LLMs Know They Are Being Tricked", 2023-08, ICLR 24 Tiny Paper, `self-filtered`, [[paper]](https://arxiv.org/pdf/2308.07308.pdf) [[repo]](https://github.com/poloclub/llm-self-defense) [[site]](https://mphute.github.io/papers/llm-self-defense)
- "Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM", 2023-09, `random-mask-filter`, [[paper]](https://arxiv.org/pdf/2309.14348.pdf)
- "Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models", 2023-12, [[paper]](https://arxiv.org/pdf/2312.14197.pdf) [[repo]](https://github.com/microsoft/BIPIA)
- "AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks", 2024-03, [[paper]](https://arxiv.org/pdf/2403.04783.pdf) [[repo]](https://github.com/XHMY/AutoDefense)
- "Protecting Your LLMs with Information Bottleneck", 2024-04, [[paper]](https://arxiv.org/pdf/2404.13968.pdf) [[repo]](https://github.com/zichuan-liu/IB4LLMs)
- "PARDEN, Can You Repeat That? Defending against Jailbreaks via Repetition", 2024-05, ICML 24, [[paper]](https://arxiv.org/pdf/2405.07932) [[repo]](https://github.com/Ed-Zh/PARDEN)
- “Adversarial Tuning: Defending Against Jailbreak Attacks for LLMs”, 2024-06, [[paper]]([https://arxiv.org/pdf/2405.07932](https://www.researchgate.net/publication/381283534_Adversarial_Tuning_Defending_Against_Jailbreak_Attacks_for_LLMs))

### Platform Security
- "LLM Platform Security: Applying a Systematic Evaluation Framework to OpenAI’s ChatGPT Plugins", 2023-09, [[paper]](https://arxiv.org/pdf/2309.10254.pdf) [[repo]](https://github.com/llm-platform-security/chatgpt-plugin-eval)

### Survey
- "Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks", 2023-10, ACL 24, [[paper]](https://arxiv.org/pdf/2310.10844.pdf)
- "Security and Privacy Challenges of Large Language Models: A Survey", 2024-02, [[paper]](https://arxiv.org/pdf/2402.00888.pdf)
- "Breaking Down the Defenses: A Comparative Survey of Attacks on Large Language Models", 2024-03, [[paper]](https://arxiv.org/pdf/2403.04786.pdf)

## Tools

- [Plexiglass](https://github.com/kortex-labs/plexiglass): a security toolbox for testing and safeguarding LLMs ![GitHub Repo stars](https://img.shields.io/github/stars/kortex-labs/plexiglass?style=social)
- [PurpleLlama](https://github.com/facebookresearch/PurpleLlama): set of tools to assess and improve LLM security. ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/PurpleLlama?style=social)
- [Rebuff](https://github.com/protectai/rebuff): a self-hardening prompt injection detector ![GitHub Repo stars](https://img.shields.io/github/stars/protectai/rebuff?style=social)
- [Garak](https://github.com/leondz/garak/): a LLM vulnerability scanner ![GitHub Repo stars](https://img.shields.io/github/stars/leondz/garak?style=social)
- [LLMFuzzer](https://github.com/mnns/LLMFuzzer): a fuzzing framework for LLMs ![GitHub Repo stars](https://img.shields.io/github/stars/mnns/LLMFuzzer?style=social)
- [LLM Guard](https://github.com/laiyer-ai/llm-guard): a security toolkit for LLM Interactions ![GitHub Repo stars](https://img.shields.io/github/stars/laiyer-ai/llm-guard?style=social)
- [Vigil](https://github.com/deadbits/vigil-llm): a LLM prompt injection detection toolkit ![GitHub Repo stars](https://img.shields.io/github/stars/deadbits/vigil-llm?style=social)
- [jailbreak-evaluation](https://github.com/controllability/jailbreak-evaluation): an easy-to-use Python package for language model jailbreak evaluation ![GitHub Repo stars](https://img.shields.io/github/stars/controllability/jailbreak-evaluation?style=social)
- [Prompt Fuzzer](https://github.com/prompt-security/ps-fuzz): the open-source tool to help you harden your GenAI applications ![GitHub Repo stars](https://img.shields.io/github/stars/prompt-security/ps-fuzz?style=social)

## Articles

- [Hacking Auto-GPT and escaping its docker container](https://positive.security/blog/auto-gpt-rce)
- [Prompt Injection Cheat Sheet: How To Manipulate AI Language Models](https://blog.seclify.com/prompt-injection-cheat-sheet/)
- [Indirect Prompt Injection Threats](https://greshake.github.io/)
- [Prompt injection: What’s the worst that can happen?](https://simonwillison.net/2023/Apr/14/worst-that-can-happen/)
- [OWASP Top 10 for Large Language Model Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [PoisonGPT: How we hid a lobotomized LLM on Hugging Face to spread fake news](https://blog.mithrilsecurity.io/poisongpt-how-we-hid-a-lobotomized-llm-on-hugging-face-to-spread-fake-news/)
- [ChatGPT Plugins: Data Exfiltration via Images & Cross Plugin Request Forgery](https://embracethered.com/blog/posts/2023/chatgpt-webpilot-data-exfil-via-markdown-injection/)
- [Jailbreaking GPT-4's code interpreter](https://www.lesswrong.com/posts/KSroBnxCHodGmPPJ8/jailbreaking-gpt-4-s-code-interpreter)
- [Securing LLM Systems Against Prompt Injection](https://developer.nvidia.com/blog/securing-llm-systems-against-prompt-injection/)
- [The AI Attack Surface Map v1.0](https://danielmiessler.com/p/the-ai-attack-surface-map-v1-0/)
- [Adversarial Attacks on LLMs](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/)
- [How Anyone can Hack ChatGPT - GPT4o](https://medium.com/@deltaaruna/how-anyone-can-hack-chatgpt-aa7959684ef0)

## Other Awesome Projects

- (0din GenAI Bug Bounty from Mozilla)(https://0din.ai): The 0Day Investigative Network is a bug bounty program focusing on flaws within GenAI models. Vulnerability classes include Prompt Injection, Training Data Poisoning, DoS, and more.
- [Gandalf](https://gandalf.lakera.ai/): a prompt injection wargame
- [LangChain vulnerable to code injection - CVE-2023-29374](https://github.com/advisories/GHSA-fprp-p869-w6q2)
- [Jailbreak Chat](https://www.jailbreakchat.com/)
- [Adversarial Prompting](https://www.promptingguide.ai/risks/adversarial)
- [Epivolis](https://epivolis.com/): a prompt injection aware chatbot designed to mitigate adversarial efforts
- [LLM Security Problems at DEFCON31 Quals](https://github.com/Nautilus-Institute/quals-2023/tree/main/pawan_gupta): the world's top security competition
- [PromptBounty.io](https://sites.google.com/view/promptbounty/)
- [PALLMs (Payloads for Attacking Large Language Models)](https://github.com/mik0w/pallms)
- [Machine_Learning_CTF_Challenges](https://github.com/alexdevassy/Machine_Learning_CTF_Challenges)

## Other Useful Resources

- Twitter: [@llm_sec](https://twitter.com/llm_sec)
- Blog: [LLM Security](https://llmsecurity.net/) authored by [@llm_sec](https://twitter.com/llm_sec)
- Blog: [Embrace The Red](https://embracethered.com/blog/index.html)
- Blog: [Kai's Blog](https://kai-greshake.de/)
- Newsletter: [AI safety takes](https://newsletter.danielpaleka.com/)
- Newsletter & Blog: [Hackstery](https://hackstery.com)

<a href="https://star-history.com/#corca-ai/awesome-llm-security&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=corca-ai/awesome-llm-security&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=corca-ai/awesome-llm-security&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=corca-ai/awesome-llm-security&type=Date" />
  </picture>
</a>
