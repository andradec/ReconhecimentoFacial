# 🧠 Projetos de Deep Learning e LLM

Este repositório contém dois projetos focados em **Deep Learning**, **Computer Vision** e **LLMs**, utilizando **TensorFlow**, **OpenCV** e integração com **Modelos de Linguagem**.

---

# 📌 Projeto 1 — Detecção de Faces com Deep Learning (TensorFlow)

## 📖 Descrição

Este projeto implementa um modelo de **Deep Learning** para **detecção de múltiplas faces em imagens** utilizando **TensorFlow/Keras**.

O modelo é treinado para prever **bounding boxes** de faces humanas em imagens em escala de cinza.

O projeto também compara **dois modelos CNN diferentes** para avaliar desempenho e precisão.

---

## 🚀 Tecnologias Utilizadas

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 🧠 Arquitetura do Projeto

### Modelo 1

CNN com:

- Conv2D
- MaxPooling
- GlobalAveragePooling
- Dense Layers
- Função de ativação LeakyReLU

### Modelo 2

CNN otimizada com:

- Conv2D
- Dropout
- BatchNormalization
- MaxPooling
- GlobalAveragePooling

---

## 📂 Estrutura do Pipeline

### 1. Carregamento dos Dados

- Dataset de imagens com bounding boxes
- Arquivo CSV com coordenadas das faces

### 2. Pré-processamento

- Redimensionamento das imagens (128x128)
- Normalização dos dados
- Conversão para escala de cinza

### 3. Treinamento

- Divisão treino/teste
- Treinamento dos dois modelos

### 4. Avaliação

- Accuracy
- Loss
- Mean Absolute Error

### 5. Comparação dos Modelos

- Gráfico comparativo
- Visualização de bounding boxes

---

## 📊 Métricas Utilizadas

- Accuracy
- Loss
- Precision
- Mean Absolute Error (MAE)

---

## 📈 Resultados

O projeto compara dois modelos:

- Modelo 1 — CNN simples
- Modelo 2 — CNN com regularização

Resultados exibidos:

- Gráfico de perda
- Gráfico de acurácia
- Comparação entre modelos

---

## ▶️ Como Executar

### 1. Clonar repositório

```bash
git clone https://github.com/seu-repositorio
cd projeto-face-detection
```

### 2. Instalar dependências

```bash
pip install tensorflow opencv-python numpy pandas matplotlib scikit-learn
```

### 3. Executar notebook

Executar no:

- Google Colab
- Jupyter Notebook

---

## 📸 Exemplo de Resultado

O modelo detecta múltiplas faces:

- Bounding boxes
- Localização das faces

---

## 🎯 Objetivo do Projeto

- Aprender Deep Learning
- Trabalhar com detecção de objetos
- Comparar arquiteturas CNN
- Treinar modelos customizados

---

# 📌 Projeto 2 — Análise de Vídeo com Deep Learning + LLM

## 📖 Descrição

Este projeto implementa um pipeline completo de **análise inteligente de vídeo**, combinando:

- Deep Learning
- Detecção de objetos (YOLO)
- CNN para classificação
- LLM para descrição automática

O sistema:

1. Extrai frames do vídeo
2. Detecta objetos
3. Classifica frames
4. Gera descrições usando LLM
5. Permite perguntas sobre o vídeo

---

## 🚀 Tecnologias Utilizadas

- Python
- TensorFlow
- OpenCV
- MoviePy
- YOLOv3
- OpenAI API
- Google Colab
- NumPy

---

## 🧠 Arquitetura do Pipeline

### 1. Extração de Frames

- Leitura de vídeo
- Conversão para frames
- Redimensionamento

### 2. Modelo CNN

- Conv2D
- MaxPooling
- Flatten
- Dense

### 3. Detecção de Objetos

- YOLOv3
- OpenCV DNN

### 4. Integração com LLM

- Geração de descrições
- Análise semântica

### 5. Sistema de Perguntas

- Perguntas sobre o vídeo
- Respostas inteligentes

---

## 🔁 Pipeline Completo

```
Vídeo → Frames → CNN → YOLO → LLM → Descrição → Perguntas
```

---

## ▶️ Como Executar

### 1. Instalar dependências

```bash
pip install tensorflow
pip install opencv-python
pip install moviepy
pip install numpy
pip install openai
```

---

### 2. Baixar arquivos YOLO

Necessário:

- yolov3.weights
- yolov3.cfg
- coco.names

---

### 3. Executar notebook

Executar no:

- Google Colab
- Jupyter Notebook

---

## 💡 Funcionalidades

- Detecção de objetos
- Classificação de frames
- Descrição automática
- Perguntas sobre vídeo

---

## 🎯 Objetivo do Projeto

- Construir pipeline de visão computacional
- Integrar Deep Learning com LLM
- Criar sistema inteligente de vídeo

---

# 📊 Comparação dos Projetos

| Projeto | Área | Tecnologias |
|---------|------|-------------|
| Detecção de Faces | Computer Vision | TensorFlow, CNN |
| Análise de Vídeo | Vision + LLM | TensorFlow, YOLO, LLM |

---

# 🚀 Possíveis Melhorias

- Treinar com datasets maiores
- Utilizar modelos pré-treinados
- Implementar API REST
- Deploy em Cloud
- Interface Web

---

# 👨‍💻 Autor

Projeto desenvolvido para estudos em:

- Deep Learning
- Computer Vision
- LLMs

---

# ⭐ Objetivo

Demonstrar conhecimento em:

- Deep Learning
- TensorFlow
- LLMs
- Computer Vision

---

# 📜 Licença

MIT License

---

# 🔥 Contato

Se este projeto foi útil, deixe uma ⭐ no repositório.

---

