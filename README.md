# Deep Learning for Dental Diagnostics in Panoramic Radiographs

MSc thesis research at Ozyegin University on multi-model deep learning for dental diagnostics, conducted with clinical collaborators in dentistry. This repository accompanies two peer-reviewed publications.

> **Note on code availability:** The codebase is being extended for a follow-up submission and will be released publicly upon its publication. Until then, this repository documents the methods and findings. For academic inquiries, contact abdelaziz.ashraf.wahid@gmail.com.

---

## 📄 Publications

### 1. ATF-Attention: Attention-Based Fusion for Multi-Model Dental Object Detection in Panoramic Radiographs
*IEEE Symposium on Computers and Communications (ISCC), 2026*

Single detectors miss differently: each architecture has its own blind spots on panoramic radiographs, where findings are small, overlapping, and rare. ATF-Attention fuses the predictions of multiple heterogeneous detectors through a learned attention mechanism, letting the ensemble weight each model's evidence per region instead of averaging blindly.

**Highlights**
- Attention-based fusion across multiple detector families (CNN- and transformer-based)
- Designed for small, imbalanced clinical datasets where the informative finding is the rare one
- Improved detection performance by ~20% over single-model baselines through fusion

### 2. Deep Learning based Tooth Multi-Disease Detection in Dental Diagnostics
*IEEE Signal Processing and Communications Applications Conference (SIU), 2025*
*A. Hussein, H. G. Gunec, K. C. Aydin, H. F. Ates*

Multi-disease detection on panoramic radiographs under real clinical constraints: limited annotations, strong class imbalance, and device-dependent image appearance.

---

## 🔬 Research Context

This work is part of a broader research agenda on **reliable vision models for rare findings under acquisition shift**: representations that stay sensitive to the clinically decisive (rare) finding, and robust when the imaging device or protocol changes.

## 🏥 Clinical Collaboration

Conducted with dental clinicians (H. G. Gunec, K. C. Aydin), with supervision by Prof. Hasan F. Ates (Ozyegin University).

**Data availability:** the clinical panoramic radiograph dataset cannot be shared publicly due to patient privacy regulations.

## 📚 Citation

```bibtex
@inproceedings{hussein2026atf,
  title={ATF-Attention: Attention-Based Fusion for Multi-Model Dental Object Detection in Panoramic Radiographs},
  author={Hussein, Abdelaziz and Gunec, Hatice Gokcen and Aydin, Kader Cesur and Ates, Hasan F.},
  booktitle={IEEE Symposium on Computers and Communications (ISCC)},
  year={2026}
}

@inproceedings{hussein2025tooth,
  title={Deep Learning based Tooth Multi-Disease Detection in Dental Diagnostics},
  author={Hussein, Abdelaziz and Gunec, Hatice Gokcen and Aydin, Kader Cesur and Ates, Hasan F.},
  booktitle={IEEE Signal Processing and Communications Applications Conference (SIU)},
  year={2025}
}
```

## 👤 Author

**Abdelaziz Hussein** — MSc in Artificial Intelligence, Ozyegin University
[Google Scholar](https://scholar.google.com/citations?user=IcqqORIAAAAJ) · [ORCID](https://orcid.org/0000-0001-9532-2958) · [LinkedIn](https://www.linkedin.com/in/abdelaziz-ashraf-hussein-2b34821b5/)
