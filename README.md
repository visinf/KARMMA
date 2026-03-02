<div align="center">
<h1>Multimodal Knowledge Distillation for Egocentric Action Recognition Robust to Missing Modalities</h1>

[**Maria Santos-Villafranca**](https://maria-sanvil.github.io/)<sup>* 1</sup>
[**Dustin Carrión-Ojeda**](https://dustincarrion.github.io/)<sup>* 2,3</sup>
[**Alejandro Perez-Yus**](https://i3a.unizar.es/es/investigadores/alejandro-perez-yus)<sup>1</sup>
[**Jesus Bermudez-Cameo**](https://jesusbermudezcameo.github.io/)<sup>1</sup>
[**Jose J. Guerrero**](https://webdiis.unizar.es/~jguerrer/)<sup>1</sup>
[**Simone Schaub-Meyer**](https://schaubsi.github.io/)<sup>2,3</sup>

<sup>1</sup>University of Zaragoza
<sup>2</sup>TU Darmstadt
<sup>3</sup>hessian.AI
*equal contribution

<a href="https://arxiv.org/abs/2504.08578"><img src='https://img.shields.io/badge/arXiv-grey' alt='Paper arXiv'></a>
<a href="https://visinf.github.io/KARMMA/"><img src='https://img.shields.io/badge/Project Page-grey' alt='Project Page URL'></a>
</div>

---

🚧 The code will be released soon. Stay tuned!


## 🚀 About
This repository contains the official implementation of the paper *Multimodal Knowledge Distillation for Egocentric Action Recognition Robust to Missing Modalities*.



<p align="center">
  <img src="assets/teaser.svg" alt="Teaser" width="500"/>
</p>




Existing methods for egocentric action recognition often rely solely on RGB videos, although additional modalities, e.g., audio, can improve accuracy in challenging scenarios. However, most multimodal approaches assume all modalities are available at inference, leading to significant accuracy drops, or even failure, when inputs are missing. To address this, we introduce KARMMA, a multimodal <b>K</b>nowledge distillation framework for egocentric <b>A</b>ction <b>R</b>ecognition robust to <b>M</b>issing <b>M</b>od<b>A</b>lities that requires no modality alignment across all samples during training or inference. KARMMA distills knowledge from a multimodal teacher into a multimodal student that benefits from all available modalities while remaining robust to missing ones, making it suitable for diverse scenarios without retraining. Our student uses approximately 50% fewer computational resources than our teacher, resulting in a lightweight and fast model. Experiments on Epic-Kitchens and Something-Something show that our student achieves competitive accuracy while significantly reducing accuracy drops under missing modality conditions.

