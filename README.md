># LottoAI
Crawling &amp; AI

https://www.dhlottery.co.kr/common.do?method=getLottoNumber&drwNo={번호}
- 번호는 회차를 의미한다.

```javascript
// 번호에 1을 넣었을 때 예시
{"totSellamnt":3681782000,
 "returnValue":"success",
 "drwNoDate":"2002-12-07",
 "firstWinamnt":0,
 "drwtNo6":40,
 "drwtNo4":33,
 "firstPrzwnerCo":0,
 "drwtNo5":37,
 "bnusNo":16,
 "firstAccumamnt":863604600,
 "drwNo":1,
 "drwtNo2":23,
 "drwtNo3":29,
 "drwtNo1":10}
```

|Key|Value|
|:--:|:--:|
|totSellamnt|총 판매금액|
|returnValue|실행 결과|
|drwNoDate|추첨 일자|
|firstWinamnt|1등 수령액|
|firstPrzwnerCo|1등 당첨 인원|
|firstAccumamnt|총 1등 당첨금|
|drwNo|회차|
|drwtNo1~6|당첨 번호|
|bnusNo|보너스 번호|
