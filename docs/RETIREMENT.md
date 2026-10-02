# Consolidated repository retirement guide

The maintained collections are [Digital Image Processing](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions), [Machine Learning](https://github.com/Muhammad-Huzifa/Machine_Learning), [Deep Learning](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow), and [Sign Language Recognition](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition). Keep all four.

The ML, DL, and SLR consolidation changes are merged into `main`: [ML PR #2](https://github.com/Muhammad-Huzifa/Machine_Learning/pull/2), [DL PR #2](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/pull/2), and [SLR PR #2](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/pull/2). The original repositories have not been deleted or archived.

## Six sources to retire later

| Source repository | Maintained destination | Preserved scope |
| --- | --- | --- |
| [Artifitail-Neural-Networks](https://github.com/Muhammad-Huzifa/Artifitail-Neural-Networks) | [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow / notebooks/01_neural_network_fundamentals](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/tree/main/notebooks/01_neural_network_fundamentals) | ANN lessons and clearly labeled historical drafts |
| [ML-End-to-End-project](https://github.com/Muhammad-Huzifa/ML-End-to-End-project) | [Machine_Learning / projects/adult_income](https://github.com/Muhammad-Huzifa/Machine_Learning/tree/main/projects/adult_income) | Adult Income package, commands, deployment launchers, reports, and tests |
| [Object-Detection-Yolo-Models](https://github.com/Muhammad-Huzifa/Object-Detection-Yolo-Models) | [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow / projects/object_detection/yolo](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/tree/main/projects/object_detection/yolo) | Navigation-only repository; no source models or checkpoints were present |
| [ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism](https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/01_bilstm_attention](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/01_bilstm_attention) | Three extraction and 100/300-class training notebooks |
| [MSE-GCN-Paper-Methodology](https://github.com/Muhammad-Huzifa/MSE-GCN-Paper-Methodology) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/02_mse_gcn](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/02_mse_gcn) | Two extraction and graph-model notebooks |
| [TT-STGCN-for-Sign-Language-Recognition](https://github.com/Muhammad-Huzifa/TT-STGCN-for-Sign-Language-Recognition) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/03_tt_stgcn](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/03_tt_stgcn) | Two extraction and graph/temporal-model notebooks |

Machine_Learning is now a maintained collection, so it is not a deletion candidate. Keep the application repositories, both teaching courses, the GitHub profile repository, and the n8n starter if you intend to add workflows. Keeping the four collections and removing these six duplicates would reduce the account from 20 repositories to 14.

## Source snapshots reviewed

These are the source heads before the redirect README updates. SLR notebooks retain their original code-cell sequences; ANN/ML copies include the earlier reviewed path and lesson fixes. Adult Income's package and commands are preserved in the ML collection. The source maps in each maintained collection record file destinations and provenance.

| Source repository | Reviewed source commit |
| --- | --- |
| `Artifitail-Neural-Networks` | `795bf03b43b4d3d0f5c6666aed11d7ab6feface3` |
| `ML-End-to-End-project` | `e7d8ccfbb93e9e406565798415b3bfeda00bf80c` |
| `Object-Detection-Yolo-Models` | `649ba60e25316a01df81ee10e321110f7e7b8ba2` |
| `ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism` | `0adb04466a0969fd3bec32f23fc28427ecfd96bc` |
| `MSE-GCN-Paper-Methodology` | `a0a433898ab126d70ebaf6d76e7f1040d7e8204f` |
| `TT-STGCN-for-Sign-Language-Recognition` | `84fb316b31f7770cb5dfe539b83af3c2ce57ed9c` |

## Before deleting a source

1. Open the maintained destination and check the expected notebooks, project files, datasets, and documentation. The source snapshots do not cover later commits, unmerged branches, or local unpushed work.
2. Check the source repository for open pull requests, issues, releases, downloads, GitHub Pages, deployments, and integrations. File copies do not migrate those items. Save needed records/assets or redirect their consumers before deletion.
3. Make and verify a Git mirror backup of each source. A mirror stores Git branches/tags/history; it does not back up GitHub issues, release assets, permissions, or deployment settings. Keep the backup outside the source repository and on durable storage.
4. Delete only a source whose destination and backups you have reviewed. The owner performs this deletion later; none of the commands here deletes a GitHub repository.

## Mirror backup commands

Run these in Git Bash or another terminal with Git installed, from a folder where you keep backups:

```bash
mkdir github-source-backups
cd github-source-backups
git clone --mirror https://github.com/Muhammad-Huzifa/Artifitail-Neural-Networks.git Artifitail-Neural-Networks.git
git clone --mirror https://github.com/Muhammad-Huzifa/ML-End-to-End-project.git ML-End-to-End-project.git
git clone --mirror https://github.com/Muhammad-Huzifa/Object-Detection-Yolo-Models.git Object-Detection-Yolo-Models.git
git clone --mirror https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism.git ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism.git
git clone --mirror https://github.com/Muhammad-Huzifa/MSE-GCN-Paper-Methodology.git MSE-GCN-Paper-Methodology.git
git clone --mirror https://github.com/Muhammad-Huzifa/TT-STGCN-for-Sign-Language-Recognition.git TT-STGCN-for-Sign-Language-Recognition.git
```

Verify each mirror; for example:

```bash
git -C TT-STGCN-for-Sign-Language-Recognition.git fsck --full
git -C TT-STGCN-for-Sign-Language-Recognition.git show-ref
```

Inspect all six mirrors, and save any needed release assets or issue records separately. A notebook source map is useful provenance but does not replace a complete history backup.

## Owner deletion steps

On GitHub, open the source repository, choose **Settings → General → Danger Zone → Delete this repository**, and follow GitHub's prompts to confirm the exact owner/repository name. Deletion removes the source repository and its associated GitHub data, so complete the checks above first. Remove one source at a time and confirm the maintained destination still opens correctly.

The shorter collection names are optional settings changes. Renaming a maintained collection is a separate action from deleting a duplicate source; update clone commands and links afterward.
