# Lab 10: Attention Mechanisms

## Description

This lab explores how attention mechanisms allow neural networks to focus on relevant information rather than compressing an entire sequence into a single fixed-size representation.

Using NumPy, the lab implements scaled dot-product attention and demonstrates how queries, keys, and values work together to retrieve and combine information.

## Lab Exercises

1. **Scaled Dot-Product Attention:** Implement attention score calculation, softmax normalization, and weighted value aggregation.
2. **Attention-Based Retrieval:** Explore how different queries influence attention weights and retrieved outputs.
3. **Attention Scaling:** Investigate why attention scores are divided by the square root of the key dimension.
4. **Attention vs. Bottleneck:** Compare attention-based retrieval with a fixed-size summary as sequence length increases.
5. **Self-Attention:** Implement self-attention where queries, keys, and values come from the same sequence.

## Assessment

- **Causal Masking:** Implement a lower-triangular mask that prevents positions from attending to future tokens.
- **Masked vs. Unmasked Attention:** Compare the number of visible keys and self-attention weights with and without causal masking.

## Learning Outcomes

By completing this lab, students gain practical experience implementing attention mechanisms, understanding information retrieval, exploring self-attention, and applying causal masking used in autoregressive transformer models.

**Tools:** Python, NumPy, Matplotlib.
