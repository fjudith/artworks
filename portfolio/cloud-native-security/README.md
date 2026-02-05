# 5Cs of cloud native security

The cybersecurity framework is based on the **five dimensions of large-scale distributed application security**, which incorporates:

* **Cloud deployment best practices**, such as the [12-Factor App](https://12factor.net/).
* **Configuration hardening recommendations** from [CIS](https://www.cisecurity.org) and [OWASP](https://owasp.org).
* **Open-source license deviation** monitoring and control (via [FOSSA](https://fossa.com)).

## Définitions

### 1. Clients

**Identity and Access Management (IAM):** Managing authentication and authorization for every individual or integrated service utilizing the platform.

### 2. Cloud, Co-location, Corporate Datacenter

**Infrastructure Security:** Securing workload deployment and enforcing admission control for configurations and secrets. This includes resource hardening, granular network traffic filtering, and guaranteeing the confidentiality of communications both internally and at the platform's edge.

### 3. Cluster

**Orchestration Security:** Securing the distribution, concurrency, and fault tolerance of the workload.

### 4. Compute & Containers

**Runtime Security:** Monitoring active workloads and neutralizing unauthorized actions (e.g., post-deployment package installations).

### 5. Code

**Vulnerability Management:** Continuous static and dynamic scanning (SAST/DAST) of source code and third-party libraries for vulnerabilities.
