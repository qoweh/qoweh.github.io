# 🗂️ 사이트 구조 가이드

## 📂 파일 구조
```
qoweh.github.io/
├── README.md         # 메인 랜딩 페이지 (진입점)
├── index.md          # 홈페이지 (About Me)
├── portfolio.md      # 포트폴리오 페이지
├── blog.md          # 블로그 페이지
├── contact.md       # 연락처 페이지
├── templates/       # 새 페이지용 템플릿
│   └── page-template.md
├── introduce/       # 기존 소개 자료
└── portfolio/       # 프로젝트 파일들
```

## 🎯 페이지별 역할

### README.md (랜딩 페이지)
- 사이트 전체 개요
- 빠른 네비게이션
- 구조 설명

### index.md (홈페이지)
- 개인 소개
- 전문성과 관심사
- 현재 학습 중인 내용

### portfolio.md (포트폴리오)
- 프로젝트들 상세 설명
- 성과와 경험
- 다운로드 링크

### blog.md (블로그)
- 기술 포스트 (예정)
- 학습 노트
- 경험 공유

### contact.md (연락처)
- 연락 방법
- 소셜 링크
- 협업 제안 안내

## 🚀 확장 방법

### 새 페이지 추가하기
1. `templates/page-template.md`를 복사
2. 적절한 이름으로 변경
3. 내용 수정
4. 각 페이지의 네비게이션에 링크 추가

### 네비게이션 업데이트
모든 페이지 상단의 네비게이션에 새 페이지 링크를 추가:
```markdown
- [🏠 Home](./index.md) | [💼 Portfolio](./portfolio.md) | [📚 Blog](./blog.md) | [📞 Contact](./contact.md) | [🆕 New Page](./new-page.md)
```

### 섹션 추가 예시
- `projects.md` - 개별 프로젝트 상세
- `skills.md` - 기술 스택 상세
- `experience.md` - 경험과 이력
- `achievements.md` - 수상과 인증

## 💡 유지보수 팁

1. **일관성 유지**: 모든 페이지에 동일한 네비게이션 구조 사용
2. **링크 확인**: 새 페이지 추가 시 모든 링크 업데이트
3. **템플릿 활용**: 새 페이지는 템플릿을 기반으로 제작
4. **구조 문서화**: 이 파일을 계속 업데이트
