# 요구사항


- `http://localhost:8080/greeting` 주소로 오는 `GET` 요청을 받아 다음과 같이 응답해 줄 수 있도록 합니다.

  ```json
  {"id":1,"content":"Hello, World!"}
  ```

- `query string`의 `name` 파라미터에 따라 다른 응답을 줄 수 있도록 합니다.
 
    - e.g.
      - `http://localhost:8080/greeting?name=User`

  ```json
  {"id":1,"content":"Hello, User!"}
  ```

- `id` 값은 매 요청 시 증가해야 합니다.