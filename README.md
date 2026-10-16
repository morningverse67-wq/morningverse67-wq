<p align="center">
  <img src="./morningverse-banner.svg" width="100%" alt="morningverse. Reproduce. Measure. Record." />
</p>

<div align="center">

### 백엔드의 데이터·성능 문제를 재현하고, 측정하고, 기록합니다.

"왜 느리지?"에서 멈추지 않고 작은 코드로 다시 만들어 보고,  
직접 잰 숫자로 선택의 근거를 남깁니다.

<sub>REPRODUCE · MEASURE · RECORD</sub>

</div>

<br />

<table>
<tr>
<td width="400" valign="top">
<h3>01 / Reproduce</h3>
<b>작게 다시 만들기</b>
<p>N+1, 인덱스, 페이징 같은 문제를<br />바로 실행되는 작은 코드로 재현.</p>
</td>
<td width="400" valign="top">
<h3>02 / Measure</h3>
<b>직접 재기</b>
<p>쿼리 수와 응답 시간을 직접 측정하고<br />추측 대신 숫자로 비교.</p>
</td>
<td width="400" valign="top">
<h3>03 / Record</h3>
<b>근거 남기기</b>
<p>무엇을 골랐고 무엇을 포기했는지<br />트레이드오프까지 기록.</p>
</td>
</tr>
</table>

<br />

### Now

**[backend-interview-lab](https://github.com/morningverse67-wq/backend-interview-lab)** &nbsp; 백엔드 면접 질문, 직접 실행하고 측정한 근거로 답하기  
<sub>N+1: 쿼리 501번 321.82ms → 1번 1.68ms · 인덱스: 선택적 조회 887배, 90% 조회는 0.9배 · 복합 인덱스 순서: 505배 · OFFSET vs 커서: 10,000페이지 100회 조회 합계 244.7배</sub>

**[backend-lab](https://github.com/morningverse67-wq/backend-lab)** &nbsp; 위 답변의 근거가 되는 실험 코드. 주제마다 폴더 하나로 재현하고 측정합니다  
<sub>Python lab은 표준 라이브러리만 써서 `python3 main.py` 한 줄로 실행 · MyBatis lab(003)은 Java·MyBatis·MySQL·Docker</sub>

**[donworry-poc](https://github.com/morningverse67-wq/donworry-poc)** &nbsp; 기존 보험이 무엇을 몇 살까지 보장하는지 보여주는 서비스 PoC (팀 과제)  
<sub>단일 HTML · 바닐라 JS, 외부 라이브러리·서버 없음</sub>

### Writing

**[Velog @morningverse](https://velog.io/@morningverse)** &nbsp; 실험과 문제 해결 과정을 글로 풀어 씁니다

- [바닐라 JS 단일 HTML 앱 PoC 개발기: 이벤트 위임부터 Web Crypto 비밀번호 페이지의 한계까지](https://velog.io/@morningverse/바닐라-JS-단일-HTML-앱-PoC-개발기-이벤트-위임부터-Web-Crypto-비밀번호-페이지의-한계까지)
- [stale-if-error, 외부 API 장애 때 만료된 캐시를 돌려줘도 되는 경계 (Spring RestClient)](https://velog.io/@morningverse/stale-if-error-외부-API-장애-때-만료된-캐시를-돌려줘도-되는-경계-Spring-RestClient)
- [JWT 검증, Spring Boot 기본 설정이 놓치는 aud·iss·exp까지 테스트로 막기](https://velog.io/@morningverse/JWT-검증-Spring-Boot-기본-설정이-놓치는-audissexp까지-테스트로-막기)
- [Testcontainers 통합 테스트, 컨테이너 한 번만 띄우고 데이터 안 섞이게 (Spring Boot)](https://velog.io/@morningverse/Testcontainers-통합-테스트-컨테이너-한-번만)
- [Jira와 Linear, 무엇이 다를까?](https://velog.io/@morningverse/Jira와-Linear-무엇이-다를까)
- [MyBatis N+1 문제 해결, 로그 확인부터 일대다 페이징까지](https://velog.io/@morningverse/N1-%EC%BF%BC%EB%A6%AC%EB%8A%94-%EC%99%9C-%EC%83%9D%EA%B8%B8%EA%B9%8C)

### Tools

backend &nbsp; · &nbsp; `Java` &nbsp; `Spring Boot` &nbsp; `MyBatis` &nbsp; `MySQL` &nbsp; `SQL`  
experiments &nbsp; · &nbsp; `Python` &nbsp; `SQLite` &nbsp; `Docker`  
also &nbsp; · &nbsp; `JavaScript` &nbsp; `Swift`

<br />

---

<p align="center">
  <sub>SMALL STEPS. MEASURED CHOICES. A LITTLE BETTER, EVERY DAY.</sub>
</p>
