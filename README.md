# Reinforcement Learning with Rendering Feedback for Vector Graphic Generation

- Problems to be solved: Obtaining an interpretable method for synthesizing images for Pre/Post-Training Multimodal Models
- Domain: Visual Code Generation

While omnimodal models with vision decoders claim their potential of generating images, their image generation mechanism is opaque, posing challenges in obtaining a reliable method to synthesize images.
On the other hand, vector graphics, constituted with code, provide an interpretable method to synthesize images thereby allowing developers modify the synthetic images.
In pursuit of an economical method to obtain models capable of synthesizing vector graphics, we examine how Nemo RL can be a useful tool to obtain a task-specific model that allows low-cost image synthesis.

## Tools to be used

Nemo RL

## Must Have

- RLRF Mechanism

## Nice to have

- Methods for faster code generation
  - MTP for speculative decoding
  - SVG Context-Free Grammar(CFG) guided decoding
