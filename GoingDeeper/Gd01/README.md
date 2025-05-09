# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영숙
- 리뷰어 : 조성호


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 예
    - 성능이 80% 이상이며, 여러 vocab size에 대해 비교분석했다.
![image](https://github.com/user-attachments/assets/0f79a18f-1e91-415b-b99b-5e5656a070f6)

![image](https://github.com/user-attachments/assets/508bcfde-04bf-44f2-aac2-957a2869d147)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 예
    - 토크나이저 학습에 필요한 하이퍼 파라미터에 주석 처리가 되어있고, 그 중 자신이 수정해본 하이퍼 파라미터(VOCAB_SIZE, seq_max_len)가 무엇인지 이해할 수 있게 설명하였다.
![image](https://github.com/user-attachments/assets/b657d447-1616-48e6-bad7-5cf9d7cf889c)

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 예
    - vocab size 별로 테스트를 반복 진행하여 어떤 차이가 있는지 설명함.
![image](https://github.com/user-attachments/assets/eb07a2fe-63d7-4d09-a02a-6cac91c664e0)

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 예
    - 많은 내용이 담겨있진 않으나, 시도한 실험에 대한 결과가 잘 정리되어 있다.
![image](https://github.com/user-attachments/assets/36ba7c27-09e0-4995-81ef-3cde437c94e2)

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 예
    - 반복 사용하는 어휘 사전 제작 함수와 토크나이즈 수행 함수를 만들어 코드 중복을 피했다.
![image](https://github.com/user-attachments/assets/9e518400-20bc-4140-9e43-8ff63b6649d0)


# 회고(참고 링크 및 코드 개선)
```
저는 2번밖에 실험해보지 못한 vocab size별 실험 결과를 더 많이 확인할 수 있어 좋았습니다.
vocab size를 다르게 한 경우 어휘 사전의 단어들이 어떻게 바뀌는지 궁금했는데 그 내용에 대한 답을 얻지 못해 아쉬웠습니다.
```

