## Ali Nasser Ahmed Albaihani

Cybersecurity researcher and blue team practitioner. M.Sc. Information Security, Universiti Putra Malaysia. CEH v13.

My work sits at the intersection of detection engineering and applied research — building SOC tooling that actually runs, and publishing on the problems it exposes. Most of the labs below were built on Apple Silicon / ARM64, where the standard vendor tooling either doesn't exist or doesn't work, so each one includes the workarounds rather than pretending the happy path applied.

---

### Detection engineering

**[mitre-soc-detection-lab-arm64](https://github.com/aalbaihani/mitre-soc-detection-lab-arm64)** — SOC detection lab on Windows 11 ARM64 under UTM. Two MITRE ATT&CK techniques proven end to end: T1059.001 (encoded PowerShell) and T1003.001 (LSASS credential access). Because no ARM64 Splunk Universal Forwarder exists, the pipeline uses a custom PowerShell HEC forwarder. Includes Sigma rules, tuned SPL, and an ATT&CK Navigator coverage layer.

**[soar-shuffle-automation](https://github.com/aalbaihani/soar-shuffle-automation)** — Shuffle SOAR on Kali ARM64, extending the detection lab with automated IOC enrichment against the VirusTotal v3 API. Documented with execution evidence, including the runs that failed and why.

### Research

**[hdfl-ec-wormhole-detection](https://github.com/aalbaihani/hdfl-ec-wormhole-detection)** — Hybrid deep feature learning with ensemble classification for wormhole attack detection in IoT networks. 99.95% accuracy on a 637,862-sample dataset, with false negatives reduced from 132 to 7.

Current research interests: ransomware threat actor attribution, phishing detection, and IoT intrusion detection datasets, with manuscripts currently under peer review.

### Writing

I write beginner-focused cybersecurity material at **[Cyber With Ali Albaihani](https://cyberwithali.blogspot.com)** — the explanations I wish had existed when I was starting out.

---

Based in Kuala Lumpur.
