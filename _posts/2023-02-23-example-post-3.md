---
title: 三维重建以及神经渲染中的学习
image: images/photo.jpg
author: john-doe
tags: biology, medicine
---
1：摘要
提出基于学习（learning-based）方法，使用野外照片的非结构化集合（unstructured collections of in-the-wild photographs）来合成复杂场景。之前的Nerf通过MLP的权重来模拟场景的密度、颜色。虽然在静态对象生成上比较好，但在uncontrolled images不受控的图片中，会有一些ubiquitous，real-world phenomenon，也就是可变照明或者瞬时遮光器variable illumination or transient occluders，本文基于Nerf引入了一些列扩展来解决这些问题。

概况来讲：
Nerf要求在相同位置、视角拍摄的照片完全一样，也就是必须在尽可能短的时间内拍的照片，因为这种情况下光线变化等影响会很小；nerf-wild放松了限制，通过解决光照变化以及移动遮挡的问题，来使得输入的照片不一定完全一样，同一个位置、同一个视角上午拍的或者下午拍的都可以作为输入。

