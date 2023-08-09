# VidEdit video examples

This repository contains examples of edited videos performed with VidEdit. 

* `VidEdit-samples` folder contains various edits for multiple videos. In each folder, `edit_prompts.txt` file details the prompts used to perform the edits. `original.gif` is the input video to edit.

* `Baseline-comparison` folder contains the outputs of the baselines for multiple video edits.

* `Ablations` folder contains videos illustrating the ablation study. Each file name indicates the ablation case. `mask` or `no_mask` in the filename indicates the use or the absence of mask in the denoising pipeline. `hed` or `no_hed` indicates the use or the absence of HED conditioning in the pipeline. VidEdit case correponds to `mask_&_hed`.

* `Atlas-quality` folder contains videos illustrating the impact of the atlas quality on the edited video.
