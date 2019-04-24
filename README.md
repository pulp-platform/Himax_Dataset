# Himax Dataset

```
├── Himax
    ├── test_2
    ├── test_10
    ├── test_15
    ├── test_23
```

The *Himax* dataset has been collected at ETH Zürich using a Himax ultra-low power, gray-scale, and QVGA camera.
The dataset has been used for testing the inference capability of our [PULP-DroNet](https://github.com/pulp-platform/pulp-dronet), and it extends the testing dataset previously introduced in [DroNet](https://github.com/uzh-rpg/rpg_public_dronet) with the Himax set.
This release includes the test set described in the PULP-DroNet paper: https://arxiv.org/abs/1805.01831.
It is composed of 228 `.pgm` images with resolution 324x244, each tagged with a 0/1 collision label.
Each sub-folder contains a variable number of gray-scale `.pgm` images, ordered by number (e.g., `frame_1.pgm`, `frame_2.pgm`, etc.) and one `labels.txt` file with all the ground-truth labels in the same order.
