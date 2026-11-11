# No.64 — Complete Nim-Words and Sharp Preperiods for the Four-Move Subtraction Family {5,11,15,c}

Ryutaro Yonezu — Independent Researcher  
**Published: 11 November 2026 (JST) · Version 1.0 · Preprint**  
**Copyright (c) 2026 Ryutaro Yonezu. All rights reserved.** No Creative Commons or open-source license is granted.

## Result and limits

For the normal-play one-pile subtraction game S_c={5,11,15,c}, odd c>15, this preprint classifies the complete Sprague–Grundy words and the least eventual periods and preperiods. For odd c>=59, the explicit word uses fixed blocks B (44 digits) and D (29 digits), with least T=c+29 and p=2. The remaining 21 odd c=17..57 have individual finite recurrence certificates, including the previously observed exceptions c=21: (T,p)=(0,26) and c=29: (36,20).

The uniform symbolic proof is asserted for c>=59. T=c+29 also occurs in the finite table at odd c=45..57, and the full word agrees in a finite check at c=49; neither changes the proved uniform boundary. The wider all-odd-a quadratic formula T=c+2a^2-4a-1 remains an **unproved computational conjecture**.

## Review and reproducibility status

- AI-assisted mathematical research.
- External independent AI review: **MODEL / PROOF / COMPUTATION / MINIMALITY / PACKAGE PASS within the reviewed scope**, as reported in author-supplied review text. Reviewer raw code and logs were not supplied or independently rerun by the publication editor.
- Windows PowerShell 5.1: **author-run PASS on canonical frozen v0.1**, not independently witnessed. The original ZIP hash, 11-entry manifest, exact 12-file inventory, Python, CSV regeneration and C++17 PASS are tied to the author's prior run record. No new Windows execution is claimed for editorial v1.0.
- Publication preparation: original outer/inner archives and manifests verified; byte-identical frozen Python/C++17 sources rerun on Linux; both generated CSVs match; v0.2 PDF rebuilt from TeX with exact extracted-text agreement. The v0.1/v0.2/v1.0 mathematical core is unchanged; v0.2/v1.0 formula tokens match.
- **NOVELTY INCONCLUSIVE / REFERENCES PARTIAL / HUMAN REVIEW NOT DONE / FORMAL PROOF ASSISTANT NOT DONE / ALL RIGHTS RESERVED.**

Earlier HOLD and not-yet-tested records described their historical packaging states. The author's 11 November 2026 conditional publication instruction supersedes the historical HOLD after the mandatory gates pass. The frozen code retains historical labels without changing its calculations.

## Assets

- [Preprint PDF](No64_v1.0_PREPRINT.pdf)
- [LaTeX source](No64_v1.0_SOURCE.tex)
- [Reproducibility ZIP](No64_v1.0_REPRODUCIBILITY.zip)
- [SHA256 checksums](SHA256SUMS.txt)

Only the public PDF, TeX, reproducibility ZIP, README and checksums are distributed. No private audit ZIP, raw Windows log, local absolute path, authentication material or third-party full text is included.

## Reproduce

Extract the ZIP into a writable folder. Use Python 3.10+ (standard library only):

```text
python -B verify_no64.py
```

For the independent C++17 recurrence implementation:

```text
g++ -std=c++17 -O2 -Wall -Wextra -Werror verify_no64_independent.cpp -o verify_no64_independent
./verify_no64_independent
```

On Windows PowerShell 5.1, use the unchanged `run_windows.ps1`; its original candidate/HOLD console labels are retained as historical metadata. Python regenerates both frozen CSVs. Python validates 29 c-independent mex equations, all 21 small certificates and 972 odd c=59..2001 examples. C++ additionally checks sharp periods/preperiods for all 993 odd c=17..2001. Finite numerical checks supplement the separate analytical infinite-family proof.

## Prior work and unresolved coverage

Ho (2015), Theorem 5, gives the known base triple {5,11,15} with T=44,p=2. Zhang (2024), Remark 7, gives bounded observations for the wider family and the c=21 and 29 exceptions. Those results are not claimed as new. The reported examination of Flammenkamp's original dissertation found no direct anticipation in the compared relevant material; the expanded 1997 book (ISBN 3-932136-10-1) remains unread. Moriwaki (2026), Theorems 2 and 4, fail as direct applications under the compared hypotheses; this is not an exhaustive non-overlap proof. No priority or worldwide novelty claim is made.

References, preserved from editorial v0.2:

1. S. Zhang, “On the linearity of the periods of subtraction games,” Theoretical Computer Science 985 (2024), 114350. https://doi.org/10.1016/j.tcs.2023.114350 ; author-posted revision 30 July 2025, Remark 7.
2. G. Cairns and N. B. Ho, “Ultimately bipartite subtraction games,” Australasian Journal of Combinatorics 48 (2010), 213–220.
3. N. B. Ho, “On the expansion of three-element subtraction sets,” Theoretical Computer Science 582 (2015), 35–47, Theorem 5. https://doi.org/10.1016/j.tcs.2015.03.025
4. A. Flammenkamp, Lange Perioden in Subtraktions-Spielen, dissertation, Universität Bielefeld (submitted November 1996; often cited 1997). Original source link only: https://wwwhomes.uni-bielefeld.de/achim/diss.ps.gz . Expanded 1997 book not checked.
5. Y. Moriwaki, “Subtraction Nim with Continuous Parameters,” arXiv:2606.11658v1 (2026), Theorems 2 and 4. https://arxiv.org/abs/2606.11658

## Canonical provenance

Sole preparation archive: No64_v02_EDITORIAL_AUDIT_HOLD_20261111.zip  
SHA256: d6cbc50a29bb83eecfe81173c5b389f47003dea2e2ba949e87b5632405565baf

Canonical frozen archive: No64_v01_CANDIDATE_HOLD_20261111.zip  
SHA256: 46fc4386ddb61cc606de8a491ba99800f262bd375e8070c7d7b195102ab116b5

The 12 original files are retained unchanged privately. The public computational sources, Windows runner and finite CSVs are byte-identical to that archive. The proof Markdown is an editorial derivative of v0.2 with only publication-status changes; its mathematical core is unchanged.

## Immutable asset hashes

| File | Bytes | SHA256 |
| --- | ---: | --- |
| No64_v1.0_PREPRINT.pdf | 383315 | `1ee82a18621b09a2f767f67e4826a03e5e673e437022b78c810d4230e6c60820` |
| No64_v1.0_SOURCE.tex | 13616 | `a2c366f13ecc7e6c105a483e29a23c26b19cacd98d038c865b5c2cdb4a3f6fc9` |
| No64_v1.0_REPRODUCIBILITY.zip | 12878 | `a786e2cc18ca1a0b09ad399de14d1d5ab6d679a476b7051b5c7c8cad55b20365` |
