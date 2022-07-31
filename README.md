# Interior_GANs-WALL-2-SPACE-VOXELIZATION-FUSION

This research project addresses the problem of interior spaces design (ISD) as it demonstrates a lot of variation and styles that are widely expanding recently with multiple designers tending to get their own distinguished signatures. Moreover, ISD is time-consuming, multi-step / multi-layer through a continuous iterative process to finding alternatives. Recently, computational design elaboration on ISD is manifested only through benches and shelves. However, the whole space is evolved to be a fusion with a cloud of voxels that respond to use patterns of special needs like the ones of disabled. Space voxelization is aimed to be interactive to sensors reading as well. This approach can generate more ISD to accommodate disabled usability. Inference Wasserstein Generative Adversarial Network (iWGAN) is adopted to apply generative ISD, hence extending the boundaries of space furnishing to space articulation as behave as one. Three iterations with three different samples and hyperparameters are used to improve results. As iWGAN is trained more to learn both an encoder and a decoder simultaneously. This approach is adequate to train 3D datasets and learn in a 3-dimensional space. Results have delineated progress after 19,801 to resemble the trained data with almost 82% accuracy.   

# Methodology
The methodology undertakes 5 main steps. At first, the geometry generative modeling uses Gh scripting. Then, bounding generated models in 64 X64 X64 to get txt files of 0 & 1 . These models will be turned into a NumPy array which will be utilized to train the iWGAN model. Finally, results and latent space exploration takes place. 

![image](https://user-images.githubusercontent.com/108461498/182040786-40c28e17-d614-4124-a013-f17ee7990d45.png)

# iWGANs Iterations
The project hypothesis undergoes 3 iterations. The first uses 103 samples to train 5000 hyperparameters. The second uses double the dataset with 10,000 hyperparameters. At last, in iteration 3 triple the samples with 20,000 hyperparameters.


![image](https://user-images.githubusercontent.com/108461498/182040959-1d53e6c5-dc05-4491-a2a0-b81087ae0e1e.png)


# References
1.Chen, Y., Gao, Q., Wang, X. (2021) Inferential Wasserstein Generative Adversarial, Machine Learning Statistics, Cornell, University, https://doi.org/10.48550/arXiv.2109.05652.
2. Feri, Ludia E., Jaehun Ahn, Shahrullohon Lutfillohonov, and Joonho Kwon. 2021. "A Three-Dimensional Microstructure Reconstruction Framework for Permeable Pavement Analysis Based on 3D-IWGAN with Enhanced Gradient Penalty" Sensors 21, no. 11: 3603. https://doi.org/10.3390/s21113603
3. AI generated interior Design , Michael Hasey, retrieved n 10/96/2022 : http://www.michaelhasey.com/gan_interior
4. Zhang, T., Liu, Q., Wang, X., Ji, X., Du, Y., 2022, A 3D reconstruction method of porous media based on improved WGAN-GP
, computers and geosciences, https://doi.org/10.1016/j.cageo.2022.105151
