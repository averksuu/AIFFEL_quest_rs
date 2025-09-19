# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 세냐
- 리뷰어 : 최은학


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - SFT, RM, PPO 학습 부분을 모두 분리해서 작성했고 모델별 답변을 비교한 표까지 제출되었다.
    - <img width="700" height="250" alt="image" src="https://github.com/user-attachments/assets/ebe461b3-b937-423b-bd6d-cc0decc16d90" />

- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 기존 GPTRM_custom는 LoRA를 적용할 수 없는 구조였는데 이를 위해 GPT2RewardModel 클래스를 직접 구성
    - <img width="500" height="520" alt="image" src="https://github.com/user-attachments/assets/dd28d7a1-2628-4ce8-952d-b4ef3ac8557f" />

- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - result.md에 단계별 학습 과정을 상세하게 정리
    - 각각의 변경사항, 구조, 예시, 결과 분석 등 여러 요소로 정리
    - <img width="700" height="1000" alt="image" src="https://github.com/user-attachments/assets/d79d7d89-5545-41eb-8aee-a2c2e56b458a" />

- [ ]  **4. 회고를 잘 작성했나요?**
    - 각 실험/모델 별 특징을 정리했고 한계점을 잘 설명함, 향후 어떤 부분을 개선해야할지 잘 정리됨
    - <img width="700" height="600" alt="image" src="https://github.com/user-attachments/assets/9117ee84-8a8b-414c-b24c-3932fb4cdfc4" />

- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 결과를 정리한 result.md는 너무 잘 정리되어있음
    - PPO_2_github.ipynb와 같은 각각의 코드 파일을 보면,
    - cell 나누기, 함수화 등의 정리 요소는 부족
    - <img width="700" height="1000" alt="image" src="https://github.com/user-attachments/assets/a7f223b5-7b5b-4162-8907-b1359aeab642" />


# 회고(참고 링크 및 코드 개선)
```
# 데이터 정제(prompt 길이를 기준으로 너무 짧거나 긴 데이터 제거), Reward Model에 LoRA 적용, 결과 해석 등 합리적이고 좋은 방법을 많이 사용한 것 같습니다.

```
