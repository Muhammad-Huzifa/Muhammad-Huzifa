# Consolidation and backup record

As checked on 2 October 2026, the six duplicate source repositories are absent from the owner's account after manual retirement. Their maintained destinations remain available in [machine-learning](https://github.com/Muhammad-Huzifa/machine-learning), [deep-learning](https://github.com/Muhammad-Huzifa/deep-learning), and [sign-language-recognition](https://github.com/Muhammad-Huzifa/sign-language-recognition). Keep these collections and the separate [digital-image-processing](https://github.com/Muhammad-Huzifa/digital-image-processing) collection.

## Retired sources and destinations

Source names below are historical identifiers rather than live links.

| Retired source | Maintained destination | Preserved scope |
| --- | --- | --- |
| `Artifitail-Neural-Networks` | [Open destination](https://github.com/Muhammad-Huzifa/deep-learning/tree/main/notebooks/01_neural_network_fundamentals) | ANN lessons and labeled historical drafts |
| `ML-End-to-End-project` | [Open destination](https://github.com/Muhammad-Huzifa/machine-learning/tree/main/projects/adult_income) | Package, commands, serving launchers, reports, and tests |
| `Object-Detection-Yolo-Models` | [Open destination](https://github.com/Muhammad-Huzifa/deep-learning/tree/main/projects/object_detection/yolo) | Navigation and detection starting point; source had no model code or checkpoints |
| `ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism` | [Open destination](https://github.com/Muhammad-Huzifa/sign-language-recognition/tree/main/experiments/01_bilstm_attention) | Three extraction and 100/300-class training notebooks |
| `MSE-GCN-Paper-Methodology` | [Open destination](https://github.com/Muhammad-Huzifa/sign-language-recognition/tree/main/experiments/02_mse_gcn) | Two extraction and graph-model notebooks |
| `TT-STGCN-for-Sign-Language-Recognition` | [Open destination](https://github.com/Muhammad-Huzifa/sign-language-recognition/tree/main/experiments/03_tt_stgcn) | Two extraction and graph/temporal-model notebooks |

SLR notebooks preserve their original code-cell sequences. ANN/ML copies retain the earlier reviewed path and lesson fixes. Source maps record file destinations. Newly authored CPU lessons are documented separately from migrated material.

## Reviewed source snapshots

These source heads precede the redirect README updates; they are not the final backup heads.

| Source | Reviewed commit |
| --- | --- |
| `Artifitail-Neural-Networks` | `795bf03b43b4d3d0f5c6666aed11d7ab6feface3` |
| `ML-End-to-End-project` | `e7d8ccfbb93e9e406565798415b3bfeda00bf80c` |
| `Object-Detection-Yolo-Models` | `649ba60e25316a01df81ee10e321110f7e7b8ba2` |
| `ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism` | `0adb04466a0969fd3bec32f23fc28427ecfd96bc` |
| `MSE-GCN-Paper-Methodology` | `a0a433898ab126d70ebaf6d76e7f1040d7e8204f` |
| `TT-STGCN-for-Sign-Language-Recognition` | `84fb316b31f7770cb5dfe539b83af3c2ce57ed9c` |

## Verified history backup

Before retirement, the owner was supplied `github-duplicate-source-backups_2026-10-02.zip`. It contains six verified mirror histories, portable Git bundles, a manifest, and repository/issue/PR/release inventory records. The histories contain 43 commits in total; Git integrity checks passed before the archive was supplied.

This is a Git-history backup with audit records, not a complete export of every GitHub setting, integration, or release asset. Keep it outside the maintained repositories. Deleted source URLs cannot be used for a new mirror clone.

After extracting the archive, restore an individual history using its bundle. Run from the folder containing that bundle; for example:

```bash
git clone Artifitail-Neural-Networks.bundle restored-ann-history
git -C restored-ann-history fsck --full
git -C restored-ann-history log --all --oneline
```

This restores a local Git repository and does not create or publish a GitHub repository. Use the archive's README and manifest for exact bundle locations and backup heads.

Current maintained names are already in use. Live clone commands and portfolio links have been updated to match. The former `n8n` starter is also absent from the inventory and is not listed as an active project.
