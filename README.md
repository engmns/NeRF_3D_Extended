# NeRF_3D_Extended

This is an extended version of NeRF from NeRF: Neural Radiance Fields implemented in PyTorch, but using the Tiny version (the architecture is able to run on small GPUs) of it which can works well on Google Colab.
The original paper NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis by Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi and Ren Ng appeared at ECCV 2020.

Compared to the previous versions implementation of Tiny NeRF, this version includes using the Gaussian Density Function, 5D input + view directions and Hierarchical Sampling.

Adding 5D input, including view directions, and implementing hierarchical sampling to Tiny NeRF can significantly enhance its performance and the quality of rendered images.The Gaussian density function plays a crucial role in Neural Radiance Fields (NeRF) by modeling the distribution of densities along a ray as it passes through a scene. In the context of volume rendering, which is central to NeRF's operation, the scene is represented as a continuous field of density and color values. The density at any point in the scene indicates the likelihood of a ray being absorbed or scattered at that point, which directly affects how light interacts with the scene.
