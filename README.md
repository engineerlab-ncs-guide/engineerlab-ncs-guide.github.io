# 엔지니어랩 공기업·NCS — GitHub Pages 업로드 안내

홈페이지 주소: https://engineerlab-ncs-guide.github.io/

- Organization 이름: `engineerlab-ncs-guide`
- Repository 이름: `engineerlab-ncs-guide.github.io`
- 저장소 공개 범위(Visibility): **Public**
- 기본 브랜치: **main**
- 게시 폴더: **/(root)**

## 처음 업로드하는 방법

1. GitHub에 로그인하여 `engineerlab-ncs-guide` Organization을 만들거나, 이미 생성한 경우 선택합니다. 동일한 이름이 이미 사용 중이면 조직/주소를 임의로 변경하지 말고 사용 가능한 주소로 다시 제작해야 합니다.
2. Organization 안에서 이름이 **`engineerlab-ncs-guide.github.io`**인 **Public** 저장소를 만듭니다.
3. 제공한 ZIP 파일을 컴퓨터에서 **압축 해제**합니다.
4. 압축 해제한 폴더 *안의 파일과 폴더들*(`index.html`, `assets`, `favicon.png`, `robots.txt`, `sitemap.xml`, `.nojekyll` 등)을 저장소 **최상위(root)**에 업로드합니다. 사이트 폴더를 한 겹 더 넣으면 안 됩니다. `assets` 폴더의 내부 구조를 유지하세요.
5. 저장소의 `Settings → Pages`에서 Source를 **Deploy from a branch**, Branch를 **main**, Folder를 **/(root)**로 선택하고 저장합니다.
6. GitHub가 게시를 완료한 후 **https://engineerlab-ncs-guide.github.io/** 에 접속해 확인합니다. 게시에 시간이 걸릴 수 있습니다.
7. 상단 **'할인쿠폰 확인'** 버튼과 본문의 긴 랜딩 이미지 아무 곳이나 눌러 새 탭으로 **https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288** 주소가 열리는지 확인합니다. 본문 중간의 강좌 비교 가이드 링크는 **https://engineerlab-guide.netlify.app/public-enterprise-ncs/**로 연결됩니다.
8. 콘텐츠를 수정하려면 `index.html` 및 `assets/css/style.css`를 편집한 다음, 같은 경로에 다시 업로드하여 반영합니다.

## 파일 역할

- `index.html`: 콘텐츠, 메타 태그, SEO용 구조화 데이터, 링크
- `assets/css/style.css`: 모바일과 PC 스타일 및 상단 고정 헤더
- `assets/images/landing.webp`: 제공하신 **936×8416** 원본 WebP (크롭·리사이즈 없음)
- `assets/images/thumbnail.webp`: 생성한 **1254×1254** SEO 공유용 정사각형 이미지
- `favicon.png`: 96×96 픽셀 파비콘
- `apple-touch-icon.png`: 180×180 픽셀 모바일 홈 화면 아이콘
- `assets/images/logo.png`: 고정 헤더·푸터에 사용한 사이트 로고 심볼 (파비콘과 동일한 디자인)
- `robots.txt`, `sitemap.xml`, `.nojekyll`: 검색로봇 경로 안내와 GitHub Pages 설정

## 꼭 확인하세요

- 랜딩 이미지 및 상단 할인쿠폰 버튼은 **https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288**로 연결됩니다. 프로모션 내용과 실제 쿠폰 발급 조건은 이동한 페이지에서 확인하세요. (이 사이트의 로고는 별도로 제작된 사이트용 심볼로 공식 업체 로고와 다를 수 있습니다.)
- 가격은 2026년 10월 26일 전달된 강좌 화면 기준입니다. 상품명/가격/수강조건은 공식 페이지에서 수시 확인하세요.
- 검색 결과 노출, 순위, 네이버 사이트명·파비콘 표시 및 AI 검색 인용은 보장되지 않습니다. 배포 후 네이버 서치어드바이저·Google Search Console에서 사이트 소유 확인과 사이트맵 제출은 직접 진행해야 합니다.
