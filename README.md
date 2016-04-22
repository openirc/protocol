# 프로토콜

이 문서는 openirc에서 서버와 클라이언트가 어떤 것을 얼마나 어떻게 서로 주고받을지를 기술합니다.


## 방법

[웹소켓](http://tools.ietf.org/html/rfc6455)을 통해서 데이터를 주고받습니다.


## 데이터 포맷

[메세지팩](http://msgpack.org/index.html)을 사용합니다.

주고받는 메세지팩 데이터는 무조건 `object` 형태여야 합니다.

