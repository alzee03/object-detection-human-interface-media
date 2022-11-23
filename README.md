# object-detection-human-interface-media
## 휴먼 인터페이스 같은 그림 찾기 과제물 실행을 위한 간단한 설명
### 사용한 라이브러리
find_same_picture.ipynb를 실행하기 위해서 파이썬과 주피터 노트북을 다운받아야 함.

추가로 사용한 라이브러리는 pytorch, matplotlib, numpy 등이 있는데 pip를 이용해서 설치해야함
```python
pip install pytorch matplotlib numpy
```
---
### 같은 그림 찾기에 사용한 그림
![output](https://user-images.githubusercontent.com/44120370/203473563-c5c35994-a785-44e2-be67-c0d56861ddb1.png)
---
### 프로그램을 실행한 결과물 
#### cross-correlation의 분포를 나타낸 히트맵
![correlation_heatmap](https://user-images.githubusercontent.com/44120370/203473955-34c36b68-af10-4bdb-8529-1a33384441c6.png) 변화를 한 눈에 알아보기 위해 컬러맵의 바운드를 설정함
---
#### 결과값들 중 threshold를 넘어간 지점에 대해 박스로 표시한 그림
![output2](https://user-images.githubusercontent.com/44120370/203474235-58fd8225-fcfa-49a4-86dd-f1b2555ab9a8.png)
