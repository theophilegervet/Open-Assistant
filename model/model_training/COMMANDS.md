SFT
```
python trainer_sft.py --configs llama-7b webgpt_dataset_only --wandb-entity tgervet
python trainer_sft.py --configs lora-llama-13b webgpt_dataset_only --wandb-entity tgervet
python trainer_sft.py --configs lora-llama-13b oasst_export_eu --wandb-entity tgervet
python trainer_sft.py --configs lora-llama-30b webgpt_dataset_only --wandb-entity tgervet
```

Reward model
```
python trainer_rm.py --configs defaults_rm oasst-rm-1-pythia-1.4b --wandb-entity tgervet
```
