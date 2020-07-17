## 멀티 모달 감정 인식 모델 및 연구

### 연구 배경
- 배경
인공지능 기술이 발전하고 고도화됨에 따라 인간과 컴퓨터 사이의 인터랙션을 담당하고 인간의 감정을 
다양한 인터페이스를 통해 파악하고 분석하는 멀티 모달리티 서비스·시스템 등의 필요성이 높아질 것으로 예상된다. 
따라서 각각의 모달리티에서 얻은 데이터 사이의 관계를 통합적으로 해석할 수 있는 것이 중요하다.
- 목표
텍스트, 이미지, 음성 3가지의 모달리티 사용
각각의 모달리티에서의 감정 관계를 분석해 더 나은 사용자 인터페이스와 경험을 제공할 수 있는 방법을 제안
머신러닝 모델 설계에 대해서도 연구
음성 모달리티에서 dialogue와 utterance 별 감정과다른 모달리티에서 예측된 감정의 종류와의 관계 분석

### 연구 진행 과정
![aa](https://user-images.githubusercontent.com/48430005/87754860-ceba4f00-c840-11ea-9cea-1daca9927003.png)

### 결과 및 분석
![bb](https://user-images.githubusercontent.com/48430005/87754864-d1b53f80-c840-11ea-810d-24081557efea.png)

-3가지 Sentiment(Positive, Neutral, Negative)에 대해 Multi-Modal Sentiment F1-Score가 가장 높게 나오는 것을 확인하였다.

- 한계 및 분석
Text는 사람의 주관적 요소, Image는 화자 전환·배경및 주변 인물·표정 숨김, Audio는 파형에 따른 언어 해석 불가·반어법 등의 이유로 감정 분류에 한계점이 있다.
각각의 모달리티보다 사람과 같은 방식으로 동시에 여러 모달리티로 감정을 인식하는 것이 보다 정확한 인식방법이라는 것을 확인했다. 
모델링, 정성평가 개선과 함께 문맥적 요소를 포함하도록 Text Vectorization한다면 더 향상된 감정 인식 결과를 기대할 수 있다


