---
layout: page
title: Automated detection of security sensitive UI elements
description: Automated detection of security sensitive UI elements for Clickshield
img: assets/img/dns-report-image.png
importance: 1
category: completed
---

Designed a three-stage pipeline to automatically identify and tag security-sensitive UI widgets for Clickshield. Proposed using UI-CTX for static code analysis to construct UI Handler Graphs, applying a Graph Neural Network for binary classification at the graph level, and defining automatic code-level annotations (e.g., custom XML attributes) to drive runtime overlay protection.

Here is the full [proposal]({{ "/assets/pdf/dns-report.pdf" | relative_url }}){:target="_blank"}.