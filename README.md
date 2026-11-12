# Sidali

Cybersecurity and infrastructure student: M2 at Université Paris-Saclay (2026–2027), after an M1 at
Université Claude Bernard Lyon 1. I build security tooling and test it honestly: defender
evaluation, hardened Kubernetes infrastructure and detection research.

**Looking for an end-of-studies internship in cybersecurity from April 2027, and open to full-time
roles.** · [LinkedIn](https://www.linkedin.com/in/Sidali/)

## Flagwake

A free, offline test of how an AI security defender behaves during an incident. A defender works
through simulated incidents in an invented company and is scored in business cost. Every result can
be re-checked from the stored commands, and an edited report fails.

- Works with any defender: a program, a model endpoint, or a product with its own tools (MCP or REST)
- Releases are built by GitHub Actions and published to PyPI with signed provenance
- `pip install flagwake` · [Repository](https://github.com/Sid00011/Flagwake) · [PyPI](https://pypi.org/project/flagwake/)

## Selected projects

| project | what it is |
|---|---|
| [k8s-cni-benchmark](https://github.com/Sid00011/k8s-cni-benchmark) | Cilium, Calico, Kube-OVN and Flannel compared on 14 TCP/UDP metrics on a multi-node cluster. Cilium reached 2.28 Gbps TCP with 0 retransmissions in this setup, using eBPF routing that bypasses iptables. |
| [k8s-devsecops-project](https://github.com/Sid00011/k8s-devsecops-project) | Multi-node Kubernetes with a DevSecOps pipeline: Ansible provisioning, Trivy image scanning as a CI gate, HashiCorp Vault for dynamic secrets. |
| [zerotrust-evasion-detection](https://github.com/Sid00011/zerotrust-evasion-detection) | Research on evading detection in Zero-Trust setups: four vectors mapped to MITRE ATT&CK, a pass-the-cookie lab (Keycloak, ELK, Evilginx2) and an 8-dimension maturity grid aligned with ANSSI and NIS2. |
| [cloud-cosmographer](https://github.com/Sid00011/cloud-cosmographer) | Read-only AWS resource graph and misconfiguration mapper, tested against moto. |
| [zparty](https://github.com/Sid00011/zparty) | Web application security testing framework for authorised engagements: recon, 30+ vulnerability checks, CVSS-scored reports, optional local LLM (Ollama). |
| [Anti-Ransomware](https://github.com/Sid00011/Anti-Ransomware) | Windows ransomware detection prototype: real-time filesystem monitoring, hash matching and an SVM classifier on PE features. |
| [secure-voip-ha-lab](https://github.com/Sid00011/secure-voip-ha-lab) | Secure, highly available VoIP lab: Asterisk, Kamailio, TLS/SRTP, keepalived, SIPp load tests. |
| [AdaptiveFlow](https://github.com/Sid00011/AdaptiveFlow-) | Research prototype: a self-tuning scheduler for streaming workflows (HEFT-LC, Q-learning, MAPE-K controller). |

## Tools I work with

**Security** Burp Suite · Metasploit · Nmap · Wireshark · Trivy · Vault · ELK  
**Cloud and infrastructure** Kubernetes · Docker · Ansible · Terraform · AWS  
**Networking** BGP · OSPF · DMZ segmentation · WPA2-EAP-TLS · eBPF (Cilium)  
**Languages** Python · Bash · C/C++ · JavaScript · SQL
