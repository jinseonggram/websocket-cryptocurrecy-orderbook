# Websocket 가상화페 가격 프로그램
_______

## 설명서
- 관련 라이브러리 다운로드

   - pip install -r requirements
- 서버 접속 오류 시 관리자에게 연락주세요
- \##### 여기서부터 코드를 입력해주세요 \##### : 에서부터 원하시는 코드를 입력해주세요. 

```
# 업비트
th.upbit = {'time': '2022-01-10 17:44:48', 'code': 'KRW-BTC', 'ask_price': 51311000.0, 'bid_price': 51309000.0, 'ask_qty': 0.56319447, 'bid_qty': 1.36991597}

# 바이비트
th.bybit = {'time': '2022-01-10 17:45:29', 'code': 'BTCUSDT', 'ask_price': 41739.09, 'bid_price': 41739.09, 'ask_qty': 0.51545, 'bid_qty': 0.30458}

time      :  현재 시작 
code      :  코인명
ask_price :  호가 매도 가격
bid_price :  호가 매수 가격
ask_qty   :  호가 매도 수량
bid_qty   :  호가 매수 수량

```


### 관련 문서
- 바이낸스 공식 문서 :  https://github.com/binance/binance-spot-api-docs/blob/master/web-socket-streams.md
- 업비트 공식 문서 :  https://docs.upbit.com/docs/upbit-quotation-websocket