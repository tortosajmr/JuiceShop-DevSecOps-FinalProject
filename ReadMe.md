# DevSecOps Certification Final Project
## JuiceShop CICD Pipeline to DefectDojo

As part of this exam, this projects wants to scan JuiceShop vulnerable application in order to manage vulnerabilities in DefectDojo by using a CICD Pipeline.

### Tools used were:
- GitLab SAST - Semgrep
- Gitlab Secrets detection - Gitleaks
- DAST - Zaproxy ZAP
- SBOM Generation - Syft
- SCA - Grype

### Some details I forgot to mention in the video
- Grype can both scan for SCA vulnerabilities in both an SBOM file or the code directly. In this case I preferred to scan the code for SCA directly instead of the generated SBOM.
- In DefectDojo, the SBOM upload seems fine but I can't seem to find the results. Seems like if the SBOM is only a component list instead of having vulnerabilites it doesn't show anything.
