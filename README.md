# 🧑‍💻 남궁도현 (Namgung Dhohyeon) | Software Engineer

> **"동작 원리를 파고들어, 탄탄한 기반 위에서 문제를 해결합니다."**

단순히 프레임워크나 API를 사용하는 것을 넘어, 그 이면의 동작 원리를 이해하고 코드를 작성하는 것을 중요하게 생각합니다. 학부 과정 동안 운영체제, 컴파일러, 3D 그래픽스, 데이터 알고리즘 등을 라이브러리에 의존하지 않고 밑바닥부터(From Scratch) 직접 구현하며 컴퓨터 공학의 뼈대를 다졌습니다.

어떤 도메인이나 기술 스택을 마주하더라도 현상의 '본질'을 파악하고 최적의 구조를 설계하는 엔지니어가 되겠습니다.

<br>

## 🙋‍♂️ About Me

- 🎓 **한양대학교 컴퓨터소프트웨어학부** (2021.03 ~ 재학 중)
- 🌱 현재 **Low-level System** 구조와 **렌더링/AI 최적화**에 깊은 관심을 두고 있습니다.
- 💻 프레임워크의 마법에 기대기보다, 시스템의 동작 원리를 뜯어보고 직접 구현하는 과정을 즐깁니다.
- 🎮 초등학교 시절 ActionScript로 게임을 만들며 느꼈던 순수한 즐거움을 원동력 삼아 코드를 작성합니다.

<br>

## 🛠 Technical Skills

### Languages

- `C` / `C++` (Fluent)
- `Python`
- `SQL`
- `Verilog`

### Core & Systems

- **OS & Architecture**: `xv6 OS`, `Computer Architecture`
- **Graphics & AI**: `OpenGL`, `Skeletal Animation (BVH)`, `Machine Learning (From Scratch)`
- **Tools**: `Git`, `Linux`, `MySQL`

<br>

## 🚀 Key Projects

### 1. 3D Mesh & 계층적 모션 데이터(BVH) 뷰어

**Forward Kinematics 기반의 계층적 렌더링 파이프라인 구축**

- **Tech Stack**: C++, OpenGL, Python
- **주요 구현**:
  - 4개 이상의 정점을 가진 비정형 폴리곤(N-gon) 면 데이터를 GPU 렌더링에 적합하도록 삼각형으로 자동 분할(**Triangulation**)하는 알고리즘 구현.
  - BVH 파일의 트리 구조를 파싱하고 **Forward Kinematics(순운동학)** 연산을 적용하여 각 뼈대의 전역 변환 행렬을 도출, 프레임별 모션 동기화.
- **Troubleshooting**: 메쉬 렌더링 시 발생하는 깨짐 문제를 인덱싱 기반의 분할 로직으로 해결하여 출력 안정성 확보.
- [🔗 Repository Link](레포지토리 주소 입력) | [🎥 Demo Video](유튜브 등 영상 주소 입력)

### 2. Decision Tree & Bagging Ensemble from Scratch

**외부 라이브러리 없이 구현한 지능적 의사결정 모델**

- **Tech Stack**: Python
- **주요 구현**:
  - `scikit-learn` 등 외부 라이브러리 없이 엔트로피 기반의 **정보 획득량(Information Gain)** 수식을 직접 코드로 구현하여 최적의 분기점 탐색 로직 완성.
  - 단일 트리의 **과적합(Overfitting)** 문제를 방지하기 위해 부트스트랩 샘플링과 다수결(Majority Voting) 방식의 **배깅(Bagging)** 기법 적용.
- **Insight**: 알고리즘의 귀납적 편향(Inductive Bias) 등 확률 모델의 구조적 특성을 체화.
- [🔗 Repository Link](레포지토리 주소 입력)

### 3. System Software Suite (OS, Compiler, CPU)

**하드웨어-소프트웨어 통합 설계 및 시스템 최적화**

- **xv6 OS 고도화**: 커널 레벨에서 `MLFQ 스케줄러`, `멀티스레드`, `Copy-On-Write(COW)` 기능을 직접 구현하며 자원 관리 메커니즘 체화.
- **C-Minus 컴파일러 구현**: Lexical/Syntax/Semantic 분석을 거쳐 `AST(Abstract Syntax Tree)`를 생성하는 컴파일러 파이프라인 전 과정 설계.
- **Pipelined CPU 설계**: Verilog를 활용해 `Branch Predictor`가 탑재된 파이프라인 CPU를 설계하고 연산 지연 최적화.
- [🔗 Repository Link](관련 레포지토리 주소 묶음 혹은 대표 주소 입력)

<br>

## 📬 Contact

- 📧 **Email**: [dhohyeon007@gmail.com](mailto:dhohyeon007@gmail.com)
- 📝 **Blog**: [기술 블로그 주소](블로그 링크)
