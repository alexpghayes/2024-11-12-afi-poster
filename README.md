---
output:
  pdf_document: default
  html_document: default
---
# Estimating network-mediated causal effects via spectral embeddings
Alex Hayes, Mark M. Fredrickson, Keith Levin  
Presented at ACIC 2023

Causal inference for network data is an area of active interest in the social sciences. Unfortunately, the complicated dependence structure of network data presents an obstacle to many causal inference procedures. We consider the task of mediation analysis for network data, and present a model in which mediation occurs in a latent embedding space. Under this model, node-level interventions have causal eﬀects on nodal outcomes, and these eﬀects can be partitioned into a direct eﬀect independent of the network, and an indirect eﬀect induced by homophily. To estimate network-mediated eﬀects, we embed nodes into a low-dimensional space and ﬁt two regression models: (1) an outcome model describing how nodal outcomes vary with treatment, controls, and position in latent space; and (2) a mediator model describing how latent positions vary with treatment and controls. We prove that the estimated coeﬃcients are asymptotically normal about the true coeﬃcients under a sub-gamma generalization of the random dot product graph, a widely-used latent space model. We show that these coeﬃcients can be used in product-of-coeﬃcients estimators for causal inference. Our method is easy to implement, scales to networks with millions of edges, and can be extended to accommodate a variety of structured data.

![](poster.png)
