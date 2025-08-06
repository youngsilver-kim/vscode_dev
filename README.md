# YOLO 기반 객체 탐지 특강

## 1. 교육 개요

* **기간**: 2025년 8월 4일(월) \~ 8월 15일(금)
* **시간**: 매일 09:00 \~ 18:00
* **장소**: VS Code 활용 온라인/오프라인 교육 환경
* **대상**: 컴퓨터 비전 기초 지식 보유자 (Python, OpenCV 사용 경험 권장)
* **목표**: 최신 YOLO 모델을 활용한 객체 탐지 원리 이해 및 실습 완성

## 2. 사전 준비 사항

1. **Python 3.8 이상** 설치
2. **VS Code** 및 필수 확장( *Python*, *Jupyter* ) 설치
3. **가상환경(Anaconda/venv)** 구성
4. **필수 라이브러리** 설치:

   ```bash
   pip install ultralytics torch torchvision opencv-python matplotlib
   ```
5. 예제 데이터와 코드 저장소(깃허브) 클론:

   ```bash
   git clone https://github.com/your-repo/object-detection-course.git
   ```

## 3. 개발 환경 설정

* **인터프리터**: `C:\ProgramData\Miniconda3\python.exe` 또는 가상환경 경로 설정
* **VS Code 워크스페이스**: 본 강의 폴더 루트
* **필수 확장**: Python, Jupyter, GitLens

## 4. 강의 일정 및 커리큘럼

| 날짜       | 오전 (09:00-12:00)               | 오후 (13:00-18:00)                 |
| -------- | ------------------------------ | -------------------------------- |
| 8/4 (월)  | 오리엔테이션 및 환경 설정                 | YOLO 개요 및 모델 아키텍처 분석             |
| 8/5 (화)  | 데이터셋 준비 및 라벨링 도구 사용법           | DataLoader, 전처리 파이프라인 구현         |
| 8/6 (수)  | Ultralytics YOLO 설치 및 기본 예제 실행 | 모델 학습 파라미터 이해 (epochs, batch 등)  |
| 8/7 (목)  | 커스텀 데이터셋 학습 실습                 | 학습 결과 시각화 및 로그 분석                |
| 8/8 (금)  | 검증(Validation) 및 테스트 방법론       | 성능 지표(Precision, Recall, mAP) 계산 |
| 8/11 (월) | 모델 최적화: 하이퍼파라미터 튜닝             | Pruning, Quantization 기법 소개      |
| 8/12 (화) | 실시간 추론 구현 (웹캠/동영상)             | 추론 속도 개선 기법 및 배치 처리              |
| 8/13 (수) | 고급 주제: Transfer Learning 적용    | 앙상블 및 다중 스케일 입력 기법               |
| 8/14 (목) | TensorRT 및 ONNX 변환 실습          | 경량화 모델 배포 전략 (Edge, Mobile)      |
| 8/15 (금) | 종합 실습 프로젝트 시작                  | QA 및 마무리, 최종 결과 공유               |


## 5. 실습 예제

* **apple\_car\_detection.ipynb**: 과일과 자동차 객체 탐지 실습
* **custom\_train.py**: 사용자 정의 데이터셋 학습 스크립트
* **real\_time\_inference.py**: 웹캠 기반 실시간 객체 탐지

## 6. 참고 자료

* Ultralytics YOLO 공식 문서: [https://docs.ultralytics.com](https://docs.ultralytics.com)
