# Leitor LIBRAS

Este projeto utiliza OpenCV, MediaPipe e um modelo Keras para reconhecer sinais de LIBRAS (Língua Brasileira de Sinais) a partir de uma câmera.

## Requisitos

- Python 3.x
- OpenCV
- MediaPipe
- TensorFlow 2.9.1
- Keras

## Instalação

1. Clone o repositório:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    cd leitor_LIBRAS
    ```

2. Instale as dependências:
    ```sh
    pip install opencv-python mediapipe tensorflow keras
    ```

3. Certifique-se de ter o arquivo `keras_model.h5` no diretório do projeto.

## Uso

1. Execute o script principal:
    ```sh
    python main.py
    ```

2. A câmera será ativada e o script começará a detectar sinais de LIBRAS. Uma caixa verde aparecerá ao redor da mão detectada e a letra correspondente será exibida.

## Estrutura do Projeto

- `main.py`: Script principal que captura a imagem da câmera, processa a imagem para detectar a mão e usa o modelo Keras para prever o sinal de LIBRAS.

## Contribuição

Sinta-se à vontade para contribuir com melhorias para este projeto. Faça um fork do repositório, crie uma branch para suas alterações e envie um pull request.

