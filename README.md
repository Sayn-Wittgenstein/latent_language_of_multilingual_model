## Usage

### Translation
```papermill Translation.ipynb out.ipynb -p input_lang en -p latent_lang_1 en -p latent_lang_2 ja -p target_lang zh -p model_selected 3 -p layer_num 40```
### Cloze
```papermill Cloze_multi.ipynb out.ipynb -p latent_lang_1 en -p latent_lang_2 ja -p target_lang ja -p model_selected 3  -p layer_num 40```

## Acknowledgements
The `llamawrapper.py` script is adapted from the work of [wendlerc](https://github.com/epfl-dlab/llm-latent-language/tree/main). We thank them for their valuable contribution.
