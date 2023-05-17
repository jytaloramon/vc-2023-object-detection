# Detecção de Objetos

- **Título**: Identificação de Objetos em Imagens e Vídeos
- **Alunos**:
  - Alan Duda dos Santos
  - José Ytalo Ramon de Almeida Gonçalves
- **Disciplina**: Visão Computacional (VC) - 2022.2
- **Professor**: Tácito Trindade de Araújo Tiburtino Neves
- **Código-Font**:
  - **Colab**: <https://colab.research.google.com/drive/1-EtKYzO9s0CpFUQUF3HgwlCkIvt2Q5Ys?usp=sharing>
  - **Github**: <https://github.com/jytaloramon/vc-2023-object-detection>


## Galeria

### Imagens

#### Central Park

![Central Park - Entrada](tests/central-park.jpg)

![Central Park - Saída Comum](tests-output/park-common.png)

![Central Park - Saída Com Supressão](tests-output/park-suppression.png)

#### Via (Tráfego)

![Via (Tráfego) - Entrada](tests/traffic.jpeg)

![Via (Tráfego) - Saída Comum](tests-output/traffic-common.png)

![Via (Tráfego) - Saída Com Supressão](tests-output/traffic-suppression.png)

#### Carro

![Carro - Entrada](tests/car.jpg)

![Carro - Saída](tests-output/car-common.png)

#### Neymar

![Neymar - Entrada](tests/futebol.jpg)

![Neymar - Saída](tests-output/futebol-common.png)


#### Animais

![Animais - Entrada](tests/animals.jpg)

![Animais - Saída](tests-output/animals-common.png)

### Vídeos

#### MARQUETTI MKT

[![MARQUETTI MKT - Entrada](https://asciinema.org/a/113463.png)](tests/video-moto.mp4)

[![MARQUETTI MKT - Saída](https://asciinema.org/a/113463.png)](tests-output/video-moto-common.avi)

#### Aero - Por Trás da Aviação

[![Aero - Por Trás da Aviação - Entrada](https://asciinema.org/a/113463.png)](tests/video-aero.mp4)


## Conjunto Dados (Rede Neural)

1. Arquivo de rótulos (labels), de extensão .txt. Usado o COCO, link: https://github.com/zafarRehan/object_detection_COCO/blob/main/labels.txt.
2. Arquivo binário de treinamento contendo a topologia e os pesos da rede treinada, esse arquivo possui a extensão .pb (protobuf). Usado “MobileNet-SSD v3.pb”, link: http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v3_large_coco_2020_01_14.tar.gz.
3. Arquivo de configuração da rede como formato .pbtxt (protobuf Text). Usado “ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt”, link: https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7.
