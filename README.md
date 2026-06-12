# A Lightweight Hybrid Multilayer Perceptron Model for Deployable Dark Pattern Detection in E-Commerce Websites

## Abstract

This paper proposes a lightweight hybrid Multi-Layer Perceptron (MLP) framework for automated dark pattern detection in e-commerce interfaces under practical deployment constraints. The proposed model combines Term Frequency-Inverse Document Frequency (TF-IDF) representations with 51 psycholinguistic features engineered from urgency, scarcity, social proof, typography, sentiment, and structural cues to capture manipulative linguistic patterns in interface text.

While transformer-based models such as BERT and RoBERTa achieve state-of-the-art accuracy on dark pattern detection benchmarks, their computational and deployment requirements limit practical use in resource-constrained environments. The proposed hybrid MLP achieves competitive performance while maintaining a substantially smaller model size and lower computational cost.

Experiments conducted on the Waseda E-Commerce Dark Pattern Corpus demonstrate that the proposed approach achieves 96.35% ± 1.69% five-fold cross-validation accuracy with an F1-score of 0.963. The model contains only 286,400 parameters, occupies 6.65 MB of storage, and achieves a mean inference latency of 10.9 ms, enabling efficient client-side and serverless deployment.

This work also presents a deployment-oriented benchmark including latency profiling, throughput analysis, and memory footprint evaluation, highlighting the practicality of lightweight neural architectures for real-world dark pattern detection systems.

**Keywords:** Dark Patterns, E-Commerce, Text Classification, Lightweight Neural Networks, Hybrid Feature Engineering, Deployment Benchmark

---

**Authors**

Md. Mustakim Mia, Alamgir Hosain, Abdul Jalil Tamjid, Md. Sazzad Hossain

Department of Computer Science and Engineering
Mawlana Bhashani Science and Technology University, Tangail-1902, Bangladesh

