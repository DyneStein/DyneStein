# Muhammad Dyen Asif

Undergraduate researcher in trustworthy machine learning, computer vision and edge AI.
BS Computer Science, FAST-NUCES Islamabad.

I work on the problem of models that are confidently wrong, and on the systems that have to
survive that: uncertainty quantification, calibration, out-of-distribution behaviour, and
human-in-the-loop escalation when a prediction should not be trusted.

## Research

**Risk-Aware Active Learning for Skin Lesion Classification** · *manuscript under peer review, 2026*
L. Noor, **M. D. Asif**, H. Ramzan, A. Atiq, M. A. Saeed, A. Jamil, A. Din

A dual-metric human-in-the-loop escalation policy for dermoscopy: a case is routed to a clinician
when either model uncertainty or a dedicated clinical-risk head crosses a per-round calibrated
threshold. This targets the failure standard active learning cannot see, where a model is
confidently wrong about a melanoma and auto-accepts it. We prove the escalation set is a
superset of the uncertainty-only set, so unsafe auto-acceptance cannot increase.

Across 24 experiments on HAM10000: **43% fewer unsafe auto-accepts in 12 of 12 matched
configurations**, at 9.1% more oracle labels (Holm-corrected p = 0.003), with no significant change in F1-macro
(p = 0.305). Validated out-of-distribution on 14,885 ISIC-2019 images with HAM10000
duplicates removed: 83.3% accuracy win rate, 75.0% melanoma-safety win rate.
→ [`RiskAware-ActiveLearning`](https://github.com/DyneStein/RiskAware-ActiveLearning)

**Hallucination-Free Retrieval-Augmented Generation** · *undergraduate research assistant, FAST-NUCES*

An agentic RAG question-answering system for Classical Arabic: GATE Arabic embeddings fine-tuned
with Matryoshka loss, an HNSW index over 12,472 provenance-tagged passages, and a bounded
retrieve → sufficiency-check → rewrite loop with per-step citation validation. I build the
evaluation framework, including a knowledge-graph guardrail that extracts subject-relation-object
triples from source and answer to reject unsupported claims.

## Selected work

| | |
|---|---|
| [**ISBGlyph**](https://github.com/DyneStein/ISBGlyph) | Smart-city simulation of Islamabad in C++/SFML with every data structure written from scratch — adjacency-list graphs with Dijkstra routing, n-ary trees, heaps, open-addressing hash tables. Zero STL. |
| [**PBSVertex**](https://github.com/DyneStein/PBS) | Pakistan's Consumer Price Index across 17 cities modelled as a price-similarity graph, using cosine similarity and centrality analysis to identify economic hubs. [Live](https://pbsvertex.netlify.app/) |
| [**Super Mario (Inspired)**](https://github.com/DyneStein/SuperMario) | A playable four-level platformer in pure x86 Assembly: hand-rolled memory management, stack-based collision detection, custom real-time sound manager. No engine, no standard library. |

Production work at **DenseFusion** (geospatial ML platforms, YOLO11n on NVIDIA Jetson, offline-first
agricultural advisory systems) is under NDA. One deployment is publicly viewable at
[serena.com.pk/green](https://serena.com.pk/green/).

## Technical

**Languages** Python · C++ · Java · JavaScript/TypeScript · SQL · x86 Assembly
**ML** PyTorch · scikit-learn · Ultralytics YOLO · active learning · uncertainty quantification · calibration · OOD detection · Grad-CAM++ / Score-CAM · RAG · HNSW retrieval
**Vision & geospatial** Rasterio · GDAL · PROJ · QGIS · GeoPandas · Cloud-Optimized GeoTIFF · PostGIS · TiTiler
**Edge** NVIDIA Jetson Nano / Orin Nano · MAVLink telemetry · on-board inference under power and thermal constraints
**Systems** FastAPI · Next.js · NestJS · PostgreSQL · Redis · RabbitMQ · MinIO · Docker · Nginx · Linux

## Contact

[mdyenasif@gmail.com](mailto:mdyenasif@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dynestein/) · Islamabad, Pakistan
