# 💻 데이콘 이미지 복원 경진대회 💻

## 📢 소개
본 프로젝트는 **데이콘 이미지 복원 경진대회**에 참여하여, 손실된 이미지의 특정 영역을 복구하고 흑백 이미지에 적합한 색을 입혀 원본과 유사한 이미지로 재생성하는 알고리즘을 개발한 프로젝트입니다.

### 📢 주요 목표
- 손실된 이미지의 특정 영역 복원
- 복원된 흑백 이미지에 적합한 색을 입히는 알고리즘 개발
- 최적의 성능을 위한 다양한 딥러닝 모델 실험

## 📢 데이터

본 경진대회에서 제공된 데이터는 손실된 흑백 이미지를 복원하기 위한 학습 및 평가 데이터로 구성되어 있습니다.

### 📢 데이터 구성

| **폴더/파일**           | **설명**                                                                                      |
|-------------------------|---------------------------------------------------------------------------------------------|
| **train_input/**        | 학습용 입력 이미지 폴더 (손실된 흑백 PNG 이미지, 총 29,603장)                                 |
| **train_gt/**           | 학습용 타겟 이미지 폴더 (원본 PNG 이미지, 총 29,603장)                                        | 
| **train.csv**           | 학습 데이터 입력 이미지(`train_input`)와 타겟 이미지(`train_gt`)의 파일 경로를 매칭한 CSV 파일      |
| **test_input/**         | 평가용 입력 이미지 폴더 (손실된 흑백 PNG 이미지, 총 100장)                                   |
| **test.csv**            | 평가 데이터 입력 이미지(`test_input`)의 파일 경로 정보가 포함된 CSV 파일                      |
| **sample_submission.zip** | 추론 결과 제출 양식. ZIP 파일 내부에 복원된 PNG 이미지를 포함해야 하며, 이미지 파일명은 평가 입력 이미지 파일명과 동일해야 함 |

