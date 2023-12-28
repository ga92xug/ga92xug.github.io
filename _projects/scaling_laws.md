---
layout: page
title: Scaling Laws for Equivariant Convolutional Neural Networks
description: Master's Thesis
img: assets/img/scaling_laws_ecnns.gif
importance: 1
category: University
---
# Coming soon
We are currently working on a publication links and additional information will be added after Release. 

<!-- Thesis image and description -->
<div class="row justify-content-center">
    <div class="col-auto">
        {% include figure.html path="assets/img/scaling_laws_ecnns.gif" alt="Scaling Laws for ECNNs" class="img-fluid rounded z-depth-1" width="300" height="300"%}
    </div>
</div>
<!-- Download buttons -->
<div class="row mt-4 justify-content-center">
    <div class=".col-sm">
        <a href="path_to_thesis" class="btn btn-primary">
            <i class="fa fa-download"></i> Thesis
        </a>
    </div>
    <div class=".col-sm">
        <a href="path_to_poster" class="btn btn-primary">
            <i class="fa fa-download"></i> Poster
        </a>
    </div>
    <div class=".col-sm">
        <a href="path_to_code" class="btn btn-primary">
            <i class="fa fa-code"></i> Code
        </a>
    </div>
</div>

# Abstract

Convolutional Neural Networks (CNNs) have revolutionized the field of computer vision, largely due to their inherent ability to exploit translational symmetries in images. Building on this success, there has been a growing effort to leverage rotations and reflections. Early studies on rotation and reflection Equivariant Convolutional Neural Networks (ECNNs) have demonstrated improved sample efficiency and better generalization than traditional CNNs. However, despite their potential advantages, ECNNs have yet to be widely adopted in practical applications. This limited adoption is partly due to the fact that current ECNNs frequently fail to surpass CNNs in performance, compounded by their unexplored design space and computational overhead. Our study aims to bridge this gap by reexamining and applying the foundational design principles of CNNs within the context of ECNNs.

We introduce a novel baseline architecture, Eq-NASNet, developed through a multiobjective neural architecture search. This search optimizes computational efficiency and performance, tailoring the architecture for practical applications. A key contribution of our research is the empirical demonstration of scaling laws for ECNNs. We systematically investigate how width, depth, and resolution scaling impact the performance and computational complexity of Eq-NASNet.

Our rigorous empirical evaluations highlight the superiority of Eq-NASNet over established models like EfficientNet and Vision Transformer (ViT) in challenging medical image classification scenarios. Notably, Eq-NASNet is more parameter efficient and matches the computational efficiency of current architectures like EfficientNet, while displaying superior performance. Furthermore, we demonstrate Eq-NASNet's robustness and effectiveness in low-data regimes and against adversarial attacks, where it distinctly outperforms both EfficientNet and ViT. The outcomes of our study position Eq-NASNet as a superior alternative for challenging medical tasks, where its ability to exploit increased image symmetry offers significant advantages.








