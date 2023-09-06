# 3D ResNet-based Children's Behavior Recognition Method Using Video Image Sequence

이 논문은 유아의 행동을 비디오 이미지 시퀀스를 통해 인식하는 딥러닝 모델을 제안한다.

## 목적 및 배경
- **목적**: 유아의 다양한 행동을 인식하기 위한 딥러닝 모델을 개발한다.
- **특징**: 이 모델은 다양한 표현과 방법으로 동일한 행동을 분석할 수 있어야 한다.

## 방법론
- **기반 알고리즘**: 3D ResNet을 사용한다.
- **스켈레톤 노이즈 감지**: Z-score를 사용한다.
- **인간 감지와 스켈레톤 이미지 추출**: MMCV와 MMDetection을 사용한다.
- **키 포인트 추출**: HRNet을 사용한다.

## 데이터 수집
- **대상**: 50명의 아이들
- **행동 종류**: 총 13가지 행동에 대한 이미지 데이터를 수집한다.

## 실험 결과
- **정확도**: 3D ResNet 모델은 약 72.21%의 정확도로 13가지 행동을 인식한다.
- **특정 행동의 정확도**: 서기, 밀기/당기기, 앉기 등은 약 90%의 정확도로 인식된다.

## 참고 논문 및 기술
- Straudenmayer et al. (2009)
- Chen et al. (2019)
- Duan et al. (2022)

## Action Recognition process
![image](https://github.com/Jedo0224/3dresnet_for_child_action_recognition/assets/90050514/93d4308c-861f-4212-acf4-5cf99b486ed7)

## Input image processing result (skeleton)
![image](https://github.com/Jedo0224/3dresnet_for_child_action_recognition/assets/90050514/6293ce94-19de-469c-bb8e-d45935ebbbdb)

## 3D Resnet architecture
![image](https://github.com/Jedo0224/3dresnet_for_child_action_recognition/assets/90050514/92c7e02e-1b24-4b2f-bb49-7553718094cd)

## result
![image](https://github.com/Jedo0224/3dresnet_for_child_action_recognition/assets/90050514/7d4f50ef-f608-4ac4-8512-2a95271a9815)
