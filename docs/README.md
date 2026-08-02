<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-02
- 运行时间：2026-08-02 21:28:44 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：8
- 速读区：9

### 今日简报（AI）
今日聚焦17篇论文，精读8篇，其中图像与视频生成加速、长视频音频驱动数字人成为高价值方向。  
最值得看的是满分论文《Parallel Decoding Distillation》实现图像/视频生成并行加速，以及9分《AptAvatar》实现长音频驱动视频生成，适合关注生成效率与虚拟人落地。  
对普通读者，建议优先跟踪扩散模型蒸馏与音频驱动视频技术，后续可关注视频阴影去除等实用方向。
- 详情：[/202608/02/README](/202608/02/README)

### 精读区论文标签
1. [Parallel Decoding Distillation for Fast Image and Video Generation](/202608/02/2607.26004v1-parallel-decoding-distillation-for-fast-image-and-video-generation)  
   标签：评分：10.0/10、query:vd
   evidence：针对少步视频生成的轨迹蒸馏，解决多样性缺失和运动匮乏
2. [AptAvatar: Fast and Vivid Long-Form Audio-Driven Video Generation for Production-Ready Avatars](/202608/02/2607.24013v2-aptavatar-fast-and-vivid-long-form-audio-driven-video-generation-for-production-ready-avatars)  
   标签：评分：9.0/10、query:vd
   evidence：面向长视频头像生成的两步蒸馏加速，在保持表达力的同时显著加速推理
3. [Visko Orbis 1.0: A Live Model for Real-Time Interactive Long Video Generation](/202608/02/2607.26694v1-visko-orbis-10-a-live-model-for-real-time-interactive-long-video-generation)  
   标签：评分：9.0/10、query:fast-gen
   evidence：实时交互式长视频生成，基于蒸馏流式生成器
4. [DistillAlign: Coordinating Mode Covering and Mode Seeking in Autoregressive Video Distillation](/202608/02/2607.26811v1-distillalign-coordinating-mode-covering-and-mode-seeking-in-autoregressive-video-distillation)  
   标签：评分：9.0/10、query:vd
   evidence：协调自回归视频蒸馏中的模式覆盖与模式寻求
5. [ReGenVC: End-to-End Real-Time Generative Video Coding at Ultra-Low Bitrate](/202608/02/2607.28144v1-regenvc-end-to-end-real-time-generative-video-coding-at-ultra-low-bitrate)  
   标签：评分：9.0/10、query:vd
   evidence：四步蒸馏扩散变换器，实现实时视频生成与重建
6. [Chimera: Designing and Chinchilla-Scaling Hybrid Visual Diffusion Transformers](/202608/02/2607.28611v1-chimera-designing-and-chinchilla-scaling-hybrid-visual-diffusion-transformers)  
   标签：评分：9.0/10、query:fast-gen
   evidence：面向图像视频生成的高效混合扩散骨干，含O(N)稀疏/线性注意力
7. [Flow Map Learning via Nongradient Vector Flow](/202608/02/2607.26398v1-flow-map-learning-via-nongradient-vector-flow)  
   标签：评分：8.0/10、query:vd
   evidence：学习流映射以实现扩散/流生成模型的少步采样
8. [Ripple: Real-Time Streaming Audio-Video Generation With Cross-Modal Recurrent Memory](/202608/02/2607.26818v1-ripple-real-time-streaming-audio-video-generation-with-cross-modal-recurrent-memory)  
   标签：评分：8.0/10、query:fast-gen
   evidence：实时流式音视频生成，跨模态循环记忆

### 速读区论文标签
1. [WildShadowRemover: In-the-Wild Video Shadow Removal via Detail-Preserving Video Diffusion Models](/202608/02/2607.26203v1-wildshadowremover-in-the-wild-video-shadow-removal-via-detail-preserving-video-diffusion-models)  
   标签：评分：8.0/10、query:video-refine
   evidence：基于预训练视频扩散模型的视频恢复，通过LoRA微调和细节注入模块保留高频纹理
2. [CachedSearch: Training-Free Cached Exploration for Test-Time Search in Video Diffusion](/202608/02/2607.23159v2-cachedsearch-training-free-cached-exploration-for-test-time-search-in-video-diffusion)  
   标签：评分：7.0/10、query:fast-gen
   evidence：无训练缓存加速视频扩散推理与测试时搜索
3. [Wonder: Video World Model Done Better](/202608/02/2607.26037v1-wonder-video-world-model-done-better)  
   标签：评分：7.0/10、query:fast-gen
   evidence：实时相机可控视频世界模型，支持高效记忆检索。
4. [Amortized Moment Matching for Visual Generation](/202608/02/2607.26860v1-amortized-moment-matching-for-visual-generation)  
   标签：评分：7.0/10、query:vd
   evidence：针对视觉生成模型的后训练目标，采用摊销矩匹配学习分布信号
5. [MixFrag: Fragility-Guided Mixed-Precision Post-Training Quantization for Vision Transformers](/202608/02/2607.28589v1-mixfrag-fragility-guided-mixed-precision-post-training-quantization-for-vision-transformers)  
   标签：评分：7.0/10、query:fast-gen
   evidence：面向视觉Transformer的混合精度后训练量化，可加速推理并降低显存开销
6. [ViDS: Video Diffusion Shader using 3D Face Tracking](/202608/02/2607.24124v1-vids-video-diffusion-shader-using-3d-face-tracking)  
   标签：评分：6.0/10、query:video-refine
   evidence：自回归扩散采样降低相邻片段不连续，针对生成视频的时间一致性
7. [Mitigating Compounding Error via Video Representation Regularization](/202608/02/2607.27036v1-mitigating-compounding-error-via-video-representation-regularization)  
   标签：评分：6.0/10、query:vd
   evidence：视频世界模型表示正则化，缓解误差累积以提升时间稳定性
8. [FreqForcing: Autoregressive Long Video Generation via Spectral Self-Anchoring](/202608/02/2607.27110v1-freqforcing-autoregressive-long-video-generation-via-spectral-self-anchoring)  
   标签：评分：6.0/10、query:fast-gen
   evidence：无训练的频谱自锚定方法，稳定长自回归视频生成。
9. [TARS: Timestep-Aware Data Scaling for 3D-Free Video Re-Shooting](/202608/02/2607.28261v1-tars-timestep-aware-data-scaling-for-3d-free-video-re-shooting)  
   标签：评分：6.0/10、query:vd
   evidence：视频重拍可控相机运动，提升视频生成中的运动动态


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
