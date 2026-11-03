---
name: plan
description: Планирование выполнения задачи
argument-hint: <описание задачи>
disable-model-invocation: true
effort: max
metadata:
  version: "1.0.0"
# - Скилл заменяет встроенный /plan
# - Ultracode нельзя включить из скилла; явный вызов Workflow даёт тот же
#   эффект для одной задачи.
---

Перейди в режим планирования и подготовь план выполнения задачи. Для
подготовки плана используй инструмент Workflow. Задача:

$ARGUMENTS
