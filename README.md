# 채널 관리 플랫폼 에이전트

채널 관리 플랫폼에 필요한 예약 정보를 수집하는 크롤러 및 Electron Application 프로젝트 입니다.

## 실행 방법

### chromium 실행 (크롤러 개발이 필요한 경우)
크롤러를 실행하기 위해서는 chromium 이 설치되어 있어야 합니다.

chromium 설치 후 cmd 창에서 아래 명령어로 실행합니다.

### `chromium --remote-debugging-port=21222`

이후 에이전트 실행으로 넘어갑니다.

### 에이전트 실행

**FullBooking Agent** 는 Yarn 패키지 매니저를 사용하기를 권장합니다.

프로젝트 폴더에서 다음 명령어를 실행할 수 있습니다:

### 의존성 설치

```bash
$ yarn install
```

### 프로그램 실행

```bash
# 프론트엔드 개발 모드
$ yarn start:frontend

# 크롤러 개발 모드
$ yarn start:crawler

# 통합 개발 모드
$ yarn start

# 빌드 (rebuild 로 sqlite 빌드 후 build)
$ yarn rebuild
$ yarn build

```
