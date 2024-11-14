# Verificação Facial Simples com DeepFace

Este repositório demonstra como usar a biblioteca [DeepFace](https://github.com/serengil/deepface) para realizar a verificação facial entre duas imagens. O DeepFace utiliza redes neurais profundas para análise de imagens faciais, e neste exemplo, usaremos o modelo **VGG-Face** para realizar a comparação.

## Pré-requisitos

Para rodar este projeto, você precisa de:

- Python 3.x
- [DeepFace](https://github.com/serengil/deepface)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)

### Instalando as dependências

Se você ainda não tiver as dependências instaladas, basta rodar o seguinte comando:

```bash
pip install deepface opencv-python matplotlib
```

## Como Usar
Clone o repositório para o seu computador:

```
git clone https://github.com/seu-usuario/FaceRecognition.git
cd FaceRecognition
```

Adicione as imagens que deseja comparar na pasta ./img/. As imagens devem ser salvas com os nomes beyonce-1.jpg e beyonce-2.jpg ou você pode editar os caminhos das imagens no código.


## Como Funciona
- O script utiliza o **DeepFace** para verificar se duas imagens representam a mesma pessoa.
- O modelo **VGG-Face** é utilizado para comparar as imagens, e a verificação é realizada com a função DeepFace.verify().
- As imagens são lidas com **OpenCV** e convertidas para o formato RGB para exibição.
- **Matplotlib** é usado para exibir as imagens lado a lado para visualização.
