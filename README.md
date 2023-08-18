# :scream_cat: 참고자료 모음

## :racehorse:[개발도구](https://github.com/callor/Reference/blob/master/개발자를_위한_도구.md)

- 개발도구 링크 모음

## :cat:[pom.xml](https://github.com/callor/Reference/blob/master/Setting/maven-repo/pom-2023-07-25-.xml)

- Spring MVC Project 표준 pom.xml : 2023. 07. 25일 Tomcat 9 호환


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

- Java, Spring Project git hub 업로드 금지 파일 목록

## :dromedary_camel:[Nodejs_gitignore](https://github.com/callor/Reference/blob/master/.Nodejs_gitignore)

- NodeJs, React Project git hub 업로드 금지 파일 목록

## :blowfish:[마크다운 이모지](https://github.com/callor/Reference/blob/master/마크다운이모지.md)

- git hub markdown 이모지 모음
- 원본출처 : https://www.webfx.com/tools/emoji-cheat-sheet/

## :blowfish:W3C SVG 이미지

![search](https://github.com/callor/Reference/assets/23270330/72c8868d-e115-4177-95c3-9cd9a2f5fc67){:style="border-radius:50%;padding: 0px;" width="100px" height="100px"}

```css
url(data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' class='h-6 w-6' fill='none' viewBox='0 0 24 24' stroke='%23999' stroke-width='2'%3E%3Cpath stroke-linecap='round' stroke-linejoin='round' d='M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z' /%3E%3C/svg%3E)
```

<img src="https://github.com/callor/Reference/assets/23270330/1c556861-09be-49d4-828a-a223895921ca" 
	style="border-radius:50%;" width="100px" height="100%" alt="spinner"/>

```css
url(data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='none' viewBox='0 0 24 24'%3E%3Cpath stroke='%23000' strokeLinecap='round' strokeLinejoin='round' strokeWidth='2' d='M20 4v5h-.582m0 0a8.001 8.001 0 00-15.356 2m15.356-2H15M4 20v-5h.581m0 0a8.003 8.003 0 0015.357-2M4.581 15H9' /%3E%3C/svg%3E)
```

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

## :dog:자바 Primitive 자료형

| 종류    | 설명           | 저장 공간       | 값의 범위 (최소값~최대값)                                                 |
| ------- | -------------- | --------------- | ------------------------------------------------------------------------- |
| boolean | 논리값         | 1 bits          | true / false                                                              |
| byte    | 부호 있는 정수 | 8bits, 1Byte    | -128 ~ 127                                                                |
| char    | 유니코드 문자  | 16bits, 2Bytes  | \u0000 ~ \uFFFF                                                           |
| short   | 부호 있는 정수 | 16bits, 2Bytes  | -32768 ~ 32767                                                            |
| int     | 부호 있는 정수 | 32bits, 4Bytes  | -2147483648 ~ 2147483647                                                  |
| long    | 부호 있는 정수 | 64bits, 8Bytes  | -9223372036854775808 ~ 9223372036854775807                                |
| float   | IEEE 754 실수  | 32bits, 4Bytes  | 1.40239846E-45f ~ (표현 가능 양수 범위) 3.40282347E+38f                   |
| double  | IEEE 754 실수  | 64 bits, 8Bytes | 4.94065645841246544E-324 ~ (표현 가능 양수 범위) 1.79769313486231570E+308 |

## :cyclone:정규식 문법

- 비밀번호 검사 1 : 숫자와 문자 포함 형태의 6~12자리 이내의 암호 정규식

```
/^[A-Za-z0-9]{6,12}$/;
```

- 비밀번호 검사 2 : 특수문자 / 문자 / 숫자 포함 형태의 8~15자리 이내의 암호 정규식

```
/^.*(?=^.{8,15}$)(?=.*\d)(?=.*[a-zA-Z])(?=.*[!@#$%^&+=]).*$/
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

- JavaScript 에서 사용하는 법

```
const emailRule =/^[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*@[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*.[a-zA-Z]{2,3}$/i;
if( emailRule.test("callor") ){

	console.log("Email 형식이 맞음");

} else {

	console.log("Email 형식이 맞지 않음");

}


```

## :dog:[ojdbc6 설치](https://github.com/callor/Reference/blob/master/Setting/Ojdbc6_Maven_Local.md)

- 오라클 ojdbc6.jar 로컬 maven reposotory 설치

## :dog:[ojdbc8 설치](https://mvnrepository.com/artifact/com.oracle.database.jdbc/ojdbc8)

- 2021-07-21 이후 maven 공식 다운로드 가능 : `ojdbc8`
