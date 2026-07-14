<!-- codex-summary:start -->
# exam3

An SAP Fiori application.

## 구현 기능 요약

### App 화면

- 역할: 화면 정보 표시와 사용자 입력 처리

### 직원 상세 정보 화면

- 역할: 상세 정보 표시·편집, 업무 명령 실행
- 주요 항목: 기본정보, 직원ID, 호칭, 이름, 직위, 입사일, 생일, 주소정보
- 사용자 동작: 팝업 또는 화면 닫기 [onCloseDialog]

### Main 화면

- 역할: 목록 조회 및 항목 선택
- 사용자 동작: 항목 선택 [onSelectChange]
- 처리 내용: 팝업/다이얼로그를 열어 추가 입력이나 확인을 처리

## 실행 방법

```bash
npm install
npm start
```

<!-- codex-summary:end -->

## 기존 문서

## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Thu Nov 06 2025 11:10:21 GMT+0900 (Korean Standard Time)|
|**App Generator**<br>SAP Fiori Application Generator|
|**App Generator Version**<br>1.19.3|
|**Generation Platform**<br>Visual Studio Code|
|**Template Used**<br>Basic V2|
|**Service Type**<br>OData URL|
|**Service URL**<br>https://services.odata.org/V2/Northwind/Northwind.svc/|
|**Module Name**<br>exam3|
|**Application Title**<br>SAPUI5 ?ㅼ뒿?됯? 3踰?臾몄젣 D01|
|**Namespace**<br>code.d01|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.120.39|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|

## exam3

An SAP Fiori application.

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  To launch the generated application, run the following from the generated application root folder:

```
    npm start
```

- It is also possible to run the application using mock data that reflects the OData Service URL supplied during application generation.  In order to run the application with Mock Data, run the following from the generated app root folder:

```
    npm run start-mock
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)
