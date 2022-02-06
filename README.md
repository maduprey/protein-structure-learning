# Topological protein classification

This repo provides notebooks for protein classification using topological features with data from the Protein Classification Benchmark [PCB00019](http://pongor.itk.ppke.hu/benchmark/#/Browse) test.

* `protein-classification-benchmark.ipynb` compares several boosted trees, SVM, and a TensorFlow MLP trained on persistence curves across the 55-task benchmark.
* `protein-classification-deep-learning.ipynb` constructs a multiclass classifier using a TensorFlow MLP trained on persistence curves. A SVM is also constructed using the same data, as a comparison.
* `protein-3D.ipynb` provides tools for visualizing protein structure using `py3Dmol` in a Colab notebook setting. 