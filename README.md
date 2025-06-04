# 🧪 the-lab

프론트엔드 개발자 진형님의 개인 실험실입니다.  
React, TypeScript, 상태 관리, 디자인 시스템, 퍼포먼스 최적화까지 —  
실제 프로젝트에서 겪은 문제들을 직접 실험하며 더 깊게 이해하기 위해 만들어졌습니다.

---

## 🔍 목적

- 다양한 프론트엔드 기술을 **직접 실험하고 결과를 관찰**하기
- 코드와 기록을 **동시에 관리**하여 개인 지식 기반으로 성장
- 실무에서 바로 적용 가능한 **문제 해결 능력 향상**

---

## 🧪 현재 실험 주제 #1: Storybook을 정적 빌드하여 `/storybook`으로 연동

### 🎯 목표

- `the-lab` 프로젝트 안에 Storybook을 설치하고
- `storybook-static` 파일을 생성한 뒤 `public/storybook`에 복사
- 이후 `npm run start` 명령어만으로  
  `http://localhost:3000/storybook/` 경로에서 Storybook UI 접근 가능하게 구성

### 📦 실험 항목

1. Storybook 설치 및 기본 설정
2. `npm run build-storybook`으로 static 파일 생성
3. 생성된 `storybook-static/` 디렉토리를 `/public/storybook`으로 복사
4. CRA 서버 실행 시 `/storybook` 경로에서 Storybook 사용

---

## 🛠 실행 명령어

```bash
# 1. Storybook static 파일 생성
npm run build-storybook

# 2. 생성된 폴더를 public에 복사
mv storybook-static ./public/storybook

# 3. CRA 개발 서버 실행
npm run start

# ✅ 결과: http://localhost:3000/storybook 에서 Storybook 확인 가능
