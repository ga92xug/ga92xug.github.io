---
layout: page
title: 3D Visual Grounding with Transformers
description: Project for Advanced Deep Learning for Computer Vision
img: assets/img/3D-Visual_grounding.png
importance: 3
category: University
---
<!-- Thesis image and description -->
<div class="row justify-content-center">
    <div class="col-auto">
        {% include figure.html path="assets/img/qual_analysis2.jpg" alt="Teaser 3D Visual Grounding" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<!-- Download buttons -->
<div class="row mt-4 justify-content-center">
    <div class=".col-sm">
        <a href="https://github.com/flo-stilz/3D-Visual-Grounding-with-Transformers/blob/main/paper%20%26%20figures/final_submission_3D_visual_grounding_with_transformers.pdf" class="btn btn-primary">
            <i class="fa fa-download"></i> Paper
        </a>
    </div>
    <div class=".col-sm">
        <a href="/assets/pdf/poster_3D-visual-grouding-with-transformers.pdf" class="btn btn-primary" download>
            <i class="fa fa-download"></i> Poster
        </a>
    </div>
    <div class=".col-sm">
        <a href="https://github.com/flo-stilz/3D-Visual-Grounding-with-Transformers" class="btn btn-primary">
            <i class="fa fa-code"></i> Code
        </a>
    </div>
</div>


# Abstract 
3D visual grounding lies at the intercept of 3D object detection and natural language understanding.
This work focuses on developing a transformer architecture for bounding box prediction around a target object that is described by a text description. Transformers are the superior choice for 3D object detection compared to the previously often employed VoteNet as they are capable of capturing the long-range context better and can operate on variable-sized inputs. Therefore, they are well suited to operate on 3D point clouds. We show that employing 3DETR-m as an object detection framework improves the 3D visual grounding performance. Additionally, we introduce a transformer into the matching of the textual and visual features since it is uniquely suited to capture the relevant interdependencies. Our method achieves around 2.5\% improvement over the ScanRefer architecture by replacing the object detection with 3DETR-m and adding a vanilla transformer encoder to the matching module.