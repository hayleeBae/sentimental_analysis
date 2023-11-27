# sentimental_analysis

## 목차
  - [개요](#개요)
  - [상세](#상세)

## 개요
- 프로젝트 이름 : 유불리랑 친해지길 바래(feat.약관)
- 프로젝트 기간 : 2022.12.01 ~ 2022.12.05
- 기획 의도
  - 약관에는 계약의 핵심이 담겨 있지만 전문성이 강하다 보니 딱딱하고 어렵게 느끼는 경우가 많음
  - 분쟁이 발생하였을 때 유리한 조항인지 불리한 조항인지를 구분해 줌으로써 기준점을 제공.

## 상세
- 데이터 : AI-Hub 법률/규정 (판결서, 약관 등) 텍스트 분석 데이터
- 기술 스택
  - 언어 : Python
  - 형태소 : Mecab
  - 프레임워크 : tensorflow
  - 모델 : RNN, GRU, LSTM
- 주요 기능
  - 약관의 유리하거나 불리한 조항에 대하여 학습되어 있음
  - 분쟁이 되는 내용을 입력하면 얼마나 유리한지 불리한지를 확률로 제공
  - ex) 71.47% 확률로 유리한 조항입니다.
