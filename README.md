# 반도체 공정·설비 / 데이터 분석

반도체 공정과 설비 데이터를 분석하고, Python과 Verilog로 진행한 프로젝트를 정리하고 있습니다.

## Projects

### 1. PECVD Process Analysis
**PECVD 공정 데이터 분석 · Python**

설비 센서 로그와 Recipe 조건, 49-point Wafer Map 데이터를 비교했습니다. 공정별 센서 변화와 증착 두께·균일도를 확인하고, 목표 두께에 맞춘 Recipe 개선 방향을 검토한 프로젝트입니다.

*Private repository — 프로젝트 요약만 공개*

### 2. PECVD FDC / VM Machine Learning
**공정 불량 분류 및 두께 예측 · Python / Machine Learning**

PECVD 데이터를 전처리하고 Random Forest, XGBoost, CatBoost 등 모델을 비교했습니다. FDC 불량 분류에는 Precision·Recall·F1·ROC-AUC를, VM 두께 예측에는 R²·MAE·RMSE를 활용했습니다.

*Private repository — 프로젝트 요약만 공개*

### 3. Traffic Light & Gate Controller
**디지털 회로 설계 · Verilog**

FSM 기반 신호등 제어 회로를 설계하고 Timer, PWM, 7-Segment 모듈을 연결했습니다. Testbench와 GitHub Actions로 RTL 동작을 확인하고 GDS 산출물을 정리했습니다.

[프로젝트 코드 및 설계 내용](https://github.com/bkf001-hue/total_project_trafficlight_gate)

## Skills & Tools

- **Process data:** Python, Pandas, NumPy, Matplotlib, scikit-learn
- **Machine learning:** Random Forest, XGBoost, CatBoost
- **Digital design:** Verilog, Testbench, Icarus Verilog, GitHub Actions

---

*공정 분석 및 머신러닝 프로젝트는 교육·팀 프로젝트로 진행했습니다. 모델 예측이나 Recipe 시뮬레이션을 실제 생산 설비 적용 성과와 구분해 기록했습니다.*
