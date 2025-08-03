<div align="center">
  <img src="https://raw.githubusercontent.com/YourUsername/YourUsername/main/matrix-rain.gif" width="100%">
  
  <!-- Animated Header -->
  <svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
    <style>
      @keyframes neonPulse {
        0%,100% { filter: drop-shadow(0 0 5px #0ff) drop-shadow(0 0 10px #0ff); }
        50% { filter: drop-shadow(0 0 15px #f0f) drop-shadow(0 0 30px #f0f); }
      }
      @keyframes glitch {
        0% { transform: translate(0); }
        20% { transform: translate(-5px, 5px); }
        40% { transform: translate(-5px, -5px); }
        60% { transform: translate(5px, 5px); }
        80% { transform: translate(5px, -5px); }
        100% { transform: translate(0); }
      }
      text {
        animation: neonPulse 2s infinite, glitch 1s infinite;
        font-family: 'Courier New', monospace;
        font-weight: bold;
        fill: #0ff;
        font-size: 3rem;
      }
    </style>
    <text x="50%" y="60%" text-anchor="middle">CYBERNEXUS TERMINAL v2.0</text>
  </svg>
  
  <!-- Terminal Interface -->
  <div style="position:relative; background:#000; border:2px solid #0ff; border-radius:10px; padding:20px; margin:30px 0; box-shadow:0 0 20px #0ff; max-width:800px">
    <!-- Holographic Display -->
    <div style="background:linear-gradient(135deg,#000b25,#220033); padding:15px; border-radius:8px; border:1px solid #f0f; position:relative; overflow:hidden">
      <div style="position:absolute; top:0; left:0; width:100%; height:5px; background:#0ff; box-shadow:0 0 10px #0ff; animation:scanline 6s linear infinite"></div>
      
      <!-- Terminal Text -->
      <pre style="color:#0f0; font-family:monospace">
<span style="color:#ff00ff">$</span> <span style="animation:typing 4s steps(40,end) forwards">ACCESSING USER PROFILE: [YourUsername]</span>
<span style="color:#ff00ff">$</span> <span style="animation:typing 4s steps(40,end) forwards 1s">LOCATION CONFIRMED: [Your Location]</span>
<span style="color:#ff00ff">$</span> <span style="animation:typing 4s steps(40,end) forwards 2s">INITIATING SYSTEM SCAN...</span>
      </pre>
      
      <!-- Digital DNA -->
      <div style="display:flex; justify-content:center; margin:20px 0">
        <svg width="400" height="20" xmlns="http://www.w3.org/2000/svg">
          <path d="M0 10 Q100 0, 200 10 T400 10" stroke="#0ff" stroke-width="2" fill="none">
            <animate attributeName="d" values="M0 10 Q100 0, 200 10 T400 10; M0 10 Q100 20, 200 10 T400 10; M0 10 Q100 0, 200 10 T400 10" dur="3s" repeatCount="indefinite"/>
          </path>
          <circle cx="0" cy="10" r="3" fill="#f0f">
            <animate attributeName="cx" from="0" to="400" dur="4s" repeatCount="indefinite"/>
          </circle>
        </svg>
      </div>
    </div>
    
    <!-- Skill Matrix -->
    <div style="margin-top:30px">
      <h3 style="color:#0ff; text-align:center; animation:neonPulse 3s infinite">TECH STACK MATRIX</h3>
      <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(150px, 1fr)); gap:15px">
        <div style="background:rgba(0,255,255,0.1); padding:10px; border-radius:5px; border:1px solid #0ff">
          <div style="display:flex; justify-content:space-between">
            <span style="color:#0ff">JavaScript</span>
            <span style="color:#f0f">95%</span>
          </div>
          <div style="height:8px; background:#000; border-radius:4px; margin-top:5px">
            <div style="height:100%; width:95%; background:linear-gradient(90deg,#0ff,#f0f); border-radius:4px; animation:loadBar 2s ease-out"></div>
          </div>
        </div>
        <!-- Repeat for other skills -->
      </div>
    </div>
  </div>
  
  <!-- GitHub Stats with Animated Border -->
  <div style="position:relative; display:inline-block; margin:30px 0">
    <div style="position:absolute; top:-10px; left:-10px; right:-10px; bottom:-10px; border:2px solid transparent; border-image:linear-gradient(45deg,#0ff,#f0f) 1; animation:rotateBorder 8s linear infinite; z-index:-1"></div>
    <img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=radical&bg_color=000000&title_color=0ff&text_color=fff&icon_color=f0f&border_color=0ff" />
  </div>
  
  <!-- Quantum Circuit Footer -->
  <svg width="100%" height="100" viewBox="0 0 1000 100" xmlns="http://www.w3.org/2000/svg" style="margin-top:50px">
    <defs>
      <linearGradient id="waveGradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#ff00ff" />
        <stop offset="100%" stop-color="#00ffff" />
      </linearGradient>
    </defs>
    <path d="M0,70 Q250,20 500,70 T1000,70" stroke="url(#waveGradient)" stroke-width="5" fill="none">
      <animate attributeName="d" values="M0,70 Q250,20 500,70 T1000,70; M0,70 Q250,120 500,70 T1000,70; M0,70 Q250,20 500,70 T1000,70" dur="6s" repeatCount="indefinite"/>
    </path>
    <text x="500" y="40" text-anchor="middle" fill="#0ff" font-family="monospace" font-size="20">SYSTEM STATUS: ONLINE</text>
  </svg>
</div>

<style>
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }
  @keyframes scanline {
    0% { transform: translateY(-100%); }
    100% { transform: translateY(400px); }
  }
  @keyframes neonPulse {
    0%,100% { text-shadow: 0 0 5px #0ff, 0 0 10px #0ff; }
    50% { text-shadow: 0 0 15px #f0f, 0 0 30px #f0f; }
  }
  @keyframes loadBar {
    0% { width: 0%; opacity: 0; }
    100% { width: 95%; opacity: 1; }
  }
  @keyframes rotateBorder {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
</style>
