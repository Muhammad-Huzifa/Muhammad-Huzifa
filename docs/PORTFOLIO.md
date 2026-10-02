# Public repository index

Reviewed on 2 October 2026. Four collections hold the learning and research material; applications and teaching courses keep their own repositories and environments. Collection consolidation is merged, the six duplicate sources have been retired, and live links use the current repository names.

## Learning and research

| Repository | Contents | Navigation |
| --- | --- | --- |
| [digital-image-processing](https://github.com/Muhammad-Huzifa/digital-image-processing) | Six image-processing notebooks and bundled samples | [Start here](https://github.com/Muhammad-Huzifa/digital-image-processing#readme) |
| [machine-learning](https://github.com/Muhammad-Huzifa/machine-learning) | 15 notebooks, including eight new CPU lessons; Adult Income project | [Start here](https://github.com/Muhammad-Huzifa/machine-learning/blob/main/notebooks/README.md) |
| [deep-learning](https://github.com/Muhammad-Huzifa/deep-learning) | 33 active notebooks, including eight new CPU lessons; YOLO starter | [Start here](https://github.com/Muhammad-Huzifa/deep-learning/blob/main/notebooks/README.md) |
| [sign-language-recognition](https://github.com/Muhammad-Huzifa/sign-language-recognition) | Four ordered experiments and nine notebooks | [Start here](https://github.com/Muhammad-Huzifa/sign-language-recognition#readme) |

ML additions cover pipelines, evaluation, KNN/SVM, trees and ensembles, text classification, clustering, PCA, tuning, and persistence. DL additions cover backpropagation, CPU training/checkpoints, a small CNN, recurrent models, attention, a Transformer encoder, IoU/NMS, and an autoencoder. These new lessons use generated, handcrafted, or built-in data and need no GPU or dataset download after dependency installation.

## Applications and courses

| Repository | Implemented scope |
| --- | --- |
| [aerial-object-detection](https://github.com/Muhammad-Huzifa/aerial-object-detection) | YOLO aerial detection application and dataset configuration |
| [ai-fitness-trainer](https://github.com/Muhammad-Huzifa/ai-fitness-trainer) | MediaPipe pose analysis and exercise counting |
| [egg-detection-and-estimation](https://github.com/Muhammad-Huzifa/egg-detection-and-estimation) | Browser ONNX prototype, segmentation tools, heuristic size categories |
| [tennis-video-analytics](https://github.com/Muhammad-Huzifa/tennis-video-analytics) | Checkpoint-based tracking and overlays; motion statistics in pixels |
| [fruit-video-api](https://github.com/Muhammad-Huzifa/fruit-video-api) | FastAPI demonstration service; real video generation is a future integration |
| [ai-ml-dl-course-batch-3](https://github.com/Muhammad-Huzifa/ai-ml-dl-course-batch-3) | Eight-module course, 60 notebooks, assignments, and slides; organization PR is merged |
| [machine-learning-deployment-course](https://github.com/Muhammad-Huzifa/machine-learning-deployment-course) | Published HCCDA-AI course weeks, 11 notebooks, and a planned twelve-week roadmap |
| [Muhammad-Huzifa](https://github.com/Muhammad-Huzifa/Muhammad-Huzifa) | Profile and public portfolio navigation |

## Source history

The six retired repositories and maintained destinations are in the [consolidation and backup record](RETIREMENT.md). Each collection retains historical source identifiers. A verified Git-history backup was supplied to the owner before retirement. The former `n8n` starter is absent from the current inventory and is no longer a live portfolio link.

## Validation and limits

- Machine learning: all 15 active notebooks parse. All 26 code cells in the eight new lessons passed local CPU execution. CI runs the new lessons in fresh Jupyter kernels and retains five Adult Income preprocessing/persistence tests. A real Adult benchmark and optional serving applications were not rerun.
- Deep learning: all 33 active notebooks parse. All 40 code cells in the eight new lessons passed local CPU execution, including five small PyTorch training workflows. Gradient, causal-mask, IoU/NMS, and checkpoint checks passed. CI performs full Jupyter execution of the new lessons. Larger original TensorFlow/GPU experiments and real detector inference were not rerun; the binary archive is preserved.
- Local execution used fresh Python processes with IPython display capture because this environment blocks Jupyter socket connections. Each collection documents its execution command and tested versions.
- Digital image processing: the earlier pass executed all 32 lesson code cells on bundled samples; seven array checks passed, with an OpenCV comparison skipped when unavailable. Lessons are preserved in this update.
- Public SLR: the earlier pass checked all nine notebooks and preserved their original code-cell sequences. Extraction, training, and reported accuracy were not reproduced. Notebooks are preserved in this update.
- Applications: existing checks cover their documented preprocessing, input/resource handling, and source scope. Real camera/model execution requires dependencies, inputs, and checkpoints.
- Teaching: course material and notebook structure were reviewed. Student exercises intentionally require completion; full classroom execution and cloud deployment were not performed.

Educational scores describe each lesson's small dataset and split; they are not production benchmarks. Each repository states its setup, inputs, and validation scope.
