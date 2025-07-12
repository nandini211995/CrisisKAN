# CrisisKAN
Code repository of paper "CrisisKAN: Knowledge-infused and Explainable Multimodal Attention Network for Crisis Event Classification" published in ECIR 2024


> Gupta and Saini et al. "CrisisKAN: Knowledge-infused and Explainable Multimodal Attention Network for Crisis Event Classification. 2024."

Preprint: https://arxiv.org/abs/2401.06194

To cite the paper:
```
@misc{gupta2024crisiskan,
      title={CrisisKAN: Knowledge-infused and Explainable Multimodal Attention Network for Crisis Event Classification}, 
      author={Shubham Gupta and Nandini Saini and Suman Kundu and Debasis Das},
      year={2024},
      eprint={2401.06194},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
## CrisisMMD Dataset
* Website: https://crisisnlp.qcri.org/crisismmd
* Dataset: https://crisisnlp.qcri.org/data/crisismmd/CrisisMMD_v2.0.tar.gz

## Run the model
* Setup the environemnt and download the dataset using script  `bash setup.sh`
* Run the pipeline with `bash train_debug.sh`

## Project Structure

<pre lang="bash"><code> ```bash CrisisKAN/ ├── configs/ # Model architectures, Optimization method ├── data_prep/ # Data Preparation & Preprocessing ├── datasets/ # Folder to save dataset ├── gradcam_results/ # Folder to save XAI results ├── wiki_extraction/ # Knowledge extraction (TagMe + Wikipedia) ├── args.py # Arguments script ├── main.py # Main file ├── trainer.py # Training script ├── setup.sh # Setup file, run using bash ├── train_debug.sh # Run training pipeline with detailed logs ├── train.sh # Run training pipeline ├── requirements.yml ``` </code></pre>