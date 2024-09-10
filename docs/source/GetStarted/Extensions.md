# Extensions

本文档介绍了一些在 DiffSynth 实现的 Diffusion 模型之外的相关技术，这些模型在图像和视频处理方面具有显著的应用潜力。

- **[RIFE](https://github.com/hzwer/ECCV2022-RIFE)**：FIRE（实时中间流估计算法）是一个基于实时中间流估计的帧插值（VFI）方法。FIRE采用了一种名为IFNet的神经网络，能够以更快的速度端到端估计中间流。为确保IFNet的稳定训练并提升整体性能，设计了一种特权蒸馏方案。FIRE不依赖于预训练的光流模型，能够支持任意时间步的帧插值，通过时间编码输入进行处理。

- **[ESRGAN](https://github.com/xinntao/ESRGAN)**: ESRGAN（增强型超分辨率生成对抗网络）是对 SRGAN 的一种改进方法，旨在提升单幅图像超分辨率的视觉质量。该方法通过优化SRGAN的三个关键组件——网络架构、对抗损失和感知损失，显著提升了生成图像的真实感。

- **[FastBlend](https://arxiv.org/abs/2311.09265)**: FastBlend是一个用来平滑视频的无模型工具包，与 Diffusion 模型结合打造了强大的视频处理流程。该工具能够有效消除视频中的闪烁现象，对关键帧序列插值，并且可以基于单一图像处理完整视频。


