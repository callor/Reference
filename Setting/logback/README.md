# logback pattern
* String.format("%s %d","문자열",100);

## logback form 패턴
* %m : log.info("문자열") 문자열을 표시하는 패턴 
* %n : new line 줄바꿈  
* %d{HH:mm:ss.SSS} : 시간표시  
* %-5level : 출력할때 사용한 level(method) 표시

## logback level(method)
* logger.trace("트레이스")
* logger.debug("디버그");
* logger.info("인포");
* logger.warn("워닝");
* logger.error("에러");

* level을 error로 설정하면 상위 level의 method의 출력은 모두 무시된다.
* level을 info로 설정하면 trace, debug는 무시되고, info, warn, error method의 출력만 나타난다
