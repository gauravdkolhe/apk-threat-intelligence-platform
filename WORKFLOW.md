# System Workflow

## Step 1 — APK Upload
Users or investigators upload suspicious APK files into the platform.

## Step 2 — Static Analysis
The APK is decompiled and analyzed using APK analysis tools.

## Step 3 — Permission & API Extraction
Permissions, APIs, URLs, IPs, certificates, and suspicious strings are extracted.

## Step 4 — Threat Detection
The system detects suspicious behaviors including:
- OTP interception
- Overlay attacks
- Excessive permissions
- Hidden communication
- Credential theft indicators

## Step 5 — C2 Detection
Embedded domains, IP addresses, and communication endpoints are analyzed to identify possible Command & Control infrastructure.

## Step 6 — AI Threat Scoring
The APK receives a threat score based on extracted indicators and behavioral patterns.

## Step 7 — Threat Intelligence Correlation
The system compares the APK with previously flagged applications to identify behavioral and infrastructural similarities.

## Step 8 — Community Intelligence
Users can submit risk feedback and suspicious activity reports.

## Step 9 — Authority Investigation Dashboard
Authorities can monitor malware trends, linked threats, increasing cases, and active malware campaigns through interactive dashboards and threat visualization.
