
<h1 align="center">
  NeXT-IMDL: Build Benchmark for NeXT-Generation Image Manipulation Detection &amp; Localization
</h1>

<p align="center">
  <a href="https://arxiv.org/abs/" style="margin-right: 10px;">
    <img src="https://img.shields.io/badge/arXiv--b31b1b.svg?logo=arXiv">
  </a>
  <a href="https://huggingface.co/datasets/JoeLeelyf/NeXT-IMDL" style="margin-right: 10px;">
    <img src="https://img.shields.io/badge/🤗%20Hugging%20Face-ffd21e">
  </a>
</p>

> **Abstract:** The accessibility surge and abuse risks of user-friendly image editing models have created an urgent need for generalizable, up-to-date methods for Image Manipulation Detection and Localization (IMDL). Current IMDL research typically uses cross-dataset evaluation, where models trained on one benchmark are tested on others. However, this simplified evaluation approach conceals the fragility of existing methods when handling diverse AI-generated content, leading to misleading impressions of progress. This paper challenges this illusion by proposing NeXT-IMDL, a large-scale diagnostic benchmark designed not just to collect data, but to probe the generalization boundaries of current detectors systematically. Specifically, NeXT-IMDL categorizes AIGC-based manipulations along four fundamental axes: editing models, manipulation types, content semantics, and forgery granularity. Built upon this, NeXT-IMDL implements five rigorous cross-dimension evaluation protocols. Our extensive experiments on 11 representative models reveal a critical insight: while these models perform well in their original settings, they exhibit systemic failures and significant performance degradation when evaluated under our designed protocols that simulate real-world, various generalization scenarios. By providing this diagnostic toolkit and the new findings, we aim to advance the development towards building truly robust, next-generation IMDL models.