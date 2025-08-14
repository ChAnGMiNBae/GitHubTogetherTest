---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: New Feature
assignees: ChAnGMiNBae, minjubu

---

# ================================
# ✨ Feature Request Issue Form
# ================================

name: "✨ Feature Request"

description: "새 기능을 제안합니다"

labels: ["type:feature"]

body:

  # ------------------------
  # 1. 문제/배경
  # ------------------------

  - type: textarea

    id: problem

    attributes:

      label: "문제/배경"

      description: "왜 이 기능이 필요한가요?"

    validations:

      required: true


  # ------------------------
  # 2. 제안 내용
  # ------------------------

  - type: textarea

    id: proposal

    attributes:

      label: "제안 내용"

      description: "기능 요약, 수용 기준(AC)을 써주세요."


  # ------------------------
  # 3. 대안/관련 이슈
  # ------------------------

  - type: textarea

    id: alternatives

    attributes:

      label: "대안/관련 이슈"
