## Google Colab에서 Pytorch 예제 풀어보기

0. 환경설정

리눅스 환경인 Google Colab에 맞게 파이토치 라이브러리를 불러옵니다. 

!pip3 install https://download.pytorch.org/whl/cu100/torch-1.1.0-cp36-cp36m-linux_x86_64.whl

!pip3 install https://download.pytorch.org/whl/cu100/torchvision-0.3.0-cp36-cp36m-linux_x86_64.whl

PIL에서 이미지를 임포트할 때 생기는 오류는, pytorch와 pillow의 버전이 동일하지 않아 생기는 것입니다.

따라서 pillow의 버전을 낮춰주는 과정이 필요합니다. 

!pip uninstall -y Pillow

!pip install "pillow<6.2.2"
