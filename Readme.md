# Awesome Visual Question Answering in PyTorch [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A (probably incomplete) list of PyTorch repositories for visual question answering.

<p align="center">
  <img width="460" src="https://visualqa.org/static/img/challenge.png">
</p>

<sub>Image source: [VQA Challenge](https://visualqa.org/challenge.html).</sub>

## Contents

* [Image VQA](#image-vqa)
    * [2017](#2017)
    * [2018](#2018)
    * [2019](#2019)
    * [Results](#results)
* [Video VQA](#video-vqa)


## Image VQA

### 2019
- MUREL (CVPR 2019):
[[PyTorch]](https://github.com/Cadene/murel.bootstrap.pytorch)
[[paper]](https://arxiv.org/abs/1902.09487)
- XNM (CVPR 2019):
[[PyTorch]](https://github.com/shijx12/XNM-Net)
[[paper]](https://arxiv.org/abs/1812.01855)
- VCR (CVPR 2019):
[[PyTorch]](https://github.com/rowanz/r2c/)
[[paper]](https://arxiv.org/abs/1811.10830)
- BLOCK (AAAI 2019): 
[[PyTorch]](https://github.com/Cadene/block.bootstrap.pytorch) 
[[paper]](http://remicadene.com/pdfs/paper_aaai2019.pdf)

### 2018
- Pythia (VQA 2018 challenge winner)
[[PyTorch]](https://github.com/facebookresearch/pythia)
[[Paper]](https://arxiv.org/abs/1807.09956)
- BAN (NeurIPS 2018):
[[PyTorch]](https://github.com/jnhwkim/ban-vqa)
[[paper]](https://arxiv.org/abs/1805.07932)
- Graph Attention (NeurIPS 2018)
[[PyTorch]](https://github.com/aimbrain/vqa-project)
[[Paper]](https://arxiv.org/abs/1806.07243)
- Counter (ICLR 2018):
[[PyTorch]](https://github.com/Cyanogenoid/vqa-counting)
[[paper]](https://openreview.net/forum?id=B12Js_yRb)
- Bottom-Up and Top-Down Attention (CVPR 2018):
[[PyTorch]](https://github.com/hengyuan-hu/bottom-up-attention-vqa) 
[[paper]](https://arxiv.org/abs/1707.07998)
[[Caffe]](https://github.com/peteanderson80/bottom-up-attention)

### 2017
- MUTAN (ICCV 2017): 
[[PyTorch]](https://github.com/Cadene/vqa.pytorch) 
[[paper]](https://arxiv.org/abs/1705.06676)

### Results

Results as reported in each paper (single-model):

| Method | Publication | VQA 2.0 (*) |
|--------|--------|-------------:|
| MUREL | CVPR 2019 | 68.41 |
| XNM  | CVPR 2019 | 67.5 |
| Pythia | VQA 2018 challenge winner | 70.24 |
| BAN | NeurIPS 2018 | 70.35 |
| Graph Attention | NeurIPS 2018 | 66.18 |
| Counter | ICLR 2018 | 68.41 |
| Bottom-Up and Top-Down | CVPR 2018 | 65.67 |


(*) standard test set 


## Video VQA

- HME-VideoQA (CVPR 2019):
[[PyTorch]](https://github.com/fanchenyou/HME-VideoQA)
[[Paper]](https://arxiv.org/pdf/1904.04357.pdf)
- TVQA (EMNLP 2018):
[[PyTorch]](https://github.com/jayleicn/TVQA)
[[Paper]](https://arxiv.org/abs/1809.01696)

## Contributing

Please feel free to send me pull requests or an email to `noagarcia@ids.osaka-u.ac.jp` to add repositories.

## License

This repository is published under the Creative Commons license [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

## References

For other awesome-lists about VQA, please check:
* [awesome-vqa](https://github.com/JamesChuanggg/awesome-vqa) by [JamesChuanggg](https://github.com/JamesChuanggg)
* [awesome-visual-question-answering](https://github.com/jokieleung/awesome-visual-question-answering)
by [jokieleung](https://github.com/jokieleung)