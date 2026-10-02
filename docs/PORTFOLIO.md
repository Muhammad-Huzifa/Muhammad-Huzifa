# Public repository index

This index records the organization pass on 2 October 2026. Four collections provide the maintained learning/research material. Applications and teaching courses retain their own repositories and environments. The six duplicate source repositories remain available for the owner's later backup and deletion.

## Maintained repositories

| Repository | Role | Publication |
| --- | --- | --- |
| [Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions) | Keep: digital image processing collection | [Merged](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions/pull/1) |
| [Machine_Learning](https://github.com/Muhammad-Huzifa/Machine_Learning) | Keep: classical ML and Adult Income collection | [Merged](https://github.com/Muhammad-Huzifa/Machine_Learning/pull/2) |
| [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow) | Keep: deep learning and YOLO collection | [Merged](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/pull/2) |
| [Efficient-TT-STGCN-for-Sign-Language-Recognition](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition) | Keep: four ordered public SLR experiments | [Merged](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/pull/2) |
| [Aerial-Object-Detection-YOLOv8](https://github.com/Muhammad-Huzifa/Aerial-Object-Detection-YOLOv8) | Keep: aerial detection application | [Merged](https://github.com/Muhammad-Huzifa/Aerial-Object-Detection-YOLOv8/pull/1) |
| [AI-Fitness-Trainer-Using-MediaPipe](https://github.com/Muhammad-Huzifa/AI-Fitness-Trainer-Using-MediaPipe) | Keep: pose/fitness application | [Merged](https://github.com/Muhammad-Huzifa/AI-Fitness-Trainer-Using-MediaPipe/pull/1) |
| [Egg-Detection-and-Estimation](https://github.com/Muhammad-Huzifa/Egg-Detection-and-Estimation) | Keep: browser prototype and segmentation tools | [Merged](https://github.com/Muhammad-Huzifa/Egg-Detection-and-Estimation/pull/1) |
| [tennis-pro-analytics](https://github.com/Muhammad-Huzifa/tennis-pro-analytics) | Keep: checkpoint-based video analysis | [Merged](https://github.com/Muhammad-Huzifa/tennis-pro-analytics/pull/1) |
| [FruitVideo_AI](https://github.com/Muhammad-Huzifa/FruitVideo_AI) | Keep: structured FastAPI demonstration prototype | Already structured |
| [AI-ML-DL-Batch3-](https://github.com/Muhammad-Huzifa/AI-ML-DL-Batch3-) | Keep: eight-module classroom course | [Ready PR; protected branch blocks merge](https://github.com/Muhammad-Huzifa/AI-ML-DL-Batch3-/pull/1) |
| [Cloud-Computing-AI-Course](https://github.com/Muhammad-Huzifa/Cloud-Computing-AI-Course) | Keep: published course weeks and planned roadmap | [Merged](https://github.com/Muhammad-Huzifa/Cloud-Computing-AI-Course/pull/1) |
| [n8n](https://github.com/Muhammad-Huzifa/n8n) | Keep: starter for future documented workflows | README only; no workflow exports yet |
| [Muhammad-Huzifa](https://github.com/Muhammad-Huzifa/Muhammad-Huzifa) | Keep: profile and public portfolio navigation | Published navigation |

## Consolidated sources

| Source repository | Maintained destination | Status |
| --- | --- | --- |
| [Artifitail-Neural-Networks](https://github.com/Muhammad-Huzifa/Artifitail-Neural-Networks) | [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow / notebooks/01_neural_network_fundamentals](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/tree/main/notebooks/01_neural_network_fundamentals) | Retire after backup and review |
| [ML-End-to-End-project](https://github.com/Muhammad-Huzifa/ML-End-to-End-project) | [Machine_Learning / projects/adult_income](https://github.com/Muhammad-Huzifa/Machine_Learning/tree/main/projects/adult_income) | Retire after backup and review |
| [Object-Detection-Yolo-Models](https://github.com/Muhammad-Huzifa/Object-Detection-Yolo-Models) | [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow / projects/object_detection/yolo](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/tree/main/projects/object_detection/yolo) | Retire after backup and review |
| [ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism](https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/01_bilstm_attention](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/01_bilstm_attention) | Retire after backup and review |
| [MSE-GCN-Paper-Methodology](https://github.com/Muhammad-Huzifa/MSE-GCN-Paper-Methodology) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/02_mse_gcn](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/02_mse_gcn) | Retire after backup and review |
| [TT-STGCN-for-Sign-Language-Recognition](https://github.com/Muhammad-Huzifa/TT-STGCN-for-Sign-Language-Recognition) | [Efficient-TT-STGCN-for-Sign-Language-Recognition / experiments/03_tt_stgcn](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/tree/main/experiments/03_tt_stgcn) | Retire after backup and review |

Read [the retirement guide](RETIREMENT.md) for exact source snapshots and backup/deletion steps. No repository was deleted or archived in this pass.

## Naming and structure

The current repository URLs are used in every clone command. Optional shorter names are `Digital-Image-Processing`, `Machine-Learning`, `Deep-Learning`, and `Sign-Language-Recognition`. Rename through GitHub settings only when authenticated; then update documentation and local remotes to match. The separate ML and DL collections are already published under their existing names.

## Validation and limits

- Digital image processing: all 32 lesson code cells executed on bundled samples; seven array checks passed, with an OpenCV comparison skipped when unavailable.
- Machine learning: seven active notebooks parse; both NumPy regression lessons execute from the repository root; five Adult Income tests pass. Full dataset benchmarks and optional API/UI execution were not repeated.
- Deep learning: 25 active notebooks parse, YOLO CLI help works, and the original binary dataset archive is retained. Framework installation, GPU training, and real detector inference were not performed.
- Public SLR: all nine notebooks parse, and original code-cell hashes match their source snapshots. Extraction, training, checkpoint inference, and reported accuracy were not reproduced.
- Applications: aerial/fitness checks and egg-dataset/video-resource tests pass at their documented scope. Real camera/model inference still requires the project's dependencies, inputs, and checkpoints.
- Teaching: 60 Batch 3 and 11 cloud-course notebook JSON files were inspected, with material links checked against their full trees. Student worksheets intentionally require completion; full classroom execution and cloud deployment were not performed.
- FruitVideo AI is a demonstration service; real video generation is not implemented. The n8n repository has no exported workflows yet.

The three new collection PRs passed their GitHub Actions checks before merge. Publication verifies the expected file hashes and retained data. Each README states its own setup, input requirements, and validation limits.
