# WorkNotice

전자우편 중심의 작업 공지, 일정 조율, 공동 절차서, 관리 알림을 한 곳에서 처리하는 정적 웹 프로토타입입니다.

## 실행
별도 설치가 필요 없습니다. `index.html`을 브라우저에서 열거나 정적 웹 서버로 실행하세요.

## GitHub Pages 배포
1. GitHub에서 새 Repository 생성
2. `index.html`, `style.css`, `main.js`, `README.md`를 저장소 루트에 업로드
3. Settings → Pages
4. Build and deployment의 Source를 `Deploy from a branch`로 선택
5. Branch를 `main`, 폴더를 `/ (root)`로 선택 후 Save
6. 잠시 후 제공되는 GitHub Pages 주소 접속

## 주요 기능
- 메일처럼 새 작업 등록 및 참여자 지정
- 대시보드와 나의 할 일
- 월간 작업 캘린더
- 공동 작업 절차서 추가/수정/삭제
- 후보 일정 등록 및 참여자별 가능/불가능 응답
- 일정 확정 후 캘린더 반영
- 작업/계정/백업 알림센터
- 사용자 전환을 통한 협업 데모
- 작업 활동 기록
- localStorage 저장

## 데모 데이터 초기화
브라우저 개발자도구에서 `localStorage.removeItem('worknotice_v1')` 실행 후 새로고침하세요.
