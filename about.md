---
layout: page
title: About
permalink: /about/
---

SMuPT is a series of pre-trained models for symbolic music generation. It was trained on a large-scale dataset of symbolic music, including millions of monophonic and polyphonic pieces from different genres and styles. The models are trained with the LLama2 architecture, and can be further used for downstream music generation tasks such as melody generation, accompaniment generation, and multi-track music generation.

### More Information

The details of model architecture of SMuPT-v0 are listed below:
| Name                | Parameters | Training Data (Music Pieces) | Seq Length | Hidden Size | Layers | Heads |
|---------------------|------------|-------------------------------|------------|-------------|--------|-------|
| SMuPT-v0-8192-110M  | 110M       | 7M x 5.8 epochs               | 8192       | 768         | 12     | 12    |
| SMuPT-v0-8192-345M  | 345M       | 7M x 4 epochs                 | 8192       | 1024        | 24     | 16    |
| SMuPT-v0-8192-770M  | 770M       | 7M x 3 epochs                 | 8192       | 1280        | 36     | 20    |
| SMuPT-v0-8192-1.3B  | 1.3B       | 7M x 2.2 epochs               | 8192       | 1536        | 48     | 24    |