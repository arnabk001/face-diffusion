# face-diffusion

In this project, I delve into the realm of diffusion models, which have gained considerable popularity in image generation. However, there is a limitation in unconditional diffusion models — they lack precise control over generated images. To overcome this, I implemented a conditional diffusion model, using various image attributes such as skin tone, hair color, age, and gender for nuanced image generation. My initial focus was on creating a diffusion model for hand-object interaction images, but the project evolved into implementing a baseline conditional diffusion model for facial image generation. The ultimate goal is to achieve precise control over generated images, particularly in terms of object poses and attributes. I begin by constructing an unconditional diffusion model for high-quality random face image generation and then modify it to incorporate face attribute vectors for generating controlled images. Experiments are conducted on MNIST and CelebA datasets, with results reported to showcase the efficacy of the approach. Unlike previous models that rely on complex architectures and supplementary attributes, my approach streamlines the process for one-step image generation based solely on the attributes of a given facial image.

The key contribution of this work are the following:
* We develop a diffusion model from scratch, conditioned on image attributes
* We evaluate our model on MNIST and CelebA data set, demonstrating smooth interpolation through
editing image attributes
* We compare the performance of the unconditional model with respect to conditional model, attaining a
4% increase in FID








