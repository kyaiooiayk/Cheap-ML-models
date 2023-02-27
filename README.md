# Cheap-ML-models
*A list of methods/resources/links on how to optimise training, inference and throughput of expensive ML models.*
***

## Methods
- **Pruning** allows you to remove unnecessary weights by zeroing them out of your model network. 
- **Quantisation** allows you to reduce the computation complexity of a model by reducing the precision of the weight’s representation. 
- **Distillation/Teacher-student** will force a smaller neural network to learn the objectives of a larger neural network.
- [ONNX Runtime](https://onnxruntime.ai/) was designed with a focus on performance and scalability in order to support heavy workloads in high-scale production scenarios. 
***

## Articles
- [2020 | Efficient Transformers: A Survey](https://arxiv.org/abs/2009.06732)
- [2022 | Cramming: Training a Language Model on a Single GPU in One Day](https://arxiv.org/abs/2212.14034) | In this paper, the researchers trained a masked language model / encoder-style LLM (here: BERT) for 24h on a single GPU. For comparison, the original 2018 BERT paper trained it on 16 TPUs for four days. An interesting insight is that while smaller models have higher throughput, smaller models also learn less efficiently. Thus, larger models do not require more training time to reach a specific predictive performance threshold.
- [2022 | FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)
- [2023 | A Survey on Efficient Training of Transformers](https://arxiv.org/abs/2302.01107)
***
