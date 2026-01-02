# 💌 Discord Rolling Paper Bot (익명 롤링페이퍼 봇)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Discord.py](https://img.shields.io/badge/Discord.py-2.0%2B-5865F2?logo=discord&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

디스코드 서버 멤버들끼리 서로 **익명으로 메시지(롤링페이퍼)**를 남기고 확인할 수 있는 봇입니다.
최신 디스코드 기능인 **슬래시 커맨드(Slash Command)**를 사용하여 직관적이고 편리하게 사용할 수 있습니다.

## ✨ 주요 기능 (Features)

### 👤 일반 유저 기능
- **익명 메시지 보내기**: `/롤링페이퍼쓰기 [대상] [내용]` 명령어로 친구에게 익명 편지를 보냅니다.
- **내 편지함 확인**: `/롤링페이퍼확인` 명령어로 나에게 도착한 메시지들을 모아볼 수 있습니다.
- **본인 작성 방지**: 자기 자신에게는 쓸 수 없도록 처리되어 있습니다.

### 🛡️ 관리자 기능 (Admin Only)
- **전체 발송**: `/롤링페이퍼전체쓰기`로 서버의 모든 멤버(본인 제외)에게 동시에 메시지를 보낼 수 있습니다. (이벤트 공지용 등)
- **로그 확인**: `/롤링페이퍼로그`로 누가 누구에게 보냈는지 전체 기록을 파일(.txt)로 다운로드하여 확인할 수 있습니다.
- **데이터 초기화**: `/롤링페이퍼초기화`로 저장된 모든 메시지를 삭제합니다.
- **권한 관리**: 관리자 명령어는 관리자 권한(`Administrator`)이 없는 유저에게는 보이지 않습니다.

## 🛠️ 기술 스택 (Tech Stack)
- **Language**: Python 3.12
- **Library**: discord.py (app_commands)
- **Database**: SQLite3 (내장 DB 사용, 별도 설치 불필요)

## 🚀 설치 및 실행 방법 (Installation)

1. **저장소 클론 (Clone)**
   ```bash
   git clone [https://github.com/본인아이디/Discord_Rolling_Paper_Bot.git](https://github.com/본인아이디/Discord_Rolling_Paper_Bot.git)
   cd Discord_Rolling_Paper_Bot
