# Topological protein classification

This repo provides notebooks for protein classification using topological features with data from the Protein Classification Benchmark [PCB00019](http://pongor.itk.ppke.hu/benchmark/#/Browse) test.

* `protein-classification-benchmark.ipynb` compares several boosted trees, SVM, and a TensorFlow MLP trained on persistence curves across the 55-task benchmark.
* `protein-classification-deep-learning.ipynb` constructs a multiclass classifier using a TensorFlow MLP trained on persistence curves. A SVM is also constructed using the same data, as a comparison.
* `protein-3D.ipynb` provides tools for visualizing protein structure using `py3Dmol` in a Colab notebook setting. 


## Notes
Originally inspired by Barnes et al.'s [Frontiers](https://www.frontiersin.org/articles/10.3389/frai.2021.681174/full) paper, *A Comparative Study of Machine Learning Methods for Persistence Diagrams*.

Look into incorporating ***PersLay***. *A Neural Network Layer for Persistence Diagrams and New Graph Topological Signatures.* Uses deep learning. Cited in the Frontiers paper. Need to review this paper in depth. Even uses protein data for classification (gets ~75% accuracy, it seems). [Main paper](http://proceedings.mlr.press/v108/carriere20a/carriere20a.pdf). [Supp](http://proceedings.mlr.press/v108/carriere20a/carriere20a-supp.pdf).