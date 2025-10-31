# GAN-Based-Near-Field-Channel-Estimation-for-Extremely-Large-Scale-MIMO-Systems
Source codes of the article: [1] M. Ye, X. Liang, C. Pan, Y. Xu, M. Jiang and C. Li, "GAN-Based Near-Field Channel Estimation for Extremely Large-Scale MIMO Systems," in IEEE Transactions on Green Communications and Networking, vol. 9, no. 1, pp. 304-316, Mar. 2025. 

If you use this simulation code package in any way, please cite the original paper [1] above. 
The author in charge of this simulation code pacakge is: Ming Ye (email: mye@seu.edu.cn).

Ackonwledge: We are very grateful for the author of following reference papers. Our source code is improved based on their source code. 
[22] Y. Lu and L. Dai, “Near-field channel estimation in mixed LoS/NLoS
environments for extremely large-scale MIMO systems,” IEEE Trans.
Commun., vol. 71, no. 6, pp. 3694–3707, Jun. 2023.
[31] Y. Dong, H. Wang, and Y.-D. Yao, “Channel estimation for one-bit multiuser massive MIMO using conditional GAN,” IEEE Commun. Lett.,
vol. 25, no. 3, pp. 854–858, Mar. 2021.

Please note that the MATLAB R2020a, Python 3.8 and Tensorflow 2.6.0 are used for this simulation code package,  and there may be some imcompatibility problems among different versions. 

*********************************************************************************************************************************
How to use this simulation code package?
This folder contains codes for channel data generation executed in MATLAB and codes for channel estimation executed in Python.

Channel data generation:  Use the script data_generate12.m from the archive tex8_mat.zip to generate near-field channel data.


Channel estimation: Use the script main_cGAN83.py from the archive tex83_CGAN_IE.zip to train and test the proposed method based on the GAN variant.

[main_cGAN83.py](https://github.com/user-attachments/files/22990320/main_cGAN83.py)


[tex8_mat.zip](https://github.com/user-attachments/files/22990472/tex8_mat.zip)

[tex83_CGAN_IE.zip](https://github.com/user-attachments/files/22990475/tex83_CGAN_IE.zip)
