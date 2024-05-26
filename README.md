# fine-tuning-xp

```bash
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```


```bash
~/miniconda3/bin/conda init bash
~/miniconda3/bin/conda init zsh
```

Create autotrain environment
```bash
conda create -n autotrain python=3.12.3
```

```bash
conda activate autotrain
```

Install autotrain
```bash
pip install autotrain-

conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
conda install -c "nvidia/label/cuda-12.1.0" cuda-nvcc
```