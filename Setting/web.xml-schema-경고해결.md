# eClipse에서 Dynamic Web Project의 web.xml 경고, 오류 해결

* eClipse의  
Window -> Preferences -> WEB and XML : XML catalog Entries 설정에서  
User Specified Entries 을 선택하고 [ Add ] 버튼을 눌러 아래 내용 입력
  


-------------------------------------------------------------------------------
Location : http://java.sun.com/xml/ns/j2ee/j2ee_web_services_client_1_1.xsd 
Key Type: Schema Location
Key: http://www.ibm.com/webservices/xsd/j2ee_web_services_client_1_1.xsd 
-------------------------------------------------------------------------------

* 재 설정을 하고 오류표시가 나는 프로젝트의 WEB-INF/web.xml 파일을 재 저장
