<div align="center">
  
  <!-- 코딩 심볼 LED 네온 배너 -->
  <img src="./assets/neon-code-banner.svg" alt="LEO's Code Neon" />
  
  <br/><br/>
  
  <!-- 흔들리는 키워드 SVG들 -->
  <img src="./assets/webrtc-shake.svg" height="35" />
  <img src="./assets/architecture-float.svg" height="35" />
  <img src="./assets/streaming-pulse.svg" height="35" />
  
  <br/><br/>
  
  <!-- 타이핑 애니메이션 -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=4D9EFF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=WebRTC-based+Real-time+3D+Streaming;Backend+Architecture+%26+Infrastructure;Unreal+Engine+for+Games+%26+Real-time+Content" alt="Typing SVG" />
  
</div>

<br/>

---

<br/>

## 👨‍💻 const LEO = { ... }

```javascript
const express = require('express');
const LEO = express();

// Core Identity
LEO.set('role', 'Tech Lead & System Architect');
LEO.set('company', 'DDukDDak');
LEO.set('mission', [
  'WebRTC-based Real-time 3D Streaming Infrastructure',
  'Backend Platform Architecture Design', 
  'Automation & Operations at Scale'
]);

// Technical Expertise
LEO.use('/specialization', {
  streaming: {
    technology: 'WebRTC-based Real-time 3D Rendering',
    engine: 'Unreal Engine 5.5',
    use_cases: ['Interior Design Visualization', 'Upcoming Steam Game Development']
  },
  backend: {
    stack: 'Node.js/Express + Prisma ORM',
    architecture: 'Modular Monolithic with Future MSA Readiness',
    database: 'MySQL + Redis for Distributed Sessions'
  },
  infrastructure: {
    cloud: 'Kakao Cloud with Dynamic VM Provisioning',
    orchestration: 'Docker + Portainer + GitHub Actions',
    monitoring: 'Grafana + Prometheus + Loki'
  }
});

// Philosophy - Inspired by Elbert Hubbard
LEO.use('/philosophy', (req, res, next) => {
  const wisdom = {
    quote: '"Do not take life too seriously. You will never get out of it alive."',
    author: '— Elbert Hubbard',
    interpretation: [
      'Build systems that survive, not systems that are perfect',
      'Long-term maintainability over short-term perfection',
      'Pragmatic architecture that scales with reality',
      'Operational stability beats theoretical elegance'
    ]
  };
  
  res.json({
    principle: 'Sustainable Architecture Philosophy',
    motto: 'Production-Stable Systems > Perfect Code',
    approach: wisdom
  });
  
  next();
});

// Current Mission
LEO.get('/now', (req, res) => {
  res.status(200).json({
    project: 'DDukDDak - AI Interior Design Platform',
    stack: 'WebRTC 3D Streaming + RAG-powered AI Consultation',
    milestone: 'February 2025 Closed Beta Launch',
    tasks: [
      '⚡ Kakao Cloud OpenAPI integration for auto-scaling',
      '🎮 Multiple Cirrus server orchestration via Matchmaker',
      '🔐 Redis-based distributed session management',
      '📦 TypeScript migration with Prisma type generation',
      '🎯 Steam game development with Unreal Engine'
    ]
  });
});

// Error Handling - Learn from Production
LEO.use((err, req, res, next) => {
  console.error('💥 Error detected:', err.message);
  
  // Philosophy in action: graceful degradation
  res.status(500).json({
    error: 'System architecture evolving...',
    recovery: 'Analyze logs → Network diagnostics → Incremental fixes',
    lesson: 'Every failure teaches sustainable design'
  });
});

// System Online
const PORT = process.env.PORT || 3000;
LEO.listen(PORT, () => {
  console.log(`🚀 LEO's Architecture running on port ${PORT}`);
  console.log('🎨 Drawing systems that last, not just systems that shine');
  console.log('⚡ Building for the long run, one pragmatic decision at a time');
});

module.exports = LEO;
```

<br/>

---

<br/>

## 🛠️ Tech Stack

<div align="center">

<table>
<tr>
<td width="500" valign="top">

<img src="./assets/techstack/ts-Infra.svg" height="40" />

<table>
<tr><td colspan="2"><img width="500" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" /></td></tr>
<tr><th width="100" align="left">Layer</th><th align="left">Stack</th></tr>
<tr><td width="100"><b>Cloud</b></td><td>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Kakao-FFCD00?style=flat&logo=kakao&logoColor=black" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Infra</b></td><td>
<img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Portainer-13BEF9?style=flat&logo=portainer&logoColor=white" />
<img src="https://img.shields.io/badge/PM2-2B037A?style=flat&logo=pm2&logoColor=white" />
</td></tr>
<tr><td width="100"><b>CI/CD</b></td><td>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Self--Hosted-2088FF?style=flat&logo=github&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Monitor</b></td><td>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Loki-F46800?style=flat" />
</td></tr>
<tr><td width="100"><b>DevOps</b></td><td>
<img src="https://img.shields.io/badge/NAS-B5B5B6?style=flat&logo=synology&logoColor=black" />
<img src="https://img.shields.io/badge/SVN-809CC9?style=flat&logo=subversion&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Database</b></td><td>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" />
</td></tr>
<tr><td width="100"><b>IDE</b></td><td>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white" />
<img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat&logo=eclipse&logoColor=white" />
</td></tr>
</table>

---

<img src="./assets/techstack/ts-Backend.svg" height="40" />

<table>
<tr><td colspan="2"><img width="500" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" /></td></tr>
<tr><th width="100" align="left">Layer</th><th align="left">Stack</th></tr>
<tr><td width="100"><b>Language</b></td><td>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Framework</b></td><td>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat&logo=apachetomcat&logoColor=black" /><br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
</td></tr>
</table>

---

<img src="./assets/techstack/ts-Frontend.svg" height="40" />

<table>
<tr><td colspan="2"><img width="500" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" /></td></tr>
<tr><th width="100" align="left">Layer</th><th align="left">Stack</th></tr>
<tr><td width="100"><b>Framework</b></td><td>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
</td></tr>
<tr><td width="100"><b>Styling</b></td><td>
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />
</td></tr>
</table>

</td>
<td width="50"></td>
<td width="500" valign="top">

<img src="./assets/techstack/ts-GameEngine.svg" height="40" />

<table>
<tr><td colspan="2"><img width="500" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" /></td></tr>
<tr><th width="100" align="left">Type</th><th align="left">Stack</th></tr>
<tr><td width="100"><b>Engine</b></td><td>
<img src="https://img.shields.io/badge/Unreal-0E1128?style=flat&logo=unrealengine&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Streaming</b></td><td>
<img src="https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white" />
</td></tr>
</table>

---

<img src="./assets/techstack/ts-AI.svg" height="40" />

<table>
<tr><td colspan="2"><img width="500" height="1" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" /></td></tr>
<tr><th width="100" align="left">Purpose</th><th align="left">Stack</th></tr>
<tr><td width="100"><b>LLM</b></td><td>
<img src="https://img.shields.io/badge/Claude-191919?style=flat&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/ChatGPT-412991?style=flat&logo=openai&logoColor=white" />
</td></tr>
<tr><td width="100"><b>ML/CV</b></td><td>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" /><br/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" />
</td></tr>
<tr><td width="100"><b>Vector</b></td><td>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat" />
<img src="https://img.shields.io/badge/RAG-764BA2?style=flat" />
</td></tr>
<tr><td width="100"><b>Notebook</b></td><td>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white" />
</td></tr>
</table>

</td>
</tr>
</table>

</div>

<br/>

---

<br/>

## 🏗️ Architecture Philosophy

```javascript
/**
 * LEO's Sustainable Architecture Manifesto
 * 
 * "Do not take life too seriously. You will never get out of it alive."
 * — Elbert Hubbard
 * 
 * In code: Build systems that SURVIVE, not systems that are PERFECT.
 */

const philosophy = {
  
  // Core Belief: Longevity over Perfection
  sustainability: {
    principle: 'Long-term maintainability beats short-term brilliance',
    why: 'Perfect systems fail under real-world pressure',
    how: [
      'Modular boundaries for future evolution',
      'Operational stability as first-class concern',
      'Documentation that survives team changes',
      'Error handling that teaches, not just catches'
    ]
  },
  
  // Architecture Pattern
  structure: {
    pattern: 'Modular Monolithic Architecture',
    tradeoff: 'Solo/small team efficiency + Future MSA readiness',
    decision: 'Start simple, split when pain exceeds cost',
    modules: 'Feature-based > Layer-based (for AI context & maintainability)'
  },
  
  // Code Standards
  pragmaticCode: {
    naming: '*.routes.js → *.controller.js → *.service.js → *.model.js',
    errorFlow: 'Controllers: success() only | Services: throw fail/Error',
    typeSystem: 'Prisma ORM → Type-safe queries → TypeScript migration prep',
    validation: 'Joi at boundaries, Prisma types internally'
  },
  
  // Infrastructure Principles
  operations: {
    separation: 'NPM proxy | Bastion SSH | Dedicated monitoring servers',
    networking: 'Manual port forwarding > UPnP (learned the hard way)',
    deployment: 'Docker + GitHub Actions (hybrid runners for security)',
    scaling: 'Vertical first, horizontal when metrics prove necessity'
  },
  
  // Performance Wisdom (Battle-Tested)
  optimization: {
    streaming: {
      lesson: 't.MaxFPS 30 prevents GPU bottleneck (unlimited FPS = death)',
      gpu: 'DLSS optimization: 29% utilization with quality maintained',
      tsrConflict: 'TSR + DLSS = choose one, mixing kills performance'
    },
    sessions: 'Redis for distributed state (MySQL for durability)',
    caching: 'Cache what scales poorly, not what changes frequently'
  },
  
  // The Hubbard Principle in Action
  realityCheck: {
    perfectionist: 'Rewrites code 10 times, launches never',
    pragmatist: 'Ships v1, learns from users, iterates to v10',
    winner: 'Pragmatist - because systems that don\'t ship don\'t survive',
    reminder: 'Production failures teach more than pristine local tests'
  }
  
};

// Final Wisdom
console.log('🎨 Drawing architecture for the long haul...');
console.log('⚡ Building systems that survive reality, not just impress peers');
console.log('🚀 Remember: Working software > Perfect software');

export default philosophy;
```

<br/>

---

<br/>

## 📊 GitHub Activity

<div align="center">
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=robanian&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=4D9EFF&icon_color=FFD700&text_color=C9D1D9"/>
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=robanian&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4D9EFF&text_color=C9D1D9"/>

</div>

<br/>

<div align="center">
  
  [![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=robanian&theme=tokyonight&hide_border=true&background=0D1117&stroke=4D9EFF&ring=FFD700&fire=FF6B6B&currStreakLabel=C9D1D9)](https://git.io/streak-stats)

</div>

<br/>

---

<br/>

## 💼 Current Mission: DDukDDak

<div align="center">

```mermaid
graph TB
    subgraph "Client Layer"
        A[User Browser/App]
    end
    
    subgraph "WebRTC Streaming Infrastructure"
        B[Matchmaker Service]
        C[Cirrus Server 1]
        D[Cirrus Server 2]
        E[Cirrus Server N...]
    end
    
    subgraph "Compute Layer - Kakao Cloud"
        F[UE5.5 Instance 1<br/>DLSS Optimized]
        G[UE5.5 Instance 2<br/>Dynamic Provisioning]
        H[UE5.5 Instance N<br/>Auto-scaling]
    end
    
    subgraph "Backend Services"
        I[Express Backend API]
        J[MySQL + Prisma ORM]
        K[Redis Session Store]
    end
    
    subgraph "AI Services"
        L[RAG Consultation System]
        M[Pinecone Vector DB]
        N[OpenAI GPT-4]
    end
    
    A -->|WebRTC Request| B
    B -->|Load Balance| C
    B -->|Route| D
    B -->|Distribute| E
    
    C <-->|WebSocket| F
    D <-->|WebSocket| G
    E <-->|WebSocket| H
    
    A -->|REST API| I
    I -->|Query| J
    I -->|Session| K
    I -->|AI Request| L
    
    L -->|Semantic Search| M
    L -->|LLM Response| N
    
    style A fill:#61DAFB,stroke:#333,stroke-width:2px
    style B fill:#FF6B6B,stroke:#333,stroke-width:2px
    style C fill:#FFD93D,stroke:#333,stroke-width:2px
    style D fill:#FFD93D,stroke:#333,stroke-width:2px
    style E fill:#FFD93D,stroke:#333,stroke-width:2px
    style F fill:#764BA2,stroke:#333,stroke-width:2px
    style G fill:#764BA2,stroke:#333,stroke-width:2px
    style H fill:#764BA2,stroke:#333,stroke-width:2px
    style I fill:#339933,stroke:#333,stroke-width:2px
    style J fill:#4479A1,stroke:#333,stroke-width:2px
    style K fill:#DC382D,stroke:#333,stroke-width:2px
    style L fill:#412991,stroke:#333,stroke-width:2px
    style M fill:#000000,stroke:#FFD700,stroke-width:2px
    style N fill:#412991,stroke:#333,stroke-width:2px
```

### 🎯 **DDukDDak** - AI-Powered Interior Design Platform

**Tech Stack:**
- **Streaming**: WebRTC-based 3D Visualization with Unreal Engine 5.5
- **Backend**: Node.js/Express + Prisma ORM + MySQL/Redis
- **AI**: RAG System (Pinecone + OpenAI) for Design Consultation
- **Infrastructure**: Kakao Cloud + Docker + Dynamic VM Provisioning

**Target**: February 2025 Closed Beta Launch

**What's Next**: Steam game development leveraging the same UE5.5 infrastructure

</div>

<br/>

---

<br/>

## 🎮 Beyond Enterprise: Gaming Ahead

```javascript
// Upcoming: Leveraging Unreal Engine for Game Development
const futureVision = {
  platform: 'Steam',
  engine: 'Unreal Engine 5.5',
  leverage: [
    'Reuse DDukDDak streaming infrastructure knowledge',
    'Apply production-hardened architecture patterns',
    'Bridge enterprise tech with gaming creativity'
  ],
  philosophy: 'Same engine, different canvas - still drawing systems'
};

console.log('🎮 From interior design visualization to full games');
console.log('🚀 Building worlds, not just software');
```

<br/>

---

<br/>

## 📫 Let's Connect

<div align="center">

```javascript
const contact = {
  openTo: [
    'WebRTC & Real-time Streaming Architecture',
    'Unreal Engine Integration & Optimization',
    'Backend System Design & Scalability',
    'Infrastructure Automation & Operations',
    'Gaming + Enterprise Tech Crossover'
  ],
  response: 'Usually within 24 hours',
  philosophy: 'Building systems that survive > Building perfect systems'
};

// Always happy to discuss sustainable architecture
```

<br/>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Frobanian&count_bg=%234D9EFF&title_bg=%230D1117&icon=github.svg&icon_color=%23FFFFFF&title=Profile+Views&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

<br/>

---

<div align="center">
  
  <br/>
  
  ### ⚡ The Hubbard Principle
  
  **"Do not take life too seriously. You will never get out of it alive."**  
  — Elbert Hubbard
  
  <br/>
  
  <sub>Building systems that survive reality 🎨 Not chasing perfection that never ships 🚀</sub>
  
  <br/><br/>
  
</div>
