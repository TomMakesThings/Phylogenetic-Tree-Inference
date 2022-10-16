<div align="center">
  <h1><b>Phylogenetic Tree Inference</b></h1>
  <img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/61354833?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d">
  <p><b>🟠🟠🟠 Code by <a href="https://github.com/TomMakesThings">TomMakesThings</a> 🟠🟠🟠</b></p>
  <p><b><sub>April 2022</sub></b></p>
</div>

---

## About
<a href= "https://github.com/TomMakesThings/Phylogenetic-Tree/blob/main/Phylogenetics.ipynb">This notebook</a> contains code to find the optimal mutation rate and nucleotide assignments of a hypothetical evolutionary tree through applying the Jukes-Cantor model and Felsenstein’s algorithm.

## The Evolutionary Tree
Evolutionary trees are a type of directed acyclic graph encapsulating an evolutionary process over time. For example, the binary tree below is a model of DNA sequence evolution whereby each internal node represents an ancestor with two descendants, the branch length between them represents time and leaf node represents the terminal taxa, i.e. the most recent descendant for which a nucleotide base is known.

<div align="center">
  <img src="https://github.com/TomMakesThings/Phylogenetic-Tree-Inference/blob/assets/Images/Phylogenetic_Tree_Annotated.png" width=700>
</div>

## Jukes-Cantor and Felsenstein’s Pruning Algorithm
The Jukes-Cantor model is Markov model of DNA sequence evolution used when calculating the likelihood of a phylogenetic tree. It assumes that the mutation rate μ is equal and that the substitution of a base with another occurs with equal probability. Felsenstein’s pruning algorithm is a dynamic programming algorithm that computes the likelihood of an evolutionary tree from sequence data. Combining the Jukes-Cantor model with Felsenstein’s pruning algorithm provides a quantive method for assessing the optimal mutation rate and/or likelihood of a nucleotide assignment for terminal taxa.
