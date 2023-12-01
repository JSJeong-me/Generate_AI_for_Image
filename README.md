---
### 1일차 강의 내용 
- 강의 교안: https://zrr.kr/AWr3
- 실습 교안: https://zrr.kr/yI8n
- Issue 현황 분석: [Top 50 GenAI Web Products](https://a16z.com/how-are-consumers-using-generative-ai/)
---

# 생성형AI와 이미지 생성

## 1. 생성형AI는 어떻게 이미지를 만들까요?
- **인식모델**: 주어진 데이터를 바탕으로 특정 패턴이나 객체를 인식
- **생성모델**: 데이터의 분포를 학습하여 새로운 데이터를 생성

## 2. Diffuser 모델의 이해
- 데이터의 분포 학습 및 고품질 이미지 생성

## 3. 실습환경 구축
- 파이썬 환경 설정
- 라이브러리 설치
- 데이터셋 준비

---

# 다양한 사전학습 모델의 활용

## 1. Stable Diffusion 웹 UI 활용법
- 웹 기반 UI를 통한 이미지 생성

## 2. 원하는 이미지 생성을 위한 모델 선택과 프롬프트 작성법
- 적절한 모델 선택
- 프롬프트 작성 가이드라인

---

# LoRA, VAE를 활용한 다양한 스타일 연출

## 1. 성별·나이·헤어컬러·헤어스타일 변환
- LoRA와 VAE 활용 이미지 변환

## 2. 안경·장신구·배경 변환(프롬프트)
- 프롬프트 활용 세부 스타일 변환

---

# 다양한 효과 연출 및 Portfolio 작성

## 1. ControlNet 으로 이미지생성
- ControlNet 활용 이미지 효과 연출

## 2. Portfolio 작성(실습)
- 학습 내용 및 생성 이미지를 바탕으로 포트폴리오 작성


---
### 2일차 강의 내용
---


# 나만의 모델 만들기 – LoRA 실습 1

## 1. Checkpoint, LoRA, Embedding, Hyper Network, VAE 정의
- **Checkpoint**: 학습 중간의 모델 상태를 저장하는 파일
- **LoRA (Latent Representational Analysis)**: 레이턴트 공간을 활용하는 모델
- **Embedding**: 카테고리 데이터를 연속적 벡터로 변환
- **Hyper Network**: 하나의 네트워크가 다른 네트워크의 가중치를 생성
- **VAE (Variational Autoencoder)**: 생성과 인식을 모두 수행하는 생성 모델

## 2. LoRA 학습 데이터 준비
- 데이터셋 선택
- 데이터 전처리



# 나만의 모델 만들기 - LoRA 실습 2

## 1. LoRA 모델 학습
- 학습 알고리즘 설정
- 학습 진행

## 2. LoRA 활용 Prompt 가이드
- 프롬프트 설정 방법
- 다양한 스타일과 효과 적용

## 3. txt2img 이미지 생성 파라미터 활용
- **Sampler**: 샘플링 방법
- **CFG (Configuration File)**: 설정 파일
- **VAE**: 생성 모델
- **Clip skip**: 학습 과정에서 특정 단계를 건너뛰기

---

# 비슷한 이미지 찾기(모델 평가)

## 1. Vector Similarity 평가방법
- 코사인 유사도, 유클리드 거리 등

## 2. [scipy.spatial – Distance metrics 활용](https://docs.scipy.org/doc/scipy/reference/spatial.html)
- 다양한 거리 측정 방법 활용

---

# 이미지 Caption – 이미지로부터 텍스트 생성

## 1. Visual Attention을 활용한 이미지 Captioning
- Attention 메커니즘을 사용한 캡션 생성

## 2. 이미지 Caption 모델 학습 및 활용
- 데이터 준비
- 학습 및 캡션 생성
