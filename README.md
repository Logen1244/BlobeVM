# BlobeVM (Modified DesktopOnCodespaces)

### Installation
First start a new blank codespace by going to https://github.com/codespaces/ and choosing the "Blank" template.
Then copy and paste this command in your codespace terminal and hit enter.

```
curl -O https://raw.githubusercontent.com/Blobby-Boi/BlobeVM/main/install.sh
chmod +x install.sh
./install.sh
```

---

## Risk & Disclaimer — Please Read Carefully

By using this software you acknowledge and accept the following risks. This project is provided "as‑is" and may change at any time. Use it only if you understand and accept these risks.

Important risks:
- System damage or instability: Scripts or binaries may modify system settings, packages, or configuration and can render an environment unstable or unusable.
- Data loss or corruption: Files, repositories, or other data may be accidentally deleted, overwritten, or corrupted.
- Security compromise: Running unverified code can expose secrets, SSH keys, tokens, or other credentials and may allow unauthorized access to your accounts or systems.
- Malware and backdoors: Third‑party components or scripts might contain malware, crypto‑miners, backdoors, or other unwanted software.
- Privilege escalation: Some operations may require elevated privileges; running as an administrator/root increases the risk of system‑level harm.
- Network exposure: The software may open ports, make outgoing connections, or otherwise expose your environment to the internet.
- Legal and policy violations: Using this software could violate workplace policies, GitHub Codespaces terms of service, or applicable laws and regulations.
- Dependency vulnerabilities: Included or downloaded dependencies may contain known or unknown security issues.

Recommended precautions:
- Inspect before running: Read every script and review code before executing it. Do not run code you don’t understand or cannot verify.
- Use isolated environments: Test in a disposable environment (fresh Codespace, throwaway VM, or container) that contains no sensitive data.
- Backup important data: Make backups of any data or configuration you cannot afford to lose.
- Least privilege: Avoid running scripts as root/administrator unless absolutely required.
- Revoke and rotate credentials: If the script interacts with tokens or keys, rotate or revoke them afterwards. Do not embed long‑lived secrets.
- Network controls: Restrict network access where possible and monitor outgoing connections.
- Scan for malware: Use reputable antivirus and static/dynamic analysis tools to scan downloaded artifacts.
- Audit dependencies: Verify third‑party libraries and check for known CVEs.
- Keep systems patched: Ensure your OS and runtime are up to date before use.
- Get authorization: If you are using this in a company or shared environment, obtain proper approval.

No warranty / Limitation of liability:
- This project is provided without warranty of any kind. The author and maintainers are not responsible for any direct, indirect, incidental, consequential, or punitive damages arising from use or misuse.
- You are solely responsible for compliance with applicable policies, laws, and terms of service.

If you find a security issue or unexpected behavior, please report it by opening an issue in this repository and include as much detail as possible so it can be investigated and fixed.

Use at your own risk. You assume full responsibility for anything that happens as a result of running this software.
