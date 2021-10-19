# 4.3.1 내부 구조

제어기의 구조와 각 부분의 이름을 알아 두면 설치 및 유지 보수 방법을 확인할 때 유용합니다.

![그림 26 제어기 내부 구조](../../.gitbook/assets/image107.png)

|                     **번호**                     |           **이름**          |    ****   | **설명**                                 |
| :--------------------------------------------: | :-----------------------: | :-------: | -------------------------------------- |
| ![Adobe Systems](../../.gitbook/assets/1.png)  |  <p>소형 컴퓨터  </p><p>모듈</p> | miniH6COM | 협동로봇 전반을 제어합니다.                        |
| ![Adobe Systems](../../.gitbook/assets/2.png)  | <p>전원 스위치</p><p>및 차단기</p> |    CP1    | 제어기의 주전원을 켜거나 끕니다.                     |
| ![Adobe Systems](../../.gitbook/assets/3.png)  |           노이즈 필터          |    NF1    | 전도성 노이즈를 차단하는 필터입니다.                   |
| ![Adobe Systems](../../.gitbook/assets/4.png)  |             버퍼            |   BUFFER  | 정전 시 일정 시간 동안 소형 컴퓨터 모듈에 전력을 공급합니다.    |
| ![Adobe Systems](../../.gitbook/assets/5.png)  |           전원 장치2          |   SMPS2   | 조인트 액추에이터에서 사용하는 전원(DC24V)을 생성합니다.     |
|  ![Adobe Systems](../../.gitbook/assets/6.png) |           전원 장치1          |   SMPS1   | 제어용 전원(DC48V)을 생성합니다.                  |
|  ![Adobe Systems](../../.gitbook/assets/7.png) |   <p>회생 방전</p><p>모듈</p>   |    RDM    | 조인트 액추에이터의 모터에서 발생하는 회생 전력을 방전합니다.     |
|  ![Adobe Systems](../../.gitbook/assets/8.png) |   <p>안전 제어</p><p>모듈</p>   |    SCM    | 협동로봇의 안전 기능을 제어합니다.                    |
|  ![Adobe Systems](../../.gitbook/assets/9.png) |   <p>전원 충전</p><p>모듈</p>   |    PPM    | 협동로봇에 내장된 조인트 액추에이터의 모터용 전원을 미리 충전합니다. |
