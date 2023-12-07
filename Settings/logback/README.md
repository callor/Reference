# logback pattern
* String.format("%s %d","문자열",100);

## logback form 패턴




	[Layout]
	%m : 로그내용이 출력
	%m : log.info("문자열") 문자열을 표시하는 패턴 
	%n : new line 줄바꿈  
	%n :  플랫폼 종속적인 개행문자가 출력된다. \r\n 또는 \n 일것이다

	%p : trace > debug > info > warn > error 등의 priority 출력
	%r : 어플리케이션이 시작되어 로깅이벤트가 발생하는 시점까지의 경과시간을 밀리세컨드로 출력
	%c : 예) 카테고리가 a.b.c 처럼 되어있다면 %c{2}는 b.c가 출력됩니다.

	
	%d : 로깅이벤트가 일어나 날짜 출력 ( 프로그램의 실행속도를 느리게 한다.)
	 예) %d{HH:mm:ss} 또는 %d{dd MMMM yyyy HH:mm:ss}
	%d{HH:mm:ss.SSS} : 현재 시간 표시, 시간을 표시하면 서버 딜레이가 발생할수 있다

	%C : 호출자의 클래스명 출력
	예) 클래스구조가 org.apache.xyz.SomeClass 처럼 되어있다면 %C{2}는 xyz.SomeClass 가 출력됩니다
	%M : 로깅이 발생한 method 이름을 나타냅니다.
	%F : 로깅이 발생한 프로그램 파일명을 나타냅니다.
	%l : (level)로깅이 발생한 caller의 정보를 나타냅니다 
	%L : 로깅이 발생한 caller의 라인수를 나타냅니다 
	%x : 로깅이 발생한 thread와 관련된 NDC(nested diagnostic context)를 출력합니다. 
	%X : 로깅이 발생한 thread와 관련된 MDC(mapped diagnostic context)를 출력합니다. 
	%% : % 표시를 출력하기 위해 사용한다.  
	%t : (thread) 로그이벤트가 발생된 쓰레드의 이름을 출력합니다

	%-5level : 출력할때 사용한 level(method) 표시


## logback level(method)
* logger.trace("트레이스")
* logger.debug("디버그");
* logger.info("인포");
* logger.warn("워닝");
* logger.error("에러");

* 사용법 : level을 error로 설정하면 상위 level의 method의 출력은 모두 무시된다.
* 사용법 : level을 info로 설정하면 trace, debug는 무시되고, info, warn, error method의 출력만 나타난다
