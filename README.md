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

## 주요모듈

### 전자정부프레임워크 표준 실행환경

### log4j2
- log4j-core
- log4j-api
- log4j-slf4j-impl
- log4jdbc-log4j2-jdbc4

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

## reference 
HikariCP : https://hudi.blog/dbcp-and-hikaricp/
