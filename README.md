# MoLE: Mixture of LoRA Experts
[![Paper](https://img.shields.io/badge/cs.CV-Paper-b31b1b?logo=arxiv&logoColor=red)](https://openreview.net/pdf?id=uWvKBCYh4S)


Official implementation of "**MoLE: Mixture of LoRA Experts**"

 [Xun Wu](https://yushuiwx.github.io/), [Shaohan Huang](https://buaahsh.github.io/)<sup>$+$</sup>, [Furu Wei](https://thegenerality.com/)

International Conference on Learning Representations (**ICLR**), 2024

## Abstract
> LoRA has emerged as a pivotal technique for fine-tuning large pre-trained models, renowned for its efficacy across diverse tasks. Its modular design has spurred investigations into the composition of multiple trained LoRAs to enhance task performance. Nevertheless, the effective composition of these LoRAs remains a formidable challenge: (1) Linear arithmetic composition method may lead to the loss of the generative capabilities inherent in the original pre-trained model or the distinctive attributes of the trained LoRAs, resulting in suboptimal outcomes. (2) Reference tuning-based composition method exhibits limitations in terms of the necessary adaptability for effectively composing multiple LoRAs and incurs significant costs due to retraining a sizable model. In response to these challenges, we propose Mixture of LoRA Experts (MoLE). MoLE treats each layer of trained LoRAs as distinct experts and implements hierarchical weight control by integrating a learnable gating function within each layer to learn optimal composition weights tailored to a specific domain objective. MoLE not only surpasses linear arithmetic composition in terms of LoRA composition performance but also preserves the essential flexibility required for the effective composition of trained LoRAs with minimal computational overhead. Extensive experimental evaluations conducted in both Natural Language Processing (NLP) and Vision & Language (V&L) domains validate the efficacy of MoLE.

## :fire: Updates

- [02/2024] Paper accepted by ICLR 2024.
