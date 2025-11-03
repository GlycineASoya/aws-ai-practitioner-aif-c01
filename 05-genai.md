# Generative AI

## Terminology

1. Transformer-based LLM model - model, understands and generates human-like text
2. Tokens - units of text, the model processes individually. It can be: word, charcter, punctuation, subword, etc.
3. Chunking - practice of breaking down large text, input or output, into small pieces, i.e. chunks. Chunk size (token) is important for a Vector Database.
4. Vertor - a mathematical representation (a series of numbers) of unstructured data, like text, image, video, etc.
5. Embeddings - vector representations that capture their semantic meaning and relationships. The search in the vector database performed against Embeddings, not the Vectors themselves

## Model Types

1. GTP or Generative Pre-trained Transformer - a special case of Transformer-based LLM
2. Dissusion model - model, that is focused on image, audio, text (sometimes) generation, starts the generation process with noise or random data, gradually adding information until a recognizable pattern is obtained
3. Multimodal model - model, that's trained on multiple media types, including text, audio, video, images, and able to interpret and generate these media types
4. Generative Adversarial Networks (GANs) - model, that consists of two neural networks, competing with each other to get the generated content indistinguishable from real content
5. Variational AutoEncoders (VAEs) - model, combines neural network and probabilistic modeling, which allows to be effective in anomaly detection in large time-series data sets
