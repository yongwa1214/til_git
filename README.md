# Git

## 1. Git 프로그램 설치

- 프로그램 다운로드: https://git-scm.com/
- 64 bit Git for Windows Setup 설치

## 2. Git 버전 확인

- 윈도우+R : `cmd` 입력

```bash
git --version 
```

- 출력창 확인

## 3. VSCode 에 Git 설정하기

### 3.1. 터미널 환경을 git bash 로 설정하기

- 윈도우, 맥, 리눅스 의 명령창을 통일하려고.
- 관리도구 선택 > 설정메뉴 선택
- 설정화면 > `default:Windows` 입력
- Git Bash 선택
- 설정화면 닫고, VSCode 재실행 추천

### 3.2. VSCode 에서 Git 옵션 설정하기

- 터미널 실행: `ctrl + 백틱` 추천

```bash
git --version
```

- 기본 브랜치명을 `main` 으로 설정

```bash
git config --global init.defaultBranch main
```

- 윈도우, 맥, 리눅스 환경에서 Enter 키 처리를 통일함.

``` bash
git config --global core.autocrlf true
```

-git commit 명령을 VSCode에서 작성하도록 설정

```bash
git config --global core.editor "code --wait"
```

- git 사용자 아이디 설정하기

```bash
git config --global user.name "아이디"
```

- git 사용자 아이디 확인하기

```bash
git config --global user.name
```

- git 사용자 이메일 저장하기

```bash
git config --global user.email "이메일"
```

- git 사용자 이메일 확인하기

``` bash
git config --global user.email
```

## 4. git 작업하기

### 4.1. git 프로젝트 관리 초기화 하기

```bash
git init
```

### 4.2. git 현재 상태 파악하기

```bash
git status
```

### 4.3. git 현재 수정된 내용, 파일, 폴더 등을 저장하기

- 원하는 파일만 저장하기

```bash
git add README.md
```

# GitHub
