# 🔐 ORION – SOC Security Case Study

**Security Assessment & Monitoring Design for AIoT-Based Smart Guidance System**

---

## 📌 Project Background

ORION was initiated after direct observation at **Yayasan Pendidikan Anak Buta (YPAB)**, located in Gebang Putih, Surabaya.

The environment is home to approximately **20 visually impaired students and 7 visually impaired teachers** who carry out daily educational activities within the same area. During observation and informal discussions, one of the teachers shared that students often **stumble, fall, or lose their sense of direction**, particularly when navigating open spaces such as the school field.

These incidents are not isolated cases, but part of everyday challenges faced by visually impaired students when moving independently.

---

## 🧭 Why Existing Solutions Were Not Enough

Several assistive technologies had been introduced in the past, including **smart canes, smart glasses, and smart gloves**. However, according to feedback from visually impaired teachers, these solutions were considered **expensive, uncomfortable, and impractical**.

More importantly, they felt such devices made users appear *mechanical*, rather than empowering them as equal individuals. This feedback strongly influenced the design direction of ORION: technology should adapt to users, not redefine them.

---

## 🎯 Purpose of ORION

At its core, ORION aims to **support visually impaired individuals in achieving equal independence**, particularly in mobility within educational environments.

Without a system like ORION, visually impaired students often require continuous assistance, which can:

* Limit independence
* Increase the risk of physical accidents
* Create ongoing concern for parents, caregivers, and teachers

ORION is designed to reduce these risks while maintaining dignity and autonomy.

---

## 🔍 SOC Perspective: Why Security Matters

From a Security Operations Center (SOC) perspective, ORION presents **unique security and privacy challenges**.

Visually impaired users are inherently more vulnerable to certain risks, especially when systems involve **live location tracking and personal data**. If such data were intercepted or abused, the consequences would go beyond technical failure and could lead to **real-world safety threats**.

For users who cannot visually verify their surroundings, malicious tracking or account compromise introduces a serious risk that must be addressed proactively.

---

## ⚠️ Key Risk Considerations

The most critical concern identified in this system is **location tracking**.

While tracking is intended to provide safety and reassurance, continuous or unauthorized monitoring could become dangerous if misused. Improper access to live location data may expose users to stalking, targeting, or other forms of harm.

Additionally, user accounts must be protected to prevent unauthorized access, impersonation, or manipulation of navigation guidance.

---

## 🧪 Project Assumptions & Limitations

This security case study was conducted during the **MVP stage**, where features are still being developed incrementally.

Several assumptions were made during analysis:

* The school environment is relatively stable
* Beacon placement follows planned design
* Usage is limited to authorized contexts

These assumptions are acknowledged as potential limitations and are documented transparently as part of the security assessment.

---

## 🛡️ Scope of This SOC Case Study

This repository focuses on:

* Identifying critical assets and sensitive data
* Analyzing realistic threat scenarios, especially related to tracking and navigation
* Designing basic detection and monitoring strategies
* Simulating potential security incidents before production deployment

The emphasis is on **security-by-design**, rather than post-incident reaction.

---

## 🧠 Personal SOC Reflection

This project reinforced an important realization:
**social impact and security cannot be separated**.

Providing assistive technology without proper security may unintentionally create new risks. For visually impaired users, privacy and safety are not abstract concepts—they directly affect daily life.

This case study reflects a mindset of not only designing what works today, but also thinking ahead about **what could go wrong tomorrow**.

---

## 🚀 Project Status & Next Steps

ORION is currently in the **MVP phase**, with features being developed step by step.

Future security priorities include:

* Strengthening protection of user data
* Ensuring safe handling of location information
* Improving monitoring and incident readiness

The ultimate goal is simple: **all user data must remain secure**, without compromising accessibility or trust.

---

## 📬 Author Note

This project represents a SOC-oriented approach to assistive technology, combining **risk awareness, ethical consideration, and proactive security thinking** in a real-world social context.


