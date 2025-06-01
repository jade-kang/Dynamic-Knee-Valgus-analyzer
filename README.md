# Dynamic-Knee-Valgus Analyzer

> **단일 카메라**(옵션: IMU)를 이용해  
> Small Knee Bend (SKB) 테스트 중 **무릎 내반 (Dynamic Knee Valgus, DKV)** 및  
> **무릎 안쪽 이동 거리**를 실시간으로 정량화하고, PDF·CSV 리포트를 자동 생성합니다.

---

## 📖 DKV란?

* **Dynamic Knee Valgus(DKV)**  
  체중 지지 동작(달리기·점프·스쿼트 등)에서 무릎이 **안쪽으로 붕괴**되는 움직임 패턴  
  (일명 *knock-knee*).
* **원인**   
  고관절·무릎 근력 및 신경-근 조절 저하, 족궁 붕괴 등.
* **임상적 위험**   
  연구에 따르면 DKV가 심할수록 **전방십자인대(ACL) 손상**과 **슬개대퇴 통증** 등
  하지 부상 위험이 높아집니다.

---

## 🔍 DKV를 확인하는 방법

한발 스쿼트(Single-Leg Squat)나 한발 점프 착지 동작에서  
앉았다 일어설 때 무릎의 위치가 **안쪽으로 굽어지는지**를 관찰합니다.

<div align="center">
  <img src="https://github.com/user-attachments/assets/bb32fc8a-c38d-462a-b99a-4127349718a0" width="450" alt="무릎 내반 예시">
  <br><sub>이미지 출처: Precision Physical Therapy</sub>
</div>

---

## 🛠️ 프로젝트 배경

| 핵심 이슈 | 설명 |
|-----------|------|
| **검사자 주관성** | SKB·SLS 등 동적 정렬 검사는 **검사자 경험**에 좌우 → 검사자 간 신뢰도↓ |
| **2-D 측정 근거** | 단일 카메라로 산출한 **Frontal-Plane Projection Angle(FPPA)** 가 3-D 모션캡처 대비 **평균 오차 2–3°** (선행 연구) |
| **직관적 거리 지표** | **Medial Knee Displacement(MKD)** 는 “무릎이 얼마나 안쪽으로 이동했는가”를 **쉽게 시각화**하여 교육용 피드백에 적합 |

---

## 🎯 프로젝트 목표

* **카메라 기반 실시간 분석**으로 검사자 주관성을 최소화하고  
  **표준화된 수치**로 치료·운동 결정을 지원한다.
* 결과를 **즉시 시각화**하며, **PDF/CSV 리포트**를 자동 출력해
  임상 문서화와 연구·교육 자료로 바로 활용할 수 있도록 한다.
