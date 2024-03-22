# 1.4 트랜잭션

* HTTP 트랜잭션은 요청 명령(클라이언트 -> 서버) 과 응답 결과(서버 -> 클라이언트) 로 구성
* 이 상호작용은 HTTP 메시지라고 불리는 정형화된 데이터로 이루어짐
* 요청 명령
```
GET /specials/saw-blade.gif HTTP/1.0
Host: www.joes-hardware.com
```
* 응답 결과
```
HTTP/1.0 200 OK
Content-type: image/gif
Content-length: 8572
```