Windows Server 2025 Long-Term Servicing Channel (LTSC) build 10.0.26100.33451 Update date: September 14, 2026 available as Server Core or Server with Desktop Experience
Editions: Standard and Datacenter
Mainstream support ends: November 13, 2029
Extended support ends: November 14, 2034

Windows 11 2025 build 26200.9550 Update date: September 22, 2026 preface to AI actions in File Explorer, Click to Do on compatible Copilot+ PCs,
Agent in Settings, Wi‑Fi 7 enterprise connectivity, and additional enterprise app-management controls
Editions: 64-bit arm:Professional Secure Compute 
Mainstream support ends: October 12, 2027
Extended support ends: October 10, 2028

Before switching editions, enabling cross-platform compatibility or maintain networking capabilities
- Advise to create a System Restore Point or use DiskManager to set a layer on current file-system
- All Microsoft products are Paid Licenses and set restrictions on upgrading Windows Home editions to Pro, Enterprise, Server, arm-specific that explicity require a clean install.
    - Prior to purchasing a OEM license, ensure pre-requisities are met unconditionally.
- Upgrading Microsoft Core editions require temporarilty turning-off Bitlocker Drive Entity, Windows Hello, Windows TPM 2.0 secure, Intel vPRO or AMI-BIOS Secure Boot, yubikey Iron Lynx, AI-threat Detection on valid Windows Licenses
- Re-enable shell-specific hardening rulesets, pre-configured firewall access to senstive PORTS, Office Edition (Windows Mail, Outlook Express, and Adobe Cloud Symphony)
- Re-install NVIDIA/amd-specific drivers most commonly associated with Microsoft Store Purchases (Electronic Arts, DICE Battlefiled, Need for Speed)
- Re-enable shell-specific Tally ERP (GST and IMS reconciliation, HSN/SAC online validation, E-invoice and e-Way Bill workflows, Connected Banking on BharatConnect API)
- Web-apps that require OEM-signed drivers (NEST by Omnesys, Sensibull, Cleartax, GSTN signer utility, TDS-CPC TAN, em-signer and em-bridge, e-Mudhra or V-sign DSC-token base, CBIC - Export Reporting)
- Standalone Enterprise on SAP/HANA, Salesforce, Tableau, kaggle-Compute (Explicitly require extended Powershell versioning)
- Network-associated devices (kyocera, PANTUM, Kodak Enterprise, Canon Offset - Port Binding)
- .NET Framework Policies (Shell Core, IDE-signing, uFIDO2 WebAuthn - VISA passkey, GOV.SmartCard)
- BGP CERT-IN (Wireless Access Point) - S/MIME certificate (Email Security)
- eSIM or cellular devices (Secure APN for eSIM Profiles SGP.32) running C# R# Windows Elements on NR-SAN, LTE (Wireless Connectivity)

Re-configure User Settings, such as enabling Desktop Shortcuts (Secure Load hyperlinks as Web-apps inside Incognito or Limited Access with 48x48.ico Recognition on IoT-priviliedged login)

Right-click to Create a Desktop Shortcut on Microsoft Windows edition of choice via Wizard for Chromium PWA instead of MSEdge or Microsoft Edge PWA

To ensure all NIST touchpoints are met, zero-trust can be implemented on Chromium by adding

```
"C:\Program Files\Google\Chrome\Application\chrome_proxy.exe" --guest --enable-features=IsolateOrigins,site-per-process --no-sandbox --profile-directory=Default --app-url=https://aws.amazon.com --app-run-on-os-login-mode=windowed --app-launch-source=19
```

Disable Chrome’s sandbox, enable Chrome's Web Security similar to safe browsing - standards applied to Shortcut (.lnk) opened in 
isolated mode, with the following disabled - active mixed content, invalid or expired .TLS certificates, localhost,
chrome extensions (password managers,sheets, slides,etc.) - insecure identified routes such as cookie redirects - encrypted, or gpu use in Sandbox

To enable legacy Microsoft Edge compatibility for port-bind, use the following command

To ensure all NIST touchpoints are met, zero-trust can be implemented on MS Edge Shortcut (.lnk) by adding

```
"C:\Program Files (x86)\Microsoft\Edge\Application\msedge_proxy.exe" --guest --enable-features=IsolateOrigins,site-per-process --no-sandbox --profile-directory=Default --app-url=https://aws.amazon.com --app-run-on-os-login-mode=windowed --app-launch-source=default
```

Disable default browser incompatibility via Edge’s native Web Security similar to safe browsing - standards applied to Shortcut (.lnk) opened in 
isolated mode, with the following disabled - active mixed content, invalid or expired .TLS certificates, localhost,
edge extensions (password managers,sheets, slides,etc.) - insecure identified routes such as browser ping, cookie redirects - memory (encrypted), or shared memory, console memory - use in Sandbox

To enable legacy PWA compatibility for port-bind, use the following command on community editions - Safari, Brave, and Firefox

To ensure all NIST touchpoints are met, zero-trust can be implemented on MS Edge Shortcut (.lnk) by adding

```
"C:\Program Files (x86)\Mozilla Firefox\firefox_proxy.exe" -private-window --enable-features=IsolateOrigins,site-per-process --no-sandbox --profile-directory=Default --app-url=https://aws.amazon.com --app-run-on-os-login-mode=windowed --app-launch-source=default
```

To ensure all NIST touchpoints are met, zero-trust can be implemented on Apple Silicon running OEM Windows - Shortcut (.lnk) by adding

```
"\Program Files (x86)\SafariWeb\safari_pwa.exe" -private-window --enable-features=IsolateOrigins,site-per-process --no-sandbox --profile-directory=Default --app-url=https://aws.amazon.com --app-run-on-os-login-mode=windowed --app-launch-source=default
```

To ensure all NIST touchpoints are met, zero-trust can be implemented on Apple Silicon running legacy .NET code-signer or pwa utilites - Shortcut (.lnk) by adding application to Restricted PWA list on GPO Editor (Business Manager Profiler)

```
"\Program Files (x86)\Brave\brave_pwa.msix" -private-window --enable-features=IsolateOrigins,site-per-process --no-sandbox --profile-directory=Default --app-url=https://aws.amazon.com --app-run-on-os-login-mode=windowed --app-launch-source=default
```

```
%USERPROFILE%\AppData\Local\Microsoft\Edge\User Data\Default\Web Applications\_crx__jkllfbcigkgmooahlaallkmcodobkbpf\site.webmanifest (Machine-readable Executable)
```

```
Remediate by Applying .MD5 where _crx__jkllfbcigkgmooahlaallkmcodobkbpf\ is the Code-signed Application Name and Patch Source for Verifiable AES Key stored inside %USERPROFILE%\AppData\Local\Microsoft\Edge\User Data\Default\Web Applications
```

Mandatory Disclosures on Code-Signing Certificates that are issued independently and must confer across NIST standards and compatible definitions regardless to compute or sentry applicable to.

Disable default browser incompatibility via Windows’s native Web Security similar to safe browsing - standards applied to Shortcut (.lnk) opened in 
isolated mode, with the following disabled - active mixed content, invalid or expired .TLS certificates, localhost,
edge extensions (password managers,sheets, slides,etc.) - insecure identified routes such as browser ping, cookie redirects - memory (encrypted), or shared memory, console memory - use in Sandbox

Enter the protected-url as Location - `https://aws.amazon.com` (Replace URL) - If AV or Windows Defender has high-security mode enabled, 
symbiotic links following the url such as /?nc2=h_home&trk=011f28e3-1dfa-405d-894f-3e05b14038a6&sc_channel=ps for app-url will be invalid
Add an identifiable Shortcut name to PWA app source if developing packages or apps for .MSIX, .APP or .EXE for .MD5 integrity for TPM or LTE-protected AR VR (Communication-specific Assemblies)

