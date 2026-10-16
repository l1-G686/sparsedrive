# sparsedrive

Checkpoints are attached to GitHub Releases. Each weight file is above GitHub's 100MB git blob limit.

## DiffusionDrive

Release: [weights-g3-g5](https://github.com/l1-G686/sparsedrive/releases/tag/weights-g3-g5)

| file | experiment |
| --- | --- |
| `dd_geo_g3_s0_best.ckpt` | G3, seed 0, best |
| `dd_geo_g5_s0_best.ckpt` | G5, seed 0, best |

## SparseDrive R3

Release: [weights-r3-ep5-ep10](https://github.com/l1-G686/sparsedrive/releases/tag/weights-r3-ep5-ep10)

Run `three_run_r3_factorized_credit/r3_1x8`.

| file | experiment |
| --- | --- |
| `r3_1x8_ep0005.ckpt` | epoch 5 |
| `r3_1x8_ep0010.ckpt` | epoch 10 |
| `r3_ep0005_navtest_v2.csv` | epoch 5 navtest scores |
| `r3_ep0005_navhard.csv` | epoch 5 navhard scores |
| `r3_ep0005_metrics.txt` | epoch 5 summary |
| `r3_ep0010_navtest_v2.csv` | epoch 10 navtest scores |
| `r3_ep0010_navhard.csv` | epoch 10 navhard scores |
| `r3_ep0010_metrics.txt` | epoch 10 summary |

| epoch | navtest | navhard extended PDM |
| --- | --- | --- |
| 5 | 0.866309 | 0.450689 |
| 10 | 0.872611 | 0.426486 |
