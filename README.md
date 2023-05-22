리눅스 명령어 정리 (top, ps, jobs, kill)
===============
## 1. top

top 명령어는 시스템의 현재 상태와 실행 중인 프로세스에 대한 정보를 실시간으로 제공하는 명령어이다.

CPU 사용량, 메모리 사용량, 프로세스 목록 및 관련 정보, 로드 평균 등을 확인할 수 있다.

시스템 모니터링, 성능 분석을 하는 명령어 이므로 윈도우의 '**작업 관리자**'와 비슷한 기능을 한다고 볼 수 있다.

**스페이스 바**로 화면을 갱신할 수 있고 **Z**를 통해 글의 색상을 변경할 수 있다.

`$ top`

<img src="https://github.com/A20233174/study_opensource/assets/133977632/649558a1-4638-4eb7-9eaf-cbfca68d14bd" width="500" height="500">

> *우분투* 터미널에서 *top*를 실행한 모습, **Z**를 통해 색상을 변경한 모습을 볼 수 있다.

---

## 2. ps

ps 명령어는 시스템의 프로세스에 대한 정보 제공하는 명령어이다.

현재 실행 중인 프로세스 목록을 확인할 수 있다.

-e 또는 -A : 모든 사용자의 프로세스를 표시한다.

-f : 프로세스에 대한 정보를 자세하게 표시한다.

> *" -ef " 로 모든 사용자의 프로세스에 대한 정보를 자세하게 표시할 수 있다."*

**top**는 프로세스에 대한 정보(CPU, 메모리 사용량 등)를 실시간으로 보여준다면
**ps**는 시스템을 부팅했을 때부터 명령을 실행했을 때까지의 정보를 보여주는 것에서 차이가 있다.

<img src="https://github.com/A20233174/study_opensource/assets/133977632/649558a1-4638-4eb7-9eaf-cbfca68d14bd](https://github.com/A20233174/study_opensource/assets/133977632/81aabed6-1902-467c-94c6-3cf76636535b" width="500" height="500">

