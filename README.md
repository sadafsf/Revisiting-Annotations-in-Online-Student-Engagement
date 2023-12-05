# Re-Annotation of DAiSEE Dataset Using HELP Protocol

## Article Name
*Re-Annotation of DAiSEE Dataset Using HELP Protocol*

## Authors
*Shehroz Khan,Sadaf Safa*

## Description of Annotations
This repository contains two CSV files with the re-annotations of the DAiSEE dataset, employing the Human Expert Labeling Protocol (HELP). These annotations provide a more nuanced understanding of learner engagement, incorporating emotional, behavioral, and engagement scales.

The annotations follow the numeric conventions of the HELP protocol, which classifies behavioral and emotional states, as well as engagement levels, using the following scheme:
## Annotation Categories

| Category      | Value | State       |
|---------------|-------|-------------|
| Behavioral    | `0`   | Off-Task    |
|               | `1`   | On-Task     |
| Emotional     | `0`   | Bored       |
|               | `1`   | Calm        |
|               | `2`   | Confused    |
|               | `3`   | Excited     |
| Engagement    | `0`   | Not Engaged |
|               | `1`   | Engaged     |

## References

For detailed information on the original DAiSEE dataset and the HELP protocol, please refer to the following sources:

- DAiSEE dataset: Gupta, A., D'Cunha, A., Awasthi, K., & Balasubramanian, V. (2016). [DAiSEE: Towards User Engagement Recognition in the Wild](https://arxiv.org/pdf/1609.01885v7.pdf). arXiv preprint arXiv:1609.01885.
- HELP Protocol: Authors. (Year). [Title of the HELP Protocol Paper](https://www.jstor.org/stable/44430540). Journal Name, Volume(Issue), pages.

## Citation

If you find these annotations useful for your research, please consider citing the original DAiSEE dataset and the HELP protocol accordingly.

```bibtex
@inproceedings{daisee2016,
  title={DAiSEE: Towards User Engagement Recognition in the Wild},
  author={Gupta, Abhay and D'Cunha, Alisha and Awasthi, Kamal and Balasubramanian, Vineeth},
  booktitle={arXiv preprint arXiv:1609.01885},
  year={2016}
}

