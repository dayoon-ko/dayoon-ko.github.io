---
title: "StreamEmbed: Real-Time Indexing from Pixels for Screenshot Retrieval"
collection: publications
category: preprints
permalink: /publication/2026-arxiv-streamembed
excerpt: 'Real-time, on-device indexing of screen history from pixels, by re-encoding only the parts of each screenshot that changed.'
date: 2026-11-13
venue: 'arXiv 2026'
paperurl: 'https://arxiv.org/abs/2611.18516'
link: 'https://arxiv.org/abs/2611.18516'
citation: 'Dayoon Ko, Yichuan Wang, Soyeong Jeong, Joseph E. Gonzalez, Gunhee Kim, Sewon Min. (2026). &quot;StreamEmbed: Real-Time Indexing from Pixels for Screenshot Retrieval.&quot; <i>arXiv preprint arXiv:2611.18516</i>.'
authors: '<strong>Dayoon Ko</strong>, Yichuan Wang, Soyeong Jeong, Joseph E. Gonzalez, Gunhee Kim, Sewon Min'
---

Screen history can serve as searchable visual memory for people and agents, but it must be indexed as each screenshot arrives. OCR-based indexing is fast but loses visual information, while encoding the full screenshot takes over two seconds on a laptop GPU. StreamEmbed exploits the fact that screens change incrementally: guided only by pixel differences, it skips blocks that repeat a neighbor (spatial token pruning) and reuses cached keys and values for blocks unchanged across screenshots (temporal KV reuse), with a small adapter that keeps embeddings faithful to the full screenshot. On ScreenMemEval, a benchmark of 10,426 questions over 184 hours of screen history from two humans and a computer-use agent, StreamEmbed encodes up to 3.7× faster than full-screenshot encoding without sacrificing accuracy and improves over OCR-based indexing by up to 6.3 Recall@10 at matched latency. It runs fully on-device: `pip install streamembed`.

[Paper](https://arxiv.org/abs/2611.18516) | [Code](https://github.com/StarTrail-org/StreamEmbed) | [PyPI](https://pypi.org/project/streamembed/)
