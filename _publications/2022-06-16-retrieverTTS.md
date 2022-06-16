---
title: "RetrieverTTS: Modeling Decomposed Factors for Text-Based Speech Insertion"
collection: publications
permalink: /publication/2022-06-16-retrieverTTS
excerpt: '**Dacheng Yin**, Chuanxin Tang, Yanqing Liu, Xiaoqiang Wang, Zhiyuan Zhao, Yucheng Zhao, Zhiwei Xiong, Sheng Zhao, Chong Luo.'
date: 2022-06-16
venue: 'InterSpeech'
---
\[[Paper]()\] \[[demo](https://ydcustc.github.io/retrieverTTS-demo/)\] \[[code]()\]

![Architecture](/files/retrieverTTS.png)

This paper proposes a new paradigm for the text-based speech
insertion task that enables long insertion and full sentence generation. It is achieved by explicitly decomposing local and
global factors and controlling them separately. Technically, we
guarantee high speaker similarity by extracting multiple global
factor tokens and introducing a link-attention mechanism that
fully models and utilizes global factor information, including
timbre and style. By introducing a prosody smoothing task,
we model the local factors like prosody to be context-aware
and achieve satisfactory prosody continuity. We guarantee high
voice quality with an adversarial training stage. In the subjective test, our method achieves state-of-the-art in both naturalness and similarity. Audio samples can be found in the supplementary materials.

Cite
===

```latex
@article{yin2022retrievertts,
  title={RetrieverTTS: Modeling Decomposed Factors for Text-Based Speech Insertion},
  author={Dacheng, Yin and Chuanxin, Tang and Yanqing, Liu and Xiaoqiang, Wang and Zhiyuan, Zhao and Yucheng, Zhao and Zhiwei, Xiong and Sheng, Zhao and Chong, Luo}
  booktitle={Interspeech},
  year={2022}
}
```
