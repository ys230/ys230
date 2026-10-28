![ys230 — Embedded Linux](assets/profile-header.svg)

# ys230

**Embedded Linux · Board Bring-up · Device Validation**

RK3588 기반 보드의 OS 구성부터 배포, 시험, 현장 적용까지 이어지는 개발 과정을 기록합니다.
직접 구현한 내용과 확인한 결과를 연결하고, 남은 검증도 함께 정리합니다.

[01 Platform](projects/platform.md) · [02 RF Validation](projects/rf-validation.md) · [03 Field Devices](projects/field-devices.md) · [FPGA Notes](https://github.com/ys230/FPGA)

## Current focus

| | Project | Focus |
|:---:|---|---|
| **01** | [**RK3588 Linux Platform**](projects/platform.md) | OS 이미지 구성, 보드 bring-up, 검증과 배포. **01.2**는 사용자용 OS 이미저 개발입니다. |
| **02** | [**RF Test & Validation**](projects/rf-validation.md) | AP6354 / AP6398S 시험 제어 GUI, 스펙트럼 애널라이저를 활용한 확인, KC 인증 대응. |
| **03** | [**NPU Field Devices**](projects/field-devices.md) | 국산 NPU 실증 디바이스의 구성, 요구사항별 검증, 이슈 정리와 인계. |

각 항목은 현재 집중하는 개발 목표입니다. 구체적인 구현 범위와 검증 결과는 프로젝트별 기록에서 관리합니다.

## How I document engineering work

| Question | Record |
|---|---|
| 무엇을 해결하려 했는가? | 요구사항, 재현 조건, 확인할 기준 |
| 무엇을 직접 만들고 변경했는가? | 구현 내용, 변경 이유, 원본과 협업 범위 |
| 어떤 근거로 판단했는가? | 버전, 로그, 시험 조건, 측정 결과 |
| 다음 사람이 이어갈 수 있는가? | 설치·재현 절차, 알려진 제한, 다음 작업 |

## Learning notes

[**FPGA**](https://github.com/ys230/FPGA) — RTL / FPGA 관련 학습과 실험 기록.

---

<sub>Platform engineering · Deployment tooling · RF validation · Field integration</sub>
