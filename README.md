# AI-Assisted Cybersecurity Home Lab: Kali Linux, DVWA, Wireshark and Penligent AI

## Project Overview

This project demonstrates the creation of a cybersecurity home lab designed for hands-on learning in network reconnaissance, service enumeration, web application assessment, and packet analysis.

The environment was deployed using VirtualBox and consisted of an attacker machine running Kali Linux and a target Ubuntu system hosting DVWA (Damn Vulnerable Web Application).

Penligent AI was utilized as an AI-assisted penetration testing companion to support reconnaissance activities, target analysis, workflow guidance, and assessment planning.

---

## Objectives

* Build an isolated penetration testing environment
* Perform initial reconnaissance against a target host
* Identify active services and exposed attack surface
* Validate DVWA deployment and accessibility
* Capture and analyze network traffic generated during assessments
* Document findings and security observations

---

## Lab Architecture

Kali Linux (Attacker)
|
|
VirtualBox Internal Network
|
|
Ubuntu Server + Apache + DVWA

---

## Technologies Used

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| Kali Linux   | Security Testing Platform      |
| Ubuntu       | Target Host                    |
| DVWA         | Vulnerable Web Application     |
| Penligent AI | AI-Assisted Reconnaissance     |
| Nmap         | Host Discovery and Enumeration |
| Wireshark    | Packet Analysis                |
| Apache2      | Web Service                    |
| VirtualBox   | Virtualization Platform        |

---

## Phase 1: Environment Validation

### Activities

* Verified network communication between attacker and target systems
* Confirmed Ubuntu host availability
* Validated Apache web service accessibility
* Confirmed DVWA deployment

### Outcome

Successful communication established between both virtual machines.

---

## Phase 2: Initial Reconnaissance

### Tools

* Nmap
* Penligent AI

### Activities

* Host discovery
* Open port identification
* Service enumeration
* Technology fingerprinting

### Findings

Open services discovered included:

* SSH
* HTTP (Apache)

The reconnaissance phase provided visibility into the target's exposed attack surface.

---

## Phase 3: Penligent AI Assessment

### Purpose

Penligent AI was used as an AI-driven penetration testing assistant to support reconnaissance and assessment activities.

### Activities

* Target analysis
* Reconnaissance planning
* Enumeration guidance
* Service identification support
* Workflow recommendations

### Benefits Observed

* Structured assessment methodology
* Faster reconnaissance planning
* Improved understanding of attack surface mapping
* Guidance on enumeration workflows

### Key Learning

AI-assisted security tools can enhance analyst efficiency while maintaining a structured testing approach.

---

## Phase 4: DVWA Validation

### Activities

* Verified DVWA deployment
* Confirmed web application accessibility
* Reviewed application structure
* Tested authentication workflow

### Observations

DVWA successfully served as a realistic web application target for learning web security concepts and reconnaissance techniques.

---

## Phase 5: Packet Analysis

### Tool

Wireshark

### Activities

* Captured reconnaissance traffic
* Monitored HTTP communications
* Reviewed TCP sessions
* Analyzed packet-level interactions

### Findings

Traffic analysis provided visibility into:

* HTTP requests and responses
* TCP connection establishment
* Network communication patterns
* Reconnaissance-generated traffic

---

## Skills Demonstrated

* Linux Administration
* Network Reconnaissance
* Service Enumeration
* Web Application Assessment
* Packet Analysis
* Documentation and Reporting
* Virtualization
* AI-Assisted Security Operations

---

## Key Takeaways

This project provided practical experience in:

* Building and maintaining a cybersecurity home lab
* Conducting structured reconnaissance activities
* Utilizing AI-assisted security tooling
* Understanding network communications through packet analysis
* Documenting findings using professional reporting practices

The project successfully demonstrated the integration of traditional security tools and AI-assisted assessment techniques within a controlled laboratory environment.
