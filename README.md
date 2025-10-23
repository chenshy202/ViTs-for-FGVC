# An Empirical Study of Vision Transformers for Fine-Grained Visual Classification

**Final project for Artificial Neural Networks**

## Report
The detailed project report and slides can be found in the `report/` directory.


## Setup

For dependencies, pre-trained model downloads, and dataset preparation, please follow the instructions provided in the original [**TransFG GitHub repository**](https://github.com/TACJu/TransFG).

## Training

Once the setup is complete, use the following commands to start training.

*   **Train on CUB-200-2011:**
```bash
python train.py \
    --name CUB_ViT-B_16 \
    --dataset cub \
    --model_type ViT-B_16 \
    --pretrained_dir /path/to/your/model/ViT-B_16.npz
```

*   **Train on Stanford Dogs:**
```bash
python train.py \
    --name Dog_ViT-B_16 \
    --dataset dog \
    --model_type ViT-B_16 \
    --pretrained_dir /path/to/your/model/ViT-B_16.npz
```