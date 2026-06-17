# We are Team P.R.I.S.M!

우리는 **Team P.R.I.S.M**입니다.  
건국대학교 드림학기제(2024-2026)를 통해 **Vulkan 기반 실시간 레이 트레이싱 + GPU 소프트바디 물리 시뮬레이션 통합 렌더링 엔진**을 연구하고 개발합니다.

---

## Meet Our Team

| <img src="./Picture/LSM.png" width="200" height="300"> | <img src="./Picture/JGN.jpg" width="200" height="300"> | <img src="./Picture/HSH.jpg" width="200" height="300"> |
| :---: | :---: | :---: |
| **LSM (이수민)** | **JGN (정근녕)** | **HSH (한승현)** |
| **Physics & Denoising** | **Engine Architect & Rendering** | **Physics Simulation (FEM)** |
| *물리 시뮬레이션 & 디노이징* | *아키텍처 설계 & RT 파이프라인* | *FEM 소프트바디 시뮬레이션* |
| 물리 시뮬레이션 구현 및<br>NRD 디노이징 통합 | 엔진 아키텍처 설계 및<br>하이브리드 렌더링 파이프라인 구현 | FEM 기반 소프트바디<br>물리 시뮬레이션 구현 |
| https://github.com/nunsori | https://github.com/Kkackit02 | https://github.com/asbbicsar |

---

## Project: P.R.I.S.M

**Physics · Ray-tracing · Interactive · Softbody-simulation · Module**

Raw Vulkan 위에서 GPU 주도형 레이 트레이싱과 소프트바디 물리 시뮬레이션을 결합하여, 실시간으로 상호작용 가능한 물리 환경을 구축하는 렌더링 엔진입니다.

- **P**hysics — XPBD, FEM 기반 GPU 소프트바디 물리 시뮬레이션
- **R**ay-tracing — 7-bounce Path Tracing + ReSTIR DI/PT 실시간 광원 샘플링
- **I**nteractive — 마우스 인터랙션을 통한 소프트바디 직접 조작
- **S**oftbody — 천, 젤리, 변형체 등 연체 시뮬레이션 (Zero-copy GPU 메모리 공유)
- **M**odule — Render Graph, 디노이저(NRD), 업스케일러(DLSS) 등 모듈화된 엔진 구조

---

## Tech Stack

- **Language**: C++17
- **Graphics API**: Vulkan 1.3 (Ray Tracing, Compute)
- **Shader**: GLSL (RT), HLSL (Compute), SPIR-V
- **Physics**: XPBD, FEM (Neo-Hookean), Vulkan Compute Shader
- **Denoising**: NVIDIA NRD (RELAX / RELAX-SH)
- **Upscaling**: NVIDIA Streamline (DLSS-RR, DLSS-G, Reflex)
- **Rendering**: Cook-Torrance Disney BRDF, BSDF, BSSRDF, ReSTIR DI/PT
- **Build**: CMake 3.20+

---

## Completed Milestones

- [x] OGRE Next 코어 아키텍처 분석 및 하이브리드 파이프라인 프로토타입
- [x] Raw Vulkan 기반 자체 엔진(RawPRISMEngine) 전면 재설계
- [x] Disney BRDF/BSDF/BSSRDF PBR 재질 시스템 구현
- [x] 7-bounce Path Tracing 레이 트레이싱 파이프라인
- [x] ReSTIR DI / ReSTIR PT 실시간 광원 샘플링
- [x] NVIDIA NRD 디노이저 통합
- [x] NVIDIA DLSS-RR / DLSS-G 통합
- [x] DAG 기반 Render Graph (자동 의존성 관리)
- [x] XPBD GPU 소프트바디 시뮬레이션 엔진 통합
- [x] FEM (Neo-Hookean) 사면체 메시 물리 시뮬레이션
- [x] GPU 해시 그리드 충돌 탐지 + 마우스 인터랙션
- [x] Zero-copy GPU 메모리 공유 (Physics ↔ Renderer)
- [x] glTF 2.0 / OBJ 씬 로더 + BVH Frustum Culling
- [x] ImGui 디버그 도구 (Profiler, Hierarchy, Asset Browser)

---

### Let's Connect!
프로젝트에 대해 더 궁금한 점이 있다면 메인 저장소를 방문해 주세요.

[P.R.I.S.M 메인 저장소 바로가기](https://github.com/Kobold-Troll-Murloc/P.R.I.S.M)
