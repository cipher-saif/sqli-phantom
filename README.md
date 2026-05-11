<div align="center">

```
███████╗ ██████╗ ██╗         ██╗    ██████╗ ██╗  ██╗ █████╗ ███╗   ██╗████████╗ ██████╗ ███╗   ███╗
██╔════╝██╔═══██╗██║         ██║    ██╔══██╗██║  ██║██╔══██╗████╗  ██║╚══██╔══╝██╔═══██╗████╗ ████║
███████╗██║   ██║██║         ██║    ██████╔╝███████║███████║██╔██╗ ██║   ██║   ██║   ██║██╔████╔██║
╚════██║██║▄▄ ██║██║         ██║    ██╔═══╝ ██╔══██║██╔══██║██║╚██╗██║   ██║   ██║   ██║██║╚██╔╝██║
███████║╚██████╔╝███████╗    ██║    ██║     ██║  ██║██║  ██║██║ ╚████║   ██║   ╚██████╔╝██║ ╚═╝ ██║
╚══════╝ ╚══▀▀═╝ ╚══════╝    ╚═╝    ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝    ╚═════╝ ╚═╝     ╚═╝
```

**SQL Injection Scanner — Ethical Penetration Testing Tool**

<br>

![Python](https://img.shields.io/badge/Python%203.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-007EC6?style=for-the-badge&logo=python&logoColor=white)
![ThreadPoolExecutor](https://img.shields.io/badge/Concurrent%20Futures-6E40C9?style=for-the-badge&logo=python&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![CSS3](https://img.shields.io/badge/Custom%20CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)
![PortSwigger](https://img.shields.io/badge/PortSwigger%20Labs-FF6633?style=for-the-badge&logo=hackaday&logoColor=white)
![DVWA](https://img.shields.io/badge/DVWA-8B0000?style=for-the-badge&logo=linux&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&pause=1000&color=6E40C9&center=true&vCenter=true&width=600&lines=Authorized+Penetration+Testing+Only;60%2B+Payloads+%C2%B7+7+Attack+Categories;Error-Based+%C2%B7+Blind+%C2%B7+Time-Based+Detection" alt="Typing SVG" />

</div>

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; OVERVIEW &nbsp; ◈</h3><hr></div>

<br>

SQLi Phantom is a purpose-built SQL injection scanner featuring a cartoon-cyber aesthetic Streamlit GUI. It probes web application input fields using 60+ crafted payloads across seven attack categories, detects vulnerability indicators via error-based, boolean-blind, and time-based techniques, and streams live results with confidence scoring. Built for authorized penetration testing only — validated against PortSwigger Web Security Academy labs, DVWA, and WebGoat.

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; OBJECTIVES &nbsp; ◈</h3><hr></div>

<br>

- Automate detection of SQL injection vulnerabilities across GET and POST parameters
- Implement multi-threaded concurrent scanning with configurable rate limiting
- Provide real-time log streaming and confidence-scored findings in a visual dashboard
- Support export of scan results in JSON, CSV, and plain-text log formats
- Enforce ethical usage through session-scoped targeting and legal-use guardrails

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; TOOLS & TECHNOLOGIES &nbsp; ◈</h3><hr></div>

<br>

<div align="center">

| Layer | Technology |
|:---|:---|
| Language | ![Python](https://img.shields.io/badge/Python%203.11-3776AB?style=flat-square&logo=python&logoColor=white) |
| GUI Framework | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |
| HTTP Client | ![Requests](https://img.shields.io/badge/Requests-007EC6?style=flat-square&logo=python&logoColor=white) |
| Concurrency | ![Threading](https://img.shields.io/badge/ThreadPoolExecutor-6E40C9?style=flat-square&logo=python&logoColor=white) |
| Pattern Matching | ![Regex](https://img.shields.io/badge/re%20%28Regex%29-306998?style=flat-square&logo=python&logoColor=white) |
| Data Export | ![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white) &nbsp; ![CSV](https://img.shields.io/badge/CSV-217346?style=flat-square&logo=microsoftexcel&logoColor=white) |
| Styling | ![CSS3](https://img.shields.io/badge/Custom%20CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) &nbsp; ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat-square&logo=google&logoColor=white) |
| Test Targets | ![PortSwigger](https://img.shields.io/badge/PortSwigger%20Labs-FF6633?style=flat-square&logo=hackaday&logoColor=white) &nbsp; ![DVWA](https://img.shields.io/badge/DVWA-8B0000?style=flat-square&logo=linux&logoColor=white) |

</div>

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; PROJECT STRUCTURE &nbsp; ◈</h3><hr></div>

<br>

```
SQLi-Phantom/
│
│── sqli_scanner.py          # Main application — scanner engine + Streamlit GUI
│── requirements.txt         # Python dependencies
│── README.md
│
└── Screenshots/
    │── config-panel.png
    │── target-scan.png
    │── scan-process.png
    │── results-section.png
    │── vulnerabilities-detected.png
    │── export-report.png
    └── csv-logs.png
```

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; METHODOLOGY & IMPLEMENTATION &nbsp; ◈</h3><hr></div>

<br>

### 1. Payload Engine

Seven injection categories are defined as a structured dictionary — Classic Error-Based, Boolean-Based Blind, Time-Based Blind, UNION-Based, Stacked Queries, Out-of-Band, and Authentication Bypass — totalling over 60 crafted payloads. Each is injected as a suffix onto the target parameter value.

### 2. Detection Logic

Three independent detection methods run per probe response. Error-based detection matches against 18 database error signature patterns using compiled regex. Boolean-blind detection compares content length and keyword presence between the baseline and injected responses. Time-based detection thresholds response delay against the baseline to identify `SLEEP()` and `WAITFOR` induced latency.

### 3. Concurrency & Rate Limiting

Probes are dispatched through Python's `ThreadPoolExecutor` with a configurable worker count of 1–20. A thread-safe token-bucket `RateLimiter` class enforces a user-defined ceiling of requests per second, preventing server overload and evading basic rate-based defenses.

### 4. Live Streaming Architecture

Three `queue.Queue` instances pipe progress values, log entries, and vulnerability results from the background scan thread to the Streamlit main thread in real time. The UI polls these queues at 150 ms intervals, rendering the live log terminal and updating the progress bar without blocking.

### 5. Confidence Scoring

Each finding is assigned a confidence tier — **High** for confirmed SQL error strings, **Medium** for measurable time delays, and **Low** for statistically significant content changes — displayed as color-coded chips in the results dashboard.

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; RESULTS & SCREENSHOTS &nbsp; ◈</h3><hr></div>

<br>

### Configuration Panel

<div align="center">
<table><tr><td>

![Config Panel](Screenshots/config-panel.png)

</td></tr></table>
</div>

> **Configuration Panel** — The sidebar allows full control over target URL, HTTP method, parameter injection points, payload category selection, concurrency, rate limiting, and timeout — styled with Orbitron, Rajdhani, and VT323 typefaces.

<br>

### Target Scan Setup

<div align="center">
<table><tr><td>

![Target Scan](Screenshots/target-scan.png)

</td></tr></table>
</div>

> **Target Scan Setup** — The scan tab renders a pre-flight summary of the configured target with injected parameters displayed as neon chips, alongside a runtime overview of concurrency and probe count before launch.

<br>

### Scan Process — Live Log

<div align="center">
<table><tr><td>

![Scan Process](Screenshots/scan-process.png)

</td></tr></table>
</div>

> **Live Log Terminal** — Streams real-time output from the background scanner thread, colour-coded by severity — cyan for informational entries, amber for warnings, and red for confirmed vulnerability hits.

<br>

### Results Section

<div align="center">
<table><tr><td>

![Results Section](Screenshots/results-section.png)

</td></tr></table>
</div>

> **Results Dashboard** — Findings are grouped by parameter and rendered as confidence-scored cards showing the payload, indicator type, HTTP status code, response time, and extracted evidence snippet from the server response body.

<br>

### Vulnerabilities Detected

<div align="center">
<table><tr><td>

![Vulnerabilities Detected](Screenshots/vulnerabilities-detected.png)

</td></tr></table>
</div>

> **Vulnerabilities Detected** — High-confidence findings are highlighted in critical red cards with an automated `VULNERABLE` badge, displaying the exact injection string, detection method, and server-side evidence confirming exploitability.

<br>

### Export Report

<div align="center">
<table><tr><td>

![Export Report](Screenshots/export-report.png)

</td></tr></table>
</div>

> **Export Report** — One-click downloads for a structured JSON report with full scan metadata, a flat CSV for spreadsheet analysis, and a plain-text log file for archiving or sharing.

<br>

### CSV Logs

<div align="center">
<table><tr><td>

![CSV Logs](Screenshots/csv-logs.png)

</td></tr></table>
</div>

> **CSV Logs** — Timestamped findings with columns for parameter, payload, confidence tier, indicator type, response time, HTTP status code, and evidence — ready for inclusion in a formal penetration testing report.

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; COMMANDS & SETUP &nbsp; ◈</h3><hr></div>

<br>

**Install dependencies**
```bash
pip install -r requirements.txt
```

**Launch the application**
```bash
streamlit run sqli_scanner.py
```

**Run against PortSwigger Lab**
```
URL     →  https://<lab-id>.web-security-academy.net/filter
Params  →  {"category": "Gifts"}
Method  →  GET
```

**Run against DVWA (Docker)**
```bash
docker run --rm -p 80:80 vulnerables/web-dvwa
```
```
URL     →  http://localhost/dvwa/vulnerabilities/sqli/
Params  →  {"id": "1", "Submit": "Submit"}
Method  →  GET
```

**Example payloads triggering High confidence results**
```sql
' UNION SELECT NULL,NULL--
' AND SLEEP(3)--
' OR '1'='1'--
admin'--
```

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; CONCLUSION &nbsp; ◈</h3><hr></div>

<br>

SQLi Phantom demonstrates a full-cycle implementation of a SQL injection scanner — from payload construction and multi-threaded dispatch through real-time result streaming and structured report generation. The project reinforced core penetration testing methodology, regex-based response analysis, Python concurrency patterns, and the importance of ethical scope definition. Validated across PortSwigger Web Security Academy labs and DVWA, the tool successfully identifies error-based, boolean-blind, and time-based injection vulnerabilities with confidence scoring. It serves as a practical foundation for further extension into cookie-based authentication handling, automatic form crawling, and second-order injection detection.

<br>

<!---------------------------------------------------------------------------->

<div align="center"><hr><h3>◈ &nbsp; LEGAL NOTICE &nbsp; ◈</h3><hr></div>

<br>

This tool is developed strictly for authorized security testing and educational purposes. Only use against systems you own or have explicit written permission to test. Unauthorized scanning of any system is illegal and unethical. The author assumes no liability for misuse.

<br>

---

<div align="center">

Developed as part of a personal cybersecurity tooling project

<br>

*SQLi Phantom · Authorized Penetration Testing Only*

</div>
