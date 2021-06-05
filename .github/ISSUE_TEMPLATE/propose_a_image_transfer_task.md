---
name: "Propose a Image Transfer Task"
about: This issue will trigger ffdit bot to transfer image from one registry to another.
title: 'ffdit: [Propose a Image Transfer Task] '
labels: ffdit
assignees: ''

---
{
  "version": 1,
  "image": {
    "from": "k8s.gcr.io/coredns",
    "to": "ffutop/gcr_mirror_coredns",
    "tag": "1.6.5"
  }
}
