# Logback

## Appender 종류
* ConsoleAppender : 콘솔에 log를 출력
* FileAppender : 파일 단위로 log 를 저장
* RollingFileAppender : (설정 옵션에 따라) log 를 여러 파일로 나누어 저장
* SMTPAppender : log 를 메일로 전송 하여 기록
* DBAppender: log 를 DB에 저장

### Logback 사용이유
* 운영을 위해서는 Log는 반드시 필요하다.
* Logback 설정을 하여 운영을 하기 위한 Log를 관리한다. 
* 뿐만 아니라 데이터는 돈이므로 Log는 곧 값 비싼 자산이다.