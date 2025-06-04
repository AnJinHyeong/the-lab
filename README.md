<<<<<<< HEAD
<<<<<<< HEAD
# the-lab
=======
# Getting Started with Create React App
=======
# 🧪 the-lab
>>>>>>> 90f38bf (README)

프론트엔드 개발자 진형님의 개인 실험실입니다.  
React, TypeScript, 상태 관리, 디자인 시스템, 퍼포먼스 최적화까지 —  
실제 프로젝트에서 겪은 문제들을 직접 실험하며 더 깊게 이해하기 위해 만들어졌습니다.

## 🔍 목적

- 다양한 프론트엔드 기술을 **직접 실험하고 결과를 관찰**하기
- 코드와 기록을 **동시에 관리**하여 개인 지식 기반으로 성장
- 실무에서 바로 적용 가능한 **문제 해결 능력 향상**

---

## 🧪 현재 실험 주제 #1: Storybook 외부 빌드 연동

### 🎯 목표
다른 프로젝트에서 Storybook을 **빌드(export)** 한 후,  
그 `storybook-static` 파일을 `the-lab` 프로젝트 내에서 **`npm run start`로 실행**하고,  
**로컬 서버에서 URL만 바꿔 Storybook에 접근 가능하게 하는 방법을 학습**합니다.

### 📦 실험 항목
- 외부 프로젝트에서 `storybook build`로 static 파일 생성
- 해당 빌드 파일을 `the-lab/public/storybook` 또는 `/storybook-static` 디렉토리에 복사
- `react-scripts`를 활용해 `npm run start`로 정적 파일 호스팅
- 브라우저에서 `http://localhost:3000/storybook/` 과 같이 직접 접근 가능하게 설정
- 필요한 경우 `.htaccess`, `webpack`, 또는 `express` 기반 커스터마이징 고려

<<<<<<< HEAD
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
>>>>>>> da1dacf (Initialize project using Create React App)
=======
### 📁 실험 디렉토리
>>>>>>> 90f38bf (README)
