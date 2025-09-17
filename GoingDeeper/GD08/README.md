# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 세냐.
- 리뷰어 : 김형일.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="999" height="823" alt="image" src="https://github.com/user-attachments/assets/ec726ce4-0168-4bca-b6b7-7dc00f282480" />
            - 학습이 정상 진행됨을 확인
        - <img width="427" height="135" alt="image" src="https://github.com/user-attachments/assets/de9e864e-faa0-4afe-9c05-e2dd38a9c42c" />
            - Accuracy 90 이상 확인
        - <img width="932" height="730" alt="image" src="https://github.com/user-attachments/assets/15682d53-492c-4c4d-8465-96f4dbc25190" />
        -  data collator+ dynamic batching 적용 확인   



    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="681" height="185" alt="image" src="https://github.com/user-attachments/assets/5012ccef-0506-4095-a68f-28cc4d1e926d" />
        - 실험 코드 앞부분에 실험 내역이 잘정리되어 있어 해당 실험의 목적을 쉽게 이해함.

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="707" height="737" alt="image" src="https://github.com/user-attachments/assets/98191c8a-10b5-479a-a05b-c4a38755bb89" />
        - klue/roberta-base로 모델을 변경하여 실험 확인
        - <img width="712" height="387" alt="image" src="https://github.com/user-attachments/assets/2138c8c7-35f8-48ce-8a37-8861ae6d2f17" />
        - 정성 평가로 확인 한 점이 인상깊음.  


        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="708" height="786" alt="image" src="https://github.com/user-attachments/assets/0a19f680-6c11-432b-bf0a-c473144edb26" />
        - 회고에 실험 내역과 분석 고찰이 잘 들어 있음.  

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="710" height="520" alt="image" src="https://github.com/user-attachments/assets/29b45857-edbe-4515-a907-f4ef4073beb0" />
        - 세냐님 코드는 늘 간결하고 초 깔끔함.



# 회고(참고 링크 및 코드 개선)
```
* 모델 자체를 변경하신 것과 정성 평가를 추가한 것이 인상 깊었습니다.
저는 모델 자체를 바꿀 생각 까지는 못해봤네요 ㅎㅎ
회고에서 Collator와 dynamic padding에 대해 추론 하신 내용을 볼 수 있어서 좋았습니다.
다이나믹 패딩을 하면서 정규화 효과가 사라졌을 것이라고 추측하셨는데..정규화를 유지하면서도 다이나믹 패딩을 적용하는 방법은 없을지 궁금해지네요.
고생하셨습니다. 노트북 잘 봤습니다.

# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.

