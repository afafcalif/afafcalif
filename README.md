# 안녕하세요 👋 taegkang입니다

**42경산(42 Gyeongsan)** 에서 C와 리눅스 시스템 프로그래밍을 공부했습니다.
메모리 관리, 프로세스/스레드, 시그널, IPC 같은 저수준 개념을 코드로 직접 부딪히며 익혔습니다.
Windows 커널 드라이버 위에서 AMD-V(SVM) 하드웨어 가상화를 다루는 하이퍼바이저도 만들어 봤습니다.
최근에는 Python으로 주식 데이터 파이프라인과 머신러닝 모델을 만들고, 결과를 보기 전에 판정 기준을 정해 두고 검증하는 작업을 하고 있습니다.

## 주요 프로젝트

| 프로젝트 | 한 줄 소개 |
|---|---|
| [svm-hypervisor](https://github.com/afafcalif/svm-hypervisor) | 실행 중인 Windows를 게스트로 전환하는 AMD-V(SVM) 최소 하이퍼바이저 — SimpleSvm 기반, VMCB·VMRUN·#VMEXIT 처리와 NPT 구성 |
| [kr-swing-lgbm](https://github.com/afafcalif/kr-swing-lgbm) | 국내 주식 스윙 LightGBM 종목 선택 모델 — 결과를 보기 전에 판정 기준을 고정하고 무작위 대조·누출 점검·전진 검증으로 확인 |
| [minishell](https://github.com/afafcalif/minishell) | bash의 동작을 재현한 셸 — 파이프, 리다이렉션, heredoc, 시그널 처리 (2인 팀) |
| [cub3D](https://github.com/afafcalif/cub3D) | DDA 레이캐스팅 기반 3D 렌더링 엔진 (2인 팀) |
| [philosopher](https://github.com/afafcalif/philosopher) | 식사하는 철학자 — pthread, 뮤텍스, 데이터 레이스 없는 동시성 제어 |

전체 과제 모음: [42-cursus](https://github.com/afafcalif/42-cursus) · [42-piscine](https://github.com/afafcalif/42-piscine)

## 기술

`C` `C++` `x64 Assembly` `Linux` `Windows Kernel Driver` `AMD-V(SVM)` `pthread` `Make` `Git` `Python` `pandas` `LightGBM` `REST API`
