<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shreya's GitHub README</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { background: #0d1117; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; padding: 32px 16px; }
  .readme { max-width: 860px; margin: 0 auto; background: #0d1117; border: 1px solid #30363d; border-radius: 12px; padding: 32px; }
  h1 { font-size: 26px; font-weight: 700; text-align: center; color: #e6edf3; margin-bottom: 12px; }
  h2 { font-size: 16px; font-weight: 600; color: #e6edf3; border-bottom: 1px solid #21262d; padding-bottom: 8px; margin: 24px 0 12px; }
  hr { border: none; border-top: 1px solid #21262d; margin: 20px 0; }
  .center { text-align: center; }
  .typing-wrap { text-align: center; margin: 8px 0; min-height: 28px; }
  .typing { font-family: 'Courier New', monospace; font-size: 15px; background: linear-gradient(90deg, #6C63FF, #a78bfa); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: 600; }
  .cursor { color: #6C63FF; -webkit-text-fill-color: #6C63FF; animation: blink 1s infinite; }
  @keyframes blink { 0%,100%{opacity:1}50%{opacity:0} }
  .views { display: inline-block; background: #6C63FF22; border: 1px solid #6C63FF44; color: #a78bfa; font-size: 12px; padding: 3px 12px; border-radius: 20px; margin: 6px 0; }
  table { width: 100%; border-collapse: collapse; margin: 8px 0; font-size: 13px; }
  th { background: #161b22; color: #8b949e; padding: 10px 14px; border: 1px solid #21262d; font-weight: 600; }
  td { background: #0d1117; color: #e6edf3; padding: 10px 14px; border: 1px solid #21262d; text-align: center; }
  .badges { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin: 10px 0; }
  .badge { padding: 7px 14px; border-radius: 6px; font-size: 12px; font-weight: 700; color: white; display: inline-flex; align-items: center; gap: 5px; }
  .dashboard { display: grid; grid-template-columns: 1fr 1.5fr 1fr; gap: 12px; margin: 12px 0; }
  .dash-card { background: #161b22; border: 1px solid #30363d; border-radius: 10px; padding: 14px; text-align: center; }
  .dash-title { font-size: 12px; font-weight: 600; color: #8b949e; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 12px; }
  .proj-badge { display: block; margin: 6px auto; background: linear-gradient(135deg, #e67e22, #f39c12); color: white; font-size: 11px; font-weight: 600; padding: 7px 12px; border-radius: 6px; width: 90%; }
  .stat-card { background: #0d1117; border: 1px solid #21262d; border-radius: 8px; padding: 12px; margin: 6px 0; }
  .stat-row { display: flex; justify-content: space-around; margin-top: 8px; }
  .stat-num { font-size: 20px; font-weight: 700; color: #6C63FF; }
  .stat-label { font-size: 10px; color: #8b949e; margin-top: 2px; }
  .lang-bar { height: 6px; border-radius: 3px; background: #ED8B00; margin: 6px 0; width: 100%; }
  .streak-row { display: flex; justify-content: space-around; margin-top: 8px; }
  .streak-num { font-size: 22px; font-weight: 700; }
  .leet-box { background: #0d1117; border: 1px solid #21262d; border-radius: 8px; padding: 12px; text-align: left; }
  .leet-name { font-size: 13px; font-weight: 600; color: #e6edf3; margin-bottom: 10px; text-align: center; }
  .leet-row { display: flex; justify-content: space-between; padding: 4px 0; font-size: 12px; border-bottom: 1px solid #21262d11; }
  .easy { color: #00b8a3; font-weight: 600; }
  .medium { color: #ffc01e; font-weight: 600; }
  .hard { color: #ff375f; font-weight: 600; }
  .leet-note { font-size: 10px; color: #8b949e; text-align: center; margin-top: 8px; }
  .connect-row { display: flex; gap: 10px; justify-content: center; margin: 14px 0; flex-wrap: wrap; }
  .connect-btn { display: inline-flex; align-items: center; gap: 8px; padding: 10px 20px; border-radius: 8px; font-size: 13px; font-weight: 700; text-decoration: none; color: white; cursor: pointer; border: none; }
  .linkedin { background: #0077B5; }
  .gmail { background: #D14836; }
  .leetcode { background: #FFA116; color: #1a1a1a; }
  .footer { text-align: center; color: #8b949e; font-size: 12px; font-style: italic; margin-top: 16px; }
  .live-tag { background: #238636; color: #3fb950; font-size: 10px; padding: 2px 8px; border-radius: 10px; margin-left: 6px; font-weight: 600; }
  .zero-note { font-size: 10px; color: #f0883e; margin-top: 6px; }
</style>
</head>
<body>
<div class="readme">

  <h1>Hi, I'm Shreya 👋</h1>

  <div class="typing-wrap">
    <span class="typing" id="typed"></span><span class="cursor typing">|</span>
  </div>

  <p class="center" style="margin-top:8px">
    <span class="views">👁 Profile Views <span id="views">Loading...</span> <span class="live-tag">LIVE</span></span>
  </p>

  <hr>
  <h2>👩‍💻 About Me</h2>
  <table>
    <tr>
      <th>🎯 Goal</th>
      <th>🌱 Learning</th>
      <th>💡 Habit</th>
    </tr>
    <tr>
      <td>Software Engineer at Product Company</td>
      <td>DSA + Spring Boot</td>
      <td>Solve 1 LeetCode Problem Daily</td>
    </tr>
  </table>

  <hr>
  <h2>🛠️ Tech Stack</h2>
  <div class="badges">
    <span class="badge" style="background:#ED8B00">☕ Java</span>
    <span class="badge" style="background:#6DB33F">🍃 Spring Boot</span>
    <span class="badge" style="background:#005C84">🐬 MySQL</span>
    <span class="badge" style="background:#DC382D">⚡ Redis</span>
    <span class="badge" style="background:#2496ED">🐳 Docker</span>
    <span class="badge" style="background:#F05032">🔥 Git</span>
  </div>

  <hr>
  <h2>🏗️ Portfolio Dashboard</h2>
  <div class="dashboard">

    <div class="dash-card">
      <div class="dash-title">📌 Projects</div>
      <span class="proj-badge">🏙️ Civic Issue Tracker</span>
      <span class="proj-badge">🚜 Farmer Marketplace</span>
      <span class="proj-badge">✈️ Smart Travel Companion</span>
      <div class="zero-note" style="margin-top:10px">🔨 All currently building</div>
    </div>

    <div class="dash-card">
      <div class="dash-title">📊 GitHub Stats <span class="live-tag">LIVE</span></div>
      <div class="stat-card">
        <div style="font-size:11px;color:#8b949e;margin-bottom:6px">shreyamumbale19-hub</div>
        <div class="stat-row">
          <div><div class="stat-num">0</div><div class="stat-label">Commits</div></div>
          <div><div class="stat-num" style="color:#f0883e">0</div><div class="stat-label">Stars</div></div>
          <div><div class="stat-num" style="color:#3fb950">1</div><div class="stat-label">Repos</div></div>
          <div><div class="stat-num" style="color:#58a6ff">0</div><div class="stat-label">PRs</div></div>
        </div>
      </div>
      <div class="stat-card">
        <div style="font-size:11px;color:#8b949e;margin-bottom:6px">Top Languages</div>
        <div style="display:flex;justify-content:space-between;font-size:11px"><span style="color:#ED8B00">Java</span><span>100%</span></div>
        <div class="lang-bar"></div>
      </div>
      <div class="stat-card">
        <div style="font-size:11px;color:#8b949e;margin-bottom:6px">🔥 Streak</div>
        <div class="streak-row">
          <div><div class="streak-num" style="color:#e6edf3">0</div><div class="stat-label">Total</div></div>
          <div><div class="streak-num" style="color:#f0883e">0</div><div class="stat-label">Current</div></div>
          <div><div class="streak-num" style="color:#6C63FF">0</div><div class="stat-label">Longest</div></div>
        </div>
        <div class="zero-note">Push your first commit to start! 🚀</div>
      </div>
    </div>

    <div class="dash-card">
      <div class="dash-title">⚡ LeetCode <span class="live-tag">LIVE</span></div>
      <div class="leet-box">
        <div class="leet-name">shreya_gm</div>
        <div class="leet-row"><span class="easy">Easy</span><span style="color:#e6edf3">0 / 834</span></div>
        <div class="leet-row"><span class="medium">Medium</span><span style="color:#e6edf3">0 / 1756</span></div>
        <div class="leet-row"><span class="hard">Hard</span><span style="color:#e6edf3">0 / 762</span></div>
        <div class="leet-note">Solve problems to see progress here! 💪</div>
      </div>
    </div>

  </div>

  <hr>
  <h2>📫 Connect With Me</h2>
  <div class="connect-row">
    <a class="connect-btn linkedin" href="https://linkedin.com/in/shreyamumbale" target="_blank">💼 LinkedIn</a>
    <a class="connect-btn gmail" href="mailto:shfreyamumbale19@gmail.com">✉️ Gmail</a>
    <a class="connect-btn leetcode" href="https://leetcode.com/shreya_gm" target="_blank">⚡ LeetCode</a>
  </div>

  <hr>
  <p align="center">
  <i> The stars never question those who keep moving forward. ⭐</i>
</p>

</div>

<script>
const lines = [
  "CS Student | Java Developer",
  "DSA Enthusiast | Problem Solver",
  "Aspiring Software Engineer"
];
let li = 0, ci = 0, deleting = false;
const el = document.getElementById("typed");

function type() {
  if (!deleting) {
    el.textContent = lines[li].slice(0, ++ci);
    if (ci === lines[li].length) {
      deleting = true;
      setTimeout(type, 1800);
      return;
    }
  } else {
    el.textContent = lines[li].slice(0, --ci);
    if (ci === 0) {
      deleting = false;
      li = (li + 1) % lines.length;
    }
  }
  setTimeout(type, deleting ? 40 : 85);
}
type();

// Simulate live view counter loading
setTimeout(() => {
  document.getElementById("views").textContent = "counting live visits...";
}, 800);
</script>
</body>
</html>
