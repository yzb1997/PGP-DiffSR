<div align="center">
    <h1>PGP-DiffSR: Phase-Guided Progressive Pruning for Efficient Diffusion-based Image Super-Resolution</h1>
    <!-- <div>
        <a href='https://github.com/AnxQ/' target='_blank'>Xiaoqi An</a><sup>1</sup>&emsp;
        <a href='https://sharling-lz.github.io/' target='_blank'>Lin Zhao</a><sup>1</sup>&emsp;
        <a href='https://gcatnjust.github.io/ChenGong/index.html' target='_blank'>Chen Gong</a><sup>1</sup>&emsp;
        <a href='https://sites.google.com/view/junlineu/' target='_blank'>Jun Li</a><sup>1</sup>&emsp;
        <a href='https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN' target='_blank'>Jian Yang</a><sup>1</sup>
    </div> -->
    <!-- <div>
        <sup>School of Computer Science and Engineering, Nanjing University of Science and Technology
    </div> -->
</div>

<div align="center">
  
[![Paper](https://img.shields.io/badge/arXiv-PDF-b31b1b)](http://arxiv.org/abs/2512.02681)

</div>

Although diffusion-based models have achieved impressive results in image super-resolution, they often rely on large-scale backbones such as Stable Diffusion XL (SDXL) and Diffusion Transformers (DiT), which lead to excessive computational and memory costs during training and inference. To address this issue, we develop a lightweight diffusion method, PGP-DiffSR, by removing redundant information from diffusion models under the guidance of the phase information of inputs for efficient image super-resolution. We first identify the intra-block redundancy within the diffusion backbone and propose a progressive pruning approach that removes redundant blocks while preserving restoration capability. We note that the phase information of the restored images produced by the pruned diffusion model is not well estimated. To solve this problem, we propose a phase-exchange adapter module that explores the phase information of the inputs to guide the pruned diffusion model for better restoration performance. We formulate the progressive pruning approach and the phase-exchange adapter module into a unified model. Extensive experiments demonstrate that our method achieves competitive restoration quality while significantly reducing computational load and memory consumption.
