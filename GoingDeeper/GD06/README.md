# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 세냐.
- 리뷰어 : 김형일.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="976" height="795" alt="image" src="https://github.com/user-attachments/assets/ef67f368-744e-4ef1-98b2-35a0f3e3be5b" />
        - <img width="911" height="751" alt="image" src="https://github.com/user-attachments/assets/f2ccae2d-6065-4b07-91d7-d0817bb5fb16" />
            - MLM, NSP task가 수행된 pretrain용 데이터셋 생성 확인
        - <img width="568" height="465" alt="image" src="https://github.com/user-attachments/assets/9b1a251b-a487-4feb-88fe-b2205bf59579" />
        - <img width="588" height="452" alt="image" src="https://github.com/user-attachments/assets/44f18dab-6e83-48b8-bd17-6a3eb5cd62b3" />  
            - MLM, NSP loss 그래프를 통해 감소 확인
        - <img width="810" height="524" alt="image" src="https://github.com/user-attachments/assets/cdb4ee84-20d9-4ca9-85c3-0b45bb0827a8" />
        - <img width="755" height="171" alt="image" src="https://github.com/user-attachments/assets/81fe1616-48d5-4814-88b1-a1e49c327a9c" /> 
          
            - 구축한 모델과 학습과정을 확인    






    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="907" height="624" alt="image" src="https://github.com/user-attachments/assets/58ec4bd1-2910-48f5-b6fd-8da5802f2a2b" />
        - <img width="917" height="818" alt="image" src="https://github.com/user-attachments/assets/c49acb5b-efa8-4681-96ea-eb0662e23b40" />
        - <img width="914" height="797" alt="image" src="https://github.com/user-attachments/assets/8f06600e-b9d2-44b2-bc4d-a666b00b1f6e" />
        - <img width="914" height="746" alt="image" src="https://github.com/user-attachments/assets/6d80eed5-ce77-47e6-aee7-064813b6b70d" />
        - <img width="906" height="773" alt="image" src="https://github.com/user-attachments/assets/abfcb589-3e71-42a8-9667-18c9700e3128" />
            - BERT 모델 구현이 깔금하게 잘 정리됨 







        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="907" height="307" alt="image" src="https://github.com/user-attachments/assets/e5fa1783-493d-4616-bdeb-d751ac24d329" />
            -  노드에서 제공한 방식과 차이가 있는 부분( AdamW, weight_decay 추가한 부분) 인상적이었습니다.  
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="792" height="612" alt="image" src="https://github.com/user-attachments/assets/572ff0c5-3ef3-4c65-9ba9-19b5ecc89089" />
            - 간단 명료하지만 프로젝트에 대한 명확한 이해와 분석을 기반으로 잘 작성됨

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="911" height="289" alt="image" src="https://github.com/user-attachments/assets/d9afa4b5-99e3-479d-aaf2-1a23903855da" />
            - 전반적으로 코드 작성이 간결하고 정리가 잘 되어있음 



# 회고(참고 링크 및 코드 개선)
```
* 세냐님의 리뷰는 늘 명료해서 많은 도움이 됩니다.
  분석에 있어서도 군더더기 없이 깔금하면서도 제가 보지 못한 다양한 각도에대한 의견도 있어서 특히 좋았습니다.
  수고하셨습니다.


# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
