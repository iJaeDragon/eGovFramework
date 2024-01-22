# eGovFramework

## 환경
<table>
  <tr>
    <th>jdk</th>
    <td>JDK 1.8.0_191</td>
  </tr>
  <tr>
    <th>jre</th>
    <td>JRE 1.8.0_191</td>
  </tr>
  <tr>
    <th>eGovFramework</th>
    <td>3.8.0</td>
  </tr>
</table>

## 주요모듈 (pom.xml)

### 전자정부프레임워크 표준 실행환경

### log4j2
- log4j-core
- log4j-api
- log4j-slf4j-impl
- log4jdbc-log4j2-jdbc4
  - src/main/resources/log4j2.xml
  - src/main/resources/log4jdbc.log4j2.properties

### DB Connector
- HikariCP
  - commons-dbcp -> HikariCP
  ![image](https://github.com/iJaeDragon/eGovFramework/assets/66985977/26b71e28-0d52-4771-95ff-2795f207fae6)

- mysql-connector-java

### jackson (json)
- jackson-databind
- jackson-dataformat-xml

### file
- commons-fileupload
- commons-io

## Spring Context
- /src/main/resources/egovframework/spring/context-aspect.xml
- /src/main/resources/egovframework/spring/context-common.xml
- /src/main/resources/egovframework/spring/context-datasource.xml
- /src/main/resources/egovframework/spring/context-idgen.xml
- /src/main/resources/egovframework/spring/context-properties.xml
- /src/main/resources/egovframework/spring/context-sqlMap.xml
- /src/main/resources/egovframework/spring/context-transaction.xml
- /src/main/resources/egovframework/spring/context-validator.xml

## Pattern
![image](https://github.com/iJaeDragon/eGovFramework/assets/66985977/b8aab9e8-8f83-43c1-b4b2-9be3e7593d05)

## reference 
- HikariCP
  - https://hudi.blog/dbcp-and-hikaricp/
  - https://codevang.tistory.com/264
- log4j2
  - https://rimkongs.tistory.com/312
- eGovFramework
  - https://bkjo94.tistory.com/entry/%EC%A0%84%EC%9E%90%EC%A0%95%EB%B6%80-%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-%EC%83%98%ED%94%8C-%EC%BD%94%EB%93%9C-%EB%B6%84%EC%84%9Dcontext-aspectxml
