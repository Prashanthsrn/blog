---
title: "BrepGen: A B-rep Generative Diffusion Model"
collection: talks
permalink: /talks/BrepGen
---

This paper uses a diffusion-based generative model to present BrepGen, a method for directly generating 3D CAD models in the Boundary Representation (B-rep) format. The key to BrepGen is using a hierarchical tree structure to represent the Brep geometry and topology. The root of the tree is the entire solid structure and the child nodes are the components such as its edges, vertices, and faces. Thus the geometry is maintained in the nodes of the tree and the topology is encoded implicitly through node duplication. BrepGen opens up the possibility of generating more complex and realistic shapes, as it can generate free-form and doubly curved surfaces. This opens up new possibilities for automating and improving the CAD design workflow. You can find the original paper [here](https://arxiv.org/pdf/2401.15563)
