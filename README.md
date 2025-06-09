# HAI-Hecto-AI-Challenge-2025
- 대회 사이트: [HAI(하이)! - Hecto AI Challenge : 2025 상반기 헥토 채용 AI 경진대회](https://dacon.io/competitions/official/236493/overview/description)
<br><br>
## 🗒️ 프로젝트 소개
- DACON과 Hecto가 협력하여 주최하는 대회
- 396종의 차량 사진 분류
- 데이터 규모 (이미지): 훈련 33,113장, 테스트 8,258장 (대회 성적 평가시 추가 데이터 있음)
- 개발 기간: 2025년 5월 ~ 6월
- 개발 환경: Python, Pytorch, Scikit learn, Google Colab (T4/CUDA)

## 📖 관련 게시글
1. [대회 규칙과 데이터 셋 살피기](https://taeddy-note.tistory.com/5)
2. [데이터 정제](https://taeddy-note.tistory.com/6)

## 📁 디렉토리
모든 노트북 파일(.ipynb)는 각 모델을 정의, 훈련, 검증, 평가, 제출물 제작 과정을 담음.<br>
models 디렉토리 안에는 각 모델의 훈련 과정중 파라미터를 저장함.
```
.
├── models
│   ├── densenet121
│   ├── mobilenet_v3_small
│   ├── resnet18
│   └── resnet50
├── README.md
├── densenet.ipynb
├── mobilenet.ipynb
├── resnet18.ipynb
└── resnet50.ipynb
```
