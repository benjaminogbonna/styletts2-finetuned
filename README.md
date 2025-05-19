# This repository is an attempt to finetune StyleTTS2 on Nigeria accented English

Audio samples: [Samples](https://github.com/benjaminogbonna/styletts2-finetuned/tree/master/samples)

Model Repo: [Hugging Face](https://huggingface.co/benjaminogbonna/tts_demo_models)


## TODO
- [ ] Getting more data for current speakers and re-training the model for better generalization 
- [ ] Adding more Speakers for diversity

## Pre-requisites
1. Python >= 3.7

2. Install python requirements: 
```bash
pip install -r requirements.txt
```


### Common Issues
- **High-pitched background noise**: This is caused by numerical float differences in older GPUs. 

## References
- [StyleTTS2](https://github.com/yl4579/StyleTTS2)

## License

Code: MIT License

Pre-Trained Models: Before using these pre-trained models, you agree to inform the listeners that the speech samples are synthesized by the pre-trained models, unless you have the permission to use the voice you synthesize. That is, you agree to only use voices whose speakers grant the permission to have their voice cloned, either directly or by license before making synthesized voices public, or you have to publicly announce that these voices are synthesized if you do not have the permission to use these voices.
