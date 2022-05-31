# Linux Commands & Vim Editer

## Linux Commands

1. top 명령어.

top 명령어는 table of processes의 약자로 실시간으로 cpu와 메모리 이용에 관한 정보를 표시함

top 사용법. 

![제목 없음](https://user-images.githubusercontent.com/106595997/171172627-b4e46c91-6e9d-4f4f-8ecb-d8110c69c459.png)

![제목 없음](https://user-images.githubusercontent.com/106595997/171171303-45788c47-bf21-4b13-881d-822d32ec22f6.png)


2. ps 명령어.

ps 명령어는 Process Status의 약자로 현재 실행중인 프로세스 목록을 보여줌.

ps 사용법.

![제목 없음](https://user-images.githubusercontent.com/106595997/171174081-d8ad6051-c8d5-4014-9283-0c2a37dbbdc4.png)

ps 명령어를 옵션없이 사용하였다.

PID는 프로세스 ID, TTY는 프로세스 터미널 TIME은 해당 프로세스가 사용한 CPU 시간의 양 CMD는 실행중인 명령을 의미한다.

![제목 없음](https://user-images.githubusercontent.com/106595997/171174505-5fb0958f-ff32-46c5-9fe7-ee34cb296fe2.png)

ps -f(풀 포맷으로 출력), ps -l(긴 포맷으로 출력), ps -e(모든 프로세스를 출력)등의 옵션이 있다.



3. jobs 명령어.

jobs 명령어는 작업의 상태를 표시함.

jobs 사용법.

![제목 없음](https://user-images.githubusercontent.com/106595997/171177902-2673967b-92ae-49ae-958f-2fc9ee52c9c0.png)

jobs -l(프로세스 그룹 ID를 state 필드 앞에 출력), jobs -n(프로세스 그룹 중에 대표 프로세스 ID를 출력), jobs -p(각 프로레스 ID에 대해 한 행씩 출력)등의 옵션이 있다.

4. kill 명령어.

kill 명령어는 프로세스에 시그널을 보낸다.

kill 사용법.

ps명령어를 사용 한 뒤 -9 옵션으로 특정 프로세스를 종료시킨다.

![제목 없음](https://user-images.githubusercontent.com/106595997/171179103-196dcaa4-363b-4729-b087-85e274b17bd6.png)


## Vim Editer

1. 메크로 q & 매크로 @

매크로 q는 명령모드에서 q[매크로 이름] 으로 실행할 수 있다.

a라는 이름을 가진 매크로를 시작했다.
이후 입력하는 모든 스트로크가 매크로에 저장이 된다.
매크로 종료를 위해서는 q를 입력한다.

앞서 저장한 매크로 q[매크로 이름]는 @[매크로 이름]로 실행이 가능하다.

![제목 없음](https://user-images.githubusercontent.com/106595997/171182715-ca6769a0-fcba-4e8d-9e1f-e2de2c0648c1.png)
























