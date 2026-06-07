<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-29 ~ 2026-06-07
- 运行时间：2026-06-07 07:27:13 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：6
- 速读区：7

### 今日简报（AI）
今日推荐13篇论文，精读6篇，聚焦视频生成与模型蒸馏两大方向，涵盖稀疏相机条件生成与少步蒸馏量化。  
最值得关注的是《CamGeo》融合3D几何先验实现稀疏相机控制，以及《Why Are DMD Students Lazy?》揭示蒸馏中的复制行为缺陷。  
建议普通读者优先精读这两篇，理解几何先验如何提升视频生成一致性，以及避免蒸馏模型“偷懒”复制的设计原则。
- 详情：[/20260529-20260607/README](/20260529-20260607/README)

### 精读区论文标签
1. [CamGeo: Sparse Camera-Conditioned Image-to-Video Generation with 3D Geometry Priors](/20260529-20260607/2605.30895v2-camgeo-sparse-camera-conditioned-image-to-video-generation-with-3d-geometry-priors)  
   标签：评分：9.0/10、query:vd
   evidence：通过仅训练蒸馏，将3D几何知识从视频到3D模型蒸馏到视频扩散骨干中
2. [Collaborative Few-Step Distillation and Low-Bit Quantization for Wan2.2 Dual-Expert Video Diffusion Models](/20260529-20260607/2606.00658v1-collaborative-few-step-distillation-and-low-bit-quantization-for-wan22-dual-expert-video-diffusion-models)  
   标签：评分：9.0/10、query:vd
   evidence：视频扩散模型的少步蒸馏方法
3. [Qwen-Image-Flash: Beyond Objective Design](/20260529-20260607/2606.03746v1-qwen-image-flash-beyond-objective-design)  
   标签：评分：9.0/10、query:vd
   evidence：面向图像生成的少步蒸馏配方提升多样性
4. [AAD-1: Asymmetric Adversarial Distillation for One-Step Autoregressive Video Generation](/20260529-20260607/2606.03972v1-aad-1-asymmetric-adversarial-distillation-for-one-step-autoregressive-video-generation)  
   标签：评分：9.0/10、query:vd
   evidence：直接通过对抗蒸馏实现一步视频生成，缓解运动崩溃
5. [AAD-1: Asymmetric Adversarial Distillation for One-Step Autoregressive Video Generation](/20260529-20260607/2606.03972v2-aad-1-asymmetric-adversarial-distillation-for-one-step-autoregressive-video-generation)  
   标签：评分：9.0/10、query:vd
   evidence：一步视频生成的非对称对抗蒸馏改善多样性并避免运动崩溃
6. [DSA: Dynamic Step Allocation for Fast Autoregressive Video Generation](/20260529-20260607/2606.04432v1-dsa-dynamic-step-allocation-for-fast-autoregressive-video-generation)  
   标签：评分：9.0/10、query:vd
   evidence：基于蒸馏的少步视频扩散生成

### 速读区论文标签
1. [CamGeo: Sparse Camera-Conditioned Image-to-Video Generation with 3D Geometry Priors](/20260529-20260607/2605.30895v1-camgeo-sparse-camera-conditioned-image-to-video-generation-with-3d-geometry-priors)  
   标签：评分：8.0/10、query:vd
   evidence：采用训练阶段蒸馏策略将几何知识注入视频扩散模型
2. [Restoring Initial Noise Sensitivity in Text-to-Image Distillation via Geometric Alignment](/20260529-20260607/2606.01651v1-restoring-initial-noise-sensitivity-in-text-to-image-distillation-via-geometric-alignment)  
   标签：评分：8.0/10、query:vd
   evidence：针对文本到图像生成的蒸馏方法；改善噪声敏感性以增强控制能力
3. [Why Are DMD Students Lazy? Understanding the Copying Behavior in Few-Step Distillation](/20260529-20260607/2606.02237v1-why-are-dmd-students-lazy-understanding-the-copying-behavior-in-few-step-distillation)  
   标签：评分：8.0/10、query:vd
   evidence：研究少步蒸馏（DMD）中的复制行为，该行为限制多样性
4. [Knowledge Distillation for Visual Autoregressive Models](/20260529-20260607/2606.06078v1-knowledge-distillation-for-visual-autoregressive-models)  
   标签：评分：8.0/10、query:vd
   evidence：面向视觉自回归图像生成多样性的知识蒸馏
5. [Physics in 2-Steps: Locking Motion Priors Before Visual Refinement Erases Them](/20260529-20260607/2606.06361v1-physics-in-2-steps-locking-motion-priors-before-visual-refinement-erases-them)  
   标签：评分：8.0/10、query:vd
   evidence：研究两步视频扩散以保持运动先验，提升物理一致性
6. [LVSA: Training-Free Sparse Attention for Long Video Diffusion](/20260529-20260607/2605.31057v1-lvsa-training-free-sparse-attention-for-long-video-diffusion)  
   标签：评分：7.0/10、query:vd
   evidence：通过稀疏注意力改进长视频扩散的运动动态；解决视频冻结重复问题
7. [DecMem: Towards Minute-Long Consistent World Generation with Decoupled Memory](/20260529-20260607/2605.31336v1-decmem-towards-minute-long-consistent-world-generation-with-decoupled-memory)  
   标签：评分：6.0/10、query:vd
   evidence：通过解耦记忆改进长视频生成的一致性和运动动态


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
