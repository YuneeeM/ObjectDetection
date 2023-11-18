# canmoya(캔모야)
시각장애인을 위한 캔음료 인식 어플(Can beverage recognition app for the visually impaired)


## 주요 특징
* YOLO v5 및 TensorFlow Lite 기반
    - 가장 빠른 실시간 객체 인식 모델은 YOLO를 사용하여 캔 음료를 분류함
    - tflite(TensorFlow Lite) 라이브러리를 사용하여 ML 모델을 Flutter 앱에 통합하는 데 사용함
* TTS (Text-to-Speech)
    - 인식된 음료 정보를 음성으로 바로 전달, 시각장애인 사용자에게 친숙한 환경 제공하기 위함
* iOS, Android에서 동시 사용 가능
    - 크로스플랫폼인 Flutter로 개발하였기에, Android와 iOS 둘다에서 사용가능한 장점
  
## 현재까지 진행 사항(모델 생성, 앱에 주입까지)
* 코카콜라 캔음료 인식 성공
![스크린샷 2023-10-16 오전 4 23 32](https://github.com/puretension/CanMoYa/assets/106448279/7049b138-7cff-4cea-aaac-896eaa40da6e)

## 개선 사항
* 모델 정확도 향상 및 상품군 확대(현재는 코카콜라, 스프라이트만 인식) -> 여러 종류의 (캔 음료 이외의) 상품까지 확대!
* OCR API를 사용한 유통기한(소비기한) 확인 
