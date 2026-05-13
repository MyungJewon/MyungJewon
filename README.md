### Hi there, I'm Jewon Myung 👋
> **Client Developer** | Focusing on Optimization, Graphics, and Engine Architecture.

연구소와 실무 현장에서 **그래픽스 이론**과 **최적화 기술(Optimization)**을 단단히 다져왔습니다.  
화려한 겉모습보다는 보이지 않는 내부 로직을 효율적으로 설계하여, 극한의 성능을 이끌어내는 것에 몰입합니다.

- 🔭 **I'm currently working on:** Low-level engine internals — building **ECS**, **SLAM pipelines**, and **native plugins** from scratch in C++.
- 🌱 **I'm currently learning:** Deep diving into **Game Engine Architecture** and **Advanced Graphics (DirectX/HLSL)**.
- 💻 **Tech Stack:**  
  ![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white) ![Unreal](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

---

### 🔬 Engine & Systems Projects

**[Cpp_SLAM](https://github.com/MyungJewon/Cpp_SLAM) — LiDAR SLAM Pipeline (C++17)** 
외부 라이브러리 없이 C++17만으로 구현한 3D LiDAR SLAM 파이프라인.  
KDTree(브루트포스 대비 ~800× 속도), ICP(Jacobi SVD), VoxelGrid, LoopCloser, ROS bag 파서까지 설계.

> **Key Tech:** C++17, KD-Tree, ICP, Voxel Grid, Point Cloud, SLAM

---

**[Cpp_ECS](https://github.com/MyungJewon/Cpp_ECS) — Mini ECS Framework (C++17)**
Unity DOTS 내부 동작 원리를 파악하기 위해 Sparse Set 기반 ECS를 바닥부터 구현.  
타입 소거 패턴, 가변 템플릿 + Fold Expression 을 활용한 다중 컴포넌트 쿼리 이터레이터 설계.

> **Key Tech:** C++17, Sparse Set, Type Erasure, Variadic Templates, Cache-Oriented Design

---

**[Cpp_PlyLoader_for_Unity](https://github.com/MyungJewon/Cpp_PlyLoader_for_Unity) — Native Plugin**  
C++로 작성한 PLY 포인트 클라우드 파서를 Unity 네이티브 플러그인으로 브리징.  
Windows / macOS 크로스플랫폼 빌드, 커스텀 Point Cloud 셰이더, 독립 실행 뷰어 포함.

> **Key Tech:** C++, P/Invoke, CMake, ShaderLab, Cross-platform

---

**[Unity_CI-CD_Library](https://github.com/MyungJewon/Unity_CI-CD_Library) — Remote Build Tool (UPM Package)**  
SSH를 통해 로컬 네트워크 빌드 서버에 원격으로 Unity 빌드를 요청하는 에디터 툴.  
Android / iOS / Windows 지원, Mac·Windows 빌드 서버 양쪽 호환. UPM 패키지로 배포 (v0.1.4).

> **Key Tech:** C#, Shell Script, SSH, Unity Editor Tools, UPM

---

### 🚀 Portfolio Projects

**[UE5_BinarySoul_Project](https://github.com/MyungJewon/UE5_BinarySoul_Project)** — Unreal Engine 5 포트폴리오 프로젝트  
**[Unity_Swarm-Protocol](https://github.com/MyungJewon/Unity_Swarm-Protocol)** — 모바일 대규모 유닛 전투 시뮬레이터 Tech Demo (DOTS + GPU Instancing, 10,000+ units @ 60FPS)

---

### 🛠 Tech Stack & Tools

| Category | Skills |
| :--- | :--- |
| **Game Engine** | ![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white) ![Unreal](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white) |
| **Languages** | ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=c-sharp&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![HLSL](https://img.shields.io/badge/HLSL-5C2D91?style=flat-square&logo=directx&logoColor=white) |
| **Graphics** | ![DirectX](https://img.shields.io/badge/DirectX-5C2D91?style=flat-square&logo=directx&logoColor=white) GPU Instancing · Compute Shader · Point Cloud |
| **Systems** | ECS · SLAM · DOTS · Native Plugin · CI/CD |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white) |

---
