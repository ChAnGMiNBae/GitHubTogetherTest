---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug, New Feature
assignees: ChAnGMiNBae, minjubu

---

# ========================
# 🐞 Bug Report Issue Form
# ========================
name: "🐞 Bug Report"

description: "버그를 신고합니다"

labels: ["type:bug", "triage"]

body:

  # ------------------------
  # 1. 버그 설명
  # ------------------------
  - type: textarea
    id: what-happened
    attributes:
      label: "무슨 일이 있었나요?"
      description: "실제 동작과 기대 동작을 자세히 써주세요."
      placeholder: "재현 단계, 실제/기대 결과…"
    validations:
      required: true


  # ------------------------
  # 2. 재현 단계
  # ------------------------
  - type: textarea
    id: steps
    attributes:
      label: "재현 단계"
      value: |
        1.
        2.
        3.


  # ------------------------
  # 3. 버전/브랜치 정보
  # ------------------------
  - type: input
    id: version
    attributes:
      label: "버전/브랜치"
      placeholder: "e.g. v1.2.0, main"


  # ------------------------
  # 4. 심각도 선택
  # ------------------------
  - type: dropdown
    id: severity
    attributes:
      label: "심각도"
      options:
        - "S1-긴급"
        - "S2-높음"
        - "S3-보통"
        - "S4-낮음"
