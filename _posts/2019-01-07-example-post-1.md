---
title: Neus：Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction
author: sarah-johnson
tags:
  - biology
  - medicine
  - big data
---

摘要本文的总目标是实现从2D图片到3D模型的高保真重建（使用神经渲染方法）。2020年Niemeyer等人提出的DVR和2020年Yariv等人提出的IDR是现存的神经表面重建（neural surface reconstruction）方法，但他们都依赖前景遮罩（foreground mask）提供监督且训练不稳定。近期的神经方法比如2020年的NeRF及其变体提出使用体积渲染（volume rendering）构造更鲁棒的场景描述，但由于缺少表面约束（surface constraints）在这种隐式（implicit）场景描述的基础上构造表面十分困难。于是本文提出一种新的神经表面重建方法NeuS，使用一个符号距离函数（SDF，signed distance function）的零级集合（zero-level set）来表示一个表面，并部署一种新的体积渲染方法来训练神经SDF描述。作者发现传统体积渲染会在表面重建引入固有几何错误比如bias，所以引入了新方法，改进这一情况，即使没有遮罩监督。
