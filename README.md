# Python_Assignment_LinuxCommendsIntroduction
# 리눅스 명령어 조사(top, ps, jobs, kill) 

## 개요

이 문서는 리눅스 명령어인 `top`, `ps`, `jobs`, `kill`에 대해 정리한 README 파일이다.

---

## 1. `top` 

### 설명

`top` 명령어는 현재 실행 중인 프로세스와 시스템 자원 사용량을 실시간으로 확인하는 명령어이다.

CPU 사용률, 메모리 사용률, 실행 중인 프로세스 목록 등을 확인할 수 있다.

### 사용법

```bash
top
```

### 주요 항목

* PID: 프로세스 ID
* %CPU: CPU 사용률
* %MEM: 메모리 사용률
* COMMAND: 실행 중인 명령어 이름

### 참고

`top` 실행 중 `q`를 누르면 종료된다.

필자는 Git Bash에서 `top` 명령어를 직접 실행해 보았으나, `bash: top: command not found`라는 오류가 발생했다.

알고 보니 `top`은 리눅스 환경에서 기본적으로 사용되는 명령어이며, Windows Git Bash에서는 기본 제공되지 않을 수 있다.

<img width="1210" height="254" alt="image" src="https://github.com/user-attachments/assets/a4ffeade-3ef4-4863-b4c9-2f6ae50a531b" />
(필자의 시행화면)

