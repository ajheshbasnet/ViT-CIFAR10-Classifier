# Vision Transformer Classifier

> “An Image Is Worth 16×16 Words: Transformers for Image Recognition at Scale”  
> – Dosovitskiy et al., 2020

This repository implements a **Vision Transformer (ViT)**–style image classifier using PyTorch. We split each input image into `16×16` patches, embed them, prepend a learnable `[CLS]` token, and process through multiple transformer encoder blocks. The final `[CLS]` embedding is fed into an MLP head for classification.

---
