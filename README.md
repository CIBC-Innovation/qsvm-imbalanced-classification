# Towards Real-World Solutions: QSVM with NSGA-II Feature Map Search for Imbalanced Classification

<div>

Official implementation of our IEEE QCNC 2026 paper:

> [**Towards Real-World Solutions: QSVM with NSGA-II Feature Map Search for Imbalanced Classification**](https://doi.org/10.1109/QCNC69040.2026.00053) <br>
> Jay Patel, Yaqi Han, Erin Li, and Jamal Kawach <br>
> *2026 IEEE International Conference on Quantum Communications, Networking, and Computing (QCNC)*, Kobe, Japan

</div>

## Abstract

We assess whether quantum models can be a practical choice for imbalanced datasets where good minority class performance is required. The proposed pipeline uses a multi-objective genetic search (NSGA-II) to discover compact feature maps under fixed qubit and depth budgets and pre-computes Gram matrices on GPU for efficiency. We compare against classical baselines on a financial dataset and measure the effect of decision-threshold selection on F1. Using QSVM as a base model of the pipeline, we obtain an F1 within about one hundredth of strong classical baselines at the default threshold and observe a stable precision-recall trade-off across a broad range of thresholds. Taken together, these results suggest that compact feature-map search and efficient circuit evaluation are key ingredients for deploying competitive quantum models for minority-class classification at this data scale.

## Code Availability

Code and reproducibility artifacts are coming soon.

## Citation

If you use or reference this work in your research, please cite the paper using the following IEEE BibTeX entry:

```bibtex
@inproceedings{Patel2026QSVM,
  author    = {Patel, Jay and Han, Yaqi and Li, Erin and Kawach, Jamal},
  booktitle = {2026 IEEE International Conference on Quantum Communications, Networking, and Computing (QCNC)}, 
  title     = {Towards Real-World Solutions: QSVM with NSGA-II Feature Map Search for Imbalanced Classification}, 
  year      = {2026},
  pages     = {253--258},
  doi       = {10.1109/QCNC69040.2026.00053}
}
```

## License
A license will be provided with the code release.

**IEEE Copyright Notice:**

© 2026 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component of this work in other works.
