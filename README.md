# :scream_cat: 참고자료 모음

## :racehorse:[개발도구](https://github.com/callor/Reference/blob/master/개발자를_위한_도구.md)

- 개발도구 링크 모음

## :cat:[settings.xml](https://github.com/callor/Reference/tree/master/Setting/maven-repo)

- maven reposotory 설정용

## :ox:[logback-test.xml](https://github.com/callor/Reference/blob/master/Setting/logback/logback-test_UTF-8-new.xml)

- logback log message 설정

## :hamster:[web.xml Encoding](https://github.com/callor/Reference/blob/master/Setting/server/web_Kor.xml)

- SpringMVC 한글 Filter와 namespace 설정

## :hamster:[web.xml Security](https://github.com/callor/Reference/blob/master/Setting/server/web_Security.xml)

- SpringMVC 한글 Filter, Security 설정

## :dolphin:[mybatis-config.xml](https://github.com/callor/Reference/blob/master/Setting/mybatis/mybatis-config.xml)

- maven, spring, oracle mybatis 설정

## :ox:[mybatis-mapper.xml](https://github.com/callor/Reference/blob/master/Setting/mybatis/mybatis-mapper.xml)

- mybatis mapper 설정

## :blowfish:[gitignore](https://github.com/callor/Reference/blob/master/.gitignore)

- Java Sprint Project git hub 업로드 금지 파일 목록

## :dromedary_camel:[Nodejs_gitignore](https://github.com/callor/Reference/blob/master/.Nodejs_gitignore)

- NodeJs git hub 업로드 금지 파일 목록

## :blowfish:[마크다운 이모지](https://github.com/callor/Reference/blob/master/마크다운이모지.md)

- git hub markdown 이모지 모음
- 원본출처 : https://www.webfx.com/tools/emoji-cheat-sheet/

## :baby_chick:[마크다운작성](https://github.com/callor/Reference/blob/master/마크다운작성.md)

- 마크다운 문서 작성법 정리
- 원본출처 : https://gist.github.com/ihoneymon/652be052a0727ad59601#file-gistfile1-md

## :moneybag:[프로젝트 샘플데이터](https://github.com/callor/Reference/blob/master/샘플데이터)

- [Open Project](https://github.com/callor/Callor-Open-Project)
- [Gallery](https://github.com/callor/Reference/blob/master/샘플데이터/Gallery데이터)
- [게시판](https://github.com/callor/Reference/blob/master/샘플데이터/게시판데이터)
- [도서정보](https://github.com/callor/Reference/blob/master/샘플데이터/도서정보데이터)
- [매입매출](https://github.com/callor/Reference/blob/master/샘플데이터/매입매출데이터)
- [정의서,양식](https://github.com/callor/Reference/blob/master/샘플데이터/정의서파일)
- [학사,성적](https://github.com/callor/Reference/blob/master/샘플데이터/학사_성적데이터)

## :cyclone:[자바자료형](https://github.com/callor/Reference/blob/master/자바자료형.md)

- 자바 primitive 자료형 정리

## :dog:정규식 문법

- 비밀번호 검사 1 : 특수문자 / 문자 / 숫자 포함 형태의 8~15자리 이내의 암호 정규식

```
/^.*(?=^.{8,15}$)(?=.*\d)(?=.*[a-zA-Z])(?=.*[!@#$%^&+=]).*$/
```

- 비밀번호 검사 2 : 숫자와 문자 포함 형태의 6~12자리 이내의 암호 정규식

```
/^[A-Za-z0-9]{6,12}$/;
```

- 이메일 정규식

```
/^[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*@[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*.[a-zA-Z]{2,3}$/i
```

- 핸드폰번호 정규식

```
/^\d{3}-\d{3,4}-\d{4}$/
```

- 일반 전화번호 정규식

```
/^\d{2,3}-\d{3,4}-\d{4}$/
```

- 사용하는 법

```
const emailRule =/^[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*@[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*.[a-zA-Z]{2,3}$/i;
if( emailRule.test("callor") ){

	console.log("Email 형식이 맞음");

} else {

	console.log("Email 형식이 맞지 않음");

}


```

## 2021-07-21

## :dog:[ojdbc6 설치](https://github.com/callor/Reference/blob/master/Setting/Ojdbc6_Maven_Local.md)

- 오라클 ojdbc6.jar 로컬 maven reposotory 설치
- maven 공식 다운로드 가능
  [바로가기](https://mvnrepository.com/artifact/com.oracle.database.jdbc/ojdbc8)
