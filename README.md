<picture>
  <source media="(prefers-color-scheme: dark)" srcset="wordmark-dark.svg">
  <img alt="Zarif Fida Chowdhury" src="wordmark-light.svg" width="640">
</picture>

Software engineer in Oxford, Ohio (B.S. Computer Science, Miami University, expected September 2026), building full-stack systems with the security work done up front.

[zariffidachowdhury.github.io](https://zariffidachowdhury.github.io/) · [Résumé (PDF)](https://zariffidachowdhury.github.io/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/zarif-fida-chowdhury/) · [Email](mailto:zariffidachowdhury@gmail.com)

## Selected work

**Capstone GPT** is a course-grounded assistant for Miami's Senior Design students: it answers from the syllabus and course materials, not the open internet. Built solo over the Spring 2026 semester in PHP 8, MySQL and plain JavaScript, with retrieval on a Dify workflow.

- The LLM API key never reaches the browser. Every call goes through one PHP control point: [`api/chat_handler.php`](https://github.com/zariffidachowdhury/capstone-gpt/blob/main/api/chat_handler.php)
- Sessions are 64-character hex tokens from `random_bytes(32)`. Passwords are stored with `password_hash()` (bcrypt): [`api/auth.php`](https://github.com/zariffidachowdhury/capstone-gpt/blob/main/api/auth.php)
- Ten REST routes in seven PHP endpoints over a normalized five-table MySQL schema: [`api/`](https://github.com/zariffidachowdhury/capstone-gpt/tree/main/api) · [`sql/`](https://github.com/zariffidachowdhury/capstone-gpt/tree/main/sql)

[Repository](https://github.com/zariffidachowdhury/capstone-gpt) · [README](https://github.com/zariffidachowdhury/capstone-gpt#readme) · [Architecture](https://github.com/zariffidachowdhury/capstone-gpt/blob/main/docs/system-architecture.md)

## Hands-on coursework

| Code | Course | Work |
|---|---|---|
| CSE 386 | Computer Graphics | A C++ ray tracer: Phong lighting, triangle, cylinder and disk intersections, texture mapping, Z-buffer hidden-surface removal, alpha blending, spotlight cones, and transformation pipelines with GLM. |
| CYB 236 | Data Security | ZFC-Cipher, a 64-bit Feistel block cipher I designed and implemented. Steganography extraction, a Saltzer & Schroeder analysis, and a physical security assessment of a campus building. |
| CYB 334 | Network Security | A pfSense firewall with LAN/WAN/DMZ rules and split DNS, an IPsec/IKEv2 VPN, and a Snort, Kiwi Syslog and Splunk monitoring pipeline. Metasploitable 2 exploitation. SSH log forensics, AES decryption, certificate inspection. |
| CYB 331 | Software Security | Threat modeling, OWASP Top 10 (CSRF, XSS, injection), SAST/DAST and fuzzing, secure code review, software supply-chain security. |

Code for these lives in course repositories. Ask and I'll walk through any of it.

## Now

Studying for CompTIA Security+ and the AWS Solutions Architect Associate exam. Open to new-grad roles in software, security, and AI. Email is the fastest way to reach me.

---

<sub>Wordmark set in Source Serif 4 (SIL OFL 1.1) and converted to outlines so it renders without webfonts. No badges, counters or scripts on this page.</sub>
