
[RPA 란?]
 -> 사람이 단순반복적으로 하던 작업을 로봇(PC)에게 인가시키고, 사람은 고부가가치를 창출하는 일에
    시간을 더 투자하기 위함.
 * RPA(Robotic Process Automation) - 사무자동화(스마트팜, 스마트시티)
 * RDA(Robotic Desktop Automation) - PC 수준에서의 자동화

[RPA 의 장점]
 * 아무리 복잡해도 단순반복적인 업무라면 아주 적합.
 * 사람은 집중력이 저하 -> 로봇은 체력X --> 프로세스가 잘 정의된다면, 거의 무한한 효율을 냄.
 * 사람의 반복 업무를 대체 혹은 도와주는 프로그램.

[RPA 의 한계]
 * 사람의 판단이 여러번 개입되어야 하는 업무
    -> RPA 프로세스 구현 부적합.

[RPA 사례]
 * CU, GS25, 미니스톱, emart24
    -> 전 지점, 정보를 취합하여 매주 시니어에게 보고
    -> 어마어마한 양의 단순반복 업무 --> RPA 적용
 
 * 뉴스레터 발송
    -> 네이버, 다음, 구글 -> 특정 키워드로 최근 1일 기사를 크롤링 -> 뉴스레터 작성 -> 담당자 메일발송
    -> 사람이 일일이 수집하던 데이터 -> RPA 적용

[RPA 주 업무 패턴]
 * 기간계시스템 접속 -> Raw 데이터(Excel) 다운 -> 엑셀가공 -> 담당자 메일발송, 기간계시스템 업로드
 * 외부 사이트 접속 -> Raw 데이터(Excel) 다운, 웹페이지 데이터 추출 -> 엑셀가공 -> 담당자 메일발송, 기간계시스템 업로드
 * 엑셀 특화 프로세스 (PDF 파일 -> 전체 페이지 데이터 추출 -> 엑셀 데이터화)

[RPA 업무 적용 가능한 App]
 * EXCEL, WORD, PPT, PDF, TXT, IE, Chrome, 3rd App, 기간계시스템(SAP, ERP), Excel Macro
 * SQL(ODBC), Excel(OLEDB)

[SoftoMotive 실행가능한 오픈소스]
 * JS, VBS, Python, PowerShell

[Exception 개념]
 * 쉽게 말해서 에러

[Exception 의 종류]
 * RPA 툴이 핸들링 가능한 에러
    -> Exception 처리 과정을 따름.(개발자 정의)
        -> 공통 ERROR 처리 Function 에서 핸들링
 
 * RPA 툴이 핸들링 불가능한 에러
    -> 개발자 정의 Exception 처리 과정 무시
        -> 핸들링 불가능
            Ex) 시스템 메모리부족 -> PC 사양 업그레이드
    -> 프로세스 수행 당시 -> 고객사 시스템 서버 다운, 랜선 out
        -> 핸들링 불가능

[R 중복기사 제거 추가 설치 패키지]
install.packages('xlsx')
install.packages('textreuse')
install.packages('igraph')
























