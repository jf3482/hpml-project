# hpml-project: Pruning for model compression

Group project component for High Performance Machine Learning done in Columbia University for Fall 2023. <br>
Work done by [Jit Soon Foo](https://github.com/jf3482), [Tri Le](https://github.com/lequangtri20)

This project looks at applying pruning to a Mask-RCNN network to reduce the model size. 

# Dataset: [Penn-Fudan Database](https://www.cis.upenn.edu/~jshi/ped_html/)
This repository looks at application and effect of pruning on a Mask-RCNN network for pedestrian detection.

## Setting up - 
1) Google colab

## Studies performed -
We studied two main pruning algorithms, [PyTorch's pruning](https://pytorch.org/tutorials/intermediate/pruning_tutorial.html) and [Torch-pruning](https://github.com/VainF/Torch-Pruning).

## Steps to reproduce experiment- 
1) Follow tutorial in (revised)torchvision_finetuning_instance_segmentation.ipynb to perform transfer learning from Faster RCNN to Mask RCNN. Then follow up with running Pytorch's pruning on the network.

2) Perform pruning with Torch-Pruning in Torch-pruning_noRetrain.ipynb and Torch-pruning_retrain.ipynb. Results are logged in wandb. 
