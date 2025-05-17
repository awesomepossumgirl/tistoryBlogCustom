
## 티스토리 블로그(귀염둥이의 일기) 커마
- 티스토리 블로그 커마용 소스 백업
  - 블로그 주소 https://awesomepossum.tistory.com
  - 기본 레이아웃 정상우님의 hELLO 스킨 사용(https://github.com/pronist/hello)

## 커스텀 History

- 2024.12.03 - 메인 Header 이미지 변경  
 - 기존 배경 제거, 고해상도 이미지로 교체 (`HTML`, `CSS`)

- 2025.01.11 - 오늘의 명언(랜덤 명언) 생성기 추가  
  → 페이지 로드시 랜덤 문구 출력되는 스크립트 삽입 (`JavaScript`)
  → HTML/CSS 는 직접 제작, 랜덤 명언 생성 자바스크립트 소스는 Aleph Kim님 블로그에서 가져옴(아래 출처 표기)

- 2025.01.29 - 사이드바 배경 음악 뮤직플레이어 삽입  
  → 오디오 자동재생 및 커스터마이징된 컨트롤러 (`HTML`, `JavaScript`, `CSS`) 로 직접제작

- 2025.02.25 - 사이드바 메뉴 hover 시 그라데이션 텍스트 + 선 효과 적용  
  → `linear-gradient` 활용, transition 부드럽게 (`CSS`)

- 2025.03.03 - 사이드바에 GitHub 및 개인 위키 뱃지 추가  
  → `.svg` 뱃지 활용하여 외부 링크 배치 (`HTML`, `CSS`)

- 2025.03.15 - 방명록 기능 활성화  
  → 비공개 댓글, 기본 입력 폼 스타일 수정 (`HTML`, `CSS`)

- 2025.03.22 - 프로필 사진 테두리에 그라데이션 효과 적용  
  → `border-image`, `clip-path` 활용 (`CSS`)

- 2025.04.05 - 코드블럭  (`HTML`, `CSS`, `JavaScript`)
  - `highlight.js` 로 글씨체 / 테마 변경
  - 줄번호 삽입
  - `clipboard.js` copy, copied 버튼 기능 삽입 

- 2025.04.05 - 인라인 코드
  - `` 백틱으로 손쉽게 인라인 블럭 추가하는 js 직접 제작 (`JavaScript`)
- 2025.04.18 - 마우스 커서 이펙트 추가  
  → 커서 따라 별똥별 이펙트 (`JavaScript`, Canvas API)

## 📦 사용한 외부 라이브러리

- [Clipboard.js](https://clipboardjs.com/) - MIT License  
  코드 블럭 복사 버튼 기능 구현에 사용했습니다.

- [highlight.js](https://highlightjs.org/) - BSD 3-Clause  
  코드 블럭에 문법 하이라이팅 적용. vs2025테마 및 line-numbers 플로그인 사용
  코드 폰트 색상/스타일과 줄번호 구현
  
- [Font Awesome](https://fontawesome.com/) - CC BY 4.0  
  아이콘 폰트로 UI 요소 꾸미는데 사용되었습니다. 

- [Google Fonts](https://fonts.google.com/) - SIL Open Font License
  - SUIT (cdn.jsdelivr 제공, @sunn-us/SUIT)
  - Jua
  - Gowun Batang
  - Grandiflora One

- [D2Coding Font(서브셋)] - Apache License 2.0
  - 개발자용 고정폭 폰트로 코드 가독성 향상
 
    
## 그 외 기타 코드 및 스크립트

- Tinkerbell Magic Sparkle (마우스 이펙트)
  - 출처: mf2fm.com
  - 2005~2013 © mf2fm web-design
  - 라이선스 명시는 없지만 대부분 퍼블릭 도메인 또는 비상업적 사용 허용

- sayDding.js
  - 랜덤 명언 생성기
  - Aleph Kim님 블로그 (https://url.kr/9nawq2)

※ 모든 외부 리소스는 CDN으로 연결되어 있으며, 라이선스에 따라 사용하였습니다.

## 직접 커스텀 (html/css 소스 안에 포함)

- 뮤직 플레이어 
- 사이드바, 메인 헤더, 썸네일 헤더 직접 수정
- 프로필사진 원형으로 만들기, 테두리 등
- 백틱으로 인라인 블럭 


## 추후 반영 내역
- 디데이 추가 예정
