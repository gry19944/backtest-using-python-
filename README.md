# backtest-using-python-
backtest using python / selecting additive buying point

In Korean
준비사항

1. 저는 젠포트 라는 백테스팅 지원 사이트에서 백테스팅 전략을 이미 만들어서 사용 중 입니다.
2. 그런데 젠포트는 추가매수 기능을 지원해주지 않습니다.
3. 그래서 언제 추가매수를 해야 이익을 극대화 혹은 손실을 최소화 할 수 있을지 테스트 해보기 위해 코딩해봤습니다.

내용

1. 젠포트에서 거래내역을 다운받아 알맞게 정리 (올려둔 code.csv 형식으로 저장)
2. csv파일을 불러와 개별 종목의 11일치 주가를 각각의 csv폴더에 저장 (저는 종목을 10일 보유하고 그 다음날(11일)에 매도하기 때문에 11일로 하였음)
3. 반복문을 통해 추가매수 지점을 설정하고 최저가, 종가를 찾아 수익률을 계산

기타 내용은 주석처리하여 설명해놨습니다.

=============================================

In English(Using Naver Papago translator)

Preparations

1. I have already developed and used a backtesting strategy on the backtesting support site called Jenport.
2. However, the JENport does not support the purchase function.
3. So we've coded to test when we can maximize profits or minimize losses.

content

1. Download the transaction details from the GENport and organize them accordingly (save them in the code.csv format you)
2. Invoke a csv file and store 11 days' worth of individual stocks in each csv folder (I held the stocks for 10 days and sold them for 11 days the following day)
3. Set additional point of purchase through repeat statement and calculate return by finding lowest price and end price

Other details have been annotated and explained.
