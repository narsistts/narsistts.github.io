# Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation

This is the demonstration page of the paper "Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation" with some selected samples generated with the proposed methods.

## Info

### Abstract

Audio token modeling has become a powerful framework for speech synthesis, with two-stage approaches employing semantic tokens remaining prevalent. In this paper, we aim to simplify this process by introducing a semantic knowledge distillation method that enables high- quality speech generation in a single stage. Our proposed model improves speech quality, intelligibility, and speaker similarity compared to a single- stage baseline. Although two-stage systems still lead in intelligibility, our model significantly narrows the gap while delivering comparable speech quality. These findings showcase the potential of single-stage models to achieve efficient, high-quality TTS with a more compact and streamlined architecture.

## Demos

The following examples are selected from the listening test described in the paper, which are generated from LibriSpeech test-clean subset. The models to compare include one single-stage model (NARSiS) without SKD (semantic knowledge distillation), two single-stage models with SDK, and a two-stage model.
