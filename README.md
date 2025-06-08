# Henrik Hansen Stormyhr's Master's Theis Repository
This repository contains the code and supplementary materials used in Henrik Hansen Stormyhr's Master's thesis called "A comparative analysis of MOS-LQO algorithms for perceptual transparency testing in audio steganography"

## References:
The references for the code presented in this repository can be found below.

### GAN Method Code:

The GAN Method code is largely based on [1]'s implementation of the papers [2] and [3], with only small modifications made to the code.

[1] A. Garg and S. Rosetti, Implementation of StegoGAN: High Capacity Image
 Steganography for Image and Audio Input with GANs, Jul. 2020. [Online].
 Available: https://github.com/garg-akash/Steganography_GANs

[2] K.A.Zhang,A.Cuesta-Infante,L.XuandK.Veeramachaneni,SteganoGAN:
 High Capacity Image Steganography with GANs,Jan.2019. DOI:10.48550/
 arXiv.1901.03892. [Online]. Available: http://arxiv.org/abs/1901.03892

 [3] D. Ye, S. Jiang and J. Huang, Heard More Than Heard: An Audio Stegano
graphy Method Based on GAN, Jul. 2019. DOI: 10.48550/arXiv.1907.
 04986. [Online]. Available: http://arxiv.org/abs/1907.04986

### PESQ Code:

"ludlows" PESQ Python wrapper [1] is used for the PESQ Code. Microsoft Copilot [2] is used together with the documentation in [1] to create the code.

[1] ludlows, GitHub- ludlows/PESQ at v0.0.4, en, May 2019. [Online]. Avail
able: https://github.com/ludlows/PESQ

[2] Microsoft_Corporation, Microsoft Copilot: Your AI companion, en-us. [On
line]. Available: https://copilot.microsoft.com

### R Correlation Code

This [1] YouTube tutorial was used to understand Pearson's Correlation in R, and Microsoft CoPilot [2] was used to generate almost all of the code.

[1] S. Bradburn, How To Perform A Pearson Correlation Test In R, Mar.
 2020. [Online]. Available: https://www.youtube.com/watch?v=2J_ZlxLeuQU

[2] Microsoft_Corporation, Microsoft Copilot: Your AI companion, en-us. [On
line]. Available: https://copilot.microsoft.com

### SNR Code

The SNR code was almost entirely based on Reyer's SNR code [1], made in connection with their thesis [2].

[1] P. M. Reyers, Steganography-analysis/compute_transparency.py at main,
 en, Jun.2023.[Online].Available: https://github.com/MatthijsReyers/steganography-analysis/blob/main/compute_transparency.py

[2] P. M. Reyers, A comparative analysis of audio steganography methods and
 tools, Publisher: University of Twente, Jul. 2023. [Online]. Available: https://essay.utwente.nl/95988/

### TAN Method Code

The TAN method code was implemented from this paper [1]. This paper contains mistakes which our thesis solves.

[1] M. T. Elkandoz and W. Alexan, ‘Logistic Tan Map Based Audio Stegano
graphy,’ in 2019International Conference on Electrical and Computing Tech
nologies and Applications (ICECTA), Nov. 2019, pp. 1–5. DOI: 10.1109/
 ICECTA48151.2019.8959683. [Online]. Available: https://ieeexplore.ieee.org/document/8959683
