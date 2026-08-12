---
title: "Learning Prostate Anatomy at Test Time for Cancer Detection in Micro-Ultrasound"
collection: publications
excerpt: 'The prostate gland remains a consistently identifiable anatomical target across patient populations, clinical centers, and scanner generations, even as low-level image statistics shift substantially with acquisition protocol and equipment. We hypothesize that this domain shift manifests as drift in an encoder’s internal feature representations of prostate anatomy, corrupting the features that underpin downstream cancer detection. Building on this, we propose ANT, a test-time adaptation method that supervises the encoder to segment the prostate at test time, re-anchoring its representations to this domain-invariant anatomical target and correcting feature drift without target domain labels. This anatomically grounded signal offers explicit structural supervision, in contrast to generic self-supervised TTA objectives that adapt only from the model’s output distribution, and ANT outperforms such entropy-based baselines (TENT, EATA, SAR, CoTTA, ROID) on clinically significant prostate cancer detection AUC.'
date: 2026-08-14
venue: 'Machine Learning for Healthcare Conference (MLHC 2026), Proceedings of Machine Learning Research (PMLR), Vol. 340'
paperurl: 'https://proceedings.mlr.press/v340/'
---
