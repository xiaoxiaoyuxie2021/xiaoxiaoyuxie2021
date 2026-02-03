<!-- 顶部装饰 SVG -->
<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#39C5BB;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#66CCFF;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#FF6B9D;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="800" height="120" fill="url(#headerGrad)" rx="10"/>
  <text x="400" y="75" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="white" text-anchor="middle">
    沐咲汐 の GitHub
  </text>
  <circle cx="50" cy="60" r="8" fill="white" opacity="0.8">
    <animate attributeName="cy" values="60;50;60" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="60" r="8" fill="white" opacity="0.8">
    <animate attributeName="cy" values="60;70;60" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>

---

<!-- 个人信息卡片 SVG -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#f0f9ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#e0f2fe;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- 卡片背景 -->
  <rect x="10" y="10" width="780" height="180" fill="url(#cardBg)" stroke="#39C5BB" stroke-width="2" rx="15"/>
  
  <!-- 头像框 -->
  <circle cx="100" cy="100" r="60" fill="#39C5BB" opacity="0.2"/>
  <circle cx="100" cy="100" r="55" fill="none" stroke="#39C5BB" stroke-width="3"/>
  <text x="100" y="110" font-family="Arial" font-size="40" text-anchor="middle">🎧</text>
  
  <!-- 文字信息 -->
  <text x="180" y="60" font-family="Arial, sans-serif" font-size="28" font-weight="bold" fill="#1a1a2e">沐咲汐</text>
  <text x="180" y="90" font-family="Arial" font-size="16" fill="#666">xiaoxiaoyuxie2021 | He/Him</text>
  <text x="180" y="115" font-family="Arial" font-size="14" fill="#39C5BB">🏫 大一非计算机专业 | 手搓博客中</text>
  
  <!-- 博客链接 -->
  <rect x="180" y="130" width="200" height="30" fill="#39C5BB" rx="5"/>
  <text x="280" y="150" font-family="Arial" font-size="14" fill="white" text-anchor="middle">🌐 muxiaoxi.com</text>
  
  <!-- 装饰音符 -->
  <text x="700" y="50" font-size="30" fill="#FF6B9D" opacity="0.6">♪</text>
  <text x="730" y="80" font-size="25" fill="#66CCFF" opacity="0.6">♫</text>
  <text x="710" y="120" font-size="20" fill="#39C5BB" opacity="0.6">♬</text>
</svg>

---

## 🎵 二次元浓度检测

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/龙女仆-托尔-FF6B9D?style=for-the-badge&logo=appveyor&logoColor=white"/>
      <br>
      <sub>小林家的龙女仆</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/魔禁-御坂美琴-FFD700?style=for-the-badge&logo=appveyor&logoColor=black"/>
      <br>
      <sub>魔法禁书目录</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/VOCALOID-初音未来-39C5BB?style=for-the-badge&logo=appveyor&logoColor=white"/>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/VOCALOID-洛天依-66CCFF?style=for-the-badge&logo=appveyor&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🚀 手搓博客工程

<!-- 项目展示 SVG -->
<svg width="100%" height="150" viewBox="0 0 800 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="projectBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#39C5BB;stop-opacity:0.1" />
      <stop offset="100%" style="stop-color:#FF6B9D;stop-opacity:0.1" />
    </linearGradient>
  </defs>
  
  <rect x="10" y="10" width="780" height="130" fill="url(#projectBg)" stroke="#39C5BB" stroke-width="2" rx="10"/>
  
  <!-- 项目图标 -->
  <rect x="30" y="30" width="80" height="80" fill="#39C5BB" rx="10" opacity="0.2"/>
  <text x="70" y="80" font-size="40" text-anchor="middle">📝</text>
  
  <!-- 项目信息 -->
  <text x="130" y="50" font-family="Arial" font-size="22" font-weight="bold" fill="#1a1a2e">Blog-muxiaoxi</text>
  <text x="130" y="75" font-family="Arial" font-size="14" fill="#666">40天手搓个人博客 | Hugo + GitHub Actions + Cloudflare</text>
  
  <!-- Lighthouse 分数 -->
  <text x="130" y="100" font-family="Arial" font-size="12" fill="#39C5BB">⚡ Performance 81</text>
  <text x="250" y="100" font-family="Arial" font-size="12" fill="#22c55e">♿ Accessibility 100</text>
  <text x="400" y="100" font-family="Arial" font-size="12" fill="#22c55e">✓ Best Practices 100</text>
  <text x="550" y="100" font-family="Arial" font-size="12" fill="#3b82f6">🔍 SEO 91</text>
  
  <!-- 目标 -->
  <rect x="130" y="115" width="300" height="6" fill="#e5e7eb" rx="3"/>
  <rect x="130" y="115" width="243" height="6" fill="#FF6B9D" rx="3">
    <animate attributeName="width" values="0;243" dur="1s" fill="freeze"/>
  </rect>
  <text x="440" y="122" font-family="Arial" font-size="11" fill="#FF6B9D">冲刺 90+ 中...</text>
</svg>

**核心成就：**
- 从"会用"升级到"会调"，掌握**调试直觉 + 性能嗅觉 + 需求翻译**
- 解决 DNSSEC 配置、Git 大小写同步、404 终极排查等生产环境问题
- 使用 Font Awesome 7.1.0 本地图标包，零外部依赖

---

## 🛠️ 技术栈

### 🎨 Frontend

| 技能 | 熟练度 | 进度 |
|:---|:---|:---|
| 🟧 **HTML5** | 95% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="190" height="16" fill="#e34c26" rx="8"/></svg> |
| 🟦 **CSS3** | 88% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="176" height="16" fill="#264de4" rx="8"/></svg> |
| 🟨 **JavaScript** | 75% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="150" height="16" fill="#f7df1e" rx="8"/></svg> |

### ⚡ Static Site & Tools

| 技能 | 熟练度 | 进度 |
|:---|:---|:---|
| 💗 **Hugo** | 82% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="164" height="16" fill="#FF4088" rx="8"/></svg> |
| 🟥 **Git/Actions** | 78% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="156" height="16" fill="#f05032" rx="8"/></svg> |
| 🟧 **Cloudflare** | 70% | <svg width="200" height="16"><rect width="200" height="16" fill="#e5e7eb" rx="8"/><rect width="140" height="16" fill="#f38020" rx="8"/></svg> |


---

## 📊 当前挑战进度

| 挑战 | 进度 | 状态 |
|------|------|------|
| 🏃 性能优化冲刺 90+ | ████████░░ 80% | 进行中 |
| 🌙 黑夜模式开发 | ██████░░░░ 60% | 进行中 |
| 🔍 本地搜索实现 | ████░░░░░░ 40% | 计划中 |
| 🛡️ 安全靶场搭建 | █████░░░░░ 50% | 进行中 |

---

## 🌐 传送门

<p align="center">
  <a href="https://muxiaoxi.com">
    <img src="https://img.shields.io/badge/🌐_个人博客-muxiaoxi.com-39C5BB?style=for-the-badge&logo=hugo&logoColor=white"/>
  </a>
  <a href="https://b23.tv/snLtCQc">
    <img src="https://img.shields.io/badge/📺_Bilibili-沐咲汐-00A1D6?style=for-the-badge&logo=bilibili&logoColor=white"/>
  </a>
  <a href="https://github.com/xiaoxiaoyuxie2021">
    <img src="https://img.shields.io/badge/💻_GitHub-xiaoxiaoyuxie2021-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<!-- 底部装饰 -->
<svg width="100%" height="80" viewBox="0 0 800 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FF6B9D;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#66CCFF;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#39C5BB;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="800" height="60" fill="url(#footerGrad)" rx="10"/>
  <!-- 装饰星星 -->
  <text x="100" y="30" font-size="20" fill="white" opacity="0.6">✦</text>
  <text x="700" y="45" font-size="15" fill="white" opacity="0.6">✦</text>
</svg>
