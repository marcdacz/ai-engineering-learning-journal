# Week 01 – Math Foundations

## Day 1 – Linear Algebra in ML

**Date:** 2025-08-27  

### 1️⃣ Videos
- [3Blue1Brown – Essence of Linear Algebra: Vectors](https://www.youtube.com/watch?v=fNk_zzaMoSs)  
- [StatQuest – Linear Algebra for Machine Learning](https://www.youtube.com/watch?v=kjBOesZCoqc)  

### 2️⃣ Reading / Reference
- [Stanford CS229 Linear Algebra Review (PDF)](https://cs229.stanford.edu/section/cs229-linalg.pdf)  

### 3️⃣ Summary / Key Takeaways
- Vectors and matrices are the fundamental language of ML.  
- ML models = transformations of matrices.  
- Dot product = measure of similarity; Eigenvectors = directions preserved by transformations.  
- Understanding these basics helps you see how neural networks and LLMs process data.  

### 4️⃣ Mini-Project / Coding Task
- Load an image using Python (`PIL` or `matplotlib`).  
- Represent it as a NumPy matrix.  
- Apply a matrix operation (e.g., invert colors or simple brightness adjustment).  
- Commit code to `invert_image.ipynb`.  

### 5️⃣ Q&A / Reflection
**Q1: Why is matrix multiplication essential for neural networks?**  
- Neural networks process multiple inputs through multiple neurons simultaneously.  
- Matrix multiplication efficiently computes weighted sums of inputs for all neurons at once.  
- It allows stacking layers to transform data through the network in a single operation.

**Q2: How do vectors represent input features?**  
- Each input feature (e.g., pixel value, word frequency) is a component of a vector.  
- A vector encodes all features of one sample as a single object, allowing mathematical operations.  
- Collections of vectors form matrices that represent the full dataset.

**Q3: How might this apply to LLM token embeddings?**  
- Each token (word/subword) is represented as a vector in embedding space.  
- Matrix multiplication transforms these embeddings through attention layers and feedforward layers.  
- Enables the model to learn complex relationships between tokens in context.