# Diffusion Model Project

This repository contains the complete code for a fully custom diffusion model, built from scratch. The model transforms random noise into detailed images based on textual prompts, integrating CLIP embeddings to bridge text and image representations effectively.

## Project Overview

The diffusion model implemented in this repository follows a sophisticated architecture that synthesizes high-resolution images from textual descriptions. The process involves several key components:

- **Random Noise**: Initiation of the image generation process from random noise.
- **Encoder**: Compression of noise into a latent space representation.
- **CLIP Encoder**: Conversion of textual prompts into embeddings that guide the image synthesis.
- **Scheduler**: Application of time embeddings to manage the diffusion steps.
- **Decoder**: Transformation of refined latent representations into the final image output.

