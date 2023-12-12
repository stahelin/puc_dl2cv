# Advanced Deep Learning for Image Analysis - PUC-Rio
Este repositório contém os materiais e modelos desenvolvidos para a disciplina "Advanced Deep Learning for Image Analysis" da Pontifícia Universidade Católica do Rio de Janeiro (PUC-Rio). O curso foca em técnicas avançadas de aprendizado profundo, com ênfase na análise de imagens e dados de séries temporais.

## Dataset OSCAR L4 OC third-deg
O projeto utiliza o conjunto de dados "OSCAR L4 OC third-deg", uma base global de correntes superficiais oceânicas do projeto "Ocean Surface Current Analyses Real-time (OSCAR)", financiado pela NASA. Esta base de dados oferece informações cruciais sobre as velocidades da camada mista da superfície do oceano, fundamentais para a compreensão das dinâmicas oceânicas. Os dados estão disponíveis em três níveis de qualidade: final, provisório e quase em tempo real (nrt), em arquivos diários no formato NetCDF.

## Modelos testados
Para a previsão e análise das correntes oceânicas, foram testados seis modelos de deep learning:

### 1. ConvLSTM
ConvLSTM é uma arquitetura que combina LSTM com operações convolucionais, aprimorando a captura de dependências espaciais e temporais em dados sequenciais.

### 2. PredRNN
PredRNN aprimora a captura de dependências temporais complexas por meio de camadas recorrentes, ideal para previsões a longo prazo em séries temporais.

### 3. PredRNN+++
Uma versão avançada do PredRNN, projetada para equilibrar complexidade computacional e capacidade de captura de padrões temporais mais profundos.

### 4. MogaNet
MogaNet é um modelo que utiliza mecanismos de atenção e camadas convolucionais, processando dados sequenciais de forma eficiente, sem recorrência.

### 5. Swin-T
Baseado na arquitetura Transformer, Swin-T é adaptado para tarefas de visão computacional, processando imagens e sequências de vídeo eficazmente.

### 6. TAU
TAU é uma arquitetura sem recorrência especializada na extração de características de sequências de imagens, utilizando técnicas avançadas de aprendizado de máquina.

## Uso do OpenSTL
O projeto também incorpora o uso do OpenSTL, uma biblioteca de código aberto para aprendizado espaço-temporal, facilitando a implementação e o teste de modelos complexos em dados de séries temporais.
