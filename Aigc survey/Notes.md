## History
* Chatgpt: Optimizing language models for dialogue,” Nov. 2022.
* RLHF: arXiv:2203.02155
* stable diffusion: arXiv:2112.10752  
* HMMs: [20]
* GMMs: [21]
* RNNs: [23]
* GANs: [29]
* the transformer architecture: [32], ViT[35], SwinTrans[36]
* CLIP: [37]
* few-shot prompting: [38]
## Foundation Model
### Transformer
* self-attention mechanism
* encoder & decoder
* multi-head attention
* feed-forward neural network  
### Pre-trained Language Models
* autoregressive language modeling and masked language modeling [41]
* BERT [42] and RoBERTa [43]
* XL-Net [44]
* GPT-3 [9] and OPT [45]
* Different from masked language models, autoregressive models are more suitable for generative tasks.

### Reinforcement Learning from Human Feedback(RLHF)[48]
* the whole pipeline of RLHF includes the following three steps: pre-training, reward learning, and fine-tuning with reinforcement learning
* ELO [47]
* KL
* Constitutional AI [50], RLAIF

## Unimodel Models

### Generative Language Models
* Generally, current state-of-the-art pre-trained language models could be categorized as masked language models (encoders), autoregressive language models (decoders) and encoder-decoder language models
#### Decoder Models. 
* One of the most prominent examples of autoregressive decoder-based language models is GPT[61]
* LayerNorm [63] with RSNorm
#### Encoder-Decoder Models
* Text-to-Text Transfer Transformer (T5) [56]
* Switch Transformer [67]
* MoE routing algorithm
* ExT5 [68]
* BART [34]

### Vision Generative Models
#### GAN
#### VAE
#### Flow
#### Diffusion
* The Generative Diffusion Model (GDM) is a cutting-edge class of generative models based on probability, which demonstrates state-of-the-art results in the field of computer vision.
* It works by progressively corrupting data with multiple-level noise perturbations and then learning to reverse this process for sample generation.
* DDPM [115]
* core-based generative models (SGMs)
* NCSN [31]
* Score SDE [116]
* knowledge distillation
* Mixed Modeling

## Multimodal Models