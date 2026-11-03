---
name: rebase
description: Rebase текущей ветки на дефолтную
disable-model-invocation: true
metadata:
  version: "1.0.1"
# - Главное назначение скилла — чтобы не забывать обновлять local main.
#   Иначе можно выполнить merge с remote main, оставив local main старым,
#   и при /review агент будет считать изменения из remote main изменениями
#   ветки
---

Выполни fetch репозитория в рабочей директории.

Обновил локальную дефолтную ветку.

Актуализируй текущую ветку до дефолтной с помощью rebase.
