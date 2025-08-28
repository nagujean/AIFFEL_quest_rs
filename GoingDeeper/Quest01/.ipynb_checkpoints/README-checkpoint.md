# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김형일
- 리뷰어 : 박범찬


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="584" height="357" alt="image" src="https://github.com/user-attachments/assets/535a057c-b933-4a6d-a6a6-d90c4919c608" />
          <img width="597" height="671" alt="image" src="https://github.com/user-attachments/assets/1bc8303c-39ae-4984-9041-ba3e48061397" />
        - 주어진 조건에 맞게 코드를 잘 완성하셨습니다!
            - 조건1 : 코퍼스 분석, 전처리, SentencePiece 적용, 토크나이저 구현 및 동작이 빠짐없이 진행하였다.
            - 조건2 : SentencePiece 토크나이저가 적용된 Text Classifier 모델이 정상적으로 수렴하여 80% 이상의 test accuracy가 확인되었다.
            - 조건3 : SentencePiece 토크나이저를 활용했을 때의 성능을 다른 토크나이저 혹은 SentencePiece의 다른 옵션의 경우와 비교하여 분석을 체계적으로 진행하였다.

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="714" height="359" alt="image" src="https://github.com/user-attachments/assets/17b14b87-7ea7-4ac6-b7d7-18607bc49885" />
          <img width="717" height="376" alt="image" src="https://github.com/user-attachments/assets/5efb5621-2a32-4254-a1b1-7dd78158f29d" />
          - 데이터를 학습하고 훈련하는 부분과 메인 블록으로 실행하는 부분이 복잡하다고 느껴졌는데 그 부분에 대한 주석을 간결하게 작성하셨습니다!
          
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="870" height="592" alt="image" src="https://github.com/user-attachments/assets/09160a6a-b03a-45bc-b50d-79756a4dc63e" />
        <img width="912" height="573" alt="image" src="https://github.com/user-attachments/assets/fc46b575-39ee-4d1c-83cb-56a0b87d167b" />
        - 에러가 난 부분은 없고, 여러 실험과정에서의 기록들과 평가 루브릭에 대한 조건을 만족시키도록 코드를 여러 방면으로 수정하셨습니다

           
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="903" height="282" alt="image" src="https://github.com/user-attachments/assets/af2682dd-bd44-4632-a3bb-1d356274a100" />
        - 주어진 프로젝트에 대한 결론과 회고를 잘 작성하셨습니다!

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="819" height="641" alt="image" src="https://github.com/user-attachments/assets/00afee04-355e-42db-9d32-1fb58e896409" />
          <img width="615" height="450" alt="image" src="https://github.com/user-attachments/assets/ee3c46cd-a817-4172-a3bc-c54a7aac1b99" />
          - 코드가 간결하게 잘 작성되었으며 개인적으로 코드들과 실험결과에 대한 부분들을 나눠서 정리하신 부분들이 인상 깊었습니다!



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

목표 자체를 텍스트 처리와 토크나이저에 대한 이해를 두고 시작하여 이 부분들을 이해하겠다는 목표를 잡으신 티가 확실히 나시는거 같습니다.
Baseline 모델을 RNN 계열이면서 빠른 실험이 가능한 GRU를 선택하셨으며 해당 코드를 잘 작성해주셨습니다.

늘 부족한 시간 속에서 베이스라인을 짜고, 데이터를 정제하고, 실험결과를 내는 과정들 속에서 많은 고민들이 들어가 있던 프로젝트라고 느껴집니다~