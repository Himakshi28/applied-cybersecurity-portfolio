# B29 — Fix a Vulnerability Using Three Different Generative AI Systems

## Objective
The purpose of this activity is to compare how different generative AI systems recommend fixing a cybersecurity vulnerability.

---

## Description
Three different AI systems were asked how to securely fix a vulnerability involving hardcoded credentials in Python source code.

The AI systems compared were:
- ChatGPT
- Gemini
- Copilot

---

## Vulnerability Reviewed

### Vulnerability
Hardcoded credentials stored directly inside source code.

### Security Risk
Sensitive passwords may become exposed if source code is leaked or uploaded publicly.

---

## AI Recommendations

### ChatGPT
Recommended using environment variables and secure credential storage.

### Gemini
Recommended secret managers and avoiding hardcoded passwords.

### Perplexity AI
Recommended secure coding practices and separating configuration data.

---

## Comparison Observation
All three AI systems consistently recommended removing hardcoded credentials and using safer credential management methods.

---

## Evidence
- `ai_fix_chatgpt.png`
- `ai_fix_gemini.png`
- `ai_fix_copilot.png`
- `ai_comparison.png`

---

## Outcome
This activity demonstrated how generative AI systems can provide cybersecurity remediation guidance and how their recommendations can be compared for consistency.

---

## Conclusion
Generative AI systems can assist developers in identifying safer coding practices and improving cybersecurity awareness during software development.
