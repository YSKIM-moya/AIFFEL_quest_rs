# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김영숙
- 리뷰어 : 반태훈


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 넵
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

X = np.array(df_X)
y = np.array(df_y) / 346
346 나누기 하니까 값이 훨씬 안정적으로 나온다

        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**

from sklearn.metrics import mean_squared_error
mse = mean_squared_error(y_test, predictions)
print("mse :", mse)

#from sklearn.metrics import root_mean_squared_error
#rmse = root_mean_squared_error(y_test, predictions)

rmse = np.sqrt(mse)
print("rmse:", rmse)

rmse mse 하는방법에대해서 잘해주신것같습니다!!

    
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **4. 회고를 잘 작성했나요?**

     넵
    
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    넵!!
    X = train[['season', 'holiday', 'workingday', 'temp', 'atemp', 'humidity', 'registered', 'year', 'month', 'day', 'hour']].values
    y = train['count'].values
    
    의미없는 데이터들은 지우신 모습이 간결하다고 생각합니다

        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


# 회고(참고 링크 및 코드 개선)
```
오늘 처음으로 코드 리뷰라는것을 해보았다
아직 많이 부족한 실력이기에 영숙님께 많이 여쭈어 보았고, 배울 수 있는 과정이였던 것 같다
특히 count를 prediction 할때 서로 관점이 달라서 설득하는 과정이 있었는데 그부분에서 나의 잘못된생각을 바로잡을 수 있는 좋은 기회였던 거같다
```

