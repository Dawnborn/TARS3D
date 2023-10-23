# MyInstallation

```
conda create -n hjp_tars3d python==3.7
conda activate hjp_tars3d
```

install pytorch

```
pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
```

```
pip install open3d scikit-image scikit-learn
```

```
pip install scipy imageio easydict tensorboard visdom matplotlib trimesh pyyaml jupyter jsonpatch pymcubes plyfile pyvista pillow
```

vigra

pip install not work

```
conda install -c conda-forge vigra
```

# Dataset Preparation
```
wget https://s3.eu-central-1.amazonaws.com/avg-projects/differentiable_volumetric_rendering/data/NMR_Dataset.zip
unzip NMR_Dataset.zip NMR_Dataset/02691156/* # airplane
unzip NMR_Dataset.zip NMR_Dataset/02958343/* # car
unzip NMR_Dataset.zip NMR_Dataset/03001627/* # chair
rm NMR_Dataset.zip
```