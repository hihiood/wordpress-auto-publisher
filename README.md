# WordPress Auto Publisher

키워드만 넣으면 ChatGPT로 SEO 원고를 만들고, 이미지를 넣어 WordPress에 자동으로 올리는 프로그램입니다.
여러 사이트에 예약 발행하고, Rank Math 실제 점수 확인과 구글 색인 요청까지 한곳에서 합니다.

## 다운로드

| 파일 | 설명 | 받기 |
|---|---|---|
| `WordPressAutoPublisher.exe` | 프로그램 실행 파일 (설치 없이 실행) | [최신 버전 받기](https://github.com/hihiood/wordpress-auto-publisher/releases/latest) |

받은 exe 를 **비어 있는 새 폴더**에 넣고 실행하세요. 설정·이력·크롬 프로필은 그 폴더 안에 저장됩니다.

```
WordPressAutoPublisher\
  WordPressAutoPublisher.exe   ← 이것만 있으면 됩니다
  (첫 실행 뒤 자동 생성) auth.json · history.json · chrome_profile\ · 생성이미지\ …
```

## 사용설명서

**[docs/MANUAL.md](docs/MANUAL.md)** — 전체 흐름도, 상황별 안내(Q1~Q7), 화면마다 버튼 하나하나의 역할과 누르면 뜨는 화면, 조작 영상.

처음이라면 이 순서대로 보세요.

1. 전체 흐름 — 사전 세팅(①사이트 설정 → ②프롬프트 조정 → ③사전 로그인)과 실제 발행(④포스팅/스케줄 → ⑤후속작업)
2. Q2. 글을 발행하기 전에 무엇을 준비해야 하나요
3. Q3. 키워드 여러 개를 한 사이트에 지금 바로 올리고 싶어요

프로그램 안의 **? 사용 설명서** 버튼을 눌러도 같은 내용이 나옵니다.

## 실행

1. exe 를 실행합니다. 첫 실행은 압축을 푸느라 10~15초 걸립니다.
2. Windows 보안 경고가 뜨면 **추가 정보 → 실행** 을 누릅니다(서명 없는 프로그램이라 뜨는 안내입니다).
3. 로그인 창에 **발급받은 아이디·비밀번호**를 넣습니다. 계정은 관리자에게 받으세요(권한이 있는 계정만 실행됩니다).
4. 오른쪽 위 **⚙ 사이트 설정** 에서 WordPress 계정을 등록하고, **? 사용 설명서** 의 Q2 순서대로 준비합니다.

실행 중 문제가 생기면 exe 옆에 생기는 `launcher.log` 를 보내 주세요.

## 요구 사항

- Windows 10 / 11 (64비트)
- Google Chrome 설치
- 인터넷 연결 (ChatGPT, WordPress, 구글 접속)
- WordPress 사이트에 Rank Math SEO 플러그인이 있으면 SEO 제목·메타 설명까지 저장됩니다(없어도 발행은 됩니다)
