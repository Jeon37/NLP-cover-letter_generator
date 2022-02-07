### CV_Generator
-------------------------------------------------------------------------------------------------------
### ✔️프로젝트 소개
- 목적 : 합격자기소개서 데이터를 기반으로 키워드 입력시 자기소개서를 자동 생성하고 요약해주는 모델 생성

### 💻문장 생성 실행 코드(Open in Colab)
[자기소개서 생성기](https://colab.research.google.com/drive/1D5DCA-ulr_J_h6H12ZgcotHRfmIzSOBA?usp=sharing)

### ✔️프로젝트 개요
#### 1. 데이터 크롤링 및 전처리
![image](https://user-images.githubusercontent.com/80508535/152725185-3588f990-b30d-4004-88fd-8f157de86fd2.png)
![image](https://user-images.githubusercontent.com/80508535/152725200-fbc4a590-cf12-4fbd-a085-b274fc64fdaa.png)

#### 2. GPT-2 모델링
![image](https://user-images.githubusercontent.com/80508535/152725250-a1b7a308-0cb2-47a4-90eb-593c9cc26b69.png)
![image](https://user-images.githubusercontent.com/80508535/152725255-9ce89659-3a82-429b-b2c5-d266895af000.png)
![image](https://user-images.githubusercontent.com/80508535/152725319-d3c82fda-fcc3-4b4c-b54d-5b5556e98c68.png)

#### 3. LexRank 알고리즘 기반 문장 요약
![image](https://user-images.githubusercontent.com/80508535/152725290-94c3492a-fdeb-4bf3-8e5a-52e4ab0960a8.png)


### ✔️파일 설명
1. 알고리즘  
train.ipynb: 데이터 전처리 및 GPT2 fine-tuning  
generate.ipynb: fine-tuning을 완료한 모델을 불러와 새로운 자기소개서 생성

2. 데이터셋  
preprocessed_data.csv: 잡코리아와 링커리어에서 합격자기소개서 크롤링 후 전처리 완료한 데이터
- 출처 : [링커리어](https://linkareer.com/cover-letter/search),[잡코리아](https://www.jobkorea.co.kr/starter/passassay/)
