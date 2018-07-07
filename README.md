# Network Robustness to BDM-Directed Sequential and Simultaneous Attack
Estimation of the robustness of networks to attacks directed using Kolmogorov complexity as estimated by the Block Decomposition Method. 

This Wolfram Mathematica code computes the R-index (robustness) according to sequential or simultaneous attacks (deletions) to vertices in the network directed through the [Block Decomposition Method](https://arxiv.org/abs/1609.00110), a metric that estimates the algorithmic information content (Kolmogorov complexity) of a graph. 

One can direct attacks to the elements (nodes/edges) in a network according to a "centrality" metric that assigns a relative importance to each. In a "sequential attack" that erases i elements, after an element is removed the centrality metric is re-evaluated to take into account the change in the network's structure, whereas in a "simultaneous" attack the centrality metric of every element is evaluated once, prior to any deletion [Iyer13].  The Block Decomposition Method (BDM) can be used to assign centrality scores to vertices or edges according to their information contribution [Zenil14, Zenil16, Zenil18a, Zenil18b]. 

![alt text](https://raw.githubusercontent.com/andandandand/Network-Attack-Robustness-by-Kolmogorov-complexity-centrality/master/img/centrality-highlight.PNG)


### References

[Rueda-Toicen18] Rueda-Toicen, A., Zenil H., Zea, A. (2018) Network Robustness to Attacks Directed through Estimations of Kolmogorov Complexity (in preparation)

[Zenil16] Zenil, H., Hernández-Orozco, S., Kiani, N. A., Soler-Toscano, F., & Rueda-Toicen, A. (2016).
A decomposition method for global evaluation of Shannon entropy and local estimations of algorithmic complexity.
arXiv preprint arXiv:1609.00110.

[Zenil14] Zenil H., Soler - Toscano F., Dingle K.and Louis A.(2014) 
Correlation of Automorphism Group Size and Topological Properties with Program-size 
Complexity Evaluations of Graphs and Complex Networks, Physica A : Statistical Mechanics and its Applications, 
vol.404, pp.341-358. 

[Iyer13] Iyer, S., Killingback, T., Sundaram, B., & Wang, Z. (2013). Attack robustness and centrality of complex networks.
PloS one, 8(4), e59613.

[Soler13] Soler-Toscano, F. and Zenil, H. Kolmogorov Complexity of 3 x 3 and 4 x 4 Squares, 
Wolfram Demonstrations Project, 2013 http://demonstrations.wolfram.com/KolmogorovComplexityOf33And44Squares/

[Zenil17] Zenil, H., Kiani, N. A., Marabita, F., Deng, Y., Elias, S., Schmidt, A. & Tegner, J. (2017). 
An Algorithmic Information Calculus for Causal Discovery and Reprogramming Systems. arXiv preprint arXiv:1709.05429.

[Zenil18a] Zenil, H., Kiani, N. A., Zea, A. & Tegnér, J. (2018). Ab initio Algorithmic Causal Deconvolution of Intertwined Programs 
and Networks by Generative Mechanism. arXiv preprint arXiv:1802.09904.

[Zenil18b] Zenil, H., Kiani, N. A., Rueda-Toicen, A., Zea, A. & Tegnér, J. (2018) Universal Data Reduction and Network 
Sparsification Method By Minimal Algorithmic Information Loss arXiv preprint arXiv:1802.05843


***If you use this code for a publication, please cite the above references and the following***:

Rueda-Toicen, Antonio, Network Robustness to BDM-directed Sequential and Simultaneous Attack, (2018), GitHub repository, 
https://github.com/andandandand/Network-Attack-Robustness-by-Kolmogorov-complexity-centrality

#### BibTex
```
@misc{Rueda-Toicen2018,
  author = {Rueda-Toicen, Antonio},
  title = {Network Robustness to BDM-directed Sequential and Simultaneous Attack},
  year = {2018},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {https://github.com/andandandand/Network-Attack-Robustness-by-Kolmogorov-complexity-centrality},
  DOI = {}
  }
```

### Author: Antonio Rueda-Toicen
- antonio "dot" rueda "." toicen "at" gmail 'dot' com
- antonio "dot" rueda "." toicen "at" algorithmicnaturelab 'dot' com

### License: MIT

