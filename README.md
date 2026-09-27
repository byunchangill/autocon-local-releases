# AutoCon Local

Windows 설치본과 업데이트 파일을 제공하는 배포 전용 저장소입니다.

## 다운로드

[최신 설치본 다운로드](https://github.com/byunchangill/autocon-local-releases/releases/latest/download/AutoCon_Local_Setup.exe) · [버전별 변경 내용](https://github.com/byunchangill/autocon-local-releases/releases)

Windows 10/11 x64에서 설치 후 시작 메뉴의 **AutoCon Local**을 실행하세요.
Node.js, Python, FFmpeg, yt-dlp는 포함되어 있습니다.

## AI 계정 연결

**AI 연결·API 설정**에서 Codex CLI와 Claude Code 공식 설치 안내를 열고 각 PC에서 계정에 로그인하세요.
**구독 권장 설정 선택 → 구독 연결 테스트 → 연결 설정 저장**으로 적용합니다.
구독 전용 모드가 기본입니다. 역할 배정에서 대본·번역·제목·검색어·컷 매칭·검수·학습·영상 분석을 ChatGPT 또는 Claude 구독으로 선택합니다. 장면 분석은 최대 32장의 샘플 이미지로 추정합니다.

음성 인식은 로컬 Whisper, 음성 생성은 Windows 기본 음성 또는 파일 업로드를 사용합니다. 구독 CLI는 음성 파일 생성을 지원하지 않습니다. Windows 음성은 해당 언어 설치가 필요하며 말투 지시는 지원하지 않습니다. 구독 한도가 적용되고 실패 시 유료 API로 전환하지 않습니다.

## 업데이트

설정에서 **새 버전 알림**, **시작 시 자동 설치**, **수동 확인만** 중 선택할 수 있습니다.
업데이트는 배포 서명 및 SHA-256 검증 후 적용됩니다. 진행 중인 작업이 있으면 설치하지 않습니다.
각 PC에 GitHub 로그인이나 토큰을 입력할 필요는 없습니다.

**1.2.1 업데이트 실패 복구:** 한글 Windows 사용자 이름에서 종료 코드 5가 표시되었다면 최신 설치 EXE(1.2.2 이상)를 다운로드해 기존 설치 폴더에 덮어 설치하세요. 새 설치본이 남아 있는 앱 프로세스를 종료하고 업데이트합니다.

설정과 작업 데이터는 `%LOCALAPPDATA%\AutoConLocal\data`에 보관되며 업데이트와 프로그램 제거 후에도 유지됩니다.

현재 설치 파일에는 Windows Authenticode 코드 서명이 적용되어 있지 않아 SmartScreen 경고가 표시될 수 있습니다.

이 저장소는 개발용 소스와 개인 계정 정보를 보관하지 않습니다. 설치본에는 앱 실행에 필요한 JavaScript 및 외부 런타임이 포함됩니다.
