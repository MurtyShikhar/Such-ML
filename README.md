# Such-ML
Reading group and collection of ML/NLP resources.

## Reading Group Sessions
### Session 1: SeqGAN
Yu, Lantao, et al. "SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient." AAAI. 2017     
Paper: https://arxiv.org/pdf/1609.05473.pdf      
Slides: http://lantaoyu.com/files/2017-02-07-aaai-seqgan.pdf       

#### Preliminary Readings: 
* Policy Gradients: http://karpathy.github.io/2016/05/31/rl/
* GANs Seminal Paper: https://arxiv.org/pdf/1406.2661.pdf

#### Key Takeaways:
* Cool way to apply GANs to sequential data
* MC Search to estimate reward at each step of token generation
* The evaluation using an Oracle model is really neat

#### Implementations:
* PyTorch: https://github.com/suragnair/seqGAN
* Tensorflow: https://github.com/LantaoYu/SeqGAN

### Session 2: Optimization Methods
Léon Bottou, Frank E. Curtis, Jorge Nocedal. "Optimization Methods for Large-Scale Machine Learning." stat.ML 2017     
Paper: https://arxiv.org/abs/1606.04838         

#### Key Takeaways:
* SGD and Mini-Batch are equivalent, Mini-Batch is suited for parallelization

## Latest interesting papers
### ICML (2017)
* Decoupled Neural Interfaces using Synthetic Gradients
* Meta networks 
* Online and Linear-Time Attention by Enforcing Monotonic Alignments
* Wasserstein GAN
* Sequence Tutor: Conservative Fine-Tuning of Sequence Generation Models with KL-control
* Deriving Neural Architectures from Sequence and Graph Kernels
* Learning to Discover Cross-Domain Relations with Generative Adversarial Networks
* Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks
* Understanding Black-box Predictions via Influence Functions
* Delta Networks for Optimized Recurrent Network Computation
* Neural Audio Synthesis of Musical Notes with WaveNet Autoencoders
* Discovering Discrete Latent Topics with Neural Variational Inference
* Image-to-Markup Generation with Coarse-to-Fine Attention
* Toward Controlled Generation of Text
* Learning Continuous Semantic Representations of Symbolic Expressions
* State-Frequency Memory Recurrent Neural Networks
* Language Modeling with Gated Convolutional Networks
* Convolutional Sequence to Sequence Learning
* End-to-End Learning for Structured Prediction Energy Networks

