# Log Forensics Toolkit

Python scripts for analyzing logs during incident response, pentests, or blue team exercises.

## Tools Included

- `ssh_brute_parser.py`: Detects brute-force attempts in auth logs.
- `priv_escalation_detector.py`: Flags suspicious sudo activity.
- `log_summary_report.py`: Summarizes log activity by timestamp or source.

## Example

```bash
python3 ssh_brute_parser.py /var/log/auth.log
