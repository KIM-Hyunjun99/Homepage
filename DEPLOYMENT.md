# GitHub Pages 배포 방법 (How to Deploy with GitHub Pages)

이 파일은 GitHub Pages를 활성화하여 웹사이트를 공개하는 방법을 설명합니다.
This file explains how to enable GitHub Pages to publish your website.

## 📋 사전 요구사항 (Prerequisites)

1. PR을 main 브랜치에 병합 (Merge PR to main branch)
2. GitHub 저장소에 대한 관리자 권한 (Admin access to GitHub repository)

## 🚀 배포 단계 (Deployment Steps)

### 1. PR 병합 (Merge Pull Request)
- 현재 PR(`copilot/create-personal-homepage-again`)을 main 브랜치로 병합합니다.
- Merge the current PR to the main branch.

### 2. GitHub Pages 활성화 (Enable GitHub Pages)

1. GitHub 저장소로 이동: https://github.com/KIM-Hyunjun99/Homepage
2. 상단 메뉴에서 **Settings** 클릭
3. 왼쪽 사이드바에서 **Pages** 클릭
4. **Source** 섹션에서:
   - Source: **GitHub Actions** 선택
5. 저장 (Save)

### 3. 배포 확인 (Verify Deployment)

1. 저장소의 **Actions** 탭으로 이동
2. "Deploy to GitHub Pages" 워크플로우가 실행되는지 확인
3. 완료되면 다음 주소에서 홈페이지 확인:
   - **https://kim-hyunjun99.github.io/Homepage/**

## ✨ 자동 배포 (Automatic Deployment)

설정 완료 후, main 브랜치에 변경사항이 푸시될 때마다 자동으로 배포됩니다.
After setup, the site will automatically deploy whenever changes are pushed to the main branch.

## 🔧 문제 해결 (Troubleshooting)

### 404 오류가 발생하는 경우
- Settings > Pages에서 GitHub Actions가 선택되어 있는지 확인
- Actions 탭에서 워크플로우가 성공적으로 완료되었는지 확인
- 브라우저 캐시를 지우고 다시 시도

### 워크플로우가 실행되지 않는 경우
- Settings > Actions > General에서 워크플로우 권한이 "Read and write permissions"로 설정되어 있는지 확인
- Settings > Pages에서 Build and deployment source가 "GitHub Actions"로 설정되어 있는지 확인

## 📞 추가 도움말 (Additional Help)

공식 GitHub Pages 문서: https://docs.github.com/en/pages
