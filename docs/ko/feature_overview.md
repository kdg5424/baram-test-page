# 프로그램

* [BaramFlow](#baramflow)
* [BaramMesh](#barammesh)

## BaramFlow

### 지원되는 격자 형식
* OpenFOAM PolyMesh
* Fluent case (.cas)
* Fluent mesh (.msh)
* Gmsh (.msh)
* I-deas Univesl (.unv)


### 격자 편집
* Scale
* Translate
* Rotate


### 난류 모델
* Laminar
* Spalart-Allmaras
* k-epsilon
    * Standard
    * RNG
    * Realizable
* k-omega
    * SST
* LES
* DES


### 셀 존 조건
* Zone Types
    * Multiple Reference Frame (MRF)
    * Porous Zone
    * Sliding Mesh
    * Actuator Disk
* Source Terms
* Fixed Values


### 모니터링
* Residual Values
* Force Coefficients
* Point Values
* Surface Values
* Volume Values


### 병렬 프로세스
* MPI Parallel Processing



## BaramMesh

* 경계면 개수에 제한 없음
* 볼륨을 구성하는 닫힌 곡면을 자동 감지
* 면의 각도에 따른 표면 분할
* 간단한 형상 지원 (육면체, 구, 원기둥)
* 프리즘 형태의 경계층 생성
* 병렬 프로세스로 격자 생성 시, 우수한 확장성 제공
* 닫힌 곡면이 (water-tight) 아닌 경우에도 작동 가능
* OpenFOAM 다중 영역 (Multi-Region) 케이스를 위한 다중 영역 격자 지원
* Conformal 및 Non-Conformal 인터페이스 지원
* 셀 존 (Cell Zone) 지원
* 외부 유동 및 내부 유동에 대한 격자 지원
* 표면, 볼륨, 엣지를 기반으로 한 격자 정밀도 조절