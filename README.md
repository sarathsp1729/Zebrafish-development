# Zebrafish Development Abnormality Dataset & Baseline Models

> **Heads‑up — data + code will be made public *soon*!**
> Everything described below is under active curation and will be released **soon**.
> Follow / ⭐ the repository to get notified the moment it drops.

---

## 1 Project overview

High‑throughput imaging of zebrafish embryos is a powerful in‑vivo model for developmental biology and early‑stage toxicology, but manual inspection of the resulting image sequences is slow and subjective.

This repository will eventually host:

* **A large‑scale image & video dataset** of zebrafish embryogenesis under control conditions and after exposure to reference toxicants.
* **Reference implementations of transformer‑based spatio‑temporal models** for two tasks:

  * Early fertility detection
  * Automated toxicity assessment

The entire pipeline is described in recent paper submitted at MICAI‑2025 paper, “Automated Detection of Abnormalities in Zebrafish Development.”

---

## 2 Current status & roadmap

| Milestone                                     | Status         | ETA         |
| --------------------------------------------- | -------------- | ----------- |
| Dataset cleaned & re‑packaged                 | ✅ complete     | —           |
| Baseline model refactor (PyTorch)             | ✅ complete     | -           |
| Dataset update with more compounds testing    | ⏳ pending      | soon        |
| Code & data pushed to `main`                  | ⏳ pending      | soon        |


---

## 3 What will be included at launch?

* **Dataset archives** (`fertility.zip`, `toxicity.zip`) — each containing:
  * Lossless PNG frames grouped by sequence ID
  * JSON annotations
  * A CSV catalogue with relative paths & labels
* **`models/`** — clean, documented PyTorch Lightning code for our ViT‑based baselines
* **`scripts/`** — utilities for downloading, verifying checksums, and reproducing paper results
* **Notebooks** demonstrating exploratory analysis and inference on a single sequence

---


