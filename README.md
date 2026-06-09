# ML Notebooks

NumPy와 Pandas 기초를 실습한 Jupyter Notebook 모음입니다.

## 노트북 목록

### `numpy_basics.ipynb`

NumPy 배열 연산 기초 실습.

- 1D / 2D 배열 생성 및 자료형 확인
- 브로드캐스팅, 슬라이싱, 인덱싱
- 수학 연산 및 집계 함수

### `pandas_data_processing.ipynb`

Pandas를 이용한 데이터 전처리 기초 실습.

- DataFrame 생성 및 결측치 확인 (`isnull`, `isnull().sum()`)
- 결측치 처리: `dropna`, `fillna`, 평균값 대체
- 기본 탐색적 데이터 분석(EDA)

## 실행 방법

```bash
pip install jupyter numpy pandas
jupyter notebook
```
