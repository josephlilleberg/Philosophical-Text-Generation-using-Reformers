# Philosophical Text Generation with Reformers*

## Motivation

Text Generation has a lot of commerical as well as creative opportunities. I have previously implement Text Generation with RNNs using TensorFlow. However, I have recently taken an NLP course that uses Trax to implement state of the art architectures including Transformers, Reformers, and Bert. Therefore, I wanted to build my own model to learn text generation in practice with reformers.

## Description

In this project, I downloaded **The Republic** from an online source and extracted the novel text. I used sentencepiece to create my own byte-pair encoding vocabulary of size 320. I then processed the text and trained a Reformer Language Model for 5000 epochs. 

### Sample Generation

*The Republic of Plato. The man is remost highest philosophy of Herodic has been said to have recognised an ancient to the authority of Hellas. The greatest of all knowing that he doubted at Socrates and Plato, is the practicabil*

## Final Thoughts

This project taught me a lot more about transformers and reformers, as well as Trax. This is only the first of many projects I aspire to build with Trax such as chatbots and text summarization. 
