# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 세냐
- 리뷰어 : 최정민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="1956" height="968" alt="image" src="https://github.com/user-attachments/assets/688036a4-215d-426d-950e-e3220eb9e2c2" />

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - EDA 와 Feature Engineering 에서 어떤 시도를 했는지 알 수 있었음.
<img width="1415" height="570" alt="image" src="https://github.com/user-attachments/assets/88a5ba82-2522-4a4b-a105-2d9b38dad098" />

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - price 와 관련이 있는 column 을 찾기 위해 scatterplot 을 이용하여 시각화함.
          <img width="1360" height="1069" alt="image" src="https://github.com/user-attachments/assets/374693e8-228a-4bc3-928b-fac3c4802f7c" />

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 코드 하단에 프로젝트 전체 과정을 잘 정리함
        - kaggle 에 제출하여 채점 된 결과와 전체적인 프로젝트 플로우를 볼 수 있었음.
        <img width="1248" height="989" alt="image" src="https://github.com/user-attachments/assets/e7867cd5-7cab-44a4-9dd2-c379291f35ea" />


        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - features list 를 작성하여 중요한 feature 들을 효율적으로 입력할 수 있게 함.
          <img width="1217" height="469" alt="image" src="https://github.com/user-attachments/assets/9d490b12-158b-401f-a2f1-5bb0a9cabdb5" />
<img width="654" height="154" alt="image" src="https://github.com/user-attachments/assets/bf26d109-5bc7-463a-8258-566d17a5fff2" />



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
feature 들 중에 price 와 관련이 큰 것들을 찾기 위해 heatmap 과 scatterplot 을 잘 활용했다.
프로젝트 전체의 진행 과정 및 중요한 부분을 따로 정리하여 이해하기 수월했다.
코드에서 중요한 부분에 바로 주석처리를 하거나 프로젝트를 하며 아쉬운 점 및 개선 방향도 같이 적으면 좋을 것 같다.

LightGBM이 다른 모델에 비해 성능이 좋아서 Ensemble 하지 않고 한 모델만 사용했지만 Ensemble 을 할 경우 더 좋은 결과를 낼 수 있을지 궁금하다.
