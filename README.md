### *top: table of processes*
##### cpu와 메모리 이용에 관한 정보를 표시함.
##### 얼마나 많은 처리량과 메모리가 사용되는지, 실행 중인 프로세스에 관한 기타 정보 또한 출력함.

>* top만 입력시 3초마다 갱신 / 나가고 싶다면 'q' 입력.
>>shift + p: CPU 사용률이 높은 순서대로 출력함.
>>
>>shift + m: 메모리 사용률이 높은 순서개로 출력함.
>>
>>shift + t: 프로세스가 돌아가고 있는 시간 순서대로 출력함.
>>
>>a: 메모리 사용량에 따라 정렬함.
>>
>>b: Batch 모드 작동함.
>>
>>c: 명령행, 프로그램 이름 토글함.
>>
>>d: 지연 시간 간격은 -d ss. tt(seonds.tenths) 와 같음.
>>
>>h: 도움말.
>>
>>H: 스레드 토글함.
>>
>>i: 유후 프로세스 토글함.
>>
>>m: VIRT / USED 토글함.
>>
>>M: 메모리 유닛 탐지함.
>>
>>n: 반봇횟수제한:-n number임.
>>
>>p: PID를 다음과 같이 모니터함. : -pN1 -pN2 ...or -pN1,N2...
>>
>>s: 보안 모드 작동함.
>>
>>S: 누적 시간 모드 토글함.
>>
>>u: 사용자별 모니터링:u somebody.
>>
>>U: 사용자별 모니터링:U somebody.
>>
>>1: cpu core별로 사용량을 보여줌.

* 토글: 다른 값으로 전환하는 것.

---

### *ps:*
##### 실행중인 프로세스의 목록을 표시함.

>* ps만 입력시 현재 실행한 사용자 프로세스에 대한 정보를 출력함.
>
>>-e: 실행중인 모든 프로세스의 정보를 출력함.
>>
>>-f: PPID로 확인 가능한, 프로세스에 대한 자세한 정보를 출력함.
>>
>>-u[사용자]: 특정 사용자에 대한 프로세스 정보를 모두 출력함.
>>
>>-p pid: pid로 지정한 프로세스의 정보를 출력함.
>>
>>u: 프로세스 소유자의 이름, CPU 사용량, 메모리 사용량 등 상세한 정보를 출력함.
>>
>>a: 터미널에서 실행한 프로세스의 정보를 출력함.
>>
>>x: 실행 중인 모든 프로세스의 정보를 출력함.


---
### *jobs:*
##### 작업의 상태를 표시함. *ex) [1] Stopped *

>* job [옵션][작업번호] 로 표시됨.
>>|상태|설명|
>>|------|---|
>>|Running|작업이 계속 진행중|
>>|Done|작업 종료+**0인 코드** 변환|
>>|Done(code)|작업 종료+**0이 아닌 코드** 변환|
>>|Stopped|작업 일시 중단|

>>-l: 프로세스 그룹 ID를 state 필드 앞에 출력함.
>>
>>-n: 프로세스 그룹 중 대표 프로세스 ID 출력함.
>>
>>-P: 각 프로세스 ID에 대해 한 행씩 출력함.
>>
>>command: 지정한 명령어를 실행함. 

* 프로세스: 컴퓨터에서 연속적으로 실행되고 있는 컴퓨터 프로그램.
---
### *kill:*

### *q:*
### *@:*
 
