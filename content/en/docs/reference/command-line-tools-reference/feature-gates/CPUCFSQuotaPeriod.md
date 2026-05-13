---
title: CPUCFSQuotaPeriod
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha
    defaultValue: false
    locked: false
    fromVersion: "1.12"
    toVersion: "1.35"
  - stage: stable
    defaultValue: true
    locked: false
    fromVersion: "1.36"
---

<!-- FIXME: Add meaningful description for CPUCFSQuotaPeriod feature gate -->
