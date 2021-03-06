# Reading Electronic Yiddish Documents (REYD): MFA-aligned TextGrid files

This repository contains Praat TextGrid files to accompany the [REYD dataset](https://github.com/REYD-TTS) for developing a TTS system in Yiddish. These files were generated by the [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) (version 2.0.0rc3), and they can be used with our fork of [FastSpeech2](https://github.com/REYD-TTS/FastSpeech2) to train a Yiddish TTS system in three different orthographies.

## Directory Structure

```
REYD-textgrids
├── README.md
├── hasidic
|   ├── TextGrid
|   |   ├── lit1
|   |   ├── lit2
|   |   └── pol1
├── yivo_original
|   ├── TextGrid
|   |   ├── lit1
|   |   ├── lit2
|   |   └── pol1
└── yivo_respelled
    └── TextGrid
        ├── lit1
        ├── lit2
        └── pol1
```
The .TextGrid files correspond to the .lab/.wav files contained in the REYD dataset.

## License

If your use of this repo results in a publication being made, we request that you cite the paper listed at https://github.com/REYD-TTS.
