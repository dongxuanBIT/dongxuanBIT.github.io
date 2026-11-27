---
title: "[C31] HiPrompt-JSCC: Hierarchical Prompt-Aided Joint Source-Channel Coding for Task-Adaptive Semantic Communication"
collection: publications
category: conferences
permalink: /publication/2026-10-30-ICICN-HiPrompt-JSCC Hierarchical Prompt-Aided Joint Source-Channel Coding for Task-Adaptive Semantic Communication-number-31
excerpt: 'This paper presents HiPrompt-JSCC, a task-adaptation framework that retains a frozen Swin-based JSCC backbone and optimizes a task-specific prompt adapter.'
date: 2026-10-30
venue: '2026 14th International Conference on Information and Communication Networks (ICICN)'
paperurl: 'http://dongxuanBIT.github.io/files/C31_HiPrompt-JSCC_Hierarchical_Prompt-Aided_Joint_Source-Channel_Coding_for_Task-Adaptive_Semantic_Communication.pdf'
citation: 'S. Zhang, B. Chen, D. He, X. Xie, H. Tan and Y. Zhao, &quot;HiPrompt-JSCC: Hierarchical Prompt-Aided Joint Source-Channel Coding for Task-Adaptive Semantic Communication; in <i>Proc. 2026 14th International Conference on Information and Communication Networks (ICICN)</i>, Xian, China, 2026, pp. 1-6.'
---

Deep joint source-channel coding (JSCC) for images is commonly trained to optimize reconstruction quality, whereas receiver-side applications are evaluated by classification, detection, or segmentation accuracy. This paper presents HiPrompt-JSCC, a task-adaptation framework that retains a frozen Swin-based JSCC backbone and optimizes a task-specific prompt adapter. The adapter fuses visual features with a learned task embedding and supplies stage-dependent key/value prompts to window attention. At 1 dB SNR under AWGN, HiPrompt-JSCC improves ImageNet100 top-1 accuracy by 7.82 percentage points over the pretrained reconstruction-oriented SwinJSCC baseline. Across the evaluated COCO operating points, it improves detection AP by 0.48-0.75 and instance-segmentation mask AP by 0.92-1.38. Task adaptation is performed exclusively through transmitter-side encoder prompts; neither the communication backbone nor the JSCC receiver is modified.