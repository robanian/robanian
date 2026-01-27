# 🎨 LEO's Canvas - Neon GitHub Profile

> **"Architecting systems like an artist draws on canvas"**

devellybutton 스타일의 독창적이고 세련된 GitHub 프로필입니다.  
LED 네온 효과, Express.js 코드 스타일, 그리고 애니메이션 SVG로 구성되어 있습니다.

---

## ✨ 주요 특징

### 1. 🌟 LED 네온 스타일 디자인
- **LED 간판 느낌의 배너**: "LEO's Canvas" 타이틀과 깜빡이는 효과
- **그라데이션 색상 테마**: 빨강(#ff6b6b) → 노랑(#ffd93d) → 초록(#6bcf7f)
- **발광 효과**: text-shadow와 filter를 활용한 네온 글로우

### 2. 💻 Express.js 코드 스타일 자기소개
```javascript
const express = require('express');
const LEO = express();

LEO.set('role', 'Tech Lead & System Architect');
LEO.set('focus', [
  'WebRTC-based Real-time 3D Streaming',
  'Backend Platform Architecture'
]);
```
- 실제 코드처럼 보이는 자기소개
- 기술 스택과 철학을 코드로 표현
- 가독성 높은 구조화된 정보

### 3. 🎭 애니메이션 SVG 키워드
| 파일 | 효과 | 색상 테마 |
|------|------|-----------|
| `webrtc-shake.svg` | 흔들림 효과 (shake) | 빨강-노랑-초록 |
| `architecture-float.svg` | 떠오름 효과 (float) | 보라-핑크 |
| `streaming-pulse.svg` | 펄스 효과 (pulse) | 핑크-빨강-노랑 |

### 4. 📊 기술 스택 테이블 구조
- **Cloud & Infrastructure**: Kakao Cloud, Docker, Nginx
- **Database & Cache**: MySQL, Redis, Prisma
- **Backend Framework**: Node.js, Express, NestJS, Python
- **Real-time Streaming**: Unreal Engine 5.5, WebRTC, Pixel Streaming
- **Frontend**: Next.js, React, Tailwind CSS
- **Monitoring & CI/CD**: Grafana, Prometheus, GitHub Actions
- **AI & ML**: OpenAI, Pinecone, RAG System

### 5. 🗺️ Mermaid 아키텍처 다이어그램
- 프로젝트의 전체 시스템 구조를 시각화
- WebRTC 플로우와 백엔드 연결 관계 표현

---

## 📦 파일 구조

```
github-profile/
├── README.md                          # 메인 프로필 (이 파일을 GitHub에 업로드)
├── SETUP_GUIDE.md                     # 설치 및 커스터마이징 가이드
├── PROJECT_OVERVIEW.md                # 이 문서
└── assets/
    ├── webrtc-shake.svg              # WebRTC 흔들림 애니메이션
    ├── architecture-float.svg        # Architecture 떠오름 애니메이션
    ├── streaming-pulse.svg           # Streaming 펄스 애니메이션
    ├── neon-banner.html              # HTML 네온 배너 (참고용)
    └── neon-banner-static.svg        # SVG 정적 배너 (대체용)
```

---

## 🚀 빠른 시작

### 1. Repository 생성
```bash
# GitHub에서 본인 username과 동일한 이름의 public repo 생성
# 예: username이 robanian이면 robanian repo 생성
```

### 2. 파일 업로드
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.git
cd YOUR_USERNAME

# assets 폴더와 파일 복사
mkdir assets
cp webrtc-shake.svg ./assets/
cp architecture-float.svg ./assets/
cp streaming-pulse.svg ./assets/

# README.md 복사
cp README.md ./

# Push
git add .
git commit -m "✨ Add neon-style profile"
git push origin main
```

### 3. Username 변경
README.md에서 모든 `robanian`을 본인 username으로 변경:
```markdown
username=robanian  →  username=YOUR_USERNAME
```

---

## 🎨 커스터마이징 가이드

### 배너 색상 변경
Capsule Render의 `customColorList` 파라미터 수정:
- `6,12,20,24`: 어두운 톤 (현재)
- `0,2,4,6`: 밝은 톤
- `14,15,16,17`: 네온 컬러

### 기술 스택 추가
테이블에 새 행 추가:
```markdown
| **🆕 Category** | ![Tech](https://img.shields.io/badge/Name-Color?style=flat&logo=logo) |
```

Badge 생성: https://shields.io

### SVG 애니메이션 속도 조절
각 SVG 파일의 `animation` duration 값 수정:
```css
animation: shake 0.5s infinite;  /* 빠름 */
animation: shake 2s infinite;    /* 느림 */
```

---

## 💡 디자인 철학

### 1. LED 네온 간판 느낌
- 실제 네온 간판의 깜빡임과 발광 효과 재현
- 어두운 배경에서 빛나는 텍스트
- 그라데이션 컬러 조합으로 시선 집중

### 2. 코드로 말하기
- 자기소개를 Express.js 코드로 표현
- 기술 역량이 코드 구조에서 자연스럽게 드러남
- 개발자답게 "실행 가능한" 프로필

### 3. 예술과 기술의 융합
- "Canvas", "Drawing"으로 시스템 설계를 예술에 비유
- 구조화된 정보 + 창의적인 시각 요소
- 기술 블로그가 아닌 "작품 전시장" 느낌

---

## 🔧 기술적 특징

### SVG 애니메이션
- **CSS Keyframes**: 순수 CSS로 애니메이션 구현
- **Filter Effects**: feGaussianBlur로 글로우 효과
- **Linear Gradient**: 그라데이션 색상 전환

### Responsive Design
- GitHub 다크모드/라이트모드 자동 대응
- 다양한 화면 크기에서 최적화된 레이아웃
- 모바일에서도 깨지지 않는 구조

### Performance
- 경량 SVG 파일 (각 2KB 이하)
- 외부 API 최소화 (Shields.io, Vercel Stats만 사용)
- 빠른 로딩 속도

---

## 📚 영감을 받은 프로필들

- [devellybutton](https://github.com/devellybutton) - 코드 스타일 자기소개
- [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) - 통계 카드
- [kyechan99/capsule-render](https://github.com/kyechan99/capsule-render) - 배너 생성

---

## 🤝 기여 및 피드백

이 프로필 템플릿이 마음에 드셨다면:
- ⭐ Star를 눌러주세요
- 🍴 Fork해서 나만의 스타일로 커스터마이징
- 💬 개선 아이디어나 버그 리포트 환영

---

## 📄 라이선스

MIT License - 자유롭게 사용하고 수정하세요!

---

**Made with 🎨 by LEO**  
*Architecting systems like an artist draws on canvas*
