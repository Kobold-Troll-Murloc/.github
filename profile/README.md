# We are Team P.R.I.S.M!

우리는 **Team P.R.I.S.M**입니다.  
건국대학교 드림학기제(2026/1학기)를 통해 **고성능 실시간 물리 시뮬레이션 엔진**를 연구하고 개발합니다.

---

## Meet Our Team

| <img src="./Picture/LSM.png" width="200" height="300"> | <img src="./Picture/JGN.jpg" width="200" height="300"> | <img src="./Picture/HSH.jpg" width="200" height="300"> |
| :---: | :---: | :---: |
| **LSM (이수민)** | **JGN (정근녕)** | **HSH (한승현)** |
| **Engine Architect & Rendering** | **Engine Architect & Rendering** | **Physics & AI Specialist** |
| *Core Architecture & Ray Tracing* | *Core Architecture & Ray Tracing* | *Softbody & Physics Simulation* |
| 상용 엔진 아키텍처 분석 및<br>렌더링 알고리즘 연구 개발 | 엔진 아키텍처 설계 및<br>하이브리드 렌더링 파이프라인 설계 | 물리 시뮬레이션 로직 구현 및<br>Physics 시뮬레이션 설계 |
| https://github.com/nunsori | https://github.com/Kkackit02 | https://github.com/asbbicsar |

---

## Project: P.R.I.S.M

**Physics Ray-tracing Interactive Softbody-simulation Module**

단순한 그래픽을 넘어, GPU 주도형 광선 추적과 AI 가속 물리 시뮬레이션을 결합하여 실시간으로 상호작용 가능한 물리 환경을 구축합니다.

- **P**hysics: XPBD, FEM 기반의 물리 시스템
- **R**ay-tracing: GPU-Driven 하이브리드 렌더링을 통한 높은 수준의 그래픽 보장
- **I**nteractive: 실시간 조작 및 즉각적인 물리 피드백 보장
- **S**oftbody: 머리카락, 옷감, 젤리 등 연체 시뮬레이션
- **M**odule: 최적화 및 다양한 유틸 도구를 지원하는 엔진 구현

---

## Tech Stack & Focus
- **Language**: Modern C++ (C++17/20), Python (for AI Trainin, Other Tools)
- **Graphics Engine**: Initially explored [OgreNext](https://github.com/OGRE-Next/ogre-next) (Core Architecture Analysis & Customization), then transitioned to a **Custom In-house Engine(Raw Vulkan).**
- **Graphics API**: Vulkan 1.3, HLMS, GLSL (SPIR-V)
- **Physics & AI**: , Extended Position Based Dynamics (XPBD) , Finite Element Method (FEM), Physics-Informed Neural Networks (PINNs) 
- **Key Tech**: GPU-Driven Rendering, Hybrid Path Tracing, Disney BSDF, ReSTIR, NRD(NVIDIA RealTime Denoiser), Physics AI Optimization

---

## Roadmap & Progress
- [x] OgreNext 2.3+ 코어 아키텍처 분석 및 환경 자동화
- [x] CPU-GPU 데이터 전송 병목 제거를 위한 시스템 설계
- [x] Disney BSDF 기반 PBR 및 프레임 누적 노이즈 제거 구현
- [ ] ReSTIR, NRD와 같은 Denoiser 구현 및 성능 개선
- [ ] 다양한 물리 시뮬레이션 알고리즘(Mass-Spring, FEM) 비교 환경 구축
- [ ] FEM 고비용 연산 해결을 위한 **Physics AI** 기술 도입
- [ ] 기술 보고서(아키텍처 설계도, 성능 분석) 및 최종 데모 제작

---

### Let's Connect!
우리의 연구 과정이나 기술 스택에 대해 더 궁금한 점이 있다면 메인 저장소를 방문해 주세요.

[P.R.I.S.M 메인 저장소 바로가기](https://github.com/Kobold-Troll-Murloc/PRISM)
