<div align="center">
  <img src="./assets/images/logo.png" width="1750"/>
</div>

<div align="center"><h1>Mark My Words: Dangers of Watermarked Images in ImageNet</h1>
<h5> Kirill Bykov, Klaus-Robert Müller and Marina M.-C. Höhne</h5>
Accepted to the ICLR 2023 TrustML-(un)Limited workshop
<h5 href="https://arxiv.org/abs/2206.04530">Paper link</h5></div>

[comment]: <> (<h5 href="https://google.com">Paper link</h5></div>)

<div align="left">
<img src="./assets/images/About.svg" height="32"/>
</div>
<hr />

Pre-trained networks, esp. those trained on ImageNet, are widely used in Computer Vision. However, watermarks in ImageNet images can lead to learning artifacts in pre-trained networks. In this paper, we assess the extent of this behavior in popular pre-trained models and identify affected classes. Our analysis shows that multiple ImageNet classes, not just the ``carton'' class, rely on spurious correlations with watermarks. We propose a simple approach to mitigate this issue in fine-tuned networks by ignoring the most watermark-sensitive encodings.

<div align="left">
<img src="./assets/images/Getting%20started.svg" height="32"/>
</div>
<hr />

<div align="left">

This GitHub repository includes multiple notebooks related to a research paper.

<ol>
  <li><b> Dataset Generation & Collection of Activations </b></li>
    The first notebook, "Dataset Generation & Collection of Activations," includes code for generating probing datasets and collecting activations from popular ImageNet pretrained models.
  <li><b>Analysis </b></li>
    The second notebook, "Analysis," contains code for performing experiments to evaluate the differentiability of output logit representations and analyzing feature extractor representations.
  <li><b> Ignoring sensitive embeddings </b></li>
    The third notebook, "Ignoring Sensitive Embeddings," includes two sub-notebooks.
    <ol>
      <li><b> Training </b></li>
        The "Training" sub-notebook provides code for training models on the Cal-Tech 256 image classification problem, fine-tuned on DenseNet-161 features. The "Analysis" sub-notebook includes code for analyzing the fine-tuned networks.
      <li><b>Analysis </b></li>
       The "Analysis" sub-notebook includes code for analyzing the fine-tuned networks.
    </ol>

</ol>

</div>

<div align="left">
<img src="./assets/images/Citation.svg" height="32"/>
</div>
<hr />