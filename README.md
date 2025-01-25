# Abstract
The rapid evolution of generative models, such as GANs and diffusion models, has significantly enhanced the realism of synthetic and manipulated images, posing critical challenges in detecting image authenticity. This study addresses these challenges by proposing a novel weakly-supervised framework for detecting and localizing manipulated image regions without requiring pixel-level annotations. The approach integrates CNN-based and Transformer-based architectures to leverage local and global features, enhancing robustness and generalization across diverse manipulation scenarios. By employing a multi-label discrepancy-aware knowledge distillation strategy and adversarial learning, the model captures subtle manipulation cues and adapts to unseen generative techniques. Extensive experiments demonstrate the effectiveness of the framework in accurately identifying real, partially fake, and fully fake images while localizing manipulated regions with high precision. The proposed method establishes a scalable and practical solution for media forensics in real-world applications, where the diversity and complexity of generative methods continuously grow.

# Model architecture
![model_architecture](/images/model_architecture.png)

# Experiments
![experiment](/images/experiment.png)