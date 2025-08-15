# Projeto de Redução de Dimensionalidade em Imagem
Projeto para redução de dimensionalidade em imagem - BairesDev - Machine Learning Training - DIO

Este projeto demonstra um exemplo básico de processamento de imagem em Python, focado em converter uma imagem colorida para tons de cinza e, em seguida, binarizá-la. Embora este exemplo não utilize técnicas avançadas de redução de dimensionalidade como PCA ou SVD diretamente neste script, ele serve como um ponto de partida para a manipulação de dados de imagem, que é um passo comum em fluxos de trabalho onde a redução de dimensionalidade pode ser aplicada (por exemplo, em tarefas de reconhecimento de padrões ou compressão).

## Funcionalidades

*   **Download de Imagem:** Baixa uma imagem de teste (Lena.png) para ser utilizada no processamento.
*   **Conversão para Tons de Cinza:** Converte uma imagem colorida para tons de cinza usando a fórmula perceptual.
*   **Binarização:** Converte a imagem em tons de cinza para uma imagem binária baseada em um limite (threshold).

## Pré-requisitos

*   Python 3.6+
*   Biblioteca Pillow (PIL)

## Como executar

1.  **Clone o repositório (ou use em um ambiente como Google Colab):** Se estiver usando este código localmente, clone o repositório. Se estiver no Google Colab, o código fornecido no notebook já baixará a imagem necessária.
2.  **Instale a biblioteca Pillow:**
