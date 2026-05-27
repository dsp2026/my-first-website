# 새 프로젝트 시작 가이드

## 빠른 시작 (템플릿 사용)

```bash
# 1. 템플릿 복사
cp -r lecture1/_template_settings lecture1/[프로젝트명]

# 2. 디렉토리 이동
cd lecture1/[프로젝트명]

# 3. 개발 서버 시작
npm run dev
```

## 포함된 패키지
- React + Vite
- React Router DOM
- MUI (Material-UI)
- MUI Icons
- Roboto Font
- MUI 테마 (theme.js)

## 디렉토리 구조
```
프로젝트/
├── src/
│   ├── components/   # 재사용 컴포넌트
│   ├── pages/        # 페이지 컴포넌트
│   ├── theme.js      # MUI 테마 설정
│   ├── main.jsx      # 앱 진입점
│   └── App.jsx       # 루트 컴포넌트
├── public/           # 정적 파일
└── package.json
```

## 개발 명령어
- `npm run dev` - 개발 서버 시작
- `npm run build` - 프로덕션 빌드
- `npm run preview` - 빌드 미리보기
