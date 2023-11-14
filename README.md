# Generative models based on ODE and SDE

This tutorial aims to introduce the reader to the mathematical methods which are widely used in contemporary generative modeling. Covered methods are applicable for generation, paired style transfer (including inverse problems) and unpaired style transfer, formalized as an optimal transport problem.

## Navigation

Current version of the tutorial can be found at `main.pdf`. The corresponding source files `main.tex` and `references.bib` are located in the root folder.

It uses a modified NeurIPS-2023 style file `neurips_2023.sty`: https://neurips.cc/Conferences/2023/PaperInformation/StyleFiles.

`old` folder contains an old version of the tutorial, written in Russian. It contains a little bit different set and sequence of topics.

## Contents:
1. Score-based generative models. Noise Conditional Score Networks (NCSN): https://arxiv.org/abs/1907.05600.
2. ODEs: reminder. SDEs: informal defitnition with Euler-Maruyama scheme. Evolution of the distribution: continuity equation, Fokker-Planck equation.
3. Construction of the backward SDE. Diffusion models based on SDEs: https://arxiv.org/abs/2011.13456.
4. Calculating likelihood of ODE diffusion models. Conditional generation: classifier (https://arxiv.org/abs/2011.13456, https://arxiv.org/abs/2105.05233) and classifier-free (https://arxiv.org/abs/2207.12598) guidance.
