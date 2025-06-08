# Overview of Foundation Models in Remote Sensing

This repository contains the published paper **"Overview of Foundation Models in Remote Sensing"**, accepted at CIIT 2025.

**Paper**: [Overview of Foundation Models in Remote Sensing](https://github.com/teostojkovski/Overview-of-Foundation-Models-in-Remote-Sensing/blob/master/Overview%20of%20Foundation%20Models%20in%20Remote%20Sensing.pdf)

## Abstract

Recent advances in artificial intelligence, particularly the rise of **foundation models**, are reshaping the field of **remote sensing**. Traditionally dependent on handcrafted features and task-specific models, remote sensing struggled with generalization, scalability, and adaptability across various geospatial modalities.

Foundation models — large-scale pre-trained architectures using **self-supervised learning** — offer cross-task generalization, better performance in detection/segmentation, and reduced reliance on annotated datasets. This paper presents a comprehensive review of these models, their architectures, training strategies, and applications in domains such as environmental monitoring, agriculture, disaster response, and urban planning.

---

## Authors

- Teo Stojkovski – [teo.stojkovski@students.finki.ukim.mk](mailto:teo.stojkovski@students.finki.ukim.mk)  
- Evrosina Stojkoska – [evrosina.stojkoska@students.finki.ukim.mk](mailto:evrosina.stojkoska@students.finki.ukim.mk)  
- Marko Petrov – [marko.petrov@finki.ukim.mk](mailto:marko.petrov@finki.ukim.mk)  
- Ema Pandilova – [ema.pandilova@finki.ukim.mk](mailto:ema.pandilova@finki.ukim.mk)  
- Vlatko Spasev – [vlatko.spasev@finki.ukim.mk](mailto:vlatko.spasev@finki.ukim.mk)  
- Ivan Kitanovski – [ivan.kitanovski@finki.ukim.mk](mailto:ivan.kitanovski@finki.ukim.mk)

Faculty of Computer Science and Engineering  
Ss. Cyril and Methodius University, Skopje, North Macedonia

---

## Topics Covered

- Foundation Models in AI and Remote Sensing  
- Self-Supervised Learning (SSL) Techniques  
- Vision Transformers (ViTs) and Model Architectures  
- Modalities: RGB, Multispectral, Hyperspectral, SAR, LiDAR  
- RemoteCLIP, SatMAE, RingMo, ScaleMAE, SkySense, and others  
- Applications in Environmental Monitoring, Agriculture, Urban Planning, Disaster Management  
- Performance Benchmarking across Classification, Segmentation, Detection, and Change Detection  

---

## Key Table

| Model     | Params | Dataset Size | Modalities              | Weights | Architecture |
|-----------|--------|---------------|--------------------------|---------|--------------|
| SeCo      | 23.5M  | 1M            | Multispectral            | ✅       | ✅            |
| GeoKR     | 138M   | 1.43M         | RGB, Multispectral       | ❌       | ✅            |
| RVSA      | 100M   | 1M            | RGB, Multispectral, SAR  | ✅       | ✅            |
| SatMAE    | 307M   | 1.05M         | RGB, Multispectral       | ✅       | ✅            |
| RingMo    | 10B    | 2M            | RGB, SAR                 | ✅       | ✅            |
| RSP       | 25.8M  | 1M            | Multispectral, Hyperspectral | ✅   | ✅            |
| ScaleMAE  | 322.9M | 1.05M         | RGB, Multispectral       | ❌       | ✅            |
| SkySense  | 2.06B  | 21.5M         | RGB, Multispectral, SAR  | ✅       | ❌            |
| Prithvi   | 100M   | 4.2M          | Multispectral            | ✅       | ✅            |
| GFM       | 100M   | 600k          | RGB, Multispectral, SAR  | ✅       | ✅            |
