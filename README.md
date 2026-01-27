<div align="center">
  
  <!-- LED 네온 배너 -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=280&section=header&text=LEO's%20Canvas&fontSize=70&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Drawing%20Systems%20%26%20Architecture&descAlignY=55&descSize=22" />
  
  <br/>
  
  <!-- 흔들리는 키워드 SVG들 -->
  <img src="./assets/webrtc-shake.svg" height="35" />
  <img src="./assets/architecture-float.svg" height="35" />
  <img src="./assets/streaming-pulse.svg" height="35" />
  
  <br/><br/>
  
  <!-- 타이핑 애니메이션 -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=FF6B6B&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=WebRTC+based+Real-time+3D+Streaming;Pixel+Streaming+Infrastructure;System+Architecture+%26+Operations" alt="Typing SVG" />
  
</div>

<br/>

---

<br/>

## 👨‍💻 const LEO = { ... }

```javascript
const express = require('express');
const LEO = express();

// 기본 설정
LEO.set('role', 'Tech Lead & System Architect');
LEO.set('company', 'DDukDDak');
LEO.set('focus', [
  'WebRTC-based Real-time 3D Streaming',
  'Backend Platform Architecture', 
  'Infrastructure Automation'
]);

// 핵심 미들웨어
LEO.use('/skills', {
  streaming: 'Pixel Streaming with Unreal Engine 5.5',
  backend: 'Node.js/Express + Prisma ORM',
  infrastructure: 'Docker + Kakao Cloud + GitHub Actions',
  database: 'MySQL + Redis Session Management'
});

// 아키텍처 철학
LEO.use('/philosophy', (req, res, next) => {
  res.json({
    principle: 'Modular Monolithic over Microservices',
    reason: 'Solo/small team efficiency + Future MSA readiness',
    priority: 'Production-stable structure > Perfect architecture'
  });
  next();
});

// 현재 작업
LEO.get('/current-work', (req, res) => {
  res.status(200).json({
    project: 'AI Interior Design Platform with Pixel Streaming',
    tasks: [
      'Kakao Cloud OpenAPI integration for dynamic VM provisioning',
      'Multiple Cirrus server management via Matchmaker',
      'Redis session management implementation',
      'TypeScript migration preparation through Prisma adoption'
    ],
    target: 'February 2025 Closed Beta Launch'
  });
});

// 에러 처리
LEO.use((err, req, res, next) => {
  console.error('❌ Error:', err.message);
  res.status(500).json({
    error: 'System architecture in progress...',
    solution: 'Analyze logs → Network diagnostics → Incremental testing'
  });
});

// 서버 실행
const PORT = process.env.PORT || 3000;
LEO.listen(PORT, () => {
  console.log(`🚀 LEO's System running on port ${PORT}`);
  console.log('📐 Drawing architecture like an artist...');
});

module.exports = LEO;
```

<br/>

---

<br/>

## 🛠️ Tech Stacks

<div align="center">

### 🎨 Canvas & Brushes

| Category | Technologies |
|:--------:|:------------|
| **☁️ Cloud & Infrastructure** | ![Kakao Cloud](https://img.shields.io/badge/Kakao_Cloud-FFCD00?style=flat&logo=kakao&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) ![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=flat&logo=portainer&logoColor=white) |
| **🗄️ Database & Cache** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) |
| **🔧 Backend Framework** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) |
| **🎮 Real-time Streaming** | ![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5.5-0E1128?style=flat&logo=unrealengine&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white) ![Pixel Streaming](https://img.shields.io/badge/Pixel_Streaming-FF6B6B?style=flat) |
| **🎨 Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) |
| **📊 Monitoring & CI/CD** | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) |
| **🤖 AI & ML** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat) ![RAG](https://img.shields.io/badge/RAG_System-764BA2?style=flat) |

</div>

<br/>

---

<br/>

## 🎯 Architecture Philosophy

```javascript
// 시스템을 그림 그리듯 설계합니다

const philosophy = {
  structure: {
    pattern: 'Modular Monolithic Architecture',
    reason: 'Clear boundaries for future MSA readiness',
    priority: 'Solo/small team development efficiency'
  },
  
  codeStyle: {
    naming: '*.routes.js → *.controller.js → *.service.js → *.model.js',
    errorHandling: 'Controller: success() only | Service: throw fail/Error',
    typeSystem: 'Prisma ORM for type-safe queries + TypeScript migration prep'
  },
  
  infrastructure: {
    separation: 'NPM for proxy | Bastion for SSH | Dedicated monitoring',
    networking: 'Manual port forwarding > UPnP (stability)',
    deployment: 'Docker + GitHub Actions (hybrid runners)'
  },
  
  optimization: {
    streaming: 't.MaxFPS 30 to prevent GPU bottleneck',
    dlss: 'TSR conflict management for performance',
    session: 'Redis for distributed session management'
  }
};

// "완벽한 코드보다 운영 가능한 구조"
console.log('🎨 Drawing production-ready systems...');
```

<br/>

---

<br/>

## 📊 GitHub Stats

<div align="center">
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=robanian&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FF6B6B&icon_color=FFD93D&text_color=C9D1D9"/>
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=robanian&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF6B6B&text_color=C9D1D9"/>

</div>

<br/>

<div align="center">
  
  [![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=robanian&theme=tokyonight&hide_border=true&background=0D1117&stroke=FF6B6B&ring=FFD93D&fire=FF6B6B&currStreakLabel=C9D1D9)](https://git.io/streak-stats)

</div>

<br/>

---

<br/>

## 💼 Current Project

<div align="center">

```mermaid
graph TB
    A[User Browser] -->|WebRTC| B[Matchmaker]
    B -->|Route| C[Cirrus Server 1]
    B -->|Route| D[Cirrus Server 2]
    C -->|WebSocket| E[UE5.5 Application]
    D -->|WebSocket| F[UE5.5 Application]
    E -->|Stream| G[Kakao Cloud VM]
    F -->|Stream| H[Kakao Cloud VM]
    
    I[Backend API] -->|Query| J[MySQL + Prisma]
    I -->|Session| K[Redis]
    I -->|AI Service| L[RAG System]
    L -->|Vector DB| M[Pinecone]
    
    style A fill:#61DAFB
    style B fill:#FF6B6B
    style C fill:#FFD93D
    style D fill:#FFD93D
    style E fill:#764BA2
    style F fill:#764BA2
    style I fill:#339933
    style J fill:#4479A1
    style K fill:#DC382D
    style L fill:#412991
```

**DDukDDak** - AI Interior Design Platform with Real-time 3D Visualization  
🎯 Target: February 2025 Closed Beta Launch

</div>

<br/>

---

<br/>

## 📫 Let's Connect

<div align="center">

```javascript
const contact = {
  role: 'Always open to discussing system architecture & real-time streaming',
  response_time: 'Usually within 24 hours',
  topics: ['WebRTC', 'Pixel Streaming', 'Backend Architecture', 'Infrastructure']
};

// Feel free to reach out!
```

<br/>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Frobanian&count_bg=%23FF6B6B&title_bg=%230D1117&icon=github.svg&icon_color=%23FFFFFF&title=Profile+Views&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

<br/>

---

<div align="center">
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=150&section=footer&fontSize=0" />
  
  <br/>
  
  **"Do not take life too seriously. You will never get out of it alive."** — Elbert Hubbard  
  <sub>Focusing on production-stable structures over perfect architecture</sub>
  
</div>
