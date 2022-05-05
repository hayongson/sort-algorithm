# sort-algorithm

## 정렬 알고리즘 비교(장단점/시간복잡도)
* 선택정렬
---
장점:구현이 간단하다./비교하는 횟수에 비해 교환이 적게 일어난다.

단점:정렬 시간이 오래 걸린다.


시간복잡도:0(n2)

---

* 삽입정렬 
---
장점:최선의 경우 0(N)으로 정렬이 가능하다.

단점:최악의 경우 0(N2)이 걸린다

시간복잡도:0(n)~0(n2)

---

* 버블정렬

---
장점:구현이 간단하다.

단점:정렬 시간이 오래 걸린다.

시간복잡도:0(n2)

---
* 퀵정렬

---
장점:평균실행시간이 빠른편이다.

단점:Pivot에 따라 성능의 차이가 심하다./최악의 경우 0(n2)이 걸리게 된다.

시간복잡도:0(nlogn)~0(n2)

---
* 힙정렬

---
장점:항상 0(nlogn)으로 빠른편이다.

단점:다른 0(nlogn)의 정렬보다 오래걸린다.

시간복잡도:0(nlogn)

---
* 쉘정렬

---
장점:0(nlogn)의 정렬보다 빠르다.

단점:설정 간격에 따라 성능의 차이가 심하다.

시간복잡도:0(n^1.25)

---

## 그래프로 표현

* 정렬된 데이터

<p align="center"><img src="https://postfiles.pstatic.net/MjAyMjA1MDVfNDEg/MDAxNjUxNzYyNjk4NDA1.8r2Tf3tEUnP-28h93eYrhEg8FAZNuMTluZyhMSnk1jYg.a6xBsEgQ-sG-Qgsm0srRbdv3ucTB9p-Tdj8kpoE_rR8g.PNG.dyddyd4/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7(15).png?type=w773" height="400px" width="600px"></p>
<br/>

* 렌덤 데이터

<p align="center"><img src="https://postfiles.pstatic.net/MjAyMjA1MDVfMjQ1/MDAxNjUxNzYyNzAzMzA5._-vGEIkJkxq1KchI5aWUTMrVTeCCq-9MtCQRKXApxdEg.pcPMTvKf6GmbNXckZS6N32utkBWG0yul0V5CjQNkEp4g.PNG.dyddyd4/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7(13).png?type=w773" height="400px" width="600px"></p>
<br/>

* 역 정렬 데이터

<p align="center"><img src="https://postfiles.pstatic.net/MjAyMjA1MDVfNjEg/MDAxNjUxNzYyNjkzNDkz._MCBJGBUgxI3iCd5LlXz-40MhETx-lCmJ8o_EsfmS3Mg.TbnJ-h6YPGJTjtm8skjfJI3onABx7BY-1k0tIWeuHsYg.PNG.dyddyd4/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7(17).png?type=w773" height="400px" width="600px"></p>
<br/>
