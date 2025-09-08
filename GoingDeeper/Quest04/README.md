# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김형일
- 리뷰어 : 박범찬


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="762" height="644" alt="image" src="https://github.com/user-attachments/assets/a2743c81-29d6-4a99-8b9d-37a021855143" />
          <img width="757" height="551" alt="image" src="https://github.com/user-attachments/assets/db0fe886-c23a-4791-b3c4-c1d180754d64" />
          -주어진 프로젝트에서 여러 실험을 해보고 그 결과를 시각화하는 코드를 완성하셨습니다!


- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="563" height="393" alt="image" src="https://github.com/user-attachments/assets/5d4a30d6-5eb4-48bb-9e61-2a6c25f6378f" />
          <img width="549" height="557" alt="image" src="https://github.com/user-attachments/assets/9d52ebd3-0b2a-4b18-9f21-fb31f6b9e031" />
          <img width="560" height="478" alt="image" src="https://github.com/user-attachments/assets/d170b42d-b563-40b6-8671-b7415d0b1535" />
          -처음 베이스라인을 잡은 상태에서 최대한 모델의 복잡도를 줄이거나 (양방향 > 단방향, 레이어 : 1) 데이터를 필터링하여 (글자 길이 조정) Loss와 학습속도를 줄이고 다양성을 표현할 수 있었습니다!

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="891" height="356" alt="image" src="https://github.com/user-attachments/assets/2dfbf7d3-1b29-4516-842b-222365de9f3b" />
          -과적합이 발생하는 것을 확인여 L2 정규화를 통해 방지하였고 가중치가 클수록 모델이 복잡해지는 경향을 파악하여 이를 억제함으로 과적합을 방지하기 위해 노력하셨습니다!

        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="736" height="521" alt="image" src="https://github.com/user-attachments/assets/91483b1e-288e-40ce-b219-aefc89f3a30f" />
          <img width="504" height="159" alt="image" src="https://github.com/user-attachments/assets/aed91078-96e6-4a05-8524-01d574e8e57c" />
          -실험에 대한 초기 계획과 회고가 잘 작성되었습니다!

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="726" height="618" alt="image" src="https://github.com/user-attachments/assets/9f722bc9-1644-469a-9293-642120c4ea73" />
          <img width="726" height="618" alt="image" src="https://github.com/user-attachments/assets/b15f7c5e-3394-4c9d-82f5-22627599ba63" />
          -각 에포크안에 plot을 찍어 에포크에 따른 시각화를 보여지게 한 부분이 인상깊었습니다. 이러한 결과로 긴 학습시간 동안 학습이 중간중간 잘되고 있는지 파악할 수 있는 효율이 있는거 같습니다!


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

-기본적으로 모델에 대한 긴 에포크 시간의 영향으로 데이터를 건드려보는 생각까지 닿았다는 부분이 너무 마음 아팠습니다. (다들 학습시간 이슈가 많은듯 합니다...)
-베이스라인을 잡은 뒤 다양하게 파라미터, 데이터, 정규화, 데이터 분리 등의 다양한 실험에 따른 결과, 기대효과를 잘 기록하신 부분에서 정성이 느껴졌습니다.
