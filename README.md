# Image Generation with DDPM

This project develops a diffusion-based generative model to synthesize 64×64 RGB images of cute animals from random noise. The model is trained on a synthetic dataset of 22,000 images spanning 11 animal classes, generated using Stable Diffusion 3 Medium. A Denoising Diffusion Probabilistic Model (DDPM) with a custom UNet architecture is implemented using the Hugging Face Diffusers library to learn the reverse diffusion process and progressively reconstruct realistic images from noisy inputs. Training is optimized with mixed-precision computation, gradient checkpointing, and EMA to improve stability and sample quality, while DDIM sampling enables faster image generation during inference.

<table align="center">
  <tr>
    <td><img src="Images/130bf5150990d0960a7bfaae8cc2575645963b556ae355f7c4ba462f00c7db8d.png" width="100" height="100"></td>
    <td><img src="Images/13619f9135bc0ad3aebb9325e30f4e70587f3dff2ac32eac010d20e5cad66a4a.png" width="100" height="100"></td>
    <td><img src="Images/13755bff85cff3bf3d0c5b4576aae21ba1f5f7bc8971b435589fe2518e91ac58.png" width="100" height="100"></td>
  </tr>
  <tr>
    <td><img src="Images/87091a432b4fea115a10295b10066eb2c43aa8bf1e81d3953038f9af3a305564.png" width="100" height="100"></td>
    <td><img src="Images/873c47011cf80905c098e095e6b4e8e6d6aca3035bff48a53a76d78ea95b7850.png" width="100" height="100"></td>
    <td><img src="Images/ed0d88be63f9ebc630f16f70e3979f7a3bf3c6fe9bb7e69206e2c242d3f40f2d.png" width="100" height="100"></td>
  </tr>
</table>


## Course

DS 542 Deep Learning with Data Science - Boston University
