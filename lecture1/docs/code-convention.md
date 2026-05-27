# Code Convention

## 파일 구조
- 컴포넌트: PascalCase (예: MyComponent.jsx)
- 유틸리티: camelCase (예: formatDate.js)
- 상수: UPPER_SNAKE_CASE (예: API_BASE_URL)

## React 컴포넌트 규칙

### 함수형 컴포넌트 사용
```jsx
const MyComponent = ({ prop1, prop2 }) => {
  return <div>{prop1}</div>;
};
export default MyComponent;
```

### Props 구조 분해
```jsx
// Good
const Card = ({ title, description, onClick }) => { ... }

// Bad
const Card = (props) => { const { title } = props; ... }
```

## Import 순서
1. React 관련
2. 외부 라이브러리 (MUI, Router 등)
3. 내부 컴포넌트
4. 스타일/CSS

## 변수명
- 상태: [noun]State 또는 is/has 접두사
- 핸들러: handle[Event] (예: handleClick, handleSubmit)
- Boolean: is/has/can 접두사
