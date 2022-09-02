---
title: Trustworthy And Certified Robustness For Deep learning
publication_types:
  - "0"
authors:
  - XIA SONG
abstract: >
  	Though Deep Learning (DL) has shown its superiority in many complex computer
  vision tasks, in recent years, researchers found out that DL-based systems
  were extremely vulnerable to adversarial attacks. By adding small and human
  imperceptible corruptions to the original inputs, adversarial attacks will
  generate adversarial examples, which, though being very similar to original
  inputs, could mislead DL with a highly successful rate.


  Randomized smoothing (RS) is a recently proposed method to provide the certified robustness for DL, which could guarantee any adversarial attack ineffective within a certain range. By using Gaussian estimation, Randomized Smoothing (RS) gives the worst-case decision boundary of DL towards all possible adversarial attacks. Under the worst-case situation, RS gives a certified robustness radius, within which, DL system is guaranteed to return a constant prediction, meaning that no adversarial attack can be effective.


  Currently, there are two problems in RS. First is that the optimization of directly maximizing certified robustness radius is non-differentiable, due to hard 0-1 mapping and Monte Carlo sampling. The second is that the useful information from original data is corrupted, due to high variance level Gaussian noise. To solve above problems, this dissertation first analyzes current robustness estimation optimization methods and proposes a new generalized consistency optimization, which consists of a looser accuracy item and a tighter robustness item. Meanwhile, this dissertation utilizes linear decomposition to decompose the data according to the value of co-variance and select the useful information. Experiment results show that our proposed generalized consistency optimization with linear decomposition outperforms previous methods and achieves new state-of-the-art results.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-09-02T16:00:12.921Z
---
