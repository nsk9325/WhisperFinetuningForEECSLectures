# WhisperFinetuningForEECSLectures
Whisper Finetuning for EECS Lectures, Dataset From MIT OCW for non-commercial use\
Data Aquired from 7+ MIT OCW EECS Lectures\
\
Dataset(Before FeatureExtraction_Wav&Text)\
https://huggingface.co/datasets/yongjune2002/MITOCW-whisper
\
Dataset(After FeatureExtraction_MelLogSpectrum)\
https://huggingface.co/datasets/yongjune2002/MITOCW-Whisper-Processed

Fine-tuned model\
https://huggingface.co/tfbghjk/whisper-mit-small_v2/tree/main

| Team member | Main responsibilities |
|-------------|-----------------------|
| 윤재원        | Overall project coordination • training pipeline orchestration • Gradio demo integration |
| 이용준        | MIT OCW audio extraction • VAD segmentation & transcript cleaning • dataset release on HF Hub |
| 정재윤        | Data augmentation & multi-domain sampler • evaluation scripts (WER, accent slices) |
| 김동영        | Whisper-small fine-tuning phases • hyper-parameter tuning • checkpoint management |
| 한지훈        | Resource profiling (GPU/CPU, wandb dashboards) • result analysis & poster layout |

