<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-20
- 运行时间：2026-07-20 21:56:59 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：4
- 速读区：9

### 今日简报（AI）
今日共梳理13篇论文，重点精读2篇高分研究，均聚焦视频生成与扩散模型加速。最值得关注的方向是：单步像素扩散实现高质量视频帧插值（SPEED），以及通过时空冗余缩减加速扩散Transformer（DSTAR）。建议读者优先深入理解这两篇核心技术，再结合速读中关于推理效率优化的Xema和DiTango参考。
- 详情：[/202607/20/README](/202607/20/README)

### 精读区论文标签
1. [SPEED: One-Step Pixel Diffusion for High-quality Video Frame Interpolation](/202607/20/2607.15585v1-speed-one-step-pixel-diffusion-for-high-quality-video-frame-interpolation)  
   标签：评分：9.0/10、query:vd
   evidence：一步像素扩散用于视频帧插值，实现少步采样
2. [DSTAR: Accelerating Diffusion Transformers via Spatial and Temporal Redundancy Reduction](/202607/20/2607.15846v1-dstar-accelerating-diffusion-transformers-via-spatial-and-temporal-redundancy-reduction)  
   标签：评分：9.0/10、query:fast-gen
   evidence：提出细粒度混合精度量化加速扩散Transformer推理
3. [Efficient Difficulty-Aware Dynamic Routing for Diffusion-Based Real-World Image Super-Resolution](/202607/20/2607.15711v1-efficient-difficulty-aware-dynamic-routing-for-diffusion-based-real-world-image-super-resolution)  
   标签：评分：8.0/10、query:video-refine
   evidence：难度感知动态路由用于高效扩散超分辨率，可应用于视频帧增强
4. [FVAttn: Adaptive Sparse Attention with Runtime Load Balancing for Video Generation](/202607/20/2607.16190v1-fvattn-adaptive-sparse-attention-with-runtime-load-balancing-for-video-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：用于视频生成的自适应稀疏注意力

### 速读区论文标签
1. [Xema: Efficient Diffusion Serving through Fine-Grained Memory Management and Auto-Configuration](/202607/20/2607.11136v1-xema-efficient-diffusion-serving-through-fine-grained-memory-management-and-auto-configuration)  
   标签：评分：7.0/10、query:fast-gen
   evidence：高效扩散模型服务实现快速视频生成
2. [Hierarchical Denoising For Multi-Step Visual Reasoning](/202607/20/2607.15278v1-hierarchical-denoising-for-multi-step-visual-reasoning)  
   标签：评分：7.0/10、query:vd
   evidence：层次去噪实现粗到细推理，减少视频生成步数
3. [DiTango: Cost-Effective Parallel Diffusion Generation with Selective Attention State Reuse](/202607/20/2607.15650v1-ditango-cost-effective-parallel-diffusion-generation-with-selective-attention-state-reuse)  
   标签：评分：7.0/10、query:fast-gen
   evidence：利用选择性注意力状态重用加速扩散生成推理
4. [Test-Time Noise Guided Adaptation for Realistic Autoregressive Video Generation](/202607/20/2607.15849v1-test-time-noise-guided-adaptation-for-realistic-autoregressive-video-generation)  
   标签：评分：7.0/10、query:vd
   evidence：自回归视频扩散模型的测试时自适应以减少误差累积
5. [Structure-Detail Decoupled Autoregressive Generation for Fast and High-Fidelity Virtual Try-On](/202607/20/2607.11233v1-structure-detail-decoupled-autoregressive-generation-for-fast-and-high-fidelity-virtual-try-on)  
   标签：评分：6.0/10、query:fast-gen
   evidence：通过自回归模型实现快速图像生成
6. [RainDancer: RGB-Event Video Deraining with Rain-Oriented Spiking Dynamics](/202607/20/2607.13802v1-raindancer-rgb-event-video-deraining-with-rain-oriented-spiking-dynamics)  
   标签：评分：6.0/10、query:video-refine
   evidence：利用RGB-事件融合的视频去雨作为恢复方法
7. [VideoRAE: Taming Video Foundation Models for Generative Modeling via Representation Autoencoders](/202607/20/2607.14088v1-videorae-taming-video-foundation-models-for-generative-modeling-via-representation-autoencoders)  
   标签：评分：6.0/10、query:vd
   evidence：利用冻结视频基础模型进行生成建模的表示自编码器
8. [Advanced Image Generation: Negative Prompt Optimization and Latent Classifier Guidance](/202607/20/2607.14580v1-advanced-image-generation-negative-prompt-optimization-and-latent-classifier-guidance)  
   标签：评分：6.0/10、query:video-refine
   evidence：负提示优化和潜在引导减少图像生成伪影
9. [On the Failure of Boundary-Seeking Distillation in Bottlenecked Generative Architectures](/202607/20/2607.15919v1-on-the-failure-of-boundary-seeking-distillation-in-bottlenecked-generative-architectures)  
   标签：评分：6.0/10、query:fast-gen
   evidence：研究自编码器生成架构中的边界搜索蒸馏


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
