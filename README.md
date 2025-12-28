# Model-Inversion-Results-Under-Different-Optimization-Strategies

This repository provides an partial implementation of the paper:
Matt Fredrikson, Somesh Jha, and Thomas Ristenpart (2015)
Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures
Proceedings of the 22nd ACM SIGSAC Conference on Computer and Communications Security (CCS ’15), pp. 1322–1333.
DOI: 10.1145/2810103.2813677

Original experimental results:
https://github.com/mfredrik/facematch
##
I explore model inversion attacks using different optimization techniques. By varying the optimizer during the inversion process, I retrieve and compare reconstructed results to understand how optimization choices affect attack effectiveness.
<p align="center">
  <img src="images/visual_set_1_1.png" width="1000">
</p>

**Figure 1:** Reconstructed class prototypes using SGD optimizer.

<p align="center">
  <img src="images/visual_set_2_2.png" width="1000">
</p>

**Figure 2:** Reconstructed class prototypes using Nesterov optimizer.

<p align="center">
  <img src="images/visual_set_3_1.png" width="1000">
</p>

**Figure 3:** Reconstructed class prototypes using AdaGrad optimizer.

<p align="center">
  <img src="images/visual_set_4.png" width="1000">
</p>

**Figure 4:** Reconstructed class prototypes using RMSprop optimizer.

<p align="center">
  <img src="images/visual_set_5.png" width="1000">
</p>

**Figure 5:** Reconstructed class prototypes using Adam optimizer.

<p align="center">
  <img src="images/visual_set_6.png" width="1000">
</p>

**Figure 6:** Reconstructed class prototypes using AdamW optimizer.

<p align="center">
  <img src="images/visual_set_7.png" width="1000">
</p>

**Figure 7:** Reconstructed class prototypes using AdaBelief optimizer.
<p align="center">
  <img src="images/visual_set_8.png" width="1000">
</p>

**Figure 8:** Reconstructed class prototypes using L-BFGS optimizer.

