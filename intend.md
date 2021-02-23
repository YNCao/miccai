## Bone Aging with Generative Adversarial Networks

### Abstract

Bone age assessment (BAA) based on hand x-ray is of great importance for diagnosing endocrine and metabolic disorders in child development. However, it is still hard to obtain the data of the same individual at different ages due to the radiation injury. In this work, we propose a new task called bone aging to generate hand x-ray at different ages for the same individual. Bone aging is of great importance for studying bone growth process and designing bone age assessment standards. Specifically, we design an encoder-decoder based generative adversarial network to achieve bone age editing with high resolution. In order to edit the bone age without changing the identity, we design an independent age modulation layer to manipulate features in the the latent space. Our model allows for continuous age editing on high resolution, which meets the demands of medical research on bone growth.

### Introduction

Greulich-Pyle

Tanner-Whitehouse 2 methods





### list

1. 提出新任务应该怎样表达，动机
2. related work: face aging, bone development, data
3. 创新：
   1. 弥补同一个体在不同时期发育数据欠缺
   2. 高分辨率（已经实现）
4. evaluation？？没有靶子，怎样评估效果？
   1. 结合发育学寻找不同年龄段特征，增强说服力（没有做出来。。。）
   2. 
5. ablation experiment
   1. classifier
   2. discriminator
   3. reconstruction
   4. age modulation
   5. latent space