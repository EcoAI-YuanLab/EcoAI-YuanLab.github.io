---
layout: page
title: Advanced AI for Earth Science Studies
description: We develop interpretable AI, knowlegde/physical guided AI, and causal inference approaches 
img: assets/img/AI.png
importance: 1
category: Selected Projects
related_publications: false
---

Earth system models driven by domain-knowledge are physically interpretable, but generally exhibit lower accuracy than machine learning models due to limited observational constraints and substantial uncertainties in model structures and parameterizations. Data-driven machine learning models generally have higher accuracy but are black-boxes with high risk of overfitting and low confidence for future climate projections. Therefore, I focus on developing and applying advanced causality inference approaches to understand and reduce uncertainties in Earth system models, and using inferred causal relationships and domain knowledge to inform and improve machine/deep learning models. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AI_AFM.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Model structure of causal-ML and the causal inference findings in methane study. 
    Details can be seen in our published in AFM.
</div>

## Related publications:
{% bibliography --file AI.bib %}