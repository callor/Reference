# :scream_cat: 참고자료 모음

### :racehorse:개발도구 링크 모음

- **2023. 8. 19.** Update

- [개발도구 바로가기](https://github.com/callor/Reference/blob/master/MarkDownDocs/개발자를_위한_도구.md)

---

### Spring STS 3 용 Legacy/MVC 프로젝트 Template
- [Spring Legacy Template](https://github.com/callor/Callor-SpringMVC-Template-2024.git)

### :cat:Spring MVC Project 표준 `pom.xml` : 2023. 07. 25일 Tomcat 9 호환

- [pom.xml](https://github.com/callor/Reference/blob/master/Setting/maven-repo/pom-2023-07-25-.xml)

---

### :cat:maven reposotory 설정용

- [settings.xml](https://github.com/callor/Reference/tree/master/Settings/maven-repo/maven-settings.xml)

---

### :cat:vsCode `settings.json` 샘플

- [settings.json](https://github.com/callor/Reference/blob/master/Settings/vsCode/settings.json)

---

### :ox:logback log message 설정

- [logback-test.xml](https://github.com/callor/Reference/blob/master/Setting/logback/logback-test_UTF-8-new.xml)

---

### :hamster:SpringMVC 한글 Filter와 namespace 설정

- [web.xml Encoding](https://github.com/callor/Reference/blob/master/Setting/server/web_Kor.xml)

---

### :hamster:SpringMVC 한글 Filter, Security 설정

- [web.xml Security](https://github.com/callor/Reference/blob/master/Setting/server/web_Security.xml)

---

### :dolphin:maven, spring, oracle mybatis 설정

- [mybatis-config.xml](https://github.com/callor/Reference/blob/master/Setting/mybatis/mybatis-config.xml)

---

### :ox:mybatis mapper 설정

- [mybatis-mapper.xml](https://github.com/callor/Reference/blob/master/Setting/mybatis/mybatis-mapper.xml)

---

### :blowfish:Java, Spring Project git hub 업로드 금지 파일 목록

- [gitignore](https://github.com/callor/Reference/blob/master/.gitignore)

---

### :dromedary_camel:NodeJs, React Project git hub 업로드 금지 파일 목록

- [Nodejs_gitignore](https://github.com/callor/Reference/blob/master/.Nodejs_gitignore)

---

### :blowfish: git hub markdown 이모지 모음

- [마크다운 이모지](https://github.com/callor/Reference/blob/master/MarkDownDocs/마크다운이모지.md)

- 원본출처 : <https://www.webfx.com/tools/emoji-cheat-sheet/>

---

### :blowfish:SVG 샘플

- [W3C SVG 이미지 샘플](https://github.com/callor/Reference/blob/master/MarkDownDocs/SVG_image.md)

---

### :baby_chick:마크다운 문서 작성법 정리

- [마크다운작성](https://github.com/callor/Reference/blob/master/MarkDownDocs/마크다운작성.md)

- 원본출처 : <https://gist.github.com/ihoneymon/652be052a0727ad59601#file-gistfile1-md>

---

### :moneybag:[프로젝트 샘플데이터](https://github.com/callor/Reference/blob/master/샘플데이터)

- [Open Project](https://github.com/callor/Callor-Open-Project)
- [Gallery](https://github.com/callor/Reference/blob/master/샘플데이터/Gallery데이터)
- [게시판](https://github.com/callor/Reference/blob/master/샘플데이터/게시판데이터)
- [도서정보](https://github.com/callor/Reference/blob/master/샘플데이터/도서정보데이터)
- [매입매출](https://github.com/callor/Reference/blob/master/샘플데이터/매입매출데이터)
- [정의서,양식](https://github.com/callor/Reference/blob/master/샘플데이터/정의서파일)
- [학사,성적](https://github.com/callor/Reference/blob/master/샘플데이터/학사_성적데이터)

---

### :dog:자바 Primitive 자료형

- [자바 자료형](https://github.com/callor/Reference/blob/master/MarkDownDocs/자바자료형.md)

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

---

### :cyclone:정규식 문법

- [정규식 문법](https://github.com/callor/Reference/blob/master/MarkDownDocs/JS정규식.md)

### :dog:[ojdbc6 설치](https://github.com/callor/Reference/blob/master/Setting/Ojdbc6_Maven_Local.md)

- 오라클 ojdbc6.jar 로컬 maven reposotory 설치
- 2021-07-21 이후 maven 에서 **objbc8** 등 공식 JDBC 다운로드 설치 가능해짐

---

### :dog:[ojdbc8 설치](https://mvnrepository.com/artifact/com.oracle.database.jdbc/ojdbc8)

- 2021-07-21 이후 maven `ojdbc8` dependency 공식 다운로드 가능 :

```xml
<!-- https://mvnrepository.com/artifact/com.oracle.database.jdbc/ojdbc8 -->
<dependency>
    <groupId>com.oracle.database.jdbc</groupId>
    <artifactId>ojdbc8</artifactId>
    <version>23.2.0.0</version>
</dependency>

```
