# Weather
날씨 일기 프로젝트

* 패키지 구조
- config : API documentation, Exception handler
- controller : API의 endpoint를 등록하고, 요청/응답의 형식을 갖는 클래스 패키지
- domain : jpa entity
- error : 커스텀 Exception, Exception Handler 클래스 패키지
- repository : Repository(DB에 연결할 때 사용하는 인터페이스)가 위치하는 패키지
- service : 비즈니스 로직을 담는 서비스 클래스 패키지
