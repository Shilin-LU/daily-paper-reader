<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-26
- 运行时间：2026-07-26 21:41:16 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日阅读19篇，精读7篇，高分论文聚焦注意力机制改进与物理感知视频生成。
最值得看的两篇9分论文：《Kernelized Linear Attention》突破线性注意力容量极限，《DeforM》通过时空掩码实现推理引导的物理感知视频生成。
建议普通读者关注线性注意力在长序列任务中的落地潜力，以及视频生成中物理约束与可控性的结合趋势。
- 详情：[/202607/26/README](/202607/26/README)

### 精读区论文标签
1. [Kernelized Linear Attention: Breaking the Capacity Wall with Symmetric Cones](/202607/26/2607.17419v1-kernelized-linear-attention-breaking-the-capacity-wall-with-symmetric-cones)  
   标签：评分：9.0/10、query:fast-gen
   evidence：提出新型线性注意力框架，提升召回容量
2. [DeforM: Reasoning-Guided Physics-Aware Video Generation via Spatial-Temporal Masking](/202607/26/2607.18664v1-deform-reasoning-guided-physics-aware-video-generation-via-spatial-temporal-masking)  
   标签：评分：9.0/10、query:vd
   evidence：物理感知视频生成提升运动动态
3. [Ms. Forcing: Efficient Streaming Video Generation with Multi-Scale Patchification and Attention](/202607/26/2607.20940v1-ms-forcing-efficient-streaming-video-generation-with-multi-scale-patchification-and-attention)  
   标签：评分：9.0/10、query:fast-gen
   evidence：提出多尺度分块注意力机制用于高效流式视频生成，直接实现快速视频生成
4. [DART: A Degradation-Aware Recurrent Transformer for Archival Film Restoration](/202607/26/2607.21219v1-dart-a-degradation-aware-recurrent-transformer-for-archival-film-restoration)  
   标签：评分：9.0/10、query:video-refine
   evidence：面向生成输出的视频修复，退化感知的时间融合
5. [SANA-Video 2.0: Hybrid Linear Attention with Attention Residuals for Efficient Video Generation](/202607/26/2607.21553v1-sana-video-20-hybrid-linear-attention-with-attention-residuals-for-efficient-video-generation)  
   标签：评分：9.0/10、query:fast-gen
   evidence：混合线性-软注意力和注意力残差实现单GPU高效视频生成
6. [HeadCast: Casting Attention Heads for Efficient Autoregressive Video Generation](/202607/26/2607.20125v1-headcast-casting-attention-heads-for-efficient-autoregressive-video-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：通过分类注意力头实现训练免费的自回归视频生成加速
7. [StreamHOI: Interaction-aware Temporal Memory Adaptation for Streaming HOI Video Generation](/202607/26/2607.20174v1-streamhoi-interaction-aware-temporal-memory-adaptation-for-streaming-hoi-video-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：低延迟流式框架用于实时视频生成

### 速读区论文标签
1. [Mage-Flow: An Efficient Native-Resolution Foundation Model for Image Generation and Editing](/202607/26/2607.19064v1-mage-flow-an-efficient-native-resolution-foundation-model-for-image-generation-and-editing)  
   标签：评分：7.0/10、query:fast-gen
   evidence：高效图像生成，使用流匹配和轻量级tokenizer，与快速生成主题相关
2. [Mage-Flow: An Efficient Native-Resolution Foundation Model for Image Generation and Editing](/202607/26/2607.19064v2-mage-flow-an-efficient-native-resolution-foundation-model-for-image-generation-and-editing)  
   标签：评分：7.0/10、query:fast-gen
   evidence：高效图像生成，轻量级分词器与原生分辨率建模
3. [OSVE: One Step Video Editing with One Step Diffusion Models](/202607/26/2607.19895v1-osve-one-step-video-editing-with-one-step-diffusion-models)  
   标签：评分：7.0/10、query:vd
   evidence：一步扩散用于视频编辑
4. [Importance-Aware OBS Pruning for Diffusion Models](/202607/26/2607.20048v1-importance-aware-obs-pruning-for-diffusion-models)  
   标签：评分：7.0/10、query:fast-gen
   evidence：提出面向扩散模型的重要性感知剪枝，可在消费级GPU上加速推理
5. [Self Gradient Forcing: Native Long Video Extrapolation](/202607/26/2607.20368v1-self-gradient-forcing-native-long-video-extrapolation)  
   标签：评分：7.0/10、query:vd
   evidence：两遍训练策略改善视频扩散模型的长视频外推
6. [RealVDeblur: One-Step Diffusion for Generalizable Real-World Video Deblurring](/202607/26/2607.20628v1-realvdeblur-one-step-diffusion-for-generalizable-real-world-video-deblurring)  
   标签：评分：7.0/10、query:video-refine
   evidence：一步扩散视频去模糊
7. [Inference-Time Scaling of Diffusion Models via Progressive Seed Pruning](/202607/26/2607.21591v1-inference-time-scaling-of-diffusion-models-via-progressive-seed-pruning)  
   标签：评分：7.0/10、query:fast-gen
   evidence：通过种子剪枝加速扩散模型推理，适用于快速生成
8. [Pixel-Space Diffusion Transformers](/202607/26/2607.17585v1-pixel-space-diffusion-transformers)  
   标签：评分：6.0/10、query:fast-gen
   evidence：像素空间扩散Transformer实现高效高保真生成
9. [BMFA: Boundary-Minority Free-Energy Adaptive Screening](/202607/26/2607.17656v1-bmfa-boundary-minority-free-energy-adaptive-screening)  
   标签：评分：6.0/10、query:fast-gen
   evidence：自适应token筛选提高视觉Transformer推理效率
10. [ShotPlan: Cinematic Video Generation with Learnable Planning Token](/202607/26/2607.17675v1-shotplan-cinematic-video-generation-with-learnable-planning-token)  
   标签：评分：6.0/10、query:vd
   evidence：可学习规划token用于多镜头视频生成，附加到预训练模型
11. [ROMS-IMLE: A Minimalist Approach to Competitive Single-Step Generative Modelling](/202607/26/2607.19332v1-roms-imle-a-minimalist-approach-to-competitive-single-step-generative-modelling)  
   标签：评分：6.0/10、query:vd
   evidence：单步生成建模用于快速采样
12. [VQ-Transplant: Efficient VQ-Module Integration for Pre-trained Visual Tokenizers](/202607/26/2607.19575v1-vq-transplant-efficient-vq-module-integration-for-pre-trained-visual-tokenizers)  
   标签：评分：6.0/10、query:fast-gen
   evidence：提出即插即用的VQ模块集成，属于模型量化技术


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
