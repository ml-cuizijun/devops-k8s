# 07 Helm Kustomize 与多环境

## Helm（优先）

- Chart 结构：`Chart.yaml`、`values.yaml`、`templates/`。
- 常用命令：`install`、`upgrade`、`rollback`。
- 参数化管理 dev/test/prod 差异。

## Kustomize

- base/overlay 模型。
- 在不改 base 的情况下按环境覆盖。
