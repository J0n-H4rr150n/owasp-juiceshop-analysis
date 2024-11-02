# OWASP Juice Shop Analysis Practice  

## Source repo  
https://github.com/juice-shop/juice-shop  
- Release v17.1.1 published on 9/9/2024  

## Cloned repo  
https://github.com/J0n-H4rr150n/owasp-juice-shop-practice  
- Cloned release v17.1.1 on 10/23/2024  
- Primary branch is [main](https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/tree/main)  
- Practice remediation branch is [remediation-practice](https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/tree/remediation-practice)  

### Baseline  

#### Static Application Security Testing (SAST)
##### GitHub Code Scanning  
[https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/security/code-scanning](https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/security/code-scanning)  
- 120 findings
  - 18 critical
  - 92 high
  - 10 medium
  - 0 low

##### Semgrep Code  
- 96 findings
  - 35 high
  - 57 medium
  - 4 low

#### Software Composition Analysis (SCA)
##### GitHub Dependabot  
[https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/security/dependabot](https://github.com/J0n-H4rr150n/owasp-juice-shop-practice/security/dependabot)  
- 13 findings
  - 2 critical
  - 4 high
  - 7 moderate

#### Dynamic Application Security Testing (DAST)  
##### OWASP ZAP  
