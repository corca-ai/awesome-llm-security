# Awesome LLM Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curation of awesome tools, documents and projects about LLM Security.

Contributions are always welcome. Please read the [Contribution Guidelines](CONTRIBUTING.md) before contributing.

## Table of Contents

- [Awesome LLM Security ](#awesome-llm-security-)
  - [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [White-box attack](#white-box-attack)
    - [Black-box attack](#black-box-attack)
    - [Backdoor attack](#backdoor-attack)
    - [Fingerprinting](#fingerprinting)
    - [Defense](#defense)
    - [Platform Security](#platform-security)
    - [Survey](#survey)
  - [Benchmark](#benchmark)
  - [Tools](#tools)
  - [Articles](#articles)
  - [Other Awesome Projects](#other-awesome-projects)
  - [Other Useful Resources](#other-useful-resources)

## Papers

### White-box attack
- "Visual Adversarial Examples Jailbreak Large Language Models", 2023-06, AAAI(Oral) 24, `multi-modal`, [[paper]](https://www.themoonlight.io/paper/share/9e1233aa-e417-448a-9032-05a11bff5a66) [[repo]](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models)
- "Are aligned neural networks adversarially aligned?", 2023-06, NeurIPS(Poster) 23, `multi-modal`, [[paper]](https://www.themoonlight.io/paper/share/282d463d-f9ce-4759-9e97-38b72c1200a7)
- "(Ab)using Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs", 2023-07, `multi-modal` [[paper]](https://www.themoonlight.io/paper/share/520e644a-b4f9-497f-9ebf-d6da198699aa)
- "Universal and Transferable Adversarial Attacks on Aligned Language Models", 2023-07, `transfer`, [[paper]](https://www.themoonlight.io/paper/share/5fc39128-9efa-49b3-8582-a909bab40dd3) [[repo]](https://github.com/llm-attacks/llm-attacks) [[page]](https://llm-attacks.org/)
- "Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models", 2023-07, `multi-modal`, [[paper]](https://www.themoonlight.io/paper/share/5409b2f8-3f70-4cee-bcf3-01563877acf8)
- "Image Hijacking: Adversarial Images can Control Generative Models at Runtime", 2023-09, `multi-modal`, [[paper]](https://www.themoonlight.io/paper/share/b06630ff-1269-4765-86ed-0c79563402c1) [[repo]](https://github.com/euanong/image-hijacks) [[site]](https://image-hijacks.github.io)
- "Weak-to-Strong Jailbreaking on Large Language Models", 2024-04, `token-prob`, [[paper]](https://www.themoonlight.io/paper/share/f8ec09ce-ebe5-4d59-ab7f-51fa27a4805e) [[repo]](https://github.com/XuandongZhao/weak-to-strong)

### Black-box attack
- "Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection", 2023-02, AISec@CCS 23 [[paper]](https://www.themoonlight.io/paper/share/8e338d56-34fc-411f-8f5f-2746997d7927)
- "Jailbroken: How Does LLM Safety Training Fail?", 2023-07, NeurIPS(Oral) 23, [[paper]](https://www.themoonlight.io/paper/share/1b53328c-f894-443b-8818-7e1d35580202)
- "Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output Robustness of Large Language Models", 2023-07, [[paper]](https://www.themoonlight.io/paper/share/4d35806f-3e25-4b28-abb3-2ea94b7246bd) [[repo]](https://github.com/qiuhuachuan/latent-jailbreak/tree/main)
- "Effective Prompt Extraction from Language Models", 2023-07, `prompt-extraction`, [[paper]](https://www.themoonlight.io/paper/share/9c059d79-6fac-47ad-93df-49db7e6bf1be)
- "Multi-step Jailbreaking Privacy Attacks on ChatGPT", 2023-04, EMNLP 23, `privacy`, [[paper]](https://www.themoonlight.io/paper/share/fec9d235-0578-4ec1-bf6a-b2b0f7049b44)
- "LLM Censorship: A Machine Learning Challenge or a Computer Security Problem?", 2023-07, [[paper]](https://www.themoonlight.io/paper/share/b638c2fa-7808-48ba-a624-1b94947bd63d)
- "Jailbreaking chatgpt via prompt engineering: An empirical study", 2023-05, [[paper]](https://www.themoonlight.io/paper/share/c63fb3e0-9767-45a9-8ef5-7d0438405fa6)
- "Prompt Injection attack against LLM-integrated Applications", 2023-06, [[paper]](https://www.themoonlight.io/paper/share/9f08a762-e3b2-4154-9696-60ade71b1a23) [[repo]](https://github.com/liu00222/Open-Prompt-Injection)
- "MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots", 2023-07, `time-side-channel`, [[paper]](https://www.themoonlight.io/paper/share/aee61233-baf5-4be7-8ac5-a012b7e0a821)
- "GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher", 2023-08, ICLR 24, `cipher`, [[paper]](https://www.themoonlight.io/paper/share/56f16d1d-ae59-4ef0-b4f1-ba78befc6e84) [[repo]](https://github.com/RobustNLP/CipherChat)
- "Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities", 2023-08, [[paper]](https://www.themoonlight.io/paper/share/8d52b850-83e9-4a32-bbd3-9e6d7da8a63b)
- "Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs", 2023-08, [[paper]](https://www.themoonlight.io/paper/share/b3ed2c03-9cca-4717-bab1-389643641bee) [[repo]](https://github.com/Libr-AI/do-not-answer) [[dataset]](https://huggingface.co/datasets/LibrAI/do-not-answer)
- "Detecting Language Model Attacks with Perplexity", 2023-08, [[paper]](https://www.themoonlight.io/paper/share/4b510f47-9a01-425a-b4e3-a2fc77623239)
- "Open Sesame! Universal Black Box Jailbreaking of Large Language Models", 2023-09, `gene-algorithm`, [[paper]](https://www.themoonlight.io/paper/share/61002df2-31c3-4c8d-ac30-165bd46d8dc7)
- "Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!", 2023-10, ICLR(oral) 24, [[paper]](https://www.themoonlight.io/paper/share/5d78aec9-b6a6-4b02-9104-cca3fedf38fd) [[repo]](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety) [[site]](https://llm-tuning-safety.github.io/) [[dataset]](https://huggingface.co/datasets/LLM-Tuning-Safety/HEx-PHI)
- "AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models", 2023-10, ICLR(poster) 24, `gene-algorithm`, `new-criterion`, [[paper]](https://www.themoonlight.io/paper/share/00bd272c-616c-4219-a5b9-249b3dd04e19)
- "Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations", 2023-10, CoRR 23, `ICL`, [[paper]](https://www.themoonlight.io/paper/share/66225baa-8a69-4c54-a0e5-9c10c5a750e4)
- "Multilingual Jailbreak Challenges in Large Language Models", 2023-10, ICLR(poster) 24, [[paper]](https://www.themoonlight.io/paper/share/b632c951-861c-4c12-8254-315ef0e074c9) [[repo]](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)
- "Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation", 2023-11, SoLaR(poster) 24, [[paper]](https://www.themoonlight.io/paper/share/540ebc2d-33bb-488f-8cc6-6f2886ffe279)
- "DeepInception: Hypnotize Large Language Model to Be Jailbreaker", 2023-11, [[paper]](https://www.themoonlight.io/paper/share/c57a3c8c-50a5-4a49-8f99-b1eec1a9b2b1) [[repo]](https://github.com/tmlr-group/DeepInception) [[site]](https://deepinception.github.io/)
- "A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily", 2023-11, NAACL 24, [[paper]](https://www.themoonlight.io/paper/share/fd52e4ff-efb3-471b-abf1-ec689418e0bf) [[repo]](https://github.com/NJUNLP/ReNeLLM)
- "AutoDAN: Automatic and Interpretable Adversarial Attacks on Large Language Models", 2023-10, [[paper]](https://www.themoonlight.io/paper/share/c340e5ed-c8d2-4b15-affe-aaad912943bd)
- "Language Model Inversion", 2023-11, ICLR(poster) 24, [[paper]](https://www.themoonlight.io/paper/share/d0615bef-03b4-4e2b-8bff-1b19e15c0056) [[repo]](https://github.com/jxmorris12/vec2text)
- "An LLM can Fool Itself: A Prompt-Based Adversarial Attack", 2023-10, ICLR(poster) 24, [[paper]](https://www.themoonlight.io/paper/share/193ec3b5-78ae-483b-adf5-aa6684919685) [[repo]](https://github.com/GodXuxilie/PromptAttack)
- "GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts", 2023-09, [[paper]](https://www.themoonlight.io/paper/share/2ebb8387-1e7a-4607-a309-fcd46a99d2be) [[repo]](https://github.com/sherdencooper/GPTFuzz) [[site]](https://github.com/sherdencooper/GPTFuzz)
- "Many-shot Jailbreaking", 2024-04, [[paper]](https://www.themoonlight.io/paper/share/4db82652-210c-45cc-942b-032a34e03930)
- "Rethinking How to Evaluate Language Model Jailbreak", 2024-04, [[paper]](https://www.themoonlight.io/paper/share/44eaf8b8-2f20-4d35-a438-1fada8e091fc) [[repo]](https://github.com/controllability/jailbreak-evaluation)

### Backdoor attack
- "BITE: Textual Backdoor Attacks with Iterative Trigger Injection", 2022-05, ACL 23, `defense` [[paper]](https://arxiv.org/pdf/2205.12700.pdf)
- "Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models", 2023-05, EMNLP 23, [[paper]](https://arxiv.org/pdf/2305.01219.pdf)
- "Backdooring Instruction-Tuned Large Language Models with Virtual Prompt Injection", 2023-07, NAACL 24, [[paper]](https://arxiv.org/pdf/2307.16888.pdf) [[repo]](https://github.com/wegodev2/virtual-prompt-injection) [[site]](https://poison-llm.github.io/)

### Fingerprinting
- "Instructional Fingerprinting of Large Language Models", 2024-01, NAACL 24 [[paper]](https://arxiv.org/abs/2401.12255) [[repo]](https://github.com/cnut1648/Model-Fingerprint) [[site]](https://cnut1648.github.io/Model-Fingerprint/)
- "TRAP: Targeted Random Adversarial Prompt Honeypot for Black-Box Identification", 2024-02, ACL 24 (findings) [[paper]](https://aclanthology.org/2024.findings-acl.683.pdf) [[repo]](https://github.com/parameterlab/trap) [[video]](https://www.youtube.com/watch?v=9PdvAaUVZ28) [[poster]](https://gubri.eu/pdf/Poster_TRAP_MGubri.pdf)
- "LLMmap: Fingerprinting For Large Language Models", 2024-07, [[paper]](https://arxiv.org/abs/2407.15847) [[repo]](https://github.com/pasquini-dario/LLMmap)

### Defense
- "Baseline Defenses for Adversarial Attacks Against Aligned Language Models", 2023-09, [[paper]](https://arxiv.org/pdf/2309.00614.pdf) [[repo]](https://github.com/neelsjain/baseline-defenses)
- "LLM Self Defense: By Self Examination, LLMs Know They Are Being Tricked", 2023-08, ICLR 24 Tiny Paper, `self-filtered`, [[paper]](https://arxiv.org/pdf/2308.07308.pdf) [[repo]](https://github.com/poloclub/llm-self-defense) [[site]](https://mphute.github.io/papers/llm-self-defense)
- "Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM", 2023-09, `random-mask-filter`, [[paper]](https://arxiv.org/pdf/2309.14348.pdf)
- "Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models", 2023-12, [[paper]](https://arxiv.org/pdf/2312.14197.pdf) [[repo]](https://github.com/microsoft/BIPIA)
- "AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks", 2024-03, [[paper]](https://arxiv.org/pdf/2403.04783.pdf) [[repo]](https://github.com/XHMY/AutoDefense)
- "Protecting Your LLMs with Information Bottleneck", 2024-04, [[paper]](https://arxiv.org/pdf/2404.13968.pdf) [[repo]](https://github.com/zichuan-liu/IB4LLMs)
- "PARDEN, Can You Repeat That? Defending against Jailbreaks via Repetition", 2024-05, ICML 24, [[paper]](https://arxiv.org/pdf/2405.07932) [[repo]](https://github.com/Ed-Zh/PARDEN)
- “Adversarial Tuning: Defending Against Jailbreak Attacks for LLMs”, 2024-06, [[paper]]([https://arxiv.org/pdf/2405.07932](https://www.researchgate.net/publication/381283534_Adversarial_Tuning_Defending_Against_Jailbreak_Attacks_for_LLMs))
- "Improving Alignment and Robustness with Circuit Breakers", 2024-06, NeurIPS 24, [[paper]](https://arxiv.org/pdf/2406.04313), [[repo]](https://github.com/GraySwanAI/circuit-breakers)

### Platform Security
- "LLM Platform Security: Applying a Systematic Evaluation Framework to OpenAI’s ChatGPT Plugins", 2023-09, [[paper]](https://arxiv.org/pdf/2309.10254.pdf) [[repo]](https://github.com/llm-platform-security/chatgpt-plugin-eval)

### Survey
- "Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks", 2023-10, ACL 24, [[paper]](https://arxiv.org/pdf/2310.10844.pdf)
- "Security and Privacy Challenges of Large Language Models: A Survey", 2024-02, [[paper]](https://arxiv.org/pdf/2402.00888.pdf)
- "Breaking Down the Defenses: A Comparative Survey of Attacks on Large Language Models", 2024-03, [[paper]](https://arxiv.org/pdf/2403.04786.pdf)
- "Operationalizing a Threat Model for Red-Teaming Large Language Models (LLMs)", 2024-07, [[paper]](https://arxiv.org/pdf/2407.14937)

## Benchmark
- "JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models", 2024-03, [[paper]](https://arxiv.org/pdf/2404.01318)
- "AgentDojo: A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents", 2024-06, NeurIPS 24, [[paper]](https://arxiv.org/pdf/2406.13352) [[repo]](https://github.com/ethz-spylab/agentdojo) [[site]](https://agentdojo.spylab.ai/)
- "Formalizing and Benchmarking Prompt Injection Attacks and Defenses", 2024-08, USENIX Security 24, [[paper]](https://www.usenix.org/system/files/usenixsecurity24-liu-yupei.pdf)
- "AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents", 2024-10, [[paper]](https://arxiv.org/abs/2410.09024)

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
- [WhistleBlower](https://github.com/Repello-AI/whistleblower): open-source tool designed to infer the system prompt of an AI agent based on its generated text outputs. ![GitHub Repo stars](https://img.shields.io/github/stars/Repello-AI/whistleblower?style=social)
- [Open-Prompt-Injection](https://github.com/liu00222/Open-Prompt-Injection): open-source tool to evaluate prompt injection attacks and defenses on benchmark datasets. ![GitHub Repo stars](https://img.shields.io/github/stars/liu00222/Open-Prompt-Injection?style=social)

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
- [LLM Evaluation metrics, frmaework, and checklist](https://repello.ai/blog/llm-evaluation-metrics-frameworks-and-checklist)
- [How RAG Poisoning Made Llama3 Racist!](https://repello.ai/blog/how-rag-poisoning-made-llama3-racist-1c5e390dd564)

## Other Awesome Projects

- (0din GenAI Bug Bounty from Mozilla)(https://0din.ai): The 0Day Investigative Network is a bug bounty program focusing on flaws within GenAI models. Vulnerability classes include Prompt Injection, Training Data Poisoning, DoS, and more.
- [Gandalf](https://gandalf.lakera.ai/): a prompt injection wargame
- [LangChain vulnerable to code injection - CVE-2023-29374](https://github.com/advisories/GHSA-fprp-p869-w6q2)
- [LLM Security startups](https://github.com/rushout09/llm-security-startups)
- [Adversarial Prompting](https://www.promptingguide.ai/risks/adversarial)
- [Epivolis](https://epivolis.com/): a prompt injection aware chatbot designed to mitigate adversarial efforts
- [LLM Security Problems at DEFCON31 Quals](https://github.com/Nautilus-Institute/quals-2023/tree/main/pawan_gupta): the world's top security competition
- [PromptBounty.io](https://sites.google.com/view/promptbounty/)
- [PALLMs (Payloads for Attacking Large Language Models)](https://github.com/mik0w/pallms)

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
