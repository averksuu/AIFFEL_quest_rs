# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 세나
- 리뷰어 : 김재성


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부

<img width="1003" height="308" alt="Image" src="https://github.com/user-attachments/assets/e7d13d75-f691-495e-9efa-583dce29186a" />

SentencePeice를 bpe type으로 학습하여 80%이상의 accuracy를 확보했다.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
<img width="826" height="602" alt="Image" src="https://github.com/user-attachments/assets/dd73fb16-f437-4c02-825a-b9ceab93b24e" />

Mecab을 통해 가장 높은 accuracy에 도달한 코드 파트.

- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

<img width="768" height="244" alt="Image" src="https://github.com/user-attachments/assets/81d14f57-d0d2-4507-bb51-0a1560efed95" />

SentencePiece의 unigram과 bpe로 vocab size를 20000으로 추가실험을 진행하였다.

개인적으로 해보고 싶던 실험인데, 못했던 실험이라 인상 깊게 확인할 수 있었다.
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

<img width="986" height="215" alt="Image" src="https://github.com/user-attachments/assets/0a8fbf75-a150-430d-8391-e4587e4c5a84" />

회고가 잘 작성되었다.

한국어라서 형태소 기반의 토크나이저가 유리하다고만 생각했는데, 구현 리소스까지 고려한 의견이 인상깊었다.
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

<img width="1063" height="549" alt="Image" src="https://github.com/user-attachments/assets/51e188f9-55a4-40c0-9306-d33369280143" />

전체적으로 코드가 간결하고, 분포를 시각화하여 파악을 시도한 부분이 좋았다.


# 회고(참고 링크 및 코드 개선)
```
# 단순히 mecab이 정확도가 좋아서 좋은 게 아니라, 구현 리소스까지 고려하여 SentencePiece가 좋다고 판단하신 게 인상깊었습니다.
# 덕분에 성능 지표 외에 효율적인 개발과 유지보수도 고려해야겠다고 느꼈습니다.
