# nnsvs_ameboshi_ciphyer_utagoe_db

[NNSVS](https://github.com/r9y9/nnsvs) recipe of Ameboshi Ciphyer's singing voice database (52 songs).
Almost all codes are derived from [kiritan_singing](https://github.com/r9y9/kiritan_singing).

## Requirements
- nnsvs
- utaupy
- nnmnkwii
- librosa
- soundfile
- scipy
- numpy
- tqdm
- jaconv
- pyyaml

## How to use
Due to the licensing issue, this recipe does not include data nor helper scripts for downloading automatically. First of all, you need to get 
雨星サイファ歌声DB.zip from https://parapluie2c56m.wixsite.com/mysite. Next, clone this repository and change `db_root` in `svs-world-resf0convlstm/config.yaml` according to your environment. Then move to `svs-world-resf0convlstm` directory and run:

    run.sh --stage 0 --stop-stage 6

The directory structure made by this recipe is the same as kiritan_singing does.

## Sample code
- 


## Resources
- 雨と星 音源配布所 https://parapluie2c56m.wixsite.com/mysite
