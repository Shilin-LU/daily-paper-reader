<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-17
- 运行时间：2026-08-17 21:05:29 UTC
- 运行状态：成功
- 本次总论文数：24
- 精读区：11
- 速读区：13

### 今日简报（AI）
今日精读聚焦视频生成，共读24篇论文，其中MotionCraft与DUET两篇获9分高分。最值得关注的方向是潜空间世界模型与蒸馏专家结合，分别以稀疏注意力实现视觉上采样、用质量多样性双蒸馏加速两步视频生成。后续可优先复现DUET的两步生成框架，并关注测试时自适应超分与轨迹评分蒸馏的交叉应用。
- 详情：[/202608/17/README](/202608/17/README)

### 精读区论文标签
1. [MotionCraft: Latent World Modeling with Sparse Attention for Visual Upscaling](/202608/17/2608.08553v1-motioncraft-latent-world-modeling-with-sparse-attention-for-visual-upscaling)  
   标签：评分：9.0/10、query:video-refine
   evidence：基于稀疏注意力的潜在世界模型用于视频超分
2. [DUET: A Diversity-Quality Duet of Distillation Experts for Two-Step Video Generation](/202608/17/2608.09637v1-duet-a-diversity-quality-duet-of-distillation-experts-for-two-step-video-generation)  
   标签：评分：9.0/10、query:vd
   evidence：面向两步视频生成的多样性-质量权衡蒸馏
3. [SparSTAR: Sparse Attention for SpaceTime AutoRegressive Video Synthesis](/202608/17/2608.10519v1-sparstar-sparse-attention-for-spacetime-autoregressive-video-synthesis)  
   标签：评分：9.0/10、query:fast-gen
   evidence：面向视频自回归合成的免训练块稀疏注意力
4. [LiveAnimate: Stable Long-Form Streaming Human Animation in Real-Time](/202608/17/2608.11745v1-liveanimate-stable-long-form-streaming-human-animation-in-real-time)  
   标签：评分：9.0/10、query:fast-gen
   evidence：基于140亿DiT的实时流式人物动画，降低采样预算
5. [LiveAnimate: Stable Long-Form Streaming Human Animation in Real-Time](/202608/17/2608.11745v2-liveanimate-stable-long-form-streaming-human-animation-in-real-time)  
   标签：评分：9.0/10、query:fast-gen
   evidence：十亿级参数规模的实时流式人体动画视频生成
6. [LoSA: Near-Lossless Sparse Attention for Training-Free Video Diffusion Acceleration](/202608/17/2608.12032v1-losa-near-lossless-sparse-attention-for-training-free-video-diffusion-acceleration)  
   标签：评分：9.0/10、query:fast-gen
   evidence：免训练视频扩散加速的近无损稀疏注意力
7. [Avatar-Forever: Decoupled Parallel Training for High-Quality Real-Time Infinite Avatars](/202608/17/2608.12107v1-avatar-forever-decoupled-parallel-training-for-high-quality-real-time-infinite-avatars)  
   标签：评分：9.0/10、query:fast-gen
   evidence：实时少步长视频生成，解耦并行训练替代顺序蒸馏
8. [GeoFlow: Efficient Driving Video Generation via Geometry-Aligned Priors](/202608/17/2608.12203v1-geoflow-efficient-driving-video-generation-via-geometry-aligned-priors)  
   标签：评分：9.0/10、query:fast-gen
   evidence：直接针对驾驶视频生成的高推理延迟与大量采样步骤问题
9. [HPSD: Hybrid-Policy Self-Distillation for Text-Image-to-Video Diffusion Models](/202608/17/2608.13205v1-hpsd-hybrid-policy-self-distillation-for-text-image-to-video-diffusion-models)  
   标签：评分：9.0/10、query:vd
   evidence：面向文图到视频扩散模型的混合策略自蒸馏
10. [Context-Matched Distillation: Teacher Causality for Autoregressive Video Distillation](/202608/17/2608.13391v1-context-matched-distillation-teacher-causality-for-autoregressive-video-distillation)  
   标签：评分：9.0/10、query:vd
   evidence：面向自回归视频生成的因果少步蒸馏，实现低延迟生成
11. [ForgeWM: Progressive Causal Training for Few-Step Action-Conditioned Video World Models](/202608/17/2608.14022v1-forgewm-progressive-causal-training-for-few-step-action-conditioned-video-world-models)  
   标签：评分：9.0/10、query:vd
   evidence：面向少步视频世界模型的渐进式因果训练与蒸馏

### 速读区论文标签
1. [Towards Adaptive Super-Resolution and Quality Assessment via Test-Time Adaptation](/202608/17/2608.08508v1-towards-adaptive-super-resolution-and-quality-assessment-via-test-time-adaptation)  
   标签：评分：8.0/10、query:video-refine
   evidence：通过测试时自适应实现自适应视频超分与质量评估，增强视频质量
2. [RL-Native Distillation: Exploiting Scored Trajectories for Few-Step Image Generation](/202608/17/2608.09226v1-rl-native-distillation-exploiting-scored-trajectories-for-few-step-image-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：基于RL评分轨迹的少步图像生成知识蒸馏
3. [Revisiting the Current Frame: Physical-Trace-Guided Network Output Correction for Video Restoration](/202608/17/2608.09342v1-revisiting-the-current-frame-physical-trace-guided-network-output-correction-for-video-restoration)  
   标签：评分：8.0/10、query:video-refine
   evidence：模型无关的视频恢复输出校正
4. [AdvFD: Boosting Visual Generation via Adversarial Fr'echet Distance Loss](/202608/17/2608.11205v1-advfd-boosting-visual-generation-via-adversarial-frechet-distance-loss)  
   标签：评分：8.0/10、query:vd
   evidence：基于对抗式Fréchet距离的生成器后训练，面向视觉生成
5. [Generative Semantic Segmentation via an Observable Semantic-Image Interface and Hierarchical Generator Evidence Alignment](/202608/17/2608.11537v1-generative-semantic-segmentation-via-an-observable-semantic-image-interface-and-hierarchical-generator-evidence-alignment)  
   标签：评分：8.0/10、query:fast-gen
   evidence：扩散蒸馏的单步生成器，直接对应生成模型知识蒸馏需求
6. [XYZFlow:Scaling Multi dimensional Shortcut Flows for Efficient Generative Modeling](/202608/17/2608.12276v1-xyzflowscaling-multi-dimensional-shortcut-flows-for-efficient-generative-modeling)  
   标签：评分：8.0/10、query:fast-gen
   evidence：通过捷径流实现高效少步生成，与快速图像生成相关
7. [Aero Realtime: Fully Aligned Input-Output Streams for Low-Latency Streaming Multimodal Generation](/202608/17/2608.08469v1-aero-realtime-fully-aligned-input-output-streams-for-low-latency-streaming-multimodal-generation)  
   标签：评分：7.0/10、query:fast-gen
   evidence：双工流式多模态实时生成，视频音频文本对齐，低延迟
8. [Preserve More Details: Mitigating Content Drift in Real-World Image Super-Resolution](/202608/17/2608.09373v1-preserve-more-details-mitigating-content-drift-in-real-world-image-super-resolution)  
   标签：评分：7.0/10、query:video-refine
   evidence：面向真实图像超分的一步扩散模型，通过双路径细节条件缓解内容漂移，可支撑生成视频的后处理增强与超分
9. [Imaginative Generative AI: Crossing the Entropy Wall into Worlds Beyond Imitation](/202608/17/2608.09385v1-imaginative-generative-ai-crossing-the-entropy-wall-into-worlds-beyond-imitation)  
   标签：评分：7.0/10、query:vd
   evidence：基于谱熵的生成模型多样性增强
10. [Imaginative Generative AI: Crossing the Entropy Wall into Worlds Beyond Imitation](/202608/17/2608.09385v2-imaginative-generative-ai-crossing-the-entropy-wall-into-worlds-beyond-imitation)  
   标签：评分：7.0/10、query:vd
   evidence：基于谱熵的生成模型多样性增强
11. [From Synthesis to Removal: Physics-Grounded Reflection Simulation and Diffusion-Based Video Dereflection](/202608/17/2608.11562v1-from-synthesis-to-removal-physics-grounded-reflection-simulation-and-diffusion-based-video-dereflection)  
   标签：评分：6.0/10、query:video-refine
   evidence：基于扩散的视频去反射，用于去除伪影并增强视觉质量
12. [QUASAR: Lowering the Loss Floor of Quantization-Aware Training with Loss-Aware Reconstruction](/202608/17/2608.13966v1-quasar-lowering-the-loss-floor-of-quantization-aware-training-with-loss-aware-reconstruction)  
   标签：评分：6.0/10、query:fast-gen
   evidence：量化感知训练支持低精度高效推理
13. [CRAFT: Constrained Reward via Attention Fine-Tuning for Subject Personalization without Composed Targets](/202608/17/2608.14403v1-craft-constrained-reward-via-attention-fine-tuning-for-subject-personalization-without-composed-targets)  
   标签：评分：6.0/10、query:vd
   evidence：基于注意力微调的多模态扩散Transformer后训练


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
