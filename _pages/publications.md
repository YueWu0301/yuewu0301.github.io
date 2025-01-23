---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



<!-- ## SimLOB: Learning Representations of Limited Order Book for Financial Market Simulation
**Abstract**: 
Financial market simulation (FMS) serves as a promising tool for understanding market anomalies and the underlying trading behaviors. To ensure high-fidelity simulations, it is crucial to calibrate the FMS model for generating data closely resembling the observed market data. Previous efforts primarily focused on calibrating the mid-price data, leading to essential information loss of the market activities and thus biasing the calibrated model. The Limit Order Book (LOB) data is the fundamental data fully capturing the market micro-structure and is adopted by worldwide exchanges. However, LOB is not applicable to existing calibration objective functions due to its tabular structure not suitable for the vectorized input requirement. This paper proposes to explicitly learn the vectorized representations of LOB with a Transformer-based autoencoder. Then the latent vector, which captures the major information of LOB, can be applied for calibration. Extensive experiments show that the learned latent representation not only preserves the non-linear auto-correlation in the temporal axis, but the precedence between successive price levels of LOB. Besides, it is verified that the performance of the representation learning stage is consistent with the downstream calibration tasks. Thus, this work also progresses the FMS on LOB data, for the first time.
You can find our preprint [here](https://arxiv.org/abs/2406.19396)
 -->


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
