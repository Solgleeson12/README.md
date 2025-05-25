<!-- PowerShell-inspired Terminal UI -->
<div align="center">
  <img src="https://i.imgur.com/3JmQZ7O.png" alt="PowerShell logo" width="100"/>
  <h1 style="font-family: 'Consolas', monospace; color: #4CAF50;">Solgleeson12@GitHub:~$ <span class="typed"></span></h1>
</div>

```powershell
# ================ SYSTEM INFO ================
# User: Solgleeson12
# Role: Full-Stack Developer & Creative Technologist
# OS: Linux/Windows Subsystem for Linux
# Shell: zsh 5.9 | PowerShell 7.3
# Terminal: Windows Terminal | VS Code Integrated

# ============ ACTIVE PROCESSES ============
- 🧠 Processing: Next.js 14 Applications
- 🔗 Networking: GraphQL/REST API Development
- 🛠️ Compiling: TypeScript → JavaScript
- 🐳 Containerizing: Docker/Kubernetes
- 🤖 Training: AI/ML Models (Python)

# ============ TECH STACK ============
$Languages = @("TypeScript", "Python", "JavaScript", "SQL")
$Frontend = @("React", "Next.js", "TailwindCSS", "Three.js")
$Backend = @("Node.js", "Express", "PostgreSQL", "MongoDB")
$Tools = @("Docker", "Git", "VS Code", "Figma", "Jest")

# Display formatted stack
Write-Host "=== CORE STACK ===" -ForegroundColor Cyan
$Languages | ForEach-Object { Write-Host "• $_" -ForegroundColor Green }
Write-Host "`n=== FRONTEND ===" -ForegroundColor Cyan
$Frontend | ForEach-Object { Write-Host "• $_" -ForegroundColor Yellow }
Write-Host "`n=== BACKEND ===" -ForegroundColor Cyan
$Backend | ForEach-Object { Write-Host "• $_" -ForegroundColor Magenta }
Write-Host "`n=== TOOLS ===" -ForegroundColor Cyan
$Tools | ForEach-Object { Write-Host "• $_" -ForegroundColor Blue }
<!-- ASCII Art Divider --><pre align="center"> _____ _ _ __ __ / ____| | | | \ \ / / | (___ | |_ __ _ _ __ ___| |__ \ V / \___ \| __/ _` | '__/ __| '_ \ > < ____) | || (_| | | \__ \ | | | / . \ |_____/ \__\__,_|_| |___/_| |_|/_/ \_\ </pre>
powershell
# ============ GIT PROCESSES ============
# Analyzing repository activity...
$Commits = Get-Content "git_log.txt" | Measure-Object -Line
$Projects = Get-ChildItem "repos" -Directory | Measure-Object

Write-Host "[✓] Version Control Stats" -ForegroundColor Green
Write-Host "├─ Commits: $($Commits.Lines)" -ForegroundColor White
Write-Host "├─ Projects: $($Projects.Count)" -ForegroundColor White
Write-Host "└─ Active Branches: main, dev, feature/*" -ForegroundColor White

# ============ RECENT ACTIVITY ============
Get-EventLog -LogName "GitHub" -Newest 3 | Format-Table -AutoSize

<# Sample Output:
TimeCreated          EventID Message
-----------          ------- -------
3/15/2024 10:00 AM   1001    Pushed to [feature/auth] 
3/14/2024 2:30 PM    1002    Merged PR #42 
3/13/2024 9:15 AM    1003    Created [web3-integration] 
#>
<!-- Interactive ASCII Terminal --><div align="center"> <img src="https://raw.githubusercontent.com/Solgleeson12/Solgleeson12/main/terminal_animation.gif" alt="Interactive Terminal" width="600"/> </div>
powershell
# ============ SYSTEM COMMANDS ============
PS Solgleeson12@GitHub:~$ <span class="blinking-cursor">_</span>

Available Commands:
• projects    - Show featured repositories
• contact     - Display contact information
• resume      - View professional experience
• skills      - Show detailed tech competencies
• clear       - Reset terminal view

Try: <span style="color: #4CAF50;">Invoke-Command</span> -Name "projects"
<!-- "Executing projects command" --><div id="projects-command" align="left"> <h3 style="font-family: 'Consolas', monospace; color: #4CAF50;">PS Solgleeson12@GitHub:~$ Invoke-Command -Name "projects"</h3> <div style="background: #1E1E1E; padding: 15px; border-radius: 5px; font-family: 'Consolas', monospace;"> <div style="color: #569CD6;">[1] nextjs-saas-boilerplate</div> <div style="color: #DCDCAA;">├─ TypeScript | Next.js 14 | Tailwind</div> <div style="color: #DCDCAA;">└─ Production-ready SaaS starter</div><br>
<div style="color: #569CD6;">[2] python-data-pipeline</div>
<div style="color: #DCDCAA;">├─ Python 3.11 | Pandas | Airflow</div>
<div style="color: #DCDCAA;">└─ ETL for large datasets</div><br>

<div style="color: #569CD6;">[3] react-three-fiber-portfolio</div>
<div style="color: #DCDCAA;">├─ React Three Fiber | GSAP</div>
<div style="color: #DCDCAA;">└─ 3D interactive portfolio</div>
</div> </div><!-- Contact Section as PowerShell Output -->
powershell
# ============ CONTACT PROTOCOLS ============
PS Solgleeson12@GitHub:~$ contact

[ℹ] Communication Channels Activated:
• Email:    solgleeson12@proton.me
• LinkedIn: <a href="https://linkedin.com/in/solgleeson12">/in/solgleeson12</a>
• Twitter:  <a href="https://twitter.com/solgleeson12">@solgleeson12</a>

[!] For secure connections:
• GPG Key:  <a href="https://keys.openpgp.org">0xAB12CD34EF56</a>
• SSH Key:  <a href="https://github.com/Solgleeson12.keys">View on GitHub</a>
<style> .blinking-cursor { animation: blink 1s step-end infinite; color: #4CAF50; } @keyframes blink { from, to { opacity: 1; } 50% { opacity: 0; } } pre { background-color: #1E1E1E; color: #D4D4D4; padding: 15px; border-radius: 5px; font-family: 'Consolas', monospace; } </style>
