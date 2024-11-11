# What I learned in week9

### 기초 백엔드 스터디 9주차

- **HTTP Method**

  브라우저 캐싱: 캐시(cache)는 컴퓨터 과학에서 데이터나 값을 미리 복사해 놓는 임시 장소를 가리킨다. 캐시에 데이터를 미리 복사해 놓으면 계산이나 접근 시간없이 더 빠른 속도로 데이터에 접근할 수 있다.

  HTTP Method : GET, POST
  GET -> 단순 조회 요청, 여러번 요청해도 결과 동일, url에 정보를 넣어 전달해도 됨, 캐싱 가능
  POST -> 새로운 리소스 생성 요청, 요청마다 결과 변경 가능, 민감한 정보를 다룸, 캐싱 불가능

  웹 통신 흐름: client가 GET방식으로 Http request후 server가 POST방식으로 HTTP response로 요청한 자료를 보내줌

- **Form 태그**

  데이터를 입력받고 전송하기 위한 태그
  Input 태그에서 데이터를 입력받을 수 있고, form 태그의 action 속성의 url로 전송한다.

  input태그의 type 속성을 이용해 입력받을 데이터의 양식을 정할 수 있다.
  type = "submit"인 input 태그 혹은 <button> 태그를 사용하면 제출버튼을 만들 수 있다. name 속성을 이용해 정보를 전달할 때 키 값을 지정할 수 있다.

---
