
# Memo Chat
<img src="./assets/Logo.png" alt="Memo_Chat Logo" width="200" />

## 📌 프로젝트 개요
> 학교/회사에서 사용할 수 있는 메모장 형태의 채팅 앱 (위장 채팅 도구)

- Flutter 기반 (Android, Web, Desktop 지원)
- FastAPI + PostgreSQL + MongoDB 백엔드 구조
- 미니멀리즘 UI
- URL 기반 실시간 공유 메모장
- 선택적 로그인 + 알림 기능

## 🛠 기술 스택
| 영역 | 기술 스택 |
|------|------------|
| 프론트엔드 | Flutter (모바일, 웹, 데스크탑) |
| 백엔드 | FastAPI (Python) |
| 실시간 통신 | WebSocket |
| 인증 | OAuth2 (선택적), JWT |
| 사용자 데이터 | PostgreSQL |
| 메모/채팅 데이터 | MongoDB |
| UI 디자인 | Figma |
| 협업 및 관리 | GitHub, Cursor |

## 🔖 주요 기능 (MVP 기준)

- 메모장 생성 및 고유 URL 발급
- URL로 누구나 입장 가능 (닉네임 입력)
- 실시간 메모 입력 반영 (WebSocket 기반)
- 선택적 OAuth 로그인 (Google, Kakao 등)
- 로그인 사용자에게는 알림, 최근 메모장 기록 제공

👉 전체 기능/비기능 요구사항 보기: [`docs/requirements.md`](./docs/requirements.md)

## ✨ 향후 확장 기능
- 친구 초대 및 관리 기능
- 이미지, 이모티콘 입력
- 메모장 테마 변경
- 다국어 지원 (한/영)