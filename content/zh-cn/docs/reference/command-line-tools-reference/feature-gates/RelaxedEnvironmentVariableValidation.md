---
title: RelaxedEnvironmentVariableValidation
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha
    defaultValue: false
    fromVersion: "1.30"
    toVersion: "1.31"
  - stage: beta
    defaultValue: true
    fromVersion: "1.32"
---

<!--
Allow almost all printable ASCII characters in environment variables.
-->
允许在环境变量中使用几乎所有可打印的 ASCII 字符。
