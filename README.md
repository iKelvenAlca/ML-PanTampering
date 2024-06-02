# ML-PanTamperingProjeto de Detecção de Manipulação em Cartão PAN
## Objetivo
Este projeto visa detectar manipulação em imagens de cartões PAN (Permanent Account Number) usando técnicas de processamento de imagem e análise estrutural.

## Bibliotecas Utilizadas
skimage.metrics: para calcular a similaridade estrutural entre as imagens.
imutils: para operações de processamento de imagem.
cv2 (OpenCV): para manipulação de imagem.
PIL: para trabalhar com imagens no formato PIL.
requests: para baixar as imagens da web.

# Passos do Projeto
Baixar as Imagens

Baixamos uma imagem original e uma imagem alterada para detecção de manipulação.
Formato e Tamanho das Imagens

Verificamos o formato e tamanho das imagens original e alterada.
Conversão de Formato e Redimensionamento

Convertemos as imagens para o formato desejado e as redimensionamos para um tamanho específico.
Conversão para Escala de Cinza

Convertemos as imagens coloridas para escala de cinza para facilitar a comparação.
Cálculo da Similaridade Estrutural (SSIM)

Calculamos a similaridade estrutural entre as imagens para identificar a presença de manipulação.
Detecção de Diferenças

Calculamos o limite e o contorno das diferenças entre as imagens para visualização.

# Resultados
O projeto fornece uma pontuação de similaridade estrutural (SSIM) entre as imagens e destaca as áreas onde foram detectadas diferenças significativas, indicando possíveis manipulações.
