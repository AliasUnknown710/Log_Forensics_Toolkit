# 🔍 Log Forensics Toolkit

Python scripts for analyzing system logs during incident response, pentests, or blue team exercises. Built for speed and clarity.

---

## 🔧 Tools Included

| Script | Description |
|--------|-------------|
| `ssh_brute_parser.py` | Detects brute-force attempts in auth logs. |
| `priv_escalation_detector.py` | Flags suspicious sudo activity. |
| `log_summary_report.py` | Summarizes log activity by timestamp or source. |

---

## 🚀 Usage

- Run `ssh_brute_parser.py /var/log/auth.log` to extract failed login attempts.
- Use `priv_escalation_detector.py` to detect privilege escalation events.
- Pipe any log file into `log_summary_report.py` for quick aggregation.

---

## 🧠 Notes

- Scripts are designed for Linux logs but can be adapted for Windows.
- Output is plaintext for easy parsing or piping into other tools.
- Ideal for post-exploitation analysis or SIEM validation.
