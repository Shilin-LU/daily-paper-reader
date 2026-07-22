<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-22
- 运行时间：2026-07-22 20:43:09 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：3
- 速读区：10

### 今日简报（AI）
今日阅读13篇论文，精读2篇高分工作：将前向过程强化学习引入平均速度生成器（MeanFlowNFT），以及面向文本到视频生成的物理与语义直接偏好优化（8.0/10）。  
最值得关注的方向是视频生成中的偏好对齐（物理+语义约束）和多目标跟踪新范式——将生成模型直接用作跟踪器。  
建议进一步探索生成与跟踪的协同，以及结合稀有性感知的离散扩散在图像超分辨率中的应用。
- 详情：[/202607/22/README](/202607/22/README)

### 精读区论文标签
1. [MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators](/202607/22/2607.15273v2-meanflownft-bringing-forward-process-rl-to-average-velocity-generators)  
   标签：评分：8.0/10、query:vd
   evidence：MeanFlow通过平均速度实现快速少步采样
2. [When Physical Preferences Meet Semantic Constraints: Physical and Semantic Direct Preference Optimization for Text-to-Video Generation](/202607/22/2607.16947v1-when-physical-preferences-meet-semantic-constraints-physical-and-semantic-direct-preference-optimization-for-text-to-video-generation)  
   标签：评分：8.0/10、query:vd
   evidence：通过DPO对视频生成模型进行后训练优化
3. [ROMS-IMLE: A Minimalist Approach to Competitive Single-Step Generative Modelling](/202607/22/2607.19332v1-roms-imle-a-minimalist-approach-to-competitive-single-step-generative-modelling)  
   标签：评分：8.0/10、query:fast-gen
   evidence：单步生成建模挑战多步扩散，实现快速生成

### 速读区论文标签
1. [The generator is the tracker: Multi-object tracking by painting persistent identity colours](/202607/22/2607.17120v1-the-generator-is-the-tracker-multi-object-tracking-by-painting-persistent-identity-colours)  
   标签：评分：7.0/10、query:vd
   evidence：使用LoRA微调视频扩散模型，将后训练应用于跟踪任务
2. [Rarity-Aware Discrete Diffusion with Spatially Consistent Decoding for Photo-Realistic Image Super-Resolution](/202607/22/2607.17612v1-rarity-aware-discrete-diffusion-with-spatially-consistent-decoding-for-photo-realistic-image-super-resolution)  
   标签：评分：7.0/10、query:video-refine
   evidence：面向图像超分辨率的稀有感知离散扩散，可应用于视频精炼
3. [Surprise Forcing: What to Remember, When to Skip in Long Video Generation](/202607/22/2607.18436v1-surprise-forcing-what-to-remember-when-to-skip-in-long-video-generation)  
   标签：评分：7.0/10、query:fast-gen
   evidence：长视频生成中无训练的资源分配方法，跳过不必要的步骤
4. [Learning Explicit Physical Parameter Control and Benchmarking for Video Generation](/202607/22/2607.18924v1-learning-explicit-physical-parameter-control-and-benchmarking-for-video-generation)  
   标签：评分：7.0/10、query:vd
   evidence：通过显式物理参数化改善运动动态
5. [Mage-Flow: An Efficient Native-Resolution Foundation Model for Image Generation and Editing](/202607/22/2607.19064v1-mage-flow-an-efficient-native-resolution-foundation-model-for-image-generation-and-editing)  
   标签：评分：7.0/10、query:fast-gen
   evidence：高效的图像生成栈，原生分辨率与CUDA融合，与消费级快速生成相关
6. [Attention-Free and Lightweight Token Reduction for Efficient Vision-Language Models](/202607/22/2607.13500v1-attention-free-and-lightweight-token-reduction-for-efficient-vision-language-models)  
   标签：评分：6.0/10、query:fast-gen
   evidence：无注意力令牌减少降低计算开销，适用于生成模型加速
7. [PE-Field 4D: Video Generation Models as Canvas](/202607/22/2607.15667v1-pe-field-4d-video-generation-models-as-canvas)  
   标签：评分：6.0/10、query:vd
   evidence：通过几何感知交叉注意力改善视频生成中的运动动态
8. [Deep Learning-based Filtering for Video Coding: A Survey on Architectures, Algorithms, and Complexity Analysis](/202607/22/2607.16319v1-deep-learning-based-filtering-for-video-coding-a-survey-on-architectures-algorithms-and-complexity-analysis)  
   标签：评分：6.0/10、query:video-refine
   evidence：深度学习滤波用于视频压缩伪影去除
9. [Spatial Transport of Integration Error in Generative ODEs](/202607/22/2607.16361v1-spatial-transport-of-integration-error-in-generative-odes)  
   标签：评分：6.0/10、query:vd
   evidence：少步生成ODE中积分误差分析
10. [Pixel-Space Diffusion Transformers](/202607/22/2607.17585v1-pixel-space-diffusion-transformers)  
   标签：评分：6.0/10、query:fast-gen
   evidence：像素空间扩散Transformer实现高效图像生成


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
