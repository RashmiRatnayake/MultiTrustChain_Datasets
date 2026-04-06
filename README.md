# MultiTrustChain-Datasets

This repository contains the datasets used to evaluate the **MultiTrustChain** framework, a lifecycle-aware, multi-dimensional trust evaluation approach for blockchain data. The datasets span financial, IoT, and supply chain use cases, covering four trust dimensions: data, data source, blockchain, and external. They combine real-world datasets with extended BDT-based data, enriched with domain-specific features and attack scenarios.

## 📦 Release

**First release (MultiTrustChain Datasets v1.0 – Financial, IoT, and Supply Chain Use Cases):**  
https://github.com/RashmiRatnayake/MultiTrustChain_Datasets/releases/tag/v1.0

The datasets are organised by application domain, with three primary use cases:

- Financial  
- IoT  
- Supply Chain  

Each use case folder contains datasets corresponding to the four trust dimensions considered in the framework.

---

## 🧩 Dataset Structure

For each use case, the following four datasets are provided:

### 1. Data Trust Dimension
This dataset is based on real-world, publicly available data and captures intrinsic properties of the observed data (e.g., sensor readings, transactions, or supply chain events). It serves as the foundation for evaluating data-level trustworthiness.

### 2. Data Source Trust Dimension
This dataset is derived from the Blockchain Data Trust (BDT) dataset and extended with domain-specific attributes. It models the trustworthiness of the data origin or source, including characteristics such as reliability, certification, identity, and behavioural inconsistencies. Domain-specific attack patterns are also incorporated.

### 3. Blockchain/System Trust Dimension
This dataset is based on the BDT dataset and enriched with blockchain-related features to capture trust in the underlying system. It includes aspects such as consensus behaviour, validation consistency, and network-level anomalies. Use-case-specific adversarial conditions are introduced to simulate realistic blockchain environments.

### 4. External / Cross-Chain Trust Dimension
This dataset extends the BDT dataset to represent trust from external entities such as oracles, cross-chain interactions, and third-party systems. It incorporates indirect trust propagation mechanisms and cross-system inconsistencies, along with attack patterns relevant to each application domain.

---

## ⚙️ Dataset Generation and Enhancements

- The data trust dimension is constructed using real-world datasets to ensure realism.
- The remaining three dimensions are derived from the BDT dataset and extended with:
  - Domain-specific features  
  - Use-case-driven data distributions  
  - Literature-informed trust indicators  
  - Realistic attack scenarios (e.g., anomalies, inconsistencies, adversarial behaviour)  

This design enables controlled evaluation of multi-dimensional trust, supports realistic simulation of adversarial conditions, and ensures consistency across different application domains.

---

## 🎯 Purpose

These datasets are intended to support:
- Evaluation of multi-dimensional trust models  
- Benchmarking of learning-based trust aggregation approaches  
- Analysis of trust under adversarial conditions  
- Research in blockchain data trust across IoT, supply chain, and financial systems  
