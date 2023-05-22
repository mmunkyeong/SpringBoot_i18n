# SpringBoot_i18n
스프링 국제화 테스트(Message, Internationalization) 🌍

### 메시지란?
여러 페이지에 있는 다양한 메시지들을 한 곳에서 관리하는 기능

### 국제화란?
나라언어 우선순위에 따라 메시지를 해당하는 나라 언어로 변경해주는 기능입니다. 예를 들면, 한국어 번역을 누르면 영어를 한국어로 바꿔주는 역할이 국제화 기능입니다. 

<br>

- messages.properties에 hello 번역정보를 추가
- messages_ko.properties, messages_en.properties 추가, 브라우저 설정에 따라 언어가 결정되도록
- 번역정보에 매개 변수 기능 사용
- 번역 정보에 매개변수로 번역정보 사용
- 기존 MessageSource 클래스 확장하여 특정 조건이 맞족할 때, 작동하는 로직을 삽입
