<h1 align="center">Machine Learning Study</h1>

<p align="center">기계학습의 실행 환경과 지도학습 기초를 정리한 Jupyter Notebook 학습 저장소</p>

<p align="center">Python · Jupyter Notebook · scikit-learn</p>

> 모델 성능을 주장하는 프로젝트가 아니라, 머신러닝 실습을 통해 데이터 준비부터 학습·평가까지의 기본 흐름을 익힌 초기 학습 기록입니다.

---

## 목차

- [학습 내용](#학습-내용)
- [노트북 안내](#노트북-안내)
- [실행 방법](#실행-방법)

## 학습 내용

이 저장소는 다음의 기본 질문을 실습으로 다룹니다.

- Python 기반 머신러닝 개발 환경을 어떻게 구성하는가?
- 데이터셋의 feature와 label을 어떻게 분리하는가?
- 지도학습 모델을 학습하고 예측 결과를 어떻게 확인하는가?

## 노트북 안내

| 파일 | 내용 |
| --- | --- |
| `01. 기본 환경 구성.ipynb` | Jupyter와 Python 데이터 분석 환경의 기본 사용법 |
| `02. 붓꽃의 품종 분류.ipynb` | Iris 데이터셋을 이용한 분류 모델 실습 |

## 실행 방법

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
pip install jupyter scikit-learn pandas matplotlib
jupyter notebook
```

노트북은 로컬 Jupyter 환경 또는 Google Colab에서 열 수 있습니다.

## 이용 안내

이 저장소는 포트폴리오·학습 기록 열람을 위해 공개합니다. 코드·문서·이미지의 재사용, 수정, 배포는 사전 문의가 필요합니다.
