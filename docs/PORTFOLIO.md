# Public repository index

This index records the public portfolio organization pass on 2 October 2026. Pull-request links show the current review and merge status; the labels below are a snapshot. Draft changes are available on each PR's branch before they are merged into `main`.

| Repository | Role | Organization review |
| --- | --- | --- |
| [Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions) | Digital image processing collection | [Merged](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions/pull/1) |
| [Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow) | Consolidated ML/deep-learning collection | [Merged](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow/pull/1) |
| [Machine_Learning](https://github.com/Muhammad-Huzifa/Machine_Learning) | Original ML source notebooks | [Draft PR](https://github.com/Muhammad-Huzifa/Machine_Learning/pull/1) |
| [Artifitail-Neural-Networks](https://github.com/Muhammad-Huzifa/Artifitail-Neural-Networks) | Original ANN source notebooks | [Draft PR](https://github.com/Muhammad-Huzifa/Artifitail-Neural-Networks/pull/1) |
| [ML-End-to-End-project](https://github.com/Muhammad-Huzifa/ML-End-to-End-project) | Adult Income application and source project | [Merged](https://github.com/Muhammad-Huzifa/ML-End-to-End-project/pull/1) |
| [Object-Detection-Yolo-Models](https://github.com/Muhammad-Huzifa/Object-Detection-Yolo-Models) | Navigation to the consolidated detection starter | README initialized and verified |
| [Aerial-Object-Detection-YOLOv8](https://github.com/Muhammad-Huzifa/Aerial-Object-Detection-YOLOv8) | Aerial detection application | [Merged](https://github.com/Muhammad-Huzifa/Aerial-Object-Detection-YOLOv8/pull/1) |
| [AI-Fitness-Trainer-Using-MediaPipe](https://github.com/Muhammad-Huzifa/AI-Fitness-Trainer-Using-MediaPipe) | Pose-based fitness application | [Merged](https://github.com/Muhammad-Huzifa/AI-Fitness-Trainer-Using-MediaPipe/pull/1) |
| [Egg-Detection-and-Estimation](https://github.com/Muhammad-Huzifa/Egg-Detection-and-Estimation) | Browser detection and segmentation tools | [Draft PR](https://github.com/Muhammad-Huzifa/Egg-Detection-and-Estimation/pull/1) |
| [tennis-pro-analytics](https://github.com/Muhammad-Huzifa/tennis-pro-analytics) | Checkpoint-based tennis video analysis | [Draft PR](https://github.com/Muhammad-Huzifa/tennis-pro-analytics/pull/1) |
| [FruitVideo_AI](https://github.com/Muhammad-Huzifa/FruitVideo_AI) | FastAPI demonstration prototype | Already structured; reviewed |
| [Efficient-TT-STGCN-for-Sign-Language-Recognition](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition) | Lightweight ISLR notebook experiments | [Draft PR](https://github.com/Muhammad-Huzifa/Efficient-TT-STGCN-for-Sign-Language-Recognition/pull/1) |
| [TT-STGCN-for-Sign-Language-Recognition](https://github.com/Muhammad-Huzifa/TT-STGCN-for-Sign-Language-Recognition) | Graph/attention ISLR notebook experiments | [Draft PR](https://github.com/Muhammad-Huzifa/TT-STGCN-for-Sign-Language-Recognition/pull/1) |
| [MSE-GCN-Paper-Methodology](https://github.com/Muhammad-Huzifa/MSE-GCN-Paper-Methodology) | Graph-model learning implementation | [Draft PR](https://github.com/Muhammad-Huzifa/MSE-GCN-Paper-Methodology/pull/1) |
| [ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism](https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism) | BiLSTM/attention ISLR experiments | [Draft PR](https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism/pull/1) |
| [AI-ML-DL-Batch3-](https://github.com/Muhammad-Huzifa/AI-ML-DL-Batch3-) | Eight-module teaching collection | [Draft PR](https://github.com/Muhammad-Huzifa/AI-ML-DL-Batch3-/pull/1) |
| [Cloud-Computing-AI-Course](https://github.com/Muhammad-Huzifa/Cloud-Computing-AI-Course) | Published course weeks and planned roadmap | [Draft PR](https://github.com/Muhammad-Huzifa/Cloud-Computing-AI-Course/pull/1) |
| [n8n](https://github.com/Muhammad-Huzifa/n8n) | Initialized workflow collection; no exports yet | README initialized and verified |
| [Muhammad-Huzifa](https://github.com/Muhammad-Huzifa/Muhammad-Huzifa) | GitHub profile and portfolio navigation | This organization branch |

## Organization decisions

The two learning destinations are [Digital Image Processing](https://github.com/Muhammad-Huzifa/Digital-Image-Proccesing-from-Scratch-and-using-Built-in-Functions) and [Machine Learning and Deep Learning](https://github.com/Muhammad-Huzifa/Neural-Networks-and-Deep-Learning-Using-Pytorch-and-Tensor-Flow). Keep application deployments, research experiments, and teaching courses as independent projects with their own environments and inputs. The original ML/ANN repositories retain source notebooks and link to the curated destination.

Recommended final repository names are `Digital-Image-Processing` and `Machine-Learning-and-Deep-Learning`. Existing names remain in clone commands and links until the repositories are renamed through GitHub settings. No repository has been archived or deleted as part of this organization pass.

The detection repository started empty and now points to the working starter in the combined collection. The n8n repository also started empty; its guide describes how future tested workflows should be documented rather than claiming completed automations.

## Validation and limits

- Digital image processing: all 32 lesson code cells executed on bundled samples; seven array-level checks passed, and an OpenCV comparison was skipped because OpenCV was unavailable.
- ML/deep learning: active Python cells parse; both NumPy regression lessons executed. Custom image datasets and full framework training remain external requirements.
- Adult Income: five preprocessing/persistence checks passed, and train/predict commands completed on a synthetic fixture. This is not an Adult dataset benchmark; the optional API/UI were not executed.
- Public sign-language research: nine notebooks were organized with original model/training source cells retained. Extraction, GPU training, and reported benchmark figures were not reproduced.
- Egg detection and tennis analytics: CLI/syntax checks and filesystem/video-resource tests passed using fixtures for unavailable model dependencies. Actual model, camera, and video inference were not executed.
- Teaching collections: notebook JSON and full material links were checked, including preserved slides. Student TODO worksheets intentionally require completion; full classroom runs were not claimed.
- FruitVideo AI: the existing structure and demo service were reviewed. Its complete FastAPI test suite was not rerun in this environment.

Each project's README and PR description gives its own commands, input requirements, and the exact scope of validation. Changed files were checked against their published Git blob hashes.
