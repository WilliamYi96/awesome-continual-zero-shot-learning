# Awesome Continual Zero-Shot Learning: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources on continual zero-shot learning, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Contributing
Please feel free to send me [pull requests](https://github.com/WilliamYi96/awesome-continual-zero-shot-learning/pulls) or email ([williamyi96@gmail.com](williamyi96@gmail.com)) to add links.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Starter code for CZSL](#Starter-Code)
+ [Other Resources](#Other-resources)

### Papers
#### Selected arXiv
+ **DACZSL**: Domain-Aware Continual Zero-Shot Learning. Kai Yi, Mohamed Elhoseiny. [[paper]](https://arxiv.org/abs/2112.12989)    
+ **DVGR**: Dynamic VAEs with Generative Replay for Continual Zero-shot Learning. Subhankar Ghosh. [[paper]](https://arxiv.org/abs/2104.12468) [[code]](https://github.com/DVGR-CZSL/DVGR-CZSL)
+ **MCZSL**: Vinay Kumar Verma, Kevin Liang, Nikhil Mehta, Lawrence Carin. Meta-Learned Attribute Self-Gating for Continual Generalized Zero-Shot Learning. arXiv (2021). [[arXiv]](https://arxiv.org/abs/2102.11856)
+ Generalized Continual Zero-Shot Learning / Generative Replay-based Continual Zero-Shot Learning. Chandan Gautam, Sethupathy Parameswaran, Ashish Mishra, Suresh Sundaram. [[paper1]](https://arxiv.org/abs/2011.08508) [[paper2]](https://arxiv.org/abs/2101.08894)

#### ICLR 2021
+ **CN-ZSL**: Ivan Skorokhodov, Mohamed Elhoseiny. "Class Normalization for Zero-Shot Learning". ICLR (2021). [[page]](https://openreview.net/forum?id=7pgFL2Dkyyy) [[code]](https://github.com/universome/class-norm-for-czsl)

#### IJCAI 2020
+ **LZSL** Kun Wei , Cheng Deng, Xu Yang. "Lifelong Zero-Shot Learning". IJCAI (2020). [[pdf]](https://www.ijcai.org/Proceedings/2020/0077.pdf) [[code]](https://github.com/Drkun/Lifelong-Zero-Shot-Learning)
#### ICLR 2019
+ **A-GEM** Arslan Chaudhry, Marc’Aurelio Ranzato, Marcus Rohrbach, Mohamed Elhoseiny. "Efficient Lifelong Learning with A-GEM". ICLR (2019). [[paper]](https://openreview.net/forum?id=Hkf2_sC5FX) [[code]](https://github.com/facebookresearch/agem)
### Datasets
+ **CN-ZSL CUB**: 200 classes randomly split into 10 tasks with 20 classes per task. [[data]](https://github.com/universome/class-norm-for-czsl)
+ **CN-ZSL SUN**: 717 classes randomly split into 15 tasks, the first 3 tasks have 47 classes and the rest of them have 48 classes each.  [[data]](https://github.com/universome/class-norm-for-czsl)
+ **A-GEM Split CUB**: 200 classes split into 20 disjoint subsets of classes.
+ **A-GEM Split AWA**: 50 animal categories, where each task is constructed by sampling 5 classes *with* replacement from the total 50 classes, constructing 20 tasks.
+ **LZSL**: Sequential training on aPY, AWA1, CUB and SUN seen classes, then evaluate on unseen classes.

### Starter Code

### Other Resources

## License
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Kai Yi](https://kaiyi.me) has waived all copyright and related or neighboring rights to this work.
