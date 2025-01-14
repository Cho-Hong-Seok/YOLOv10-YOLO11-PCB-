# YOLOv10-YOLO11-PCB
> KSC 2024_YOLOv10과 YOLO11를 이용한 인쇄 회로 기판(PCB) 결함 탐지 및 분류
---
#### 📖 개요
본 프로젝트는 최신 딥러닝 모델 YOLOv10과 YOLOv11을 이용하여 PCB의 다양한 결함을 탐지하고 분석합니다. 특히 YOLOv10은 CSPNet 구조를 기반으로 높은 연산 효율성을, YOLOv11은 Transformer 기반 구조로 복잡한 패턴 분석 성능을 제공합니다.

#### 📌 주요 내용
- 모델: YOLOv10, YOLOv11
- 데이터셋: 약 10,000장의 PCB 결함 이미지
- 결함 유형:
  - Missing Hole
  - Short
  - Mouse Bite
  - Spurious Copper
  - Open Circuit
  - Spur
- 성과:
  - YOLOv10: 대량 생산 환경에 적합한 빠른 처리 속도
  - YOLOv11: 복잡한 배경에서의 안정적 결함 탐지
#### 🛠️ 활용 사례
전자기기 제조 공정 품질 관리
대량 PCB 제조 라인의 실시간 결함 감지 시스템
