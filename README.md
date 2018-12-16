# Dynamic Graph CNN for Learning on Amino Acid Point Cloud Structure
We use a neural network module dubbed EdgeConv suitable for CNN-based high-level tasks on point clouds including classification. 

## Overview
`DGCNN` is the author's re-implementation of Dynamic Graph CNN, which achieves state-of-the-art performance on point-cloud-related high-level tasks including category classification. We build upon this work and configure this implementation for amino acid structure recognition.

## Requirements
* [TensorFlow](https://www.tensorflow.org/)

## Amino Acid Point Cloud Classification
* Run the training script:
``` bash
python train.py
```
* Run the evaluation script after training finished:
``` bash
python evalutate.py

```

## Citation
	@article{dgcnn,
	  title={Dynamic Graph CNN for Learning on Point Clouds},
	  author={Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon},
	  journal={arXiv preprint arXiv:1801.07829},
	  year={2018}
	}
    
    Reference: [[Paper]](https://arxiv.org/abs/1801.07829)     

## License
MIT License

## Acknowledgement
This code is heavily borrowed from [PointNet](https://github.com/charlesq34/pointnet).
