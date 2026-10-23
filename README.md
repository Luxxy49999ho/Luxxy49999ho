<!-- ============================================================== -->
<!-- 1. BANNER GRADIENT BERJALAN 360° (MERAH, OREN, KUNING)         -->
<!-- ============================================================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,20&height=180&section=header&text=LUXXYHub&fontSize=70&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Product-minded%20Developer&descAlignY=55&descSize=20" width="100%" />
</div>

<!-- ============================================================== -->
<!-- 2. ANIMASI TEKS GRADIENT (TYPING EFFECT)                       -->
<!-- ============================================================== -->
<div align="center">
  <a href="https://github.com/luxxy49999ho">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=FF8C00&center=true&vCenter=true&width=600&lines=DON'T+SPEAK+A+GAMBLING;Building+and+sharing+work+in+public;Lua+Scripting+%7C+Open+Source" alt="Typing SVG" />
  </a>
</div>

<br>

<!-- ============================================================== -->
<!-- 3. SYSTEM INFO & DOT-MATRIX PROFILE (ANIMASI WARNA)            -->
<!-- ============================================================== -->
<div align="center">
  <table style="background-color: #0d1117; border: 1px solid #ff4500; border-radius: 10px; width: 100%; max-width: 800px; padding: 20px; font-family: 'Courier New', monospace; box-shadow: 0 0 20px rgba(255, 69, 0, 0.5);">
    <tr>
      <td width="40%" valign="top" align="center" style="border-right: 1px dashed #ff8c00; padding-right: 20px;">
        <font color="#ff8c00" size="2"><b>VISUAL_MAP.exe</b></font><br><br>
        
        <!-- DOT MATRIX PROFILE (Bentuk Wajah/Avatar dari Titik) -->
        <div style="line-height: 1.1; font-size: 20px; text-shadow: 0 0 5px #ff4500;">
          <span style="color:#ff0000;">● ● ● ● ●</span><br>
          <span style="color:#ff0000;">●</span> <span style="color:#ff8c00;">● ● ●</span> <span style="color:#ff0000;">●</span><br>
          <span style="color:#ff0000;">●</span> <span style="color:#ff8c00;">●</span> <span style="color:#ffff00;">●</span> <span style="color:#ff8c00;">●</span> <span style="color:#ff0000;">●</span><br>
          <span style="color:#ff0000;">●</span> <span style="color:#ff8c00;">● ● ●</span> <span style="color:#ff0000;">●</span><br>
          <span style="color:#ff0000;">● ● ● ● ●</span><br>
          <span style="color:#ffff00;">● ● ● ● ●</span><br>
          <span style="color:#ff8c00;">● ● ● ● ●</span>
        </div>
        <br>
        <font color="#ffff00" size="1"><b>[STATUS: ONLINE]</b></font>
      </td>
      <td width="60%" valign="top" style="padding-left: 20px;">
        <font color="#ff8c00" size="2"><b>SYSTEM_INFO</b></font><br><br>
        <font color="#8b949e" size="2">Subject..........</font> <font color="#ffffff" size="2"><b>LUXXYHub</b></font><br>
        <font color="#8b949e" size="2">Handle...........</font> <font color="#58a6ff" size="2">@luxxy49999ho</font><br>
        <font color="#8b949e" size="2">Role.............</font> <font color="#ffffff" size="2">Product-minded Dev</font><br>
        <font color="#8b949e" size="2">Status...........</font> <font color="#ff0000" size="2">Building | Shipping</font><br>
        <font color="#8b949e" size="2">Languages........</font> <font color="#ffff00" size="2">Lua (100%)</font><br>
        <font color="#8b949e" size="2">Repositories.....</font> <font color="#ffffff" size="2">2</font><br>
        <font color="#8b949e" size="2">Contributions....</font> <font color="#ffffff" size="2">27</font><br>
        <font color="#8b949e" size="2">Stars............</font> <font color="#ffffff" size="2">0</font><br>
        <font color="#8b949e" size="2">Followers........</font> <font color="#ffffff" size="2">0</font><br>
      </td>
    </tr>
  </table>
</div>

<br>

<!-- ============================================================== -->
<!-- 4. MINI GAME AUTO-PLAY (SNAKE & BALOK SUSUN)                   -->
<!-- ============================================================== -->
<h2>🕹️ Terminal_Mini-Games [AUTO-PLAY MODE]</h2>

<!-- SVG Snake Game Berjalan Sendiri -->
<div align="center">
  <svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="220" fill="#0d1117" rx="10" stroke="#ff4500" stroke-width="2"/>
    <text x="20" y="30" fill="#ff8c00" font-family="monospace" font-size="16" font-weight="bold">SNAKE_GAME.EXE [AUTO_PLAY: ON]</text>
    <text x="20" y="55" fill="#00ffcc" font-family="monospace" font-size="14">> SCORE: <tspan><animate attributeName="fill" values="#00ffcc;#ff8c00;#00ffcc" dur="2s" repeatCount="indefinite"/>100</tspan></text>
    
    <g transform="translate(200, 70)">
      <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
        <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#30363d" stroke-width="1"/>
      </pattern>
      <rect width="400" height="120" fill="url(#grid)" stroke="#30363d" stroke-width="2"/>
      
      <!-- Ular (Snake) Bergerak -->
      <rect x="40" y="40" width="18" height="18" fill="#ff0000" rx="4" style="filter: drop-shadow(0 0 5px #ff0000);">
        <animate attributeName="x" values="40;60;80;100;120;140;160;180;180;180;160;140;120;100;80;60;40;40;40;40" dur="4s" repeatCount="indefinite"/>
      </rect>
      <rect x="20" y="40" width="18" height="18" fill="#ff8c00" rx="4" style="filter: drop-shadow(0 0 5px #ff8c00);">
        <animate attributeName="x" values="20;40;60;80;100;120;140;160;180;180;180;160;140;120;100;80;60;40;20;20" dur="4s" repeatCount="indefinite"/>
      </rect>
      <rect x="0" y="40" width="18" height="18" fill="#ffff00" rx="4" style="filter: drop-shadow(0 0 5px #ffff00);">
        <animate attributeName="x" values="0;20;40;60;80;100;120;140;160;180;180;180;160;140;120;100;80;60;40;0" dur="4s" repeatCount="indefinite"/>
      </rect>
      <!-- Belokan Ular -->
      <rect x="180" y="20" width="18" height="18" fill="#ffff00" rx="4">
        <animate attributeName="x" values="180;180;180;180;180;180;180;180;180;180;180;180;180;180;180;180;180;180;180;180" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="y" values="40;60;80;100;100;100;100;100;100;100;80;60;40;40;40;40;40;40;40;40" dur="4s" repeatCount="indefinite"/>
      </rect>
      
      <!-- Makanan (Buah) -->
      <rect x="300" y="80" width="16" height="16" fill="#ff00ff" rx="8" style="filter: drop-shadow(0 0 8px #ff00ff);">
        <animate attributeName="opacity" values="1;0.2;1" dur="1s" repeatCount="indefinite"/>
      </rect>
    </g>
  </svg>
</div>
<br>

<!-- SVG Balok Susun (Tetris) Berjalan Sendiri -->
<div align="center">
  <svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="220" fill="#0d1117" rx="10" stroke="#ff4500" stroke-width="2"/>
    <text x="20" y="30" fill="#ff8c00" font-family="monospace" font-size="16" font-weight="bold">TETRIS_BLOCKS.EXE [AUTO_PLAY: ON]</text>
    <text x="20" y="55" fill="#00ffcc" font-family="monospace" font-size="14">> LEVEL: <tspan><animate attributeName="fill" values="#00ffcc;#ff8c00;#00ffcc" dur="2s" repeatCount="indefinite"/>99</tspan></text>
    
    <g transform="translate(300, 40)">
      <!-- Balok Jatuh -->
      <rect x="0" y="-60" width="20" height="20" fill="#ffff00" rx="2" style="filter: drop-shadow(0 0 5px #ffff00);">
        <animate attributeName="y" values="-60;-20;20;60;100;140;180" dur="3s" repeatCount="indefinite" />
      </rect>
      <rect x="20" y="-60" width="20" height="20" fill="#ffff00" rx="2">
        <animate attributeName="y" values="-60;-20;20;60;100;140;180" dur="3s" repeatCount="indefinite" />
      </rect>
      
      <!-- Tumpukan Balok Bawah -->
      <rect x="0" y="140" width="20" height="20" fill="#ff0000" rx="2" />
      <rect x="20" y="140" width="20" height="20" fill="#ff8c00" rx="2" />
      <rect x="40" y="140" width="20" height="20" fill="#ffff00" rx="2" />
      <rect x="60" y="140" width="20" height="20" fill="#ff0000" rx="2" />
      <rect x="80" y="140" width="20" height="20" fill="#ff8c00" rx="2" />
      
      <rect x="20" y="120" width="20" height="20" fill="#ffff00" rx="2" />
      <rect x="40" y="120" width="20" height="20" fill="#ff0000" rx="2" />
      <rect x="60" y="120" width="20" height="20" fill="#ff8c00" rx="2" />
    </g>
  </svg>
</div>

<br>

<!-- ============================================================== -->
<!-- 5. LIVE STATS (REAL-TIME METRICS)                              -->
<!-- ============================================================== -->
<h2>📊 Live_Metrics</h2>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=luxxy49999ho&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=ff8c00&icon_color=ff0000&text_color=ffff00" width="48%" alt="Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=luxxy49999ho&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=ff8c00&text_color=ffff00" width="48%" alt="Top Languages" />
</div>
<br>
<div align="center">
  <img src="https://streak-stats.demolab.com?user=luxxy49999ho&theme=radical&hide_border=true&background=0D1117&ring=ff0000&fire=ff8c00&currStreakNum=ffff00&sideNums=ffffff&currStreakLabel=ff8c00" width="100%" alt="Streak Stats" />
</div>

<br>

<!-- ============================================================== -->
<!-- 6. SELECTED WORK (REPOSITORIES)                                -->
<!-- ============================================================== -->
<h2>📂 Selected_Work</h2>

<div align="center">
  <a href="https://github.com/luxxy49999ho/SCRIPT-OF-LUXXY">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=luxxy49999ho&repo=SCRIPT-OF-LUXXY&theme=radical&hide_border=true&bg_color=0D1117&title_color=ff8c00&icon_color=ff0000&text_color=ffff00" width="48%" />
  </a>
  <a href="https://github.com/luxxy49999ho/Luxxy49999ho">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=luxxy49999ho&repo=Luxxy49999ho&theme=radical&hide_border=true&bg_color=0D1117&title_color=ff8c00&icon_color=ff0000&text_color=ffff00" width="48%" />
  </a>
</div>

<br>

<!-- ============================================================== -->
<!-- 7. FOOTER                                                     -->
<!-- ============================================================== -->
<div align="center">
  <a href="https://github.com/luxxy49999ho">
    <img src="https://img.shields.io/badge/GitHub-Follow_Me-ff4500?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>
