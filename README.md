
## Article Name
*Revisiting-Annotations-in-Online-Student-Engagement*

## Authors
*Shehroz Khan,Sadaf Safa*

## Description of Annotations
This repository contains two CSV files with the re-annotations of the DAiSEE dataset, employing the Human Expert Labeling Protocol (HELP). These annotations provide a more nuanced understanding of learner engagement, incorporating emotional, behavioral, and engagement scales.

The annotations adhere to a numeric scheme designed for training purposes. They categorize behavioral and emotional states, along with engagement levels, according to the HELP protocol. The classification follows this scheme:
## Annotation Categories

| Category      | Value | State       |
|---------------|-------|-------------|
| Behavioral    | `0`   | Off-Task    |
|               | `1`   | On-Task     |
| Emotional     | `0`   | Bored       |
|               | `1`   | Calm/Satisfied       |
|               | `2`   | Confused/Frustrated    |
|               | `3`   | Excited/Highly Motivated     |
| Engagement    | `0`   | Not Engaged |
|               | `1`   | Engaged     |


## Files in this Repository

### `train_labels_daisee.csv`
Contains the re-annotated and original training data labels from the DAiSEE dataset.

### `test_labels_daisee.csv`
Contains the re-annotated and original testing data labels from the DAiSEE dataset.

## References

For detailed information on the original DAiSEE dataset and the HELP protocol, please refer to the following sources:

- DAiSEE dataset: Gupta, A., D'Cunha, A., Awasthi, K., & Balasubramanian, V. (2016). [DAiSEE: Towards User Engagement Recognition in the Wild](https://arxiv.org/pdf/1609.01885v7.pdf). arXiv preprint arXiv:1609.01885.
- HELP Protocol: Aslan, S., Mete, S. E., Okur, E., Oktay, E., Alyuz, N., Genc, U. E., Stanhill, D., & Esme, A. A. (2017). Human Expert Labeling Process (HELP): Towards a Reliable Higher-Order User State Labeling Process and Tool to Assess Student Engagement. Educational Technology, 57(1), 53-59. [https://www.jstor.org/stable/44430540](https://www.jstor.org/stable/44430540).

## Citation

If you use these annotations in your research, please cite the following paper:

Khan, S., & Safa, S. (2024). Revisiting Annotations in Online Student Engagement. Retrieved from [ACM](https://dl.acm.org/doi/10.1145/3641181.3641186).


