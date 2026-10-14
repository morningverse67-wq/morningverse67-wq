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
<p>N+1, 인덱스, 락, 캐시 같은 문제를<br />바로 실행되는 작은 코드로 재현.</p>
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
<sub>N+1: 쿼리 501번 321ms → 1번 1.7ms · 인덱스: 선택적 조회 887배, 90% 조회는 0.9배</sub>

**[backend-lab](https://github.com/morningverse67-wq/backend-lab)** &nbsp; 위 답변의 근거가 되는 실험 코드. 하루 하나씩 재현하고 측정합니다  
<sub>Python 표준 라이브러리만 사용, `python3 main.py` 한 줄로 재현</sub>

### Writing

**[Velog @morningverse](https://velog.io/@morningverse)** &nbsp; 실험 중 일부를 글로 풀어 씁니다  
<sub>최근 글: [N+1 쿼리는 왜 생길까?](https://velog.io/@morningverse/N1-쿼리는-왜-생길까)</sub>

### Tools

backend &nbsp; · &nbsp; `SQL` &nbsp; `MyBatis`  
experiments &nbsp; · &nbsp; `Python` &nbsp; `SQLite`  
also &nbsp; · &nbsp; `JavaScript` &nbsp; `Swift`

<br />

---

<p align="center">
  <sub>SMALL STEPS. MEASURED CHOICES. A LITTLE BETTER, EVERY DAY.</sub>
</p>
