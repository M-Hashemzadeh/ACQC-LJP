# ACQC-LJP: Apollonius Circle-based Quantum Clustering using Lennard-Jones Potential

Quantum clustering (QC) is widely considered as a powerful method in unsupervised learning problems. This clustering method first forms the potential by the wave function as a superposition of the Gaussian probability functions in the data points’ centers. Then it locates the clusters by emphasizing the minima of the potential function. However, QC is very sensitive to the kernel bandwidth parameter in the Schrödinger equation, which controls the shape of the Gaussian kernel and affects the minimum numbers on the surface of the potential function. This paper proposes an Apollonius Circle-based Quantum Clustering (ACQC) using Lennard-Jones Potential (LJP), entitled ACQC-LJP, which in addition to solving the mentioned problems, improves the ACQC method. ACQC-LJP is the first attempt to generalize the LJP concept (pair potential for simple atoms and molecules) to data points in the feature space. This method begins by screening data points in dense regions using LJP. Then, it constructs the Apollonius circles-based neighborhood groups using data points in dense regions. Finally, it solves the kernel bandwidth issue by utilizing the feature of automatic and adaptive neighborhood bandwidth extraction in the ACQC method. In the proposed approach, the QC process is performed locally and only based on data points in dense regions and their Apollonius neighborhood to optimize the computational cost. Experimental results of ACQC-LJP, compared to the original QC and ACQC methods, show a 50% and 10% improvement in detecting the correct number of clusters, respectively, and more than 90% improvement in execution time. In addition, ACQC-LJP shows significantly better performance compared to the state-of-the-art methods.



The SourceCode.rar file includes the MATLAB implementation of the ACQC-LJP:

N. Abdolmaleki, L. Mohammad Khanli, M. Hashemzadeh, and  S. Pourbahrami "ACQC-LJP: Apollonius Circle-based Quantum Clustering using Lennard-Jones Potential"

For running the code you must start with ACQCLJPscript.m as the main script of the ACQC-LJP method.
The folder of ACQC-LJP contains two folders: dataset0(include synthetic datasets) and dataset1(include 24 real-world datasets).




# Condition to use any sources of this project
Please do not distribute the database or source codes to others until the paper is published and without the authorization of Dr. Mahdi Hashemzadeh (Corresponding author) and Nasim Abdolmaleki.

Authors’ Emails: n.abdolmaleki@tabrizu.ac.ir(N.Abdolmaleki), hashemzadeh@azaruniv.ac.ir (M. Hashemzadeh).

Also for use of the ACQC code please cite the below papers:
*N. Abdolmaleki, L. Mohammad, and M. Hashemzadeh, “ACQC : Apollonius Circle-based Quantum Clustering,” vol. 64, no. May, 2022.
