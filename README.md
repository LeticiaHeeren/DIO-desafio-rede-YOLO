# Detecção de Carros com YOLOv8

Este projeto implementa um sistema de detecção de carros utilizando a rede neural YOLOv8. O modelo é treinado e executado no Google Colab, utilizando um dataset do Kaggle.

# O que tem no projeto?

*   Download de um dataset de carros via Kaggle.
*   Uso do modelo YOLOv8 pré-treinado para detecção.
*   Processamento de imagens com marcação dos carros detectados.
*   Exibição dos resultados.<br>

# Bibliotecas Utilizadas 

* ultralytics – Para carregar e rodar o modelo YOLOv8.
* cv2 (OpenCV) – Para manipulação de imagens.
* matplotlib – Para exibir os resultados.
* torch – Para suporte ao modelo YOLO.
* kaggle – Para baixar o dataset.

# Exemplo de Saída

Ao executar o código, você verá as imagens analisadas com caixas destacando os carros detectados, além da porcentagem de confiança da detecção.<br><br>
<div align="left">

![exemplo 2](https://github.com/user-attachments/assets/b18440bb-0b1d-48ff-9253-33663a6cac94) ![exemplo 3](https://github.com/user-attachments/assets/47b51e91-a045-4440-8c64-4f201ff2d9a7)   
![exemplo 1](https://github.com/user-attachments/assets/d5ade974-91e5-4186-a5fc-b86276224c83)

</div>


# Configuração do Ambiente

* Instale a biblioteca do Kaggle:
> !pip install -q kaggle

* Faça upload do arquivo kaggle.json para acessar o dataset:
> from google.colab import files<br>
> files.upload()

* Configure as permissões do arquivo:

> !mkdir -p ~/.kaggle<br>
> !mv kaggle.json ~/.kaggle/<br>
> !chmod 600 ~/.kaggle/kaggle.json
