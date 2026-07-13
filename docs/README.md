<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-13
- 运行时间：2026-07-13 21:48:59 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：8
- 速读区：10

### 今日简报（AI）
1) 今日聚焦视频生成与理解，精读8篇，速读10篇，OPSD-V与Wan-Streamer表现突出。
2) 最值得关注：OPSD-V用on-policy自蒸馏提升少步自回归视频生成质量；Wan-Streamer v0.2实现更高分辨率且延迟不变。
3) 下一步可关注自蒸馏技术对视频生成效率的改善，以及高分辨率流式方法在实时场景中的落地可能。
- 详情：[/202607/13/README](/202607/13/README)

### 精读区论文标签
1. [OPSD-V: On-Policy Self-Distillation for Post-Training Few-Step Autoregressive Video Generators](/202607/13/2607.08766v1-opsd-v-on-policy-self-distillation-for-post-training-few-step-autoregressive-video-generators)  
   标签：评分：10.0/10、query:vd
   evidence：后训练自蒸馏用于少步自回归视频生成器，减少误差积累并改善运动动态
2. [Wan-Streamer v0.2: Higher Resolution, Same Latency](/202607/13/2607.04443v1-wan-streamer-v02-higher-resolution-same-latency)  
   标签：评分：8.0/10、query:fast-gen
   evidence：在单GPU上实现低延迟实时视频生成
3. [FADRA: Frequency-Aware Diffusion with Residual Adaptation for Video Face Restoration](/202607/13/2607.06389v1-fadra-frequency-aware-diffusion-with-residual-adaptation-for-video-face-restoration)  
   标签：评分：8.0/10、query:video-refine
   evidence：利用扩散模型进行视频人脸恢复，用于生成输出后处理
4. [Prompt-Adapter Context Routing for Parameter-Efficient Multi-Shot Long Video Extrapolation](/202607/13/2607.06481v1-prompt-adapter-context-routing-for-parameter-efficient-multi-shot-long-video-extrapolation)  
   标签：评分：8.0/10、query:vd
   evidence：视频扩散模型的参数高效后训练方法
5. [DiffCVE: Diffusion-based Compressed Video Enhancement](/202607/13/2607.07195v1-diffcve-diffusion-based-compressed-video-enhancement)  
   标签：评分：8.0/10、query:video-refine
   evidence：基于扩散的压缩视频增强方法，可应用于生成视频的细化
6. [The Key to Going Linear: Analysis-Driven Transformer Linearization](/202607/13/2607.07706v1-the-key-to-going-linear-analysis-driven-transformer-linearization)  
   标签：评分：8.0/10、query:fast-gen
   evidence：分析并改进Transformer线性化以实现高效注意力，可应用于图像生成
7. [Linear Attention Architectures: Mechanisms, Trade-offs, and Cross-Layer Routing](/202607/13/2607.07953v1-linear-attention-architectures-mechanisms-trade-offs-and-cross-layer-routing)  
   标签：评分：8.0/10、query:fast-gen
   evidence：线性注意力架构的比较研究，可用于高效生成
8. [IB-Flow: Information Bottleneck-Guided CFG Distillation for Few-Step Text-to-Image Generation](/202607/13/2607.09133v1-ib-flow-information-bottleneck-guided-cfg-distillation-for-few-step-text-to-image-generation)  
   标签：评分：8.0/10、query:fast-gen
   evidence：文本到图像生成的少步蒸馏

### 速读区论文标签
1. [Wan-Streamer v0.2: Higher Resolution, Same Latency](/202607/13/2607.04443v3-wan-streamer-v02-higher-resolution-same-latency)  
   标签：评分：7.0/10、query:fast-gen
   evidence：低延迟实时流式音视频交互
2. [Gen4U: Unifying Video Generation and Understanding via Diffusion](/202607/13/2607.06856v1-gen4u-unifying-video-generation-and-understanding-via-diffusion)  
   标签：评分：7.0/10、query:vd
   evidence：通过扩散统一视频生成与理解，处于视频生成主题核心
3. [AnchorPrune: Relevance-Anchored Contextual Expansion for Visual Token Pruning](/202607/13/2607.07033v1-anchorprune-relevance-anchored-contextual-expansion-for-visual-token-pruning)  
   标签：评分：7.0/10、query:fast-gen
   evidence：视觉令牌剪枝方法，可加速大视觉语言模型推理，适用于快速生成
4. [MOSAIC: Adaptive Inter-layer Composition for Efficient Heterogeneous Vision-Language Models](/202607/13/2607.09029v1-mosaic-adaptive-inter-layer-composition-for-efficient-heterogeneous-vision-language-models)  
   标签：评分：7.0/10、query:fast-gen
   evidence：提出自动搜索集成线性和稀疏注意力的高效异构架构，可用于快速图像/视频生成
5. [Quantize the Target, Quantize the Drafter: Efficient Inference with Qwen3.5-4B](/202607/13/2607.04244v1-quantize-the-target-quantize-the-drafter-efficient-inference-with-qwen35-4b)  
   标签：评分：6.0/10、query:fast-gen
   evidence：应用量化感知蒸馏和推测解码实现高效LLM推理，与生成模型加速相关
6. [Flash-BoN: Instant Drafts for Inference-Time Scaling in Diffusion Models](/202607/13/2607.04461v1-flash-bon-instant-drafts-for-inference-time-scaling-in-diffusion-models)  
   标签：评分：6.0/10、query:fast-gen
   evidence：推理时间缩放加速生成；提出即时草稿加速扩散模型
7. [Enhancing Video Physical Consistency via Role-aware Joint Training and Modality-decoupled Denoising](/202607/13/2607.04653v1-enhancing-video-physical-consistency-via-role-aware-joint-training-and-modality-decoupled-denoising)  
   标签：评分：6.0/10、query:vd
   evidence：基于角色感知联合训练和模态解耦去噪增强视频物理一致性
8. [Patch Knowledge Transfer for Efficient AI-Generated Image Quality Assessment](/202607/13/2607.05605v1-patch-knowledge-transfer-for-efficient-ai-generated-image-quality-assessment)  
   标签：评分：6.0/10、query:fast-gen
   evidence：面向AI生成图像质量评估的知识蒸馏方法
9. [Retrieving and Refining Winning Noise Tickets for Diffusion-Based Motion Generation](/202607/13/2607.06843v1-retrieving-and-refining-winning-noise-tickets-for-diffusion-based-motion-generation)  
   标签：评分：6.0/10、query:vd
   evidence：通过噪声检索改善文本-运动对齐，增强运动动态和多样性
10. [Simon-SR: Spatially Adaptive Modulation and Visual Prompt Adaptation for Text-Reinforced Super-Resolution](/202607/13/2607.09351v1-simon-sr-spatially-adaptive-modulation-and-visual-prompt-adaptation-for-text-reinforced-super-resolution)  
   标签：评分：6.0/10、query:video-refine
   evidence：图像超分辨率方法可用于视频精炼


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
