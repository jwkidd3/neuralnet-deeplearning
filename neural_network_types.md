# Guide to Neural Network Types

## Feedforward Neural Networks (FNN)
**What they are:** Basic networks where data flows in one direction from input to output  
**Best for:** Simple classification, regression tasks  
**Think of it as:** "Assembly line - data goes straight through"  
**Example uses:** Iris classification, basic pattern recognition

## Convolutional Neural Networks (CNN)
**What they are:** Networks designed for grid-like data using convolutional layers  
**Best for:** Images, computer vision tasks  
**Think of it as:** "Smart image scanner that finds patterns"  
**Example uses:** Image classification, object detection, medical imaging

## Recurrent Neural Networks (RNN)
**What they are:** Networks with loops that can remember previous inputs  
**Best for:** Sequential data with temporal dependencies  
**Think of it as:** "Reading with memory of what came before"  
**Example uses:** Language modeling, time series prediction

## Long Short-Term Memory (LSTM)
**What they are:** Advanced RNNs that solve the vanishing gradient problem  
**Best for:** Long sequences where distant context matters  
**Think of it as:** "Smart memory that decides what to remember/forget"  
**Example uses:** Machine translation, speech recognition

## Gated Recurrent Unit (GRU)
**What they are:** Simplified version of LSTM with fewer parameters  
**Best for:** Sequential tasks where you want efficiency  
**Think of it as:** "LSTM's simpler cousin"  
**Example uses:** Text generation, sentiment analysis

## Transformer Networks
**What they are:** Attention-based networks that process sequences in parallel  
**Best for:** Natural language processing, large-scale text tasks  
**Think of it as:** "Paying attention to all parts simultaneously"  
**Example uses:** GPT, BERT, machine translation

## Autoencoders
**What they are:** Networks that compress input and then reconstruct it  
**Best for:** Dimensionality reduction, anomaly detection, denoising  
**Think of it as:** "Learning to compress and uncompress perfectly"  
**Example uses:** Image denoising, feature extraction, data compression

## Generative Adversarial Networks (GAN)
**What they are:** Two networks competing - one generates, one discriminates  
**Best for:** Creating realistic synthetic data  
**Think of it as:** "Forger vs detective in endless competition"  
**Example uses:** Image generation, data augmentation, style transfer

## Variational Autoencoders (VAE)
**What they are:** Probabilistic autoencoders that learn distributions  
**Best for:** Generating new samples similar to training data  
**Think of it as:** "Learning the recipe for making similar data"  
**Example uses:** Image generation, data synthesis

## Residual Networks (ResNet)
**What they are:** Very deep networks with skip connections  
**Best for:** When you need very deep networks without vanishing gradients  
**Think of it as:** "Highways that let information skip traffic jams"  
**Example uses:** Very deep image classification, feature extraction

## U-Net
**What they are:** Encoder-decoder with skip connections for precise localization  
**Best for:** Tasks requiring pixel-level predictions  
**Think of it as:** "Zooming out then zooming back in with perfect memory"  
**Example uses:** Medical image segmentation, semantic segmentation

## Graph Neural Networks (GNN)
**What they are:** Networks that operate on graph-structured data  
**Best for:** Data with complex relationships and connections  
**Think of it as:** "Understanding social networks and connections"  
**Example uses:** Social network analysis, molecular property prediction

---

**Choosing the right type:** Pick based on your data structure and task:
- **Tabular data** → Feedforward
- **Images** → CNN
- **Text/sequences** → RNN/LSTM/Transformer
- **Generate new data** → GAN/VAE
- **Very deep networks** → ResNet
- **Graphs/networks** → GNN