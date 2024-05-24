# Bingjian（冰鉴）：Towards Personalized Evaluation of Large Language Models with An Anonymous Crowd-Sourcing Platform

This repository contains the code implementation and relevant resources for the research paper titled "Towards Fair and Personalized Benchmarking: An Anonymous Crowd-Sourcing Platform for Large Language Model Evaluation" by Mingyue Cheng et al.

## Paper Abstract

The paper proposes BingJian, a novel crowdsourced evaluation platform for large language models, addressing the limitations of traditional evaluation methods. BingJian introduces a competitive scoring mechanism allowing users to rank models based on performance, supports open evaluation gateways for personalized question submissions, and incorporates personalized evaluation scenarios.

## Repository Structure

- `bingjian/LLMEval/`: Contains the implementation of the BingJian platform (It is not included in this repository and will be updated gradually in the future.)
- `bingjian/LLMEval_Service/`: Contains the implementation of Bingjian terminal interface (It is not included in this repository and will be updated gradually in the future.)
- `data/`: Placeholder for datasets used in the evaluation (It is not included in this repository and will be updated gradually in the future.)
- `README.md`: Placeholder for experimental results and analysis

## Usage

To utilize the BingJian platform code, follow these steps:

1. **Clone Repository**:
   ```bash
   git clone https://github.com/yangjq713/LLMEval_Service.git
   git clone https://github.com/yangjq713/LLMEval.git
   ```

2. **Navigate to Code Directory**:
   ```bash
   cd LLMEval_Service/
   cd LLMEval/
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Main Application**:

   The front end uses nginx to configure the proxy, and then uses python main.py to load it.

   ```bash
   python main.py
   ```

## Additional Information

For more details about the BingJian platform and its functionality, refer to the [original paper](https://arxiv.org/pdf/2403.08305v1).

Cheng, Mingyue, et al. "Towards Personalized Evaluation of Large Language Models with An Anonymous Crowd-Sourcing Platform." Companion Proceedings of the ACM on Web Conference 2024. 2024.

