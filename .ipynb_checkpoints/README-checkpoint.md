# ARC-Net
Official implementation of [Activity recognition through capsules](https://arxiv.org/abs/2007.03063)

## Network architectures
The different proposed ARCNet models are provided below. <br />
A preprocessing code for RealWorld is also provided.

 - [**ARCNet for the RealWorld dataset**](/ARCNet-Large-RealWorld.ipynb)
 - [**ARCNet for the PAMAP2 dataset**](/ARCNet-Large-PAMAP.ipynb)
 - [**ARCNet-Small for the RealWorld dataset**](/ARCNet-Small-RealWord.ipynb)
 - [**ARCNet-Small for the PAMAP2 dataset**](/ARCNet-Small-PAMAP.ipynb)
 
## Python requirements 

* numpy 
* PyTorch (1.4.0)
* pytorch-lightning (0.7.5)
* h5py (2.9.0)
* tables (3.6.1)
 
## Reference
````
@InProceedings{icmla20,
  author       = "H. Damirchi and R. Khorrambakht and H. Taghirad",
  title        = "ARC-Net: Activity Recognition Through Capsules",
  booktitle    = "IEEE Conference on Machine Learning and Applications (ICMLA)",
  month        = "Dec",
  year         = "2020",
  url          = "https://www.icmla-conference.org/icmla20/index.html"
}
````

## Acknowledgments
The CapsNet implementation in this code was based on [CapsNet-pytorch](https://github.com/adambielski/CapsNet-pytorch).<br/>
We sincerely thank the authors of [PerceptionNet](https://arxiv.org/abs/1811.00170) for sharing their code and processed PAMAP2 data.