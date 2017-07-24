# Such-ML
Reading group and collection of ML/NLP resources.

## Reading Group Sessions
### Session 1: SeqGAN
Yu, Lantao, et al. "SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient." AAAI. 2017     
Paper Link: https://arxiv.org/pdf/1609.05473.pdf      
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
