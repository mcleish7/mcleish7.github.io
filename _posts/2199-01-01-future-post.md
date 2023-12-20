---
title: 'Is ChatGPT a Generalist Algorithmic Learner?'
date: 2023-12-07
permalink: /posts/CLRS4LM/
tags:
  - LM
  - ChatGPT
  - Algorthmic-Reasoning
---
<html>
<h3>Sean McLeish, Avi Schwarzschild, Tom Goldstein</h3>
<p>All benchmark code is available here: <a href="https://github.com/mcleish7/CLRS4LM">CLRS4LM GitHub</a>.</p>
<p>This is an extension of our arXiv paper, available here:  <a href="https://github.com/mcleish7/CLRS4LM">arXiv</a>. Here we also present results on the CLRS size 16 training data and provide more discussion.</p>
<p>We are all at NeurIPS 2023, come talk to us!</p>


<h2>Individual Accuracy</h2>
<p>We do not necessarily see a pattern between the testing and training accuracies. This could be because ChatGPT mostly relies on Python code in these problems, so the difference between test and train data is less noticable than in the GNN case. As any Python code which can correctly answer a train problem can also answer a test problem and vice versa.</p>

<p itemprop="Individual Train 0-1 Accuracy Scores for ChatGPT">
  <figure style="text-align: center;">
    <img src='/images/CLRS-FIGURES/Train_accuracy_2.png' width="100">
    <figcaption style="text-align: center; font-size: 16px;">Individual Train 0-1 Accuracy Scores for ChatGPT</figcaption>
  </figure>
</p>
<p class="archive__item-excerpt" itemprop="Individual Test 0-1 Accuracy Scores for ChatGPT">
  <figure>
    <img src='/images/CLRS-FIGURES/Test_accuracy_2.png' width="200" style="text-align: center;">
    <figcaption style="text-align: center; font-size: 16px;">Individual Test 0-1 Accuracy Scores for ChatGPT</figcaption>
  </figure>
</p>

<h2>Individual F1</h2>
<p>Again, we do not necessarily see a pattern between the testing and training F1 scores.</p>

<p class="archive__item-excerpt" itemprop="Individual Train F1 Scores for ChatGPT">  
  <figure>
    <img src='/images/CLRS-FIGURES/bar_chart_3_train.png' width="300" style="text-align: center;">
    <figcaption style="text-align: center; font-size: 16px;">Individual Train F1 Scores for ChatGPT</figcaption>
  </figure>
</p>

<p class="archive__item-excerpt" itemprop="Individual Test F1 Scores for ChatGPT">
  <figure>
    <img src='/images/CLRS-FIGURES/bar_chart_3_test.png' width="400" style="text-align: center;">
    <figcaption style="text-align: center; font-size: 16px;">Individual Test F1 Scores for ChatGPT</figcaption>
  </figure>
</p>

<h2>Comparison F1</h2>
<p>Here we compare the test F1 scores for ChatGPT and other GNN models on the CLRS benchmark problems.</p>
<p class="archive__item-excerpt" itemprop="Comparison of Test F1 Scores to ChatGPT"> 
  <figure>
    <img src='/images/CLRS-FIGURES/Test_compare_F1.png' width="500" style="text-align: center;">
    <figcaption style="text-align: center; font-size: 16px;">Comparison of Test F1 Scores to ChatGPT</figcaption>
  </figure>
</p>
<p>Thanks for reading, please look at the <a href="https://github.com/mcleish7/CLRS4LM">GitHub</a> and cite out <a href="https://github.com/mcleish7/CLRS4LM">arXiv Paper</a>.</p>


<code>
<h2>Geometry problems - Jarvis' march</h2>
<h3>System Prompt:</h3>
<p style="font-size:18px">You are a helpful assistant for solving and explaining classical coding problems.</p>
<h3>Context:</h3>
<p style="font-size:16px">Perform the Jarvis March Algorithm on these points, X coordinates [1.2194, -1.11406, 0.38929, -1.73849, -0.31843, 1.22709, 0.43665, 0.7779, -1.62778, -0.26118, -0.24323, -0.66371, 0.81454, -1.17166, -0.03785, 1.07014], Y coordinates [1.498, -1.25286, 0.34116, 0.53362, -0.23869, 0.35766, -1.86391, 0.53266, -0.29587, 1.28856, -1.34246, -1.10064, 1.74479, -0.59935, 0.48395, 1.55081], return the indices of the points in the hull, sorting these indices in ascending order when printing, indexing from 0. If you write python code, the first code block should only be you defining the two arrays. I cannot run code, you should show as much working as possible, at least the first step of working by hand, and run until the process is complete. The last line of your output should be the solution to the problem, if this is from running code, you should restate the output in our conversation.</p>
</code>

</html>
