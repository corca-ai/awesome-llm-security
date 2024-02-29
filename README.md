# Awesome LLM Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curation of awesome tools, documents and projects about LLM Security.

Contributions are always welcome. Please read the [Contribution Guidelines](CONTRIBUTING.md) before contributing.

## Table of Contents

- [Awesome LLM Security](#awesome-llm-security-)
  - [Papers](#papers)
  - [Tools](#tools)
  - [Articles](#articles)
  - [Other Awesome Projects](#other-awesome-projects)
  - [Other Useful Resources](#other-useful-resources)

## Papers

- [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/pdf/2302.12173.pdf)
- [Visual Adversarial Examples Jailbreak Large Language Models](https://arxiv.org/pdf/2306.13213.pdf)
- [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/pdf/2307.02483.pdf)
- [Are aligned neural networks adversarially aligned?](https://arxiv.org/pdf/2306.15447.pdf)
- [Latent Jailbreak: A Benchmark for Evaluating Text Safety and Output Robustness of Large Language Models](https://arxiv.org/pdf/2307.08487.pdf)
- [(Ab)using Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/pdf/2307.10490.pdf)
- [Prompts Should not be Seen as Secrets: Systematically Measuring Prompt Extraction Attack Success](https://arxiv.org/pdf/2307.06865.pdf)
- [BITE: Textual Backdoor Attacks with Iterative Trigger Injection](https://aclanthology.org/2023.acl-long.725.pdf)
- [Multi-step Jailbreaking Privacy Attacks on ChatGPT](https://arxiv.org/pdf/2304.05197.pdf)
- [Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models](https://arxiv.org/pdf/2305.01219.pdf)
- [LLM Censorship: A Machine Learning Challenge or a Computer Security Problem?](https://arxiv.org/pdf/2307.10719.pdf)
- [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/pdf/2307.15043.pdf)
- [Plug and Pray: Exploiting off-the-shelf components of Multi-Modal Models](https://arxiv.org/pdf/2307.14539.pdf)
- [Virtual Prompt Injection for Instruction-Tuned Large Language Models](https://arxiv.org/pdf/2307.16888.pdf)
- [Jailbreaking chatgpt via prompt engineering: An empirical study](https://arxiv.org/pdf/2305.13860.pdf)
- [Prompt Injection attack against LLM-integrated Applications](https://arxiv.org/pdf/2306.05499.pdf)
- [Jailbreaker: Automated Jailbreak Across Multiple Large Language Model Chatbots](https://arxiv.org/pdf/2307.08715.pdf)
- [GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher](https://arxiv.org/pdf/2308.06463.pdf)
- [LLM Self Defense: By Self Examination, LLMs Know They Are Being Tricked](https://arxiv.org/pdf/2308.07308.pdf)
- [Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities](https://arxiv.org/pdf/2308.12833.pdf)
- [Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs](https://arxiv.org/pdf/2308.13387.pdf)
- [Detecting Language Model Attacks with Perplexity](https://arxiv.org/pdf/2308.14132.pdf)
- [Baseline Defenses for Adversarial Attacks Against Aligned Language Models](https://arxiv.org/pdf/2309.00614.pdf)
- [Image Hijacking: Adversarial Images can Control Generative Models at Runtime](https://arxiv.org/pdf/2309.00236.pdf)
- [Open Sesame! Universal Black Box Jailbreaking of Large Language Models](https://arxiv.org/pdf/2309.01446.pdf)
- [LLM Platform Security: Applying a Systematic Evaluation Framework to OpenAI’s ChatGPT Plugins](https://arxiv.org/pdf/2309.10254.pdf)
- [Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM](https://arxiv.org/pdf/2309.14348.pdf)
- [Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/pdf/2310.03693.pdf)
- [AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models](https://arxiv.org/pdf/2310.04451.pdf)
- [Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations](https://arxiv.org/pdf/2310.06387.pdf)
- [Multilingual Jailbreak Challenges in Large Language Models](https://arxiv.org/pdf/2310.06474.pdf)
- [Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks](https://arxiv.org/pdf/2310.10844.pdf)
- [Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation](https://arxiv.org/pdf/2311.03348.pdf)
- [DeepInception: Hypnotize Large Language Model to Be Jailbreaker](https://arxiv.org/pdf/2311.03191.pdf)
- [A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily](https://arxiv.org/pdf/2311.08268.pdf)
- [AutoDAN: Automatic and Interpretable Adversarial Attacks on Large Language Models](https://arxiv.org/pdf/2310.15140.pdf)
- [Language Model Inversion](https://arxiv.org/pdf/2311.13647.pdf)
- [Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models](https://arxiv.org/pdf/2312.14197.pdf)
- [An LLM can Fool Itself: A Prompt-Based Adversarial Attack](https://arxiv.org/pdf/2310.13345.pdf)
- [Weak-to-Strong Jailbreaking on Large Language Models](https://arxiv.org/pdf/2401.17256.pdf)
- [Security and Privacy Challenges of Large Language Models: A Survey](https://arxiv.org/pdf/2402.00888.pdf)
- [GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts](https://arxiv.org/pdf/2309.10253.pdf)
- [DrAttack: Prompt Decomposition and Reconstruction Makes Powerful LLM Jailbreakers](https://arxiv.org/pdf/2402.16914.pdf)

## Tools

- [Plexiglass](https://github.com/kortex-labs/plexiglass): a security toolbox for testing and safeguarding LLMs ![GitHub Repo stars](https://img.shields.io/github/stars/kortex-labs/plexiglass?style=social) 
- [PurpleLlama](https://github.com/facebookresearch/PurpleLlama): set of tools to assess and improve LLM security. ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/PurpleLlama?style=social) 
- [Rebuff](https://github.com/protectai/rebuff): a self-hardening prompt injection detector ![GitHub Repo stars](https://img.shields.io/github/stars/protectai/rebuff?style=social)
- [Garak](https://github.com/leondz/garak/): a LLM vulnerability scanner ![GitHub Repo stars](https://img.shields.io/github/stars/leondz/garak?style=social)
- [LLMFuzzer](https://github.com/mnns/LLMFuzzer): a fuzzing framework for LLMs ![GitHub Repo stars](https://img.shields.io/github/stars/mnns/LLMFuzzer?style=social)
- [LLM Guard](https://github.com/laiyer-ai/llm-guard): a security toolkit for LLM Interactions ![GitHub Repo stars](https://img.shields.io/github/stars/laiyer-ai/llm-guard?style=social)
- [Vigil](https://github.com/deadbits/vigil-llm): a LLM prompt injection detection toolkit ![GitHub Repo stars](https://img.shields.io/github/stars/deadbits/vigil-llm?style=social)

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

## Other Awesome Projects

- [Gandalf](https://gandalf.lakera.ai/): a prompt injection wargame
- [LangChain vulnerable to code injection - CVE-2023-29374](https://github.com/advisories/GHSA-fprp-p869-w6q2)
- [Jailbreak Chat](https://www.jailbreakchat.com/)
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
