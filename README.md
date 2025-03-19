# bandiview-7.05-vuln-PoC
This repository contains a PoC for vulnerabilities uncovered in Bandiview 7.05 using fuzzing

- **JXR File Parsing DoS Vulnerability**: Triggers a DoS by mishandling JXR file parsing ([CVE-2024-45870](https://nvd.nist.gov/vuln/detail/CVE-2024-45870)).  
- **PSD File Parsing DoS Vulnerability**: Causes a DoS due to flawed PSD file parsing ([CVE-2024-45871](https://nvd.nist.gov/vuln/detail/CVE-2024-45871)).  
- **PSD File Parsing Stack Buffer Overflow**: Enables a stack overflow via PSD file parsing, potentially leading to a DoS ([CVE-2024-45872](https://nvd.nist.gov/vuln/detail/CVE-2024-45872)).

### Details
- Software: [BandiView](https://kr.bandisoft.com/bandiview/)
- Version: v7.05 (2024/7/15, BuildNo=26122)

### Credit
- JaeHo Cho (@Jaecho6053)
- SongHyun Bae (@bshyuunn)
- JunSeo Bae (@V0xe1)
- LeeDong Ha (@GAP-dev)
