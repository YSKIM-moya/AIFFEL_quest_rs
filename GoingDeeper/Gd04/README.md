# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영숙
- 리뷰어 : 서지연


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 번역된 문장에 대한 어텐셥 맵을 제시하였다.
        - ![image](https://github.com/user-attachments/assets/05d0098f-a9e9-4fdc-a10b-4594ac032217)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 디코더에 인코더의 hidden state를 연결해주는 작업을 잘 설명하였다.
        - ![image](https://github.com/user-attachments/assets/924f66d4-5b97-4223-bb5e-471d7134eb03)
        - ![image](https://github.com/user-attachments/assets/9a79bfd3-6ffc-4b1f-95e2-b970305760d7)


        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 번역이 잘 되고있는지 확인하였다.
        - ![image](https://github.com/user-attachments/assets/193bc438-8b1b-4c0d-bf7e-a966180295d2)

- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 오류에 대한 회고를 잘 작성하였다.
        - ![image](https://github.com/user-attachments/assets/4eef2d95-05a8-467c-b56d-b39c67509f42)

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 문장 길이를 구하는 작업을 함수화 하여 효율적으로 진행하였다.
        - ![image](https://github.com/user-attachments/assets/2dadb0f6-b9f3-4331-aa4a-8c676f393313)


# 회고(참고 링크 및 코드 개선)
```
문장 길이를 구할 때 띄어쓰기 기준으로 토큰화 한 후 문장길이를 구하면 좋을 거 같다. 
```

