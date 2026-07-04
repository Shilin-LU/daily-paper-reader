<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-04
- 运行时间：2026-07-04 21:37:49 UTC
- 运行状态：成功
- 本次总论文数：15
- 精读区：5
- 速读区：10

### 今日简报（AI）
今天推送15篇，聚焦视频超分辨率和扩散模型量化，精读5篇含2篇高分。

最值得关注的方向：任意尺度视频超分辨率（AVSR-Diff）和图像/视频扩散Transformer量化（OrbitQuant），两者均为9.0分，是前沿且实用的技术突破。

建议优先精读这两篇高分论文，了解如何在不牺牲时间一致性的前提下提升视频分辨率，以及如何高效压缩扩散模型。
- 详情：[/202607/04/README](/202607/04/README)

### 精读区论文标签
1. [AVSR-Diff: Scale-Agnostic Diffusion Priors for Temporally Consistent Arbitrary-Scale Video Super-Resolution](/202607/04/2607.00987v1-avsr-diff-scale-agnostic-diffusion-priors-for-temporally-consistent-arbitrary-scale-video-super-resolution)  
   标签：评分：9.0/10、query:video-refine
   evidence：扩散模型视频超分辨率，直接提升生成视频质量
2. [OrbitQuant: Data-Agnostic Quantization for Image and Video Diffusion Transformers](/202607/04/2607.02461v1-orbitquant-data-agnostic-quantization-for-image-and-video-diffusion-transformers)  
   标签：评分：9.0/10、query:fast-gen
   evidence：视频扩散模型的后训练量化
3. [MASS: Motion-Aligned Selective Scan for Refinement in Flow-Based Video Frame Interpolation](/202607/04/2606.27718v1-mass-motion-aligned-selective-scan-for-refinement-in-flow-based-video-frame-interpolation)  
   标签：评分：8.0/10、query:video-refine
   evidence：运动对齐选择性扫描用于视频帧插值细化，可应用于生成视频的后处理精炼
4. [CSD: Content-aware Speculative Decoding for Efficient Image Generation](/202607/04/2606.27829v1-csd-content-aware-speculative-decoding-for-efficient-image-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：内容感知推测解码加速自回归图像生成
5. [SyncCache: Exploiting Asymmetric Dynamics for Fast Audio-Driven Portrait Animation](/202607/04/2606.30849v1-synccache-exploiting-asymmetric-dynamics-for-fast-audio-driven-portrait-animation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：无需训练的缓存加速音频驱动视频生成

### 速读区论文标签
1. [TempAct: Advancing Temporal Plausibility in Autoregressive Video Generation via Planner-Executor RL](/202607/04/2606.28016v1-tempact-advancing-temporal-plausibility-in-autoregressive-video-generation-via-planner-executor-rl)  
   标签：评分：7.0/10、query:vd
   evidence：指出自回归视频生成中蒸馏的局限性，提出RL替代方案以提升时间合理性
2. [TempAct: Advancing Temporal Plausibility in Autoregressive Video Generation via Planner-Executor RL](/202607/04/2606.28016v2-tempact-advancing-temporal-plausibility-in-autoregressive-video-generation-via-planner-executor-rl)  
   标签：评分：7.0/10、query:vd
   evidence：利用强化学习对自回归视频生成进行后训练微调
3. [Towards Memory-Efficient Autoregressive Video Generation via Instance-Specific Parametric Absorption](/202607/04/2607.00712v1-towards-memory-efficient-autoregressive-video-generation-via-instance-specific-parametric-absorption)  
   标签：评分：7.0/10、query:fast-gen
   evidence：实例特定参数吸收将全注意力转换为局部注意力，实现内存高效的自回归视频生成
4. [TrajLoc: Trajectory-Attention Localization for Multi-Object Motion Control](/202607/04/2607.00861v1-trajloc-trajectory-attention-localization-for-multi-object-motion-control)  
   标签：评分：7.0/10、query:vd
   evidence：图像到视频生成中的多目标运动控制，改善运动动态
5. [Optimizing Visual Generative Models via Distribution-wise Rewards](/202607/04/2607.02291v1-optimizing-visual-generative-models-via-distribution-wise-rewards)  
   标签：评分：7.0/10、query:vd
   evidence：分布奖励提升视觉生成模型的多样性
6. [Representation Distribution Matching for One-Step Visual Generation](/202607/04/2607.02375v1-representation-distribution-matching-for-one-step-visual-generation)  
   标签：评分：7.0/10、query:vd
   evidence：通过分布匹配的知识蒸馏实现一步图像生成
7. [World Narrative Model for Highly Controllable Video Generation: A Paradigm Shift from Pixel Sampling to Physical World Orchestration](/202607/04/2606.31946v1-world-narrative-model-for-highly-controllable-video-generation-a-paradigm-shift-from-pixel-sampling-to-physical-world-orchestration)  
   标签：评分：6.0/10、query:vd
   evidence：通过物理世界编排提升视频生成的多样性和可控性
8. [Post-Training Pruning for Diffusion Transformers](/202607/04/2607.00927v1-post-training-pruning-for-diffusion-transformers)  
   标签：评分：6.0/10、query:vd
   evidence：扩散Transformer的后训练剪枝方法，可迁移至视频生成
9. [Multi-Resolution Flow Matching: Training-Free Diffusion Acceleration via Staged Sampling](/202607/04/2607.01642v1-multi-resolution-flow-matching-training-free-diffusion-acceleration-via-staged-sampling)  
   标签：评分：6.0/10、query:fast-gen
   evidence：无训练的多分辨率加速流匹配模型，实现快速图像生成
10. [QWERTY: Training-Free Motion Control via Query-Warped Video Diffusion Transformers](/202607/04/2607.01869v1-qwerty-training-free-motion-control-via-query-warped-video-diffusion-transformers)  
   标签：评分：6.0/10、query:vd
   evidence：无需训练的视频扩散变换器运动控制


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
