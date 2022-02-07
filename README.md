### CV_Generator
-------------------------------------------------------------------------------------------------------
### ✔️프로젝트 소개
- 목적 : 합격자기소개서 데이터를 기반으로 키워드 입력시 자기소개서를 자동 생성하고 요약해주는 모델 생성

### ✔️Directory
1. 알고리즘
train.ipynb: 데이터 전처리 및 GPT2 fine-tuning
generate.ipynb: fine-tuning을 완료한 모델을 불러와 새로운 자기소개서 생성

2. 데이터셋
preprocessed_data.csv: 잡코리아와 링커리어에서 합격자기소개서 크롤링 후 전처리 완료한 데이터
출처 : https://linkareer.com/cover-letter/search (링커리어)

### 💻문장 생성 실행 코드(Open in Colab)
