---
layout: page
title: Learning World Models by Self-Supervised Exploration
description: Project for Advanced Deep Learning for Robotics
img: assets/img/learn2grab_without_drop.gif
importance: 2
category: University
---
<!-- Thesis image and description -->
<div class="row justify-content-center">
    <div class="col-auto">
        {% include figure.html path="assets/img/learn2grab_without_drop.gif" alt="Scaling Laws for ECNNs" class="img-fluid rounded z-depth-1" width="300" height="300"%}
    </div>
</div>
<!-- Download buttons -->
<div class="row mt-4 justify-content-center">
    <div class=".col-sm">
        <a href="https://github.com/ga92xug/tum-adlr-ws22-02/blob/main/report/final_report_02_pdf.pdf" class="btn btn-primary">
            <i class="fa fa-download"></i> Paper
        </a>
    </div>
    <div class=".col-sm">
        <a href="https://github.com/ga92xug/tum-adlr-ws22-02" class="btn btn-primary">
            <i class="fa fa-code"></i> Code
        </a>
    </div>
</div>

# Abstract

This project introduces an adapted version of Plan2Explore, where an agent builds a world model trained in a self-supervised manner. We introduce this framework to a new task Stacker from the DeepMind Control Suite. In addition to visual observations, we introduce proprioceptive information to Plan2Explore to enhance the agent's performance. In particular, we added contact sensors information from the fingers to the input of the agent such that it can fulfill subtasks like grabbing and stacking. These subtasks are exploration rewards that should steer the agent towards a more targeted exploration of the environment and improve the performance for the desired stacker task. In addition, we introduce a simplified version of the stacker task called Push2Target, where only the x-axis is considered.




