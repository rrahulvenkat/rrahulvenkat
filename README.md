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
| [ssh-hybrid-detector](https://github.com/rrahulvenkat/ssh-hybrid-detector) | Rules for known log formats, Claude only for lines no rule reads, with answers checked and doubtful ones queued for review. It catches a Dropbear brute force that rules miss, for $0.02 | Combining rules and AI, and being honest about where AI fails |
| [python_learning_journey](https://github.com/rrahulvenkat/python_learning_journey) | My foundations: algorithms, log parsing, encodings, and a detection engine with baselines, correlation and MITRE ATT&CK mapping | Depth behind the tools |

## 🛠️ Toolkit

**Languages:** Python · SQL · Java · JavaScript / TypeScript  
**Tools:** Git & GitHub · Linux · REST APIs · LLM APIs (Anthropic) · Docker

## 🚧 Building Now

- **Hardening the hybrid:** turning reviewed log formats into rules, so a
  prompt-injection trick that framed another IP stops working.
- **A detection engine:** my parsers, rules and correlation code as an
  installable tool for Linux, web, cloud and Windows logs.

## 🎯 My Goal

To become an engineer who can work end-to-end — from understanding a real-world problem and designing a solution to building, deploying, and delivering technology that creates value.

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/rahul-venkat-ravishankar-685843327) · [rrahul.venkat@gmail.com](mailto:rrahul.venkat@gmail.com)

**Always learning. Always building.**
