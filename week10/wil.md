# What I learned in week10

### 기초 백엔드 스터디 10주차

- **ORM 심화**

  장고 ORM 사용법

  - 클래스이름.objects.all()이라는 함수를 사용하면 모든 테이블 정보를 객체로 만들어 리스트에 넣어 반환한다.
  - 클래스이름.objects.get()이라는 함수를 사용하면 조건에 맞는 데이터를 객체로 만들어 반환한다.
  - DB에 저장을 하고 싶을 때는? -> 객체를 만들어 값을 직접 저장한다.
  - DB에 저장된 값을 수정하고 싶을 때는? -> 저장되어 있는 값을 가져온 다음 필요한 값을 수정하고 다시 저장해야한다.
  - DB에 저장된 값을 검색하고 싶을 때는? -> or연산을 사용하여 제목에 검색내용이 포함되어 있거나 내용에 포함되어 있으면 모두 가져온다.

---