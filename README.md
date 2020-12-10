# FireEye_breach_artifacts
Extracted IOCs and MITRE technique analysis from the December 2020 FireEye breach

This repository contains examples of Indicator of Compromise (IOC) data carved from FireEye's red_team_tool_countermeasures GitHub repo, located at https://github.com/fireeye/red_team_tool_countermeasures
These file accompany a soon-to-be-released LogRhythm blog about the FireEye breach.

Files:
CVE.txt - list of CVEs extracted from CVEs_red_team_tools.md
MD5hashes.txt - list of MD5 hashes extracted from the all-yara.yar file (for hash search in LR)
MITRE_subtechniques.txt - list of MITRE techniques listed in signatures_table_of_content.csv
MSThreats.txt - list of Windows Defender threat names extracted from retroactive YARA VirusTotal search located at https://docs.google.com/spreadsheets/d/e/2PACX-1vQrmeti88UJ3tEhPlqEsNVoesB-pZh6o2-zyDG_-T3MUQBeL1yd_ycFqBlmjQ8fEggkGhcMefG9KHxP/pubhtml (for ThreatName search in LR)
MITRE_technique_analysis.xlsx - Data source requirements, platform and tactic associations for the MITRE subtechniques listed in signatures_table_of_content.csv

