# AIFFEL Campus Online Code Peer Review Templete
- 김형일 : 코더의 이름을 작성하세요.
- 원균재 : 리뷰어의 이름을 작성하세요.


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부<img width="1119" height="523" alt="image" src="https://github.com/user-attachments/assets/e203e45b-7450-4bc5-a822-022ae201ac3e" />
         Baseline, PEFT LoRA, Bucketing을 적용한 여러 실험 결과를 구체적인 지표(Accuracy, 학습 시간 등)와 함께 제시하여 모델이 정상적으로 작동했다. Bucketing을 적용했을 때 학습 시간 감소 효과가 크지 않았다는 솔직한 분석이 인상깊습니다

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="877" height="630" alt="image" src="https://github.com/user-attachments/assets/04a0503b-b808-421d-8085-3a1ff6edd08b" />
        모델의 학습 과정을 알기 쉽게 주석을 잘 달아주셨다

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부<img width="708" height="136" alt="image" src="https://github.com/user-attachments/assets/fca4f255-da0d-4655-9ba4-e7fa543161a0" />
<img width="922" height="287" alt="image" src="https://github.com/user-attachments/assets/8eba6f4e-c4c1-49c9-94ae-48ab2a3646f7" />

        <img width="1103" height="200" alt="image" src="https://github.com/user-attachments/assets/c3da1fc3-dc96-484e-a8de-9eeb09199c49" />
<img width="1093" height="163" alt="image" src="https://github.com/user-attachments/assets/2e45aa2d-b5e0-47ec-afc3-04329b8427b4" />
<img width="1023" height="321" alt="image" src="https://github.com/user-attachments/assets/7f8cd249-b9f2-4c22-9ed9-9af289d208d2" />
여러 실험을 진행하면서 나온 결론들을 잘 정리해두셨다

- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
간결하고 읽기 쉽게 잘 작성해 주셨다, 다만 colab 환경에서는 쓰기 편했던 !pip install ... 등이 보기에는 안좋았다. 나중에 출력 지우기 등으로 정리하시면 깔끔한 코드를 만들 수 있을것 같다!

# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
 노드에 없는 PEFT 의 종류인 LoRA를 적용했을때 학습시간이 줄어듦을 확인 할 수 있었다. 또한 다른 조원들과 실험 결과를 공유하면서 효율적으로 프로젝트를 진행한 내용이 보여 느끼는 점이 많았다. 
 허깅페이스 프레임워크를 사용하여 하이퍼파라미터 튜닝과 모델 구조에 더욱 집중하여 좋은 결과가 나온 것 같다! 
