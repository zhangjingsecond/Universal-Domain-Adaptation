# Universal Domain Adaptation

Code release for  **Universal Domain Adaptation(CVPR 2019)** 

## Requirements
- python 3
- PyTorch 1.0

`pip install -r requirements.txt`

## Usage

- download datasets

- write your config file

- `python main.py --config /path/to/your/config/yaml/file`

- train (configurations in `officehome-train-config.yaml` are only for officehome dataset):

  `python main.py --config officehome-train-config.yaml`

- test

  `python main.py --config officehome-test-config.yaml`

## Checkpoints

We provide the checkpoints for officehome datasets at [Google Drive](https://drive.google.com/drive/folders/1Kw3Lfw4dPdTZ8RQ1cUQVDpE5odp8th7J?usp=sharing).

## Citation
please cite:
```
@InProceedings{UDA_2019_CVPR,
author = {You, Kaichao and Long, Mingsheng and Cao, Zhangjie and Wang, Jianmin and Jordan, Michael I.},
title = {Universal Domain Adaptation},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2019}
}
```

## Contact
- youkaichao@gmail.com
- longmingsheng@gmail.com
