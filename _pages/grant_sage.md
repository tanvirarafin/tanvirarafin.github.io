---
layout: page
title: "SAGE: Secure Accelerators for Next-Generation Foundation Models"
permalink: /grants/sage/
nav: false
---

## SAGE: Secure Accelerators for Next-Generation Foundation Models

**NSF Award [#2523805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2523805) &middot; SaTC &middot; 2025–2028**

### Project Summary

Foundation models are general-purpose technologies that power a wide range of artificial intelligence (AI) applications, including intelligent chatbots, voice assistants, cyber threat detection systems, and autonomous robots. These models can also be adapted to new tasks via fine-tuning techniques. However, the local deployment of foundation models on consumer devices is challenging due to the models' large size and high computational demands. The models also face significant security risks, such as intellectual property (IP) theft and malicious tampering, when deployed outside of secure platforms.

To address these challenges, this project builds modular hardware accelerators that enable secure and efficient deployment of fine-tuned foundation models in consumer devices. These accelerators can be securely integrated into existing AI hardware systems and will play a critical role in enhancing the security and resilience of the United States AI semiconductor supply chain.

### Technical Approach

The project plans the design of a heterogeneous system containing a graphics processing unit (GPU) and a custom accelerator. The GPU stores the open parameters of a foundation model, and the accelerator supports the secure execution of the fine-tuned component. The prototype is used to evaluate performance bottlenecks and security vulnerabilities of the heterogeneous system. Based on the findings, the team devises advanced acceleration methodologies and implements active locking mechanisms to protect the fine-tuned model. The final phase of the project produces a secure and modular accelerator realized on a physical platform.

Research thrusts include:

- **Performance analysis:** Characterizing computational and memory bottlenecks in heterogeneous GPU + custom-accelerator deployments of fine-tuned foundation models
- **Secure accelerator design:** Active locking mechanisms and architectural countermeasures that protect model IP while preserving performance
- **Physical realization:** Implementing the secure, modular accelerator on a real hardware platform and releasing designs via open-source platforms

### Research Team

| Role | Investigator | Institution |
|------|-------------|-------------|
| PI (Mason) | Dr. Md Tanvir Arafin | George Mason University |
| Lead PI | Dr. Wenjie Che | Howard University |

### Funding

**NSF Award [#2523805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2523805&HistoricalAwards=false)**
Collaborative Research: CISE Crosscutting Small: SaTC: SAGE: Secure Accelerators for Next-Generation Foundation Models
Total Project Award: $600,000 &middot; Mason Share: $275,000 &middot; Period: Sept. 2025 – Aug. 2028

[← Back to Grants](/grants/)
