# Projeto de Processamento de Vídeo com Detecção e Rastreamento de Objetos

## Visão Geral

Este projeto utiliza a API Ikomia para realizar a detecção e rastreamento de objetos em vídeos. A abordagem emprega o algoritmo YOLOv7 para identificar objetos e o algoritmo ByteTrack para rastrear esses objetos ao longo do vídeo. O objetivo é processar um vídeo para identificar e rastrear pessoas e salvar o vídeo resultante em um novo arquivo.

## Funcionalidades

- **Detecção de Objetos**: Utiliza o YOLOv7 para identificar objetos no vídeo.
- **Rastreamento de Objetos**: Emprega o ByteTrack para rastrear a movimentação de objetos identificados.
- **Processamento de Vídeo**: Processa cada quadro do vídeo para aplicar a detecção e rastreamento.
- **Salvamento do Vídeo**: Cria um novo vídeo com os objetos detectados e rastreados destacados.

## Requisitos

- **Ikomia API**: Biblioteca para processamento de vídeo e aplicação de algoritmos de detecção e rastreamento.
- **OpenCV**: Biblioteca para manipulação e visualização de vídeos.

## Como Utilizar

1. Instale a Ikomia API utilizando o comando:
   ```bash
   !pip install ikomia
2. Coloque o vídeo a ser processado no diretório videos/ e ajuste o nome do arquivo no código.
3. Defina o caminho para o vídeo de saída onde o resultado será salvo.
4. Execute o código em um ambiente compatível com as dependências.
