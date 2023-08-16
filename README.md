# MatSim-Dataset
The MatSim dataset includes large-scale collections of synthetic images for material self-similarity and a diverse natural image benchmark (Figure 1) to test the ability of the net to identify material states and subclasses using one or a few examples. This dataset is designed to address the general issue of one-shot material retrieval without restrictions on material types, settings, and environments. The main focus is on distinguishing between states of materials and identifying fine-grained categories such as rotten vs. ripe or coffee vs. cocoa. Additionally, we created a second adversarial benchmark to test the net's ability to recognize materials without association with objects or environments. This benchmark involves covering objects with random materials to create uncorrelated material-object associations.
# Paper
Detailed on the dataset could be found in the paper:
[One-shot recognition of any material anywhere using contrastive learning with physics-based rendering](https://arxiv.org/pdf/2212.00648v4.pdf)

# Download links:
Dataset and benchmark download links: [pcloud](https://e1.pcloud.link/publink/show?code=kZIiSQZCYU5M4HOvnQykql9jxF4h0KiC5MX),  [icedrive](https://icedrive.net/s/A13FWzZ8V2aP9T4ufGQ1N3fBZxDF),   [zenodo](https://zenodo.org/record/7390166#.Y_6cNIBBxH4)

# Dataset Generation scripts
Synthetic dataset generation script (blender): 

[1) [Materials on random objects generation script](https://github.com/sagieppel/MatSim-Generator-Generate-image-of-random-materials-on-ranodm-objects-with-Blender)


[2) [Materials inside transparent containers generation script](https://github.com/sagieppel/MatSim-Generator-Script-For-similarity-recognition-of-materials-in-transperent-vessels-blender)

# Benchmark Examples:
### Benchmark 1) Real-world scenes: materials states, gradual transitions, and fine-grained classes:  
![](/MatSimBenchmark1.jpg)

### Benchmark 2) Uncorrelated materials and objects (Random materials on random objects):
![](/Benchmark2.png)

# Synthethic dataset Examples:
### Materials on objects gradual transitions:
![](/DatasetObjects.jpg)

### Materials in transparent vessels gradual transitions:
![](/Dataset_Materials_In_Vessels.jpg)

# Supporting code:
[Example neural net trained on the dataset](https://github.com/sagieppel/Contrastive-learning-for-one-shot-materials-and-textures-similarity-recognition-from-images)
