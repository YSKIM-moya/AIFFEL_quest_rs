# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영숙
- 리뷰어 : 신기성


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 주어진 문제를 해결 하는 완성된코드는 제출 하였습니다. 
       ![mastache](./images/mastache.png)
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 스티커를 붙이기 위해서 rectangle를 설정해주고 얼굴영역과 landmark를 표시.
    - annotation 도 잘 기술 되어있다. 
    -코드의 기능 과 주석등을 설명을 잘 해 놓았다. 
    - 주석을 보고 이해가 갔고 설명을 잘해 주셨습니다.
       ![landmark](./images/landmark.png) 
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 네 원인 및 디버깅 문제를 기록에 남기고 해결 하셨습니다. 
    - 또한 프로젝트 평가 기준에 더해서 시도를 한 흔적이 있습니다. 
       ![try](./images/try.png)
       ![try2](./images/try2.png)
       ![problem1](./images/problem1.png)
       ![resolved](./images/resolved.png)
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 네 회고는 설명으로 해주셨습니다.

- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드가 잘 작되었고 가이드라인은 준수 한 것 같습니다.  
        ![code](./images/code.png)


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 참고한 링크는 없지만, 확실히 코드와 깔끔한 설명이 좋았고, 딱히 큰 문제는 없었던거 같습니다. 
```
## Face Detection + Sticker 붙이기 ##
- OpenCV 라이브러리로 2D 이미지 처리
  > OpenCV 는 BGR(파랑, 녹색, 빨강)을 사용 -> RGB로 변경하여 이미지 출력해야 
- dlib의 face detector 사용
  > HOG(Histogram of Oriented Gradients)"-이미지에서 색상의 변화량 나타냄"와 SVM(Support Vector Machine)"-선형분류기"을 사용해서 얼굴을 찾는다
- 얼굴 랜드 마크 :  shape_predictor_68_face_landmarks.dat
  > 이목구비의 위치를 추론하는 것을 face landmark localization 기술
- 스티커
  > 원본 이미지에 스티커를 붙일 영역만, 스티커이미지를 덮어씌운다.
