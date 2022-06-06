# About me model
About me model은 Dlib 모델을 활용한 닮은꼴 찾기 알고리즘 코드와, Stargan-v2 모델로 구성되어 있습니다.
## 1. DLib 모델을 활용한 닮은꼴 찾기 알고리즘
### 닮은꼴 찾기 알고리즘 코드 소개
- Dlib모델 데이터를 (연예인 얼굴) 29개의 조건으로 수치화
  - 29개 조건
    - 턱 각도 계산, 얼굴에서 코 비율, 얼굴에서 눈 비율, 중안부, 하안부 비율
- User_image를 입력시 Dlib모델로 29개 조건으로 수치화
  - 29개 조건
    - 턱 각도 계산, 얼굴에서 코 비율, 얼굴에서 눈 비율, 중안부, 하안부 비율
- 연예인의 데이터 수치와 비교하여 score 계산
- Score가 높은 3개 연예인 사진 선택

## 2. Stargan-v2 모델
