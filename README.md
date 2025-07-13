# System2-Reasoning-with-LLMs
Advanced AI course notebooks, exploring modern techniques in symbolic regression, neuro-symbolic AI, reinforcement learning for LLMs, and agent-based systems.

### 1. [Symbolic Regression](01_Symbolic_Regression/)

This project implements two methods for symbolic regression: the neural network-based Equation Learner (EQL) and a Seq2Seq Transformer that translates numerical data into mathematical expressions.

### 2. [Neuro-Symbolic Question Answering](02_Neuro-Symbolic_QA/)

This project builds a neuro-symbolic system for visual question answering, using a Seq2Seq model to translate natural language questions into executable programs. Reinforcement Learning is used to furthur improve the accuracy.

### 3. [Inference-Time Scaling for Enhanced Reasoning](03_Inference_Time_Scaling/)

This project investigates inference-time techniques to improve LLM mathematical reasoning without retraining. It implements and benchmarks methods ranging from Chain-of-Thought and Self-Refinement to advanced search algorithms like Best-of-N, Beam Search, and Tree of Thoughts.

### 4. [RL Post-Training for Enhanced Reasoning](04_RL_Post_Training_for_LLMs/)

This project enhances an LLM's reasoning by post-training it with Reinforcement Learning after an initial Supervised Fine-Tuning (SFT) stage. It implements Group Relative Policy Optimization (GRPO) to improve the model's performance on mathematical tasks.

### 5. [GraphRAG for Query-Focused Summarization](05_Graph_RAG/)

This project implements the GraphRAG pipeline to answer global questions over a text corpus by first constructing a knowledge graph from documents. It then uses the Leiden algorithm for community detection and synthesizes a final, comprehensive answer from community-level summaries.

### 6. [Multimodal LLM Agent for Visual Reasoning](06_LLM_Agent/)

This project develops a multimodal agent for visual Q&A by integrating an LLM with classic (OpenCV) and deep learning (SAM) vision tools. An ablation study is performed to evaluate how each component contributes to the agent's reasoning process.
