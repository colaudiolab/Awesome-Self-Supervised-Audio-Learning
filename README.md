# Awesome-Self-Supervised-Audio-Learning

[//]: # (# Self-Supervised Audio Learning)

<p align="center">
  <img src="./media/title.png" alt="image" style="width:1000px;">
</p>

[![Awesome](media/badge.svg)](https://github.com/colaudiolab/Awesome-Self-Supervised-Audio-Learning) 
[![License: MIT](media/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](media/Made-With-Love-red.svg)](https://github.com/colaudiolab/Awesome-Self-Supervised-Audio-Learning)
[![arXiv](media/arXiv-Paper-red.svg)](xxx) 
[![visitors](https://visitor-badge.laobi.icu/badge?page_id=colaudiolab.Awesome-Self-Supervised-Audio-Learning)](https://visitor-badge.laobi.icu/badge?page_id=colaudiolab.Awesome-Self-Supervised-Audio-Learning)

The repository is based on our survey [A Systematic Review on Self-Supervised Learning for Audio Signal: Taxonomy, Applications and Future Trends](xxx) (Submit to TPAMI 2026).

xxx, Kele Xu

National University of Defense Technology(NUDT)

## Abstract
This survey provides a comprehensive and systematic review of self-supervised learning (SSL) in audio signal processing, tracing its evolution from early heuristic-based pretext tasks to the current era of Native Large Audio Language Models (LALMs) and omni-modal foundation models. We propose a multidimensional taxonomy that categorizes SSL methods into five dominant paradigms: early auxiliary tasks, contrastive discrimination, generative reconstruction, discrete semantic prediction, and multimodal alignment. Unlike previous reviews, this paper explicitly analyzes the role of architectural inductive biases—ranging from the locality of CNNs to the global context modeling of Transformers and the linear-time efficiency of modern State Space Models (SSMs) like Mamba.
Furthermore, we evaluate the impact of SSL across diverse domains, including next-generation speech processing, environmental sound analysis, music information retrieval (MIR), and healthcare bioacoustics. A significant focus is placed on recent breakthroughs, such as Neural Codec Language Models (NCLMs), Flow Matching paradigms (e.g., F5-TTS), and the integration of deep reasoning mechanisms through post-training techniques like Group Relative Policy Optimization (GRPO). We also provide an exhaustive overview of standardized benchmark suites (e.g., SUPERB, HEAR, AudioBench) and formal mathematical definitions of core evaluation metrics. Finally, we discuss the ``perceptual bottleneck'' and security vulnerabilities as primary challenges, and outline future trends toward physics-informed, 4D audio-visual intelligence and unified end-to-end omni-modal reasoning.

## 📢 News!!!

📌 We are actively tracking the latest research and welcome contributions to our repository and survey paper. If your studies are relevant, please feel free to contact us.

📰 2026-xx-xx: Our repository now features a curated list of representative self-supervised audio learning papers published up to Jan 1, 2026.

📰 2026-xx-xx: Our survey paper has been uploaded to ArXiv.

📰 2026-03-20: Our survey paper has been submitted to TPAMI 2026.


## 🔍 BibTeX
If you find this work helpful in your research, welcome to cite the paper and give a ⭐.

```

```


## Table of contents
- [Papers](#papers)
  - <details>
    <summary>Training-Based</summary>
    
    - [Training-Based: Domain-Specific Editing with Weak Supervision](#training-based-domain-specific-editing-with-weak-supervision)
    - [Training-Based: Reference and Attribute Guidance via Self-Supervision](#training-based-reference-and-attribute-guidance-via-self-supervision)
    - [Training-Based: Instructional Editing via Full Supervision](#training-based-instructional-editing-via-full-supervision)
    - [Training-Based: Pseudo-Target Retrieval with Weak Supervision](#training-based-pseudo-target-retrieval-with-weak-supervision)
    </details>
  - <details>
    <summary>Testing-Time Finetuning</summary>
    
    - [Testing-Time Finetuning: Denosing Model Finetuning](#testing-time-finetuning-denosing-model-finetuning)
    - [Testing-Time Finetuning: Embeddings Finetuning](#testing-time-finetuning-embeddings-finetuning)
    - [Testing-Time Finetuning: Guidance with Hypernetworks](#testing-time-finetuning-guidance-with-hypernetworks)
    - [Testing-Time Finetuning: Latent Variable Optimization](#testing-time-finetuning-latent-variable-optimization)
    - [Testing-Time Finetuning: Hybrid Finetuning](#testing-time-finetuning-hybrid-finetuning)
    </details>
  - <details>
    <summary>Training and Finetuning Free</summary>
    
    - [Training and Finetuning Free: Input Text Refinement](#training-and-finetuning-free-input-text-refinement)
    - [Training and Finetuning Free: Inversion/Sampling Modification](#training-and-finetuning-free-inversionsampling-modification)
    - [Training and Finetuning Free: Attention Modification](#training-and-finetuning-free-attention-modification)
    - [Training and Finetuning Free: Mask Guidance](#training-and-finetuning-free-mask-guidance)
    - [Training and Finetuning Free: Multi-Noise Redirection](#training-and-finetuning-free-multi-noise-redirection)
    </details>
- [Benchmark EditEval_v1](#benchmark-editeval_v1)
- [Template of Computing LMM Score](EditEval_v1/Metric/LMM_Score_GPT4V_Prompt_Template.md)
- [Leaderboard](#leaderboard)
- [Star History](#star-history)

    
# Papers








# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=colaudiolab/Awesome-Self-Supervised-Audio-Learning&type=Date)](https://star-history.com/#colaudiolab/Awesome-Self-Supervised-Audio-Learning&Date)
