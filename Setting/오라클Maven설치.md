# 오라클 ojdbc6.jar 메이븐 리파지토리에 수동 설치

### maven tool 다운로드
(메이븐 바로가기)[http://maven.apache.org/]

메이븐 다운로드 폴더에서 확인
C:\bizwork\apache-maven-3.6.2\bin\mvn.cmd

시스템의 path 정보에 bin/mvn 폴더 등록
C:\oraclexe\app\oracle\product\11.2.0\server\bin;;C:\Program Files (x86)\Common Files\Oracle\Java\javapath;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Windows\System32\OpenSSH\;C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common;C:\Program Files\Git\cmd;C:\Program Files\Java\jdk1.8.0_221\bin;C:\bizwork\apache-maven-3.6.2\bin

// 윈도의 cmd 사용할때(PowerShell 사용불가)
// 오라클 ojdbc.jar를 POM 리파지토리에 저장
// oracle 11gxe가 컴퓨터에 설치되어 있을때 
mvn install:install-file -Dfile=C:/oraclexe/app/oracle/product/11.2.0/server/jdbc/lib/ojdbc6.jar -Dpackaging=jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=C:/bizwork/jdk_3rd/repo


// ojdbc6.jar 파일이 사용자의 다운로드 폴더에 저장되어 있을때 
mvn install:install-file -Dfile=/user/home/callor/Dowonload/ojdbc6.jar -Dpackaging=jar -DgeneratePom=true -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=C:/bizwork/jdk_3rd/repo

mvn install:install-file -Dfile=C:/Users/callor/Downloads/devTools/JDK_3rd/ojdbc8.jar -Dpackaging=jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=C:/user/callor/maven

// git bash 사용할때
// 오라클 ojdbc.jar를 POM 리파지토리에 저장
./mvn install:install-file -Dfile=/c/oraclexe/app/oracle/product/11.2.0/server/jdbc/lib/ojdbc6.jar -Dpackaging=jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -DlocalRepositoryPath=/c/bizwork/jdk_3rd/repo

