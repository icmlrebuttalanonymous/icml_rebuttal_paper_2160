# Installation  
Step 1: Create a new conda environment:
```
conda create -n prune_llm python=3.9
conda activate prune_llm
```
Step 2: Install relevant packages
```
conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio==0.10.1 cudatoolkit=11.3 -c pytorch -c conda-forge
pip install transformers==4.35.2 datasets==2.16.1 wandb sentencepiece
pip install accelerate==0.25.0
pip install weightwatcher

```