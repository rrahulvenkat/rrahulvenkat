# Hi, I'm Rahul Venkat 👋

🎓 **Cybersecurity Student at Purdue University**  
🚀 **Aspiring Forward Deployed Engineer**

I take real security problems and turn them into working tools, end to end:
understand what the user needs, build it, measure it, and explain it. My focus
is where **AI and cybersecurity** meet: using LLMs where they help, and making
them safe to rely on.

## 🧭 How I Work

- **Start from the user's problem.** My log analyzers answer the question a
  security analyst actually asks: *who is attacking us, and did they get in?*
- **Ship complete tools, not scripts.** Command-line options, clear errors,
  exit codes for automation, tests, and a README that states the limits.
- **Choose the right tool, not the newest one.** I solved the same detection
  problem twice, with regex and with an LLM, then measured both: on known log
  formats the regex was as accurate, free and 100,000× faster.
- **Treat AI output as untrusted.** Every LLM answer is checked against the raw
  data, with defences against prompt injection from attacker-controlled input.
- **Test before trusting.** Edge cases that break real tools (IPv6, New Year
  rollover, leap days, duplicate data) are covered by tests.

## 🔐 Featured Projects

| Project | What it does | What it shows |
|---|---|---|
| [ssh-log-analyzer](https://github.com/rrahulvenkat/ssh-log-analyzer) | Detects SSH brute-force attacks in OpenSSH logs and flags attackers who then log in successfully | A tested, automatable CLI tool |
| [log-analyzer-agent](https://github.com/rrahulvenkat/log-analyzer-agent) | The same problem solved with Claude: structured extraction, validated answers, prompt-injection defences | Using LLMs safely in a security workflow |
| [ssh-detection-eval](https://github.com/rrahulvenkat/ssh-detection-eval) | Scores both analyzers against an independent answer key: accuracy, cost and speed, plus the LLM with and without its safety checks | Measuring when AI is worth it, with evidence |
| [ssh-hybrid-detector](https://github.com/rrahulvenkat/ssh-hybrid-detector) | Rules for known log formats, Claude only for lines no rule reads, with answers checked and doubtful ones queued for review. Reviewed formats become rules: that stopped a prompt-injection trick that framed another IP | Combining rules and AI, and being honest about where AI fails |
| [log-detection-engine](https://github.com/rrahulvenkat/log-detection-engine) | Reads SSH, web, Windows and CloudTrail logs into one event format, runs rules across all of them, and correlates alerts into incidents labelled with MITRE ATT&CK. Tested on public real-world SSH, web and Windows logs, which exposed ten bugs I then fixed | Designing a system, then measuring it on real data |
| [security mini-projects](https://github.com/rrahulvenkat/python_learning_journey/tree/main/projects) | Short, self-contained tools: password strength the way crackers guess, file integrity monitoring, breaking classic ciphers, hash cracking with salts and slow hashes, attack-path graphs, a vulnerable-by-design app (SQLi, XSS, path traversal) exploited then fixed, 2FA codes (TOTP) built from scratch and checked against the RFC test values, and a secrets scanner that finds leaked keys in files and git history | The fundamentals, each with a demo and tests |
| [python_learning_journey](https://github.com/rrahulvenkat/python_learning_journey) | My foundations: algorithms, data structures, log parsing, encodings, and the OOP lessons the detection engine grew out of | Depth behind the tools |

## 🛠️ Toolkit

**Languages:** Python · SQL · Java · JavaScript / TypeScript  
**Tools:** Git & GitHub · Linux · REST APIs · LLM APIs (Anthropic) · Docker

## 🚧 Building Now

- **Small security tools in Python:** ciphers and how they break, hashing
  and file integrity, and attack paths through a network, each a short
  project in [python_learning_journey](https://github.com/rrahulvenkat/python_learning_journey).

## 🎯 My Goal

To become an engineer who can work end-to-end — from understanding a real-world problem and designing a solution to building, deploying, and delivering technology that creates value.

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/rahul-venkat-ravishankar-685843327) · [rrahul.venkat@gmail.com](mailto:rrahul.venkat@gmail.com)

**Always learning. Always building.**
