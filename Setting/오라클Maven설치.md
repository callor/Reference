# 오라클 ojdbc6.jar 메이븐 리파지토리에 수동 설치

## maven tool 다운로드
(메이븐 바로가기)[http://maven.apache.org/]

## 다운로드 받은후 작업폴더에 압축 풀고 다운로드 폴더에서 다음 파일 확인
#### cd c:\bizwork\apache-maven-x.x.x\bin  명령실행
#### dir C:\bizwork\apache-maven-x.x.x\bin\mvn.cmd 명령실행
#### x.x.x 버전번호 : 예 3.6.2

## 윈도우에서 cmd 사용할때
#### PowerShell은 사용할 수 없음
#### 오라클 11gXe가 설치된 경우에는 아래 코드 그대로 사용가능
#### mvn install:install-file -Dfile=C:/oraclexe/app/oracle/product/11.2.0/server/jdbc/lib/ojdbc6.jar -Dpackaging=jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=C:/bizwork/jdk_3rd/repo

#### 명령 끝에 -DlocalRepositoryPath=C:/bizwork/jdk_3rd/repo 부분 주의!! : 본인의 maven repository

## 별도로 ojdbc6.jar 파일을 다운로드 받았아 사용자의 다운로드 폴더에 저장했을 경우 
#### /user/home/callor/Dowonload/ojdbc6.jar 
#### mvn install:install-file -Dfile=/user/home/callor/Dowonload/ojdbc6.jar -Dpackaging=jar -DgeneratePom=true -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=C:/bizwork/jdk_3rd/repo


## git bash 사용할때
#### 오라클 11gXe가 설치된 경우 아래 코드 그대로 사용가능
#### ./mvn install:install-file -Dfile=/c/oraclexe/app/oracle/product/11.2.0/server/jdbc/lib/ojdbc6.jar -Dpackaging=jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=/c/bizwork/jdk_3rd/repo

## 코드 복사 붙이기 할때는 일단 메모장 같은 곳에 복사 붙이기 한후 모두 한줄로 만들고 복사 붙이기 할것

