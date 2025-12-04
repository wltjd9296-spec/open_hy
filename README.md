# JISUNG'S PLAYLIST
> "나를 위로해준 플레이리스트..."
본 프로젝트는 팀장의 개인적인 감정을 담은 플레이리스트를 웹페이지 형태로 기록하며 페이지 이탈 없이 유튜브 영상을 팝업의 형태로 재생할 수 있도록 구현한 반응형 웹입니다.

## 필수 배지 코드
![HTML5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)


### 주요 기능
1. **플레이리스트 목록 표시**:
   노래 제목, 아티스트, 나의 일기(스토리) 제공
2. **유튜브 플레이어 모달 구현**
   '공감 하기' 버튼 클릭 시 페이지 이동 없이 팝업으로 영상 재생 (YouTube IFrame API 활용)
3. **반응형 웹 디자인**
   모바일/데스크톱 환경에 최적화된 화면 제공

### 기술적 구현 포인트
***YouTube IFrame Player API**를 사용하여 외부 스크립트 로드 및 플레이어 객체 제어*
***Modal**: DOM을 직접 제어하여 팝업을 띄우고 외부 클릭 및 ESC 키 입력 시 팝업과 영상 재생을 동시에 중지하도록 구현*

### 개발 참여자 및 역할
**이지성(팀장, 팀 프로젝트 총괄 및 팀원의 개발 보조)**
*프로젝트 아키텍처 설계 및 핵심 로직 구현*
1. **Repostory 관리**: 초기 세팅, .gitignore, LICENSE 설정 및 디렉토리 구조화
2. **Git Flow**: Main/Develop/Feature 브랜치 전략 운용 및 Merge 충돌 해결
3. **Core Logic 개발**: SPA(Single Page Application) 느낌의 탭 메뉴 인터렉션 구현 (JS), '비밀의 방' 이스터에그 로직 및 팝업 제어
4. **배포**: GitHub Page 배포 및 최종 유효성 검사

**김민혁(팀원, UI/UX & Design 담당)**
*사용자 경험 중심의 인터페이스 디자인 및 반응형 구현*
1. **UI/UX Design**: 미니홈피 감성의 레트로 디자인 기획 및 컬러 팔레트 구성
2. **CSS Refactoring**: HTML 내 인라인 스타일 제거 및 style.css 모듈화 (유지보수성 강화)
3. **반응형 웹**: 모바일/데스크탑 환경에 따른 레이아웃 최적화 (Media Query 활용)
4. **리소스 관리**: 이미지 자산 최적화 및 폰트 로딩 성능 개선 (Preconnect 적용)

**이아름(팀원, Feature & Documentation 담당)**
*오픈소스 라이브러리 활용 및 문서화/콘텐츠 관리*
1. **오픈소스 활용**: AOS(Animate On Scroll) 리이브러리 적용 및 스크롤 애니메이션 고도화
2. **기능 구현**: 유튜브 플레이어 연동 및 모달 창 구현
3. **콘텐츠 구성**: 플레이리스트 데이터 구조화 및 감성 텍스트 작성
4. **문서화**: README.md 작성 (프로젝트 소개, 설치 방법, 기술 스택 등 정리)
  
### 사용된 오픈소스 및 라이브러리
1. **AOS**: 스크롤 시 애니메이션 효과 구현 *출처: https://unpkg.com/aos@2.3.1/dist/aos.js*
2. **YouTube IFrame Player API**: 동영상 임베딩 및 제어 *출처: https://www.youtube.com/iframe_api*
3. **Google Fonts**: 'Nanum Pen Script' 및 'Noto Sans KR' 폰트 사용

### 프로젝트 실행 방법
1. **로컬 환경**: 프로젝트 파일을 다운로드한 후 VS Code의 Live Server 등으로 HTML 파일을 실행.
2. **배포 환경**: 아래 GitHub Pages URL로 접속하여 확인.
   ***URL**: https://wltjd9296-spec.github.io/open_hy/*
