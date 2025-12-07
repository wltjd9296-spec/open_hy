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

### Pull/Push Summary

 19 pull requests merged by 2 people
docs: 팀원 프로필 추가 및 마크다운 문서 재작성/수정
#29 merged 1 minute ago

docs: 팀원 프로필 추가 및 사진 추가
#28 merged 3 days ago

최종 유효성 검사 후 오류 수정
#27 merged 3 days ago

오류 수정(최상위 폴더로 파일 이동)
#26 merged 3 days ago

파일 구조 변경
#25 merged 3 days ago

feat: Add YouTube player modal functionality
#24 merged 3 days ago

세번째 곡 수정(짝사랑, 연애, 이별 메커니즘 구상)
#23 merged 3 days ago

제목 수정
#22 merged 4 days ago

feat: 탭 메뉴 구현 및 HTML 구조/스크립트 오류 수정 (Issue #10)
#21 merged 4 days ago

feat: 탭 메뉴 구현 및 HTML 구조/스크립트 오류 수정 (Issue #10)
#20 merged 4 days ago

공통 스타일 가이드 정립 및 css 분리 s
#17 merged 4 days ago

Feat: 앨범 커버 및 플레이리스트 데이터 JSON 분리, 동적 렌더링 적용 (#6)
#18 merged 4 days ago

Fix: 모바일 반응형 UI 디테일 수정
#19 merged 4 days ago

오류 재수정
#16 merged 5 days ago

오류 수정
#15 merged 5 days ago

feat: '비밀의 방' JavaScript 인터랙션 추가
#14 merged 5 days ago

[Feat] 오픈소스 AOS 라이브러리를 활용한 UI 동적 구현 #3
#13 merged 5 days ago

[Fix] 프로젝트 설정 파일 누락 수정
#9 merged 5 days ago

[Setting] 프로젝트 초기 구조 설정 #1
#8 merged 5 days ago

 10 issues closed by 1 person
GitHub Page 배포 및 최종 점검
#7 closed 3 days ago

README.md 작성 (프로젝트 소개 및 기여 내역)
#12 closed 3 days ago

유튜브 플레이어 모달(Modal) 기능 구현
#11 closed 3 days ago

탭 메뉴 인터랙션 JavaScript 구현
#10 closed 4 days ago

공통 스타일 가이드 정립 및 CSS 분리
#2 closed 4 days ago

앨범 커버 및 플레이리스트 데이터 JSON 분리
#6 closed 4 days ago

모바일 반응형 UI 디테일 수정 (Media Query)
#4 closed 4 days ago

'비밀의 방' 이스터에그 로직 고도화
#5 closed 5 days ago

AOS 오픈소스 라이브러리 적용 가이드
#3 closed 5 days ago

프로젝트 초기 설정 및 레포지토리 구조화
#1 closed 5 days ago

### 협업 및 이슈 해결 과정
Pair Programming 도입: 프로젝트 막바지, 유튜브 API 연동 로직의 복잡성을 해결하고 충돌을 최소화하기 위해 팀장과 팀원이 한 컴퓨터에서 코드를 검토하며 함께 커밋하는 페어 프로그래밍(Pair Programming) 방식을 채택하여 개발 효율을 높였음.

## 💡 팀 회고 (Retrospective)

### 🧑‍💻 이지성 (팀장 & Tech)
초기 세팅과 브랜치 전략(Git Flow)을 수립하는 과정에서 팀원들의 이해도를 맞추는 것이 중요함을 배웠다. 특히 모달(Modal) 창 구현 시 이벤트 버블링 이슈가 있었으나 DOM 제어 로직을 개선하며 해결했다. 팀장으로서 전체적인 코드 톤 앤 매너를 맞추는 데 주력했다.

### 🎨 김민혁 (Design & UI)
단순히 예쁜 디자인보다 사용자가 편한 UI가 무엇인지 고민했다. CSS를 모듈화하여 코드 중복을 줄인 점이 가장 뿌듯하며 미디어 쿼리를 활용해 다양한 디바이스에 대응하는 반응형 웹의 원리를 깊이 이해하게 되었다.

### 📑 이아름 (Feature & Docs)
오픈소스 라이브러리(AOS)를 처음 적용해 보며 공식 문서의 중요성을 깨달았다. 개발 과정에서 Git 충돌 문제로 어려움이 있었지만 팀장과의 페어 프로그래밍을 통해 협업 워크플로우를 익히고 문제를 해결하는 값진 경험을 했다.
