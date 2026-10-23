# TST Hospital CRM — 설치본 배포

TST Hospital CRM Windows 설치본을 내려받는 곳입니다. **소스 코드는 여기에 없습니다.**

- 병원 PC에 설치된 CRM은 이 저장소의 [최신 릴리즈](../../releases/latest)를 저절로 확인하고 받아 둡니다. 새 버전이 준비되면 「지금 업데이트」를 묻습니다.
- 처음 설치할 때는 최신 릴리즈의 `TST-Hospital-CRM-Setup.exe`를 받아 실행하세요.
- 버전은 날짜입니다. `2026.10.2301`은 2026년 10월 23일의 첫 릴리즈라는 뜻입니다.

설치본에는 비밀번호·암호화 키·환자 정보가 들어 있지 않습니다. 설정은 설치한 PC의 `%APPDATA%\tst-hospital-crm\config.json`에 따로 있습니다.

릴리즈는 `npm run release:win`(소스 저장소)으로만 올립니다. 손으로 파일을 올리거나 고치지 마세요. `latest.yml`의 sha512가 설치본과 맞지 않으면 병원 PC가 업데이트를 거절합니다.
