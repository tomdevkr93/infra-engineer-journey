# Phase 1. 리눅스 + 네트워크

> ### 학습 목표

**파일 시스템, 권한, 프로세스, 서비스, 셸 스크립팅, 로그 분석**

> ### 일별 학습 계획

### 3/5 (목) — 리눅스 환경 세팅 + 파일 시스템 기초

- [x] 유튜브 "드림코딩" — 리눅스 입문 영상
  - https://www.youtube.com/watch?v=EL6AQl-e3AQ
- [x] 📄 Linux Journey — "Grasshopper" 단계 전체
  - https://linuxjourney.com
  - Getting Started, Command Line, Text-Fu 섹션
- [x] WSL2(Windows) 또는 UTM(Mac)에 Ubuntu 24.04 설치
- [x] 실습: ls, cd, cp, mv, rm, mkdir, cat, echo, pwd 반복 연습

---

### 3/12 (월) — 권한 + 프로세스 + 서비스

- [x] Linux Journey — Grasshopper (Permissions, User Management) + Journeyman (Processes, Packages)
- 실습
  - [x] chmod, chown, umask, useradd 연습
  - [x] ps aux, top, htop, kill 연습
  - [x] systemctl start/stop/enable nginx + journalctl -u nginx -f


---

### 3/16 (월) — SSH + 쉘 스크립팅 + 로그

- [x] Bash 스크립팅 가이드: https://mug896.github.io/bash-shell (변수, 조건문, 반복문만)
- 실습
  - [x] SSH 키 생성 → 원격 접속 → ~/.ssh/config 설정
  - [x] 셸 스크립트: 디스크 80% 초과 시 경고 출력
  - [x] /var/log/syslog 분석, tail -f, grep 필터링
