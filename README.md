# Music Source Separation Models Overview

This repository contains a curated and organized overview of the most relevant music source separation models as of 2024–2025. Models are evaluated using SDR (Signal-to-Distortion Ratio) metrics across different datasets: Multisong, Synth, and the MDX23 leaderboard.

Each model page includes:  
- Description  
- Available versions  
- SDR metrics  
- Notable characteristics or special editions  

## Models Included

- [Demucs4 HT](models/demucs4_ht.md)  
- [BS Roformer](models/bs_roformer.md)  
- [MelBand Roformer](models/melband_roformer.md)  
- [MDX23C](models/mdx23c.md)  
- [SCNet](models/scnet.md)  
- [DX B](models/dx_b.md)  
- [Demucs4 Vocals 2023](models/demucs4_vocals_2023.md)  

## SDR Explanation

SDR (Signal-to-Distortion Ratio) measures the quality of separated audio sources — the higher the value, the better the quality.

## Overall Recommendations

| Goal                                    | Recommended Model                    |
|-----------------------------------------|--------------------------------------|
| Highest overall quality                 | BS Roformer 2024.08                  |
| Cleanest vocal separation               | BS Roformer 2024.08                  |
| Best instrumental separation            | BS Roformer 2024.08                  |
| Speed over top quality                  | `htdemucs`, Demucs4 Vocals 2023      |
| Full multi-stem (bass/drums/other/vocals)| Demucs4 HT (`htdemucs_ft`)           |

## Sources

- [Demucs GitHub](https://github.com/facebookresearch/demucs/tree/ht/demucs)  
- MVSep community releases  
- Papers: “Mel-Band RoFormer for Music Source Separation”, “SCNet: Sparse Compression Network for Music Source Separation”  
- Contributions by @lucidrains, @viperx, @Kimberley Jensen, @Bas Curtiz, @unwa, @becruily  
