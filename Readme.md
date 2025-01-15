# TrackWise: A Next-Generation Intelligent Learning Assistant

**TrackWise** is an advanced educational platform that leverages cutting-edge AI technologies to provide students with personalized learning experiences and precise resource recommendations. This project integrates educational theories with state-of-the-art machine learning models, offering a robust and scalable intelligent tutoring system.

## 🚀 Features

- **Automatic Grading Model**: Combines LSTM and P-Tuning techniques to achieve an impressive 82.13% accuracy in automatic grading.
- **Knowledge Tracing**: Employs KTPromptCast for dynamic student performance prediction, surpassing multiple baseline models.
- **Education-Employment Matching**: Integrates BERT and vertical federated learning for matching educational content with job market demands.
- **Interactive UI**: User-friendly interface built on Vue.js, featuring real-time feedback, dynamic knowledge graphs, and collaborative learning tools.
- **Advanced Recommendations**: Personalized question recommendations using collaborative filtering algorithms.

## 📚 Theoretical Foundations

- **Knowledge Space Theory**: Structures educational content and maps logical relationships for personalized learning paths.
- **Zone of Proximal Development (ZPD)**: Tailors learning content to challenge students appropriately.
- **Constructivism**: Supports active and collaborative learning through interaction-driven designs.

## 🛠️ Technology Stack

- **Frontend**: Vue.js
- **Backend**: Spring Boot
- **Database**: Neo4j for knowledge graph management, integrated with Redis for caching
- **Model Training**: ChatGLM2-6B and LSTM models optimized with P-Tuning
- **Other Tools**: MyBatis Plus for ORM, FlashAttention for efficient model training

## 🧪 Key Components

### 1. Automatic Grading Model
- **LSTM-based neural network**: Handles long text sequences with enhanced memory capabilities.
- **P-Tuning**: Fine-tunes pre-trained language models for grading tasks, ensuring adaptability and high accuracy.

### 2. Knowledge Tracing
- **KTPromptCast**: Converts learning sequences into natural language prompts to enhance model predictions.
- **Evaluation Metrics**: Outperforms baselines in accuracy, precision, and F1 scores.

### 3. Education-Employment Matching
- **Federated Learning**: Ensures privacy-preserving model training across distributed datasets.
- **Vertical Federated Learning**: Aligns education content with job market needs while maintaining data security.

## 📊 Performance Highlights

| Model                  | AUC   | Accuracy | F1 Score | Precision |
|------------------------|-------|----------|----------|-----------|
| KTPromptCast          | 0.77  | 0.80     | 0.82     | 0.78      |
| Automatic Grading      | 82.13% Accuracy |

## 💡 Innovations

1. Fusion of multiple educational theories for scientific foundation.
2. Modular, layered system design ensuring scalability and flexibility.
3. Integration of advanced AI techniques, including RLHF for dynamic example generation.
4. High-performance knowledge tracing models outperforming baselines.

## 🖥️ System Architecture

TrackWise adopts a **three-layered architecture**:
1. **Domain Knowledge Layer**: Builds structured educational content and logic frameworks.
2. **Model Layer**: Implements key models like knowledge tracing and automatic grading.
3. **User Interface Layer**: Delivers interactive and adaptive learning tools.



## 📄 Documentation

For detailed documentation, refer to the [project documentation](./TrackWise_project_documentation.pdf).

