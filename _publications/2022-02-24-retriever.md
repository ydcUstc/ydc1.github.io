---
title: "Retriever: Learning Content-Style Representation as a Token-Level Bipartite Graph"
collection: publications
permalink: /publication/2022-02-24-retriever
excerpt: '**Dacheng Yin**, Xuanchi Ren, Chong Luo, Yuwang Wang, Zhiwei Xiong, Wenjun Zeng.'
date: 2022-02-24
venue: 'International Conference on Learning Representations'
---
\[[Paper](https://arxiv.org/pdf/2202.12307)\] \[[demo](https://ydcustc.github.io/retriever-demo/)\] \[[code](https://github.com/xrenaa/Retriever)\]

![Architecture](/images/retriever.png)
This paper addresses the unsupervised learning of content-style decomposed representation. We first give a definition of style and then model the content-style representation as a token-level bipartite graph. An unsupervised framework, named
Retriever, is proposed to learn such representations. First, a cross-attention
module is employed to retrieve permutation invariant (P.I.) information, defined
as style, from the input data. Second, a vector quantization (VQ) module is used,
together with man-induced constraints, to produce interpretable content tokens.
Last, an innovative link attention module serves as the decoder to reconstruct data
from the decomposed content and style, with the help of the linking keys. Being
modal-agnostic, the proposed Retriever is evaluated in both speech and image
domains. The state-of-the-art zero-shot voice conversion performance confirms
the disentangling ability of our framework. Top performance is also achieved in
the part discovery task for images, verifying the interpretability of our representation. In addition, the vivid part-based style transfer quality demonstrates the
potential of Retriever to support various fascinating generative tasks. Code
will be released upon acceptance of the paper.

Cite
===

```latex
@article{yin2022retriever,
  title={Retriever: Learning Content-Style Representation as a Token-Level Bipartite Graph},
  author={Yin, Dacheng and Ren, Xuanchi and Luo, Chong and Wang, Yuwang and Xiong, Zhiwei and Zeng, Wenjun},
  journal={arXiv preprint arXiv:2202.12307},
  year={2022}
}
```
