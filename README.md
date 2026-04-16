# 한 눈에 보는 2026년 정부예산안

> 2026년 정부예산안 세부사업 예산을 16대 분야별로 보여준다.

🔗 **라이브 데모**: [https://msitsti2025.github.io/fiscal-budget-2026/](https://msitsti2025.github.io/fiscal-budget-2026/)

---

## 📊 주요 기능

- **총 2,275개 세부사업** 예산 현황 조회 및 분석
- **16개 분야**별 예산 배분 현황 시각화
  - 공공질서및안전, 과학기술, 교육, 교통및물류, 국방, 국토및지역개발, 농림수산, 문화및관광, 보건, 사회복지, 산업·중소기업및에너지, 예비비, 일반·지방행정, 통신, 통일·외교, 환경
- **61개 부처**별 예산 현황
- **3D 지도 시각화** (Three.js 기반 인터랙티브 3D 빌딩 뷰)
- 다중 필터링 (사업명 검색, 분야, 부처, 회계 구분)
- 실시간 KPI 및 차트 업데이트
- 총 예산 규모: **약 624.8조원**

## 🛠 기술 스택

- **Frontend**: Vanilla HTML/CSS/JavaScript (의존성 최소화)
- **차트 라이브러리**: [Chart.js](https://www.chartjs.org/) v4.4.0
- **3D 시각화**: [Three.js](https://threejs.org/)
- **데이터**: JSON (xlsx에서 변환)
- **배포**: GitHub Pages (정적 웹사이트)

## 📁 프로젝트 구조

```
fiscal-budget-2026/
├── index.html      # 메인 대시보드 (필터링, 차트, 테이블)
├── map3d.html      # 3D 지도 시각화
├── data.json       # 정부예산 데이터 (2,275개 세부사업)
├── map3d.json      # 3D 시각화용 전처리 데이터
└── README.md       # 문서
```

## 🚀 GitHub Pages 배포 방법

### 1단계: 저장소 생성
```bash
# GitHub에서 새 저장소 생성 (예: fiscal-budget-2026)
# 또는 기존 저장소 사용
```

### 2단계: 파일 업로드
```bash
git init
git add .
git commit -m "초기 커밋: 2026 정부예산안 분석 플랫폼"
git branch -M main
git remote add origin https://github.com/[username]/fiscal-budget-2026.git
git push -u origin main
```

### 3단계: GitHub Pages 활성화
1. 저장소 → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. **Save** 클릭
5. 약 1~2분 후 `https://[username].github.io/fiscal-budget-2026/` 접속 가능

## 📈 데이터 출처

- **2026년 정부예산안** (세부사업 기준)
- 단위: 백만원

## 📝 라이선스

본 플랫폼의 코드는 MIT License를 따릅니다.
데이터는 공공데이터 이용 정책을 따릅니다.
