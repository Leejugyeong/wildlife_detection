#  Wild Boar Detection with YOLOv5
## 1. 프로젝트 개요
- 야생 멧돼지 탐지를 위한 YOLOv5 기반 객체 탐지 프로젝트
- Roboflow에서 데이터셋을 수집하고, 모델을 학습하여 실제 영상에서 탐지 가능하게 구현

## 2. 데이터셋 및 전처리
- Roboflow Universe에서 공개된 멧돼지 탐지 데이터셋 사용
- OpenCV를 활용한 데이터 증강 진행

## 3. 모델 학습 및 분석
- YOLOv5s 모델 사용, 하이퍼파라미터 튜닝 진행
- Precision, Recall, mAP 분석 및 성능 개선 방안 도출

## 4. 성능 평가 및 결과
- 최종 mAP 0.85 달성 (YOLOv5s 기준)
- 일부 오탐지 발생 → 데이터셋 보강 필요

## 5. 향후 발전 방향
- YOLOv7로 업그레이드 실험
- TensorRT 변환 및 실시간 속도 개선
