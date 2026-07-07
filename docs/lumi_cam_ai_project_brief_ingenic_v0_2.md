# Lumi AI Camera Project Brief for Ingenic

Version: `v0.2`  
Date: `2026-07-07`  
Target partner: Ingenic and recommended hardware ecosystem partners  
Target volume: `50,000 pcs` in the first year

## 1. Project Goal

Lumi is developing a new AI camera product line based on the **Ingenic T32Pro** platform. Lumi will own firmware, AI modules, cloud/app integration, final assembly, product testing, and mass-production quality control in Vietnam.

We expect Ingenic to support Lumi with the chipset platform, BSP/SDK, AI development tools, reference hardware, qualified component partners, and manufacturing test methods.

## 2. Why Lumi Is a Strong Go-to-Market Partner

| Lumi Advantage | Partner Value for Ingenic |
|---|---|
| Local Vietnamese company | Fast product localization for Vietnam users, installers, regulations and market behavior |
| In-house R&D capability | Lumi can own firmware, AI modules, product customization and long-term platform improvement |
| Lumi factory in Vietnam | Final assembly, product testing, quality control and faster iteration from pilot to mass production |
| Nationwide distribution network | Faster rollout through Lumi's dealer, installer and project channels across Vietnam |
| Leading smart home market position | AI cameras can become a natural extension of Lumi's existing smart home ecosystem |
| Large project experience in Vietnam | Practical experience to expand from home use to building, office, hospital, school, urban and smart city solutions |
| Established brand and customer trust | Better chance to scale Ingenic-based camera products beyond a single device launch |

## 3. Product Line

| Model | Type | Main Use Case | Key Requirement |
|---|---|---|---|
| Outdoor Bullet Camera | Bullet | Villa, gate, yard, perimeter | PoE, IP67, night vision, AI detection |
| Outdoor Dome Camera | Dome | Residential and light commercial installation | PoE, IP67, night vision, compact design |
| Outdoor Turret Camera | Turret | Balanced outdoor installation | PoE, IP67, easy installation, AI detection |
| Indoor Compact Camera | Compact indoor | Home indoor monitoring, family safety | Small size, two-way audio, AI detection |

## 4. Target Platform

| Item | Requirement |
|---|---|
| Main SoC | Ingenic T32Pro |
| AI performance | 1TOPS INT8 NPU |
| Video capability | 4K support |
| Product options | 2K version and 4K version |
| Target BOM range | USD 25-35 depending on 2K/4K and hardware options |
| Market focus | Vietnam first |
| First-year volume target | 50,000 pcs |

Reference checked from Ingenic public product page: T32Pro supports 4K 30fps and 1TOPS INT8 AI capability.

## 5. Hardware Requirements

| Category | Requirement |
|---|---|
| Connectivity | PoE is required for outdoor models |
| Storage | microSD card optional |
| Night vision | IR LEDs required |
| Supplemental light | White/warm light required, option by model |
| Audio input | Built-in microphone required |
| Audio output | Speaker required for warning and two-way talk |
| Two-way audio | Required |
| Outdoor protection | IP67 for outdoor models |
| Power options | No LTE/4G, no battery, no solar for this phase |
| Assembly | Final assembly and product testing at Lumi factory in Vietnam |

## 6. AI Feature Scope

| Feature | Priority | Expected Processing |
|---|---|---|
| Human detection | P0 | On-device AI |
| Pet detection | P0/P1 | On-device AI |
| Face detection | P1 | On-device AI |
| Face ID | P1/P2 | On-device or hybrid, depending on SDK capability |
| Object detection | P1 | On-device AI |
| Motion/event filtering | P0 | On-device AI + event logic |
| Smoke/fire detection | P1/P2 | Need benchmark and model validation |
| Event history | P0 | Lumi firmware + Lumi Cloud/App |
| Video understanding | Future phase | Hybrid AI, not required for first MP release |

## 7. Lumi Scope vs Ingenic Support Scope

| Area | Lumi Responsibility | Expected Ingenic Support |
|---|---|---|
| Hardware | Final product selection, assembly, factory test | Recommend qualified partners for PCBA, sensor, lens, PoE, housing, IR/light, audio, fixtures |
| BSP/Firmware | Firmware development and customization | Full BSP/SDK, build documentation, media pipeline samples, secure boot/OTA guidance |
| Rust development | Lumi wants to develop application-layer modules in Rust | Confirm toolchain support or provide C/C++ APIs suitable for Rust FFI |
| AI module | Lumi wants to own and improve AI modules | Magik/AIE SDK, model zoo, conversion tools, quantization guide, benchmark reports |
| Cloud/App | Lumi responsibility | No cloud/app integration required from Ingenic |
| Manufacturing test | Lumi factory execution | Flash tool, FCT tool, calibration method, aging test, AI smoke test, QC checklist |

## 8. Support Requested from Ingenic

| Request | Detail |
|---|---|
| Recommended partners | Please introduce partners that can supply the complete hardware ecosystem for Lumi assembly |
| Reference design | T32Pro reference camera design with PoE, IR, audio, speaker, SD option |
| BOM proposal | 2K and 4K BOM options within USD 25-35 target range |
| AI SDK package | SDK, model samples, conversion tools, benchmark data |
| Firmware package | BSP source, build guide, sample applications, debug tools |
| Factory test package | Flashing, calibration, FCT, aging, traceability and QC procedure |
| Engineering support | Fast technical support during EVT/DVT/PVT to meet 6-7 month development timeline |

## 9. Key Questions for Ingenic

| Topic | Question |
|---|---|
| T32Pro variant | Which exact T32Pro part number is recommended for PoE AI camera with 2K/4K options? |
| BOM | Can the full BOM target of USD 25-35 be achieved for 2K and 4K versions? |
| AI | Which human/pet/face/object models are already validated on T32Pro? |
| Audio | Does the platform support stable two-way audio with AEC/ANR/AGC? |
| PoE | Can Ingenic recommend a proven PoE reference design and supplier? |
| IP67 | Can partners provide IP67 bullet/dome/turret housing options? |
| Rust | Can Lumi build Rust application-layer modules on the T32Pro BSP? |
| Mass production | What factory tools and QC process can be transferred to Lumi? |

## 10. Desired Outcome

Lumi wants to work with Ingenic and its recommended partners to quickly build a reliable, cost-effective, and AI-ready camera product line for the Vietnam smart home market, then scale the same platform into building, office, hospital, school, urban and smart city solutions.
