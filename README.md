# **Multi-Block Attention for Efficient Channel Estimation in IRS-Assisted mmWave MIMO**

DOI: 10.1109/TCOMM.2025.3618696
Published in: IEEE Transactions on Communications, 2025


## 📘 **Abstract**

Intelligent Reflecting Surfaces (IRSs) have emerged as a promising technology to improve spectral and energy efficiency in millimeter-wave (mmWave) multiple-input multiple-output (MIMO) systems. However, accurate channel estimation remains a key challenge due to the passive nature of IRS elements and the high pilot overhead required in large-scale deployments.

This repository provides the implementation of our proposed Multi-Block Attention (MBA) framework for efficient cascaded channel estimation in IRS-assisted mmWave MIMO systems utilizing orthogonal frequency division multiplexing (OFDM).

The MBA framework introduces a two-stage deep learning architecture:
	1.	Convolutional Attention Network (CAN): Recovers spatial correlations among IRS elements.
	2.	Complex Multi-Convolutional Network (CMN): Performs adaptive noise suppression and feature refinement.

Through selective IRS element deactivation and attention-guided feature enhancement, the MBA approach achieves substantial improvements in efficiency and accuracy. Simulation results demonstrate:
	•	Up to 87% reduction in pilot overhead compared to least squares (LS) estimation.
	•	~51% lower NMSE at 10 dB SNR compared to leading baseline methods.
	•	Low computational complexity with strong adaptability to diverse propagation environments.



## 🧠 **Key Features**
	•	End-to-end deep learning framework for IRS channel estimation
	•	Attention-based feature refinement and denoising
	•	Compatible with DFT and Hadamard-based phase configurations
	•	Designed for large-scale IRS-assisted mmWave MIMO-OFDM systems


## ⚙️ **Requirements**
	•	Python 3.8+
	•	PyTorch ≥ 1.12
	•	NumPy, SciPy, Matplotlib
	•	CUDA-enabled GPU (recommended for training)


📄 **Citation**

If you use this code in your research, please cite our paper:

```
@article{MomenTayefeh2025MBA,
  author    = {Mehrdad Momen-Tayefeh and Mehrshad Momen-Tayefeh and Maryam Sabbaghian},
  title     = {Multi-Block Attention for Efficient Channel Estimation in IRS-Assisted mmWave MIMO},
  journal   = {IEEE Transactions on Communications},
  year      = {2025},
  doi       = {10.1109/TCOMM.2025.3618696}
}
```

## 👥 **Authors**
	•	Mehrdad Momen-Tayefeh – School of Electrical and Computer Engineering, University of Tehran
	•	Mehrshad Momen-Tayefeh – Department of Computer Engineering, Sharif University of Technology
	•	Maryam Sabbaghian – School of Electrical and Computer Engineering, University of Tehran


## 📬 **Contact**

For questions or collaboration, please contact:
📧 mehrshadmomen@sharif.edu  
  or
  mehrdad.momen@ut.ac.ir
