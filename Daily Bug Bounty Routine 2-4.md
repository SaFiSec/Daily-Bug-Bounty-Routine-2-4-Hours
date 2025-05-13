# 🐞 Bug Bounty Daily Routine (2–4 Hours Total)

A structured daily checklist to help bug bounty hunters stay consistent, improve skills, and increase earnings.

---

## 🔍 Phase 1: Recon (45 min – 1.5 hrs)

- [ ] Enumerate subdomains using `assetfinder`, `amass`, and `subfinder`
- [ ] Verify live hosts with `httpx`
- [ ] Collect archived endpoints using `waybackurls` and `gau`
- [ ] Scan for known vulnerabilities using `nuclei` (with updated templates)
- [ ] DNS bruteforce with custom wordlists using `dnsx`, `wfuzz`, or `ffuf`

---

## 🧪 Phase 2: Vulnerability Testing (1.5 – 2 hrs)

- [ ] Test for **XSS** using discovered parameters (`arjun`)
- [ ] Check for **IDOR** or Access Control issues
- [ ] Look for **SSRF** using open redirects or metadata services
- [ ] Try **Auth Bypass** and **JWT manipulation**
- [ ] Test **CORS misconfigurations** with custom `Origin` headers
- [ ] Check for **Rate Limiting/Brute-force** using `intruder`, `ffuf`, or `turbo intruder`

---

## 📋 Phase 3: Notes & Research (30 mins)

- [ ] Read 1 valid bug bounty write-up (e.g., HackerOne, Medium)
- [ ] Explore a new tool or hacking technique
- [ ] Save findings in your knowledge base (Notion, Obsidian, Joplin, etc.)

---

## 🎯 Weekly Add-on Tasks (Once per week)

- [ ] Run **GitHub dorks** using `github-search` or `truffleHog`
- [ ] Check for **Open S3 Buckets**
- [ ] Compare historical endpoints using **Archive.org`

---

## 🧠 Tip

Keep iterating your techniques. Daily learning + disciplined testing = higher success in bug bounty.

---

Created with ❤️ by WireTor Cyber Security
