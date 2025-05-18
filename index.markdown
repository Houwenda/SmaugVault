---
title: "SmaugVault"
layout: splash
date: 2025-03-23T22:54:28+08:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/smaug-img-1.jpg
  actions:
    - label: "Download"
      url: "/download/"
excerpt: "A data security solution that transforms your Mac into a fortress against cyber threats."
intro: 
  - excerpt: 'Although macOS endpoints are popularly believed to be secure, data security is only as strong as its weakest link. As the use of Macs for private data handling and financial operations has risen, so has the number of info and crypto stealers, targeting high-value organizations and individuals.'
feature_row:
  - image_path: assets/images/smaug-file-hardening.jpg
    alt: "file hardening image"
    title: "File Hardening"
    excerpt: "Granular file control with smooth user experience."
  - image_path: /assets/images/smaug-network-protection.jpg
    alt: "network protection image"
    title: "Network Protection"
    excerpt: "Exfiltration detection with content observability."
  - image_path: /assets/images/smaug-clipboard-security.jpg
    alt: "clipboard security image"
    title: "Clipboard Security"
    excerpt: "Recognition of clipboard-related attack vectors."
feature_row2:
  - image_path: /assets/images/app-access-control.jpg
    alt: "Classify Files for App Access Control"
    title: "Classify Files for App Access Control"
    excerpt: 'SmaugVault secures sensitive files through vault folders and macOS Finder tags, dynamically enforcing application-level access policies to prevent both user errors and malicious exfiltration attempts.'
feature_row3:
  - image_path: /assets/images/network-observability.jpg
    alt: "Network Observability with Minimal Effort"
    title: "Network Observability with Minimal Effort"
    excerpt: 'SmaugVault delivers full* observability of egress traffic with context-aware content inspection and responding strategies.'
feature_row4:
  - image_path: /assets/images/clipboard-access-detection.jpg
    alt: "Suspicious Clipboard Access Detection"
    title: "Suspicious Clipboard Access Detection"
    excerpt: 'macOS clipboards can be leveraged by malwares to steal passwords and inject false contents. SmaugVault detects those attempts by investigating clipboard contents and accessor processes, generating alerts for user vigilance.'
feature_row5:
  - image_path: /assets/images/behavioral-correlation.jpg
    alt: "Behavioral Correlation for Risk Mitigation"
    title: "Behavioral Correlation for Risk Mitigation"
    excerpt: 'SmaugVault orchestrates multi-dimensional countermeasures, providing in-depth defense against data leak threats acrosss network, processes, files and inter-process communications.'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="center" %}