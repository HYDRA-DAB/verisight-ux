# VeriSight

A UX-focused identity verification platform designed to simplify digital onboarding through clear guidance, intuitive interactions, transparent feedback, and a consistent design system — while maintaining high security standards.

Built as part of the **Axlero Solutions** UI/UX intern project program.

---

## 📖 Problem Statement

### Overview
As digital services continue to grow, identity verification has become an essential part of user onboarding for banking, fintech, healthcare, and government platforms. While security is a top priority, many existing verification processes are confusing, time-consuming, and difficult for users to complete successfully.

Users often encounter unclear instructions, repeated verification failures, permission-related issues, and generic error messages. These challenges reduce user confidence, increase frustration, and may even lead to users abandoning the onboarding process.

### Problem
Current identity verification systems commonly face the following issues:
- Complex and lengthy verification processes.
- Limited guidance during verification.
- Poor communication when verification fails.
- Lack of real-time progress feedback.
- Low user confidence regarding privacy and security.

### Proposed Solution
VeriSight is a UX-focused identity verification platform designed to simplify the verification process through clear guidance, intuitive interactions, transparent feedback, and a consistent user experience while maintaining high security standards.

---

## 🎯 Project Objectives

The primary objective of VeriSight is to design a secure, intuitive, and user-friendly identity verification experience.

- Simplify the identity verification process.
- Improve user experience during digital onboarding.
- Reduce verification failures through clear guidance.
- Provide meaningful feedback at every stage of verification.
- Build user trust through transparent and secure interactions.
- Create an accessible interface suitable for users with different levels of technical knowledge.
- Maintain a consistent design system throughout the application.

---

## 👥 Target Users

### Primary Users
- Adults aged 18–60 years.
- Users opening bank or fintech accounts.
- Individuals completing digital KYC verification.
- Professionals using secure digital identity services.

### Secondary Users
- First-time digital users.
- Elderly users.
- Users with limited technical experience.
- Individuals who prioritize secure authentication and privacy.

### User Needs
Users expect:
- A quick and simple verification process.
- Clear instructions throughout the journey.
- Transparent progress updates.
- Helpful recovery options when verification fails.
- Confidence that their personal information is protected.

---

## 🧑 User Persona

**Name:** Aarav Sharma
**Age:** 29
**Occupation:** Software Engineer
**Location:** Bengaluru, India

**Goals**
- Complete identity verification quickly.
- Ensure personal information remains secure.
- Successfully finish onboarding on the first attempt.

**Pain Points**
- Repeated verification failures.
- Unclear instructions.
- Poor lighting affecting face detection.
- Generic error messages with no clear solution.

**Needs**
- Step-by-step guidance.
- Immediate visual feedback.
- Easy retry options.
- Transparent communication during verification.

---

## 🔄 User Flow

### Main Verification Flow
1. Open Application
2. Create/Login to Account
3. Set Up Passkey
4. Start Identity Verification
5. Grant Camera Permission
6. Position Face Inside Guide
7. Face Scan
8. Verification Processing
9. Verification Successful
10. Redirect to Dashboard

### Error Flow — Face Not Detected
Face Scan → Display Error Message → Adjust Position → Retry Verification

### Error Flow — Poor Lighting
Face Scan → Display Lighting Warning → Improve Lighting → Retry Verification

### Error Flow — Camera Permission Denied
Permission Request → Permission Denied → Display Guidance → Allow Permission from Settings → Continue Verification

---

## 🧩 Modules

| Module | Owner | Screens |
|---|---|---|
| Authentication & Account Setup | Member 1 | Splash, Welcome, Login, Sign Up, Forgot Password |
| Passkey Setup | Member 2 | Passkey Intro, Create Passkey, Face ID/Fingerprint Setup, Passkey Success, Recovery Options |
| Identity Verification | Member 3 | Camera Permission, Face Position Guide, Face Scanning, Verification Progress, Verification Success |
| Error Handling + Dashboard | Member 4 | Camera Permission Denied, Face Not Detected, Poor Lighting, Retry Verification, Help & Support, Dashboard, Security Status, Profile, Settings |

Each module follows the same workflow: **Research → User Flow → Low-Fidelity Wireframes → High-Fidelity UI → Prototype**.

### Identity Verification Module — Overview
The Identity Verification module is responsible for securely verifying the user's identity using facial verification while ensuring a simple and intuitive user experience.

**Design Goals**
- Guide users through each verification step.
- Reduce failed verification attempts.
- Provide continuous system feedback.
- Maintain transparency throughout the verification process.
- Create a clean and accessible interface.

**UX Considerations**
- Simple permission requests.
- Clear visual guidance before scanning.
- Real-time verification progress.
- Helpful recovery options for failed verification.
- Consistent interface aligned with the project design system.

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary | `#2563eb` |
| Secondary | `#60a5fa` |
| Success | `#22c55e` |
| Warning | `#f59e0b` |
| Error | `#ef4444` |
| Background | `Edf3fa` |
| Surface | `#ffffff` |
| Text Primary | `#111827` |
| Text Secondary | `#6b7280` |
| Border | `#e5e7eb` |

- **Typography:** SF Pro — Display, Heading 1–3, Body, Body Small, Caption
- **Spacing scale:** 8 / 16 / 24 / 32 px
- **Border radius:** Small – 8, Medium – 12, Large – 16
- **Components:** Buttons (Primary/Continue, Cancel/Secondary, Disabled, Secondary Button), Inputs (default, focused, error with helper text)

---

## 🛠️ Tools Used

- **Figma** — wireframes, design system, and prototype linking

---

## 📁 Folder Structure

```
VeriSight/
├── assets/
│   └── ui/              
├── README.md
```

---

## 👤 Team

4-member team, each owning one full module end-to-end (research through prototype), with documentation split across members:

- Problem Statement & Objectives — Member 1
- Competitor Analysis — Member 2
- User Persona & User Flow — Member 3
- Final Documentation, Presentation & Prototype Linking — Member 4 
