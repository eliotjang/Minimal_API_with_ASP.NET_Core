## 웹서버 방식 Todo-List 구현 실습

### **기술 스택 및 학습 내용**

- **언어 및 프레임워크**: C# ASP.NET Core
- **데이터베이스**: Entity Framework Core
- **구현 메소드**: GET, POST, PUT, DELETE

### **주요 특징**

- **RESTful API 디자인**
    - HTTP 메서드를 활용하여 Todo 항목의 CRUD 작업을 수행하는 RESTful API 구현
- **Entity Framework Core 활용**
    - In-Memory Database를 이용하여 Todo 항목 저장 및 데이터를 수정
- **비동기 프로그래밍**
    - 비동기 방법을 활용하여 데이터베이스 작업을 효율적으로 처리
- **API 결과 처리**
    - TypedResults를 사용하여 API 요청에 대한 적절한 HTTP 상태 및 응답 반환
- **라우팅 및 그룹화**
    - ASP.NET Core의 라우팅을 활용하여 API 엔드포인트를 효율적으로 구조화하고 그룹화
- **DTO 활용**
    - 데이터 전송 객체 (DTO)를 활용하여 API에서 전송되는 데이터의 형식을 표준화
- **Swagger 문서 자동화**
    - Swagger를 통한 API 문서 자동 생성 및 편리한 API 테스트 환경 생성
- **예외 처리 필터**
    - DatabaseDeveloperPageExceptionFilter를 사용하여 개발 중 예외를 적절하게 처리

### 주요 소스코드 구현
- [기본 API 방식](Program.cs)
- d
- d
