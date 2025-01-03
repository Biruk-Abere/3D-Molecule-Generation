# Text-guided Diffusion Model for 3D Molecule Generation

Reproducing Results from the Paper: "The Curious Case of Neural Text Degeneration". This is done for my LLMs class, I'll update the changes soon!

3M-Diffusion is a novel multi-modal molecular graph generation method, to generate diverse, ideally novel molecular structures with desired properties. 3M-Diffusion encodes molecular graphs into a graph latent space which it then aligns with the text space learned by encoder-based LLMs from textual descriptions. It then reconstructs the molecular structure and atomic attributes based on the given text descriptions using the molecule decoder. It then learns a probabilistic mapping from the text space to the latent molecular graph space using a diffusion model. 

![ALT TEXT](3M-Diffusion.png)
